# ReturnReady resource database

Merged resource catalogs for ReturnReady Utah (Hack for Humanity SLC, Track 1), checked 2026-11-14 (America/Denver). These files are reference data for backend teammates. Nothing in this folder is loaded by the Flask app yet. The live app still reads `data/catalog.json` from `functions/func1.py`.

Field definitions for the v3 spreadsheet schema are in [ReturnReady_Resources_v3_DataDictionary.csv](ReturnReady_Resources_v3_DataDictionary.csv). A human-readable listing is in [ReturnReady_Resources_v3_Directory.md](ReturnReady_Resources_v3_Directory.md).

## Pick one editing master

Two full catalogs were merged independently and both contain 193 records. **Edit only one of them.** The other will drift.

| Master | Shape | Live-display flag | Recommendation |
|---|---|---|---|
| [ReturnReady_Resources_v3.json](ReturnReady_Resources_v3.json) | `opportunities[]` | `demo_ok` | Preferred editing master. `demo_ok` is already false for closed and register-interest returnships. Spreadsheet twins (CSV / XLSX) match this file. |
| [returnready_resources.json](returnready_resources.json) | `resources[]` | `show_in_demo` | Claude's alternate merge. Do not load it live until [ReturnReady_Claude_Merge_RedTeam_Fixes.json](ReturnReady_Claude_Merge_RedTeam_Fixes.json) is applied. It currently marks Fidelity, Goldman Sachs, ARUP, and Morgan Stanley as showable. |

If the team keeps the v3 master, treat `returnready_resources.json` as a cross-check, not a second source of edits.

## Display rules

- Show a v3 record in the live app only when `demo_ok` is `true`. On Claude's catalog the matching flag is `show_in_demo`, and only after the red-team fixes.
- `type` of `sample` or `synthetic` is a **fictional** card. Badge it as a sample listing. Never present it as an open job. In the v3 master these six cards use `type: "sample"`. In the demo-safe JSON and both seed files the same cards use `type: "synthetic"`.
- `demo_ok: true` means "safe to consider," not "open today." Recheck the official page the same day before an Apply button. `url_check_status` records the 2026-11-14 HTTP check (`verified-200`, `sample-no-url`, `no-url`, or `unverified-blocked-*`).
- Returnships that must be rechecked before any public card:
  - **Fidelity RESUME** (`fidelity-resume`): recorded `closed` in the v3 master (`demo_ok: false`). The page reviewed on 2026-11-14 said applications are closed and does not establish a Utah site. Claude's catalog still has `show_in_demo: true` with status `check_provider`; the red-team file says to set status `closed` and hide it.
  - **Goldman Sachs** (`goldman-sachs-returnship` / Claude id `goldman-sachs-slc`): register-interest only (`status: "interest_list"`, `demo_ok: false`). Americas cohort is described as January–March 2027. Do not call it an open application.
  - **ARUP Laboratories** (`arup-returnship`): register-interest only (`status: "interest_list"`, `demo_ok: false`). Confirm a current posting before describing a role as open.
  - **Morgan Stanley** (`morgan-stanley-ut`): recorded `check_provider` in both catalogs (`demo_ok: false` in v3; still `show_in_demo: true` in Claude's file). No confirmed current opening. Treat it like Goldman and ARUP: hide it until a same-day recheck shows a real application path, and do not label it open.
- Descriptions are paraphrases, not eligibility decisions.

## Files

### V3 master (GrokBot merge of GrokBot + Claude + ChatGPT)

- **ReturnReady_Resources_v3.json** — editing master. Top-level keys: `_meta`, `opportunities` (193), `conflicts` (46). `_meta.counts` matches the file: 143 `demo_ok`, 6 `sample`, 187 `real`, 166 URL-verified. Each opportunity includes `id`, `type` (`real` | `sample`), `kind`, `resource_type`, `title`, `name`, `org`, `organization`, `audiences`, `interest_keywords`, `skills`, `location`, `geography`, `format`, `flexibility`, `schedule`, `cost`, `description`, `url`, `source_url`, `secondary_url`, `verified_date`, `url_check_status`, `status`, `action_label`, `next_step`, `demo_ok`, `sources`, `notes`, and sometimes `pay_monthly_gross` / `hours_per_week`. `audiences` use tags such as `caregiver`, `any`, `older_worker`, `long_term_unemployed`, `veteran`, `disability`, `justice_involved`, `military_spouse`. `sources` lists which catalogs contributed the row (`GrokBot`, `Claude`, `ChatGPT`).
- **ReturnReady_Resources_v3.csv** — same 193 rows, 31 columns, header aligned with the data dictionary plus `chatgpt_id` and `claude_id`. List fields are joined for spreadsheet editing.
- **ReturnReady_Resources_v3.xlsx** — workbook sheets: All resources, Demo-safe, Data dictionary, Conflicts.
- **ReturnReady_Resources_v3_DemoSafe.csv** — the 143 `demo_ok` rows only (plus header).
- **ReturnReady_Resources_v3_DataDictionary.csv** — `field,description` for `id`, `type`, `demo_ok`, `status`, `kind`, `resource_type`, `url`, `sources`, and how to edit.
- **ReturnReady_Resources_v3_Conflicts.csv** — 46 rows where the three source catalogs disagreed (`id`, `title`, `field`, `grokbot`, `claude`, `chatgpt`, `resolution`). The same array is `conflicts` in the JSON.
- **ReturnReady_Resources_v3_Directory.md** — directory grouped for humans, suitable as a data-sources note. It repeats the live-demo rule.

`status` values in the v3 master: `ongoing` (145), `check_provider` (24), `sample` (6), `unknown` (6), `interest_list` (4), `historical_only` (3), `closed` (2), `cohort_listed` (1), `local_returnship_unverified` (1), `no_opening_seen` (1).

`demo_ok` is true only for sample cards, Tech-Moms, or a verified URL whose status is `ongoing` or `cohort_listed`. It is false for `closed`, `unknown`, `historical_only`, `no_opening_seen`, `interest_list`, `local_returnship_unverified`, and `check_provider`.

### Demo subsets (v3 schema family)

- **ReturnReady_demo_ok_opportunities_v3.json** — 143 `demo_ok` records in `opportunities[]`, same fields as the master, plus the 6 seed `courses[]`. `type: "sample"` is rewritten to `type: "synthetic"` so an existing "Sample listing" badge still matches. `meta.note`: this full set is too large for the 3-minute demo; use the seed file for that.
- **ReturnReady_seed_opportunities_v3.json** — small demo deck: 8 `opportunities[]` (Tech-Moms, USU Extension Relaunch, and 6 `synthetic` cards) and 6 `courses[]` (`title`, `provider`, `cost`, `length`, `closes_gap`, `verify`, `url`). Three courses have no URL and must stay labeled verify. `type: "synthetic"` means fictional.
- **chatgpt_seed_opportunities.json** — ChatGPT's copy of that 8-card seed. `opportunities[]` matches the v3 seed. `courses[]` is the same six courses **without** `url`.

### Claude's alternate catalog

- **returnready_resources.json** — `meta` + `resources[]` (193). Different field names: `name` (not `title`), `organization`, `category`, `show_in_demo`, `featured_for_demo`, `url_verified`, `contributed_by`, `source_ids`, `checked_on`. `meta.display_rules` say to show only `show_in_demo: true` (176 rows today) and never label a card "Open now" without a same-day check. `meta.categories` and `meta.statuses` document the controlled values.
- **returnready_resources_demo.json** — 22 featured records (`featured_for_demo` and `show_in_demo` both true), same `resources[]` schema. Includes Goldman, ARUP, and Morgan Stanley; do not use this file as the live deck until those flags are corrected.
- **ReturnReady_Claude_Merge_RedTeam_Fixes.json** — recommended flag fixes for `returnready_resources.json` only. `recommended_field_fixes` (15) and `unmerged_featured_duplicates` (3). High-severity items hide Fidelity (`status: closed`), Goldman, ARUP, and Morgan Stanley from `show_in_demo` / `featured_for_demo`. Apply these before that catalog is shown.

## How the Flask app could load this later

Do not replace `data/catalog.json` with one of these files. The shapes differ, and `GET /api/catalog` returns `CATALOG` unchanged.

Today `functions/func1.py` does:

```python
DATA_DIR = Path(__file__).resolve().parent.parent / 'data'
CATALOG = json.loads((DATA_DIR / 'catalog.json').read_text())
```

`catalog.json` is `{opportunities, courses, demoStory}`. Each opportunity uses `provider`, string `type` (`Flexible job` / `Returnship` / `Learning program`), string `style`, string `industry`, `skills` (required by the matcher; an empty list yields no score), numeric `hourly` and `hours`, boolean `sample`, plus `color`, `initials`, `duration`, `breakRequirement`, `compensation`, and `perks`. Courses are `{skill, title, provider, url, cost}` and the UI looks them up by `skill`. `functions/func2.py` sends non-sample catalog rows to Gemini as `programs`. `calculate_plan` skips any saved card whose `hourly` is missing or zero, and it treats `hourly` as an hourly wage (`hourly * hours * 52 / 12`).

A later change can point a new loader at this folder, for example `DATA_DIR / 'resources' / 'ReturnReady_Resources_v3.json'`, then:

1. Keep `opportunities` where `demo_ok` is true.
2. Badge `type` in `sample` or `synthetic`, and map that to the app's `sample: true`.
3. Map `org` or `organization` to `provider`, and map `kind` onto the app's `type` strings the filters expect. `format` / `flexibility` are arrays; `style` in the app is one string.
4. Do not copy `pay_monthly_gross` into `hourly`. Leave pay unset unless a teammate converts it on purpose. Sample cards that need the calculator still need an explicit hourly rate.
5. Map seed `courses[]` separately. They key off `closes_gap` / `title`, not `skill`.
6. For the hackathon demo deck, load `ReturnReady_seed_opportunities_v3.json` (8 cards + 6 courses). Use the 143-row demo-ok file for a directory view, not the 3-minute swipe deck.

`data/utah_childcare_table4_oct2026.json` is unrelated: it is the DWS Table 4 copay table (`source`, `effective`, `households`), not a resource list.
