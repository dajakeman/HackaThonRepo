# ReturnReady Utah — resource directory v3

Merged catalog for Hack for Humanity SLC / ReturnReady Utah, 2026-11-14 (Mountain Time).
This file can be pasted into the README data-sources section and used for MLH submission field 8 (data sources).

## How to use these files

- **ReturnReady_Resources_v3.json** — best for the website / AI Studio build. Load `opportunities[]`. Filter `demo_ok == true` for the live demo. `type: sample` rows are fictional cards from Claude's seed.
- **ReturnReady_Resources_v3.xlsx** (and `.csv`) — best for teammates who want to edit in a spreadsheet. The workbook has All resources, Demo-safe, Data dictionary, and Conflicts sheets, with a frozen header and filters.
- **This Markdown directory** — best for humans skimming by audience, and for the README / submission.

## Counts

- **193 total** entries after deduplication
- **143 demo_ok** (safe to consider for the live demo, after a same-day check)
- **6 sample** (fictional) and **187 real**
- **166 URL-verified**, 14 unverified-blocked, 13 with no URL
- Source coverage: GrokBot 78, Claude 44, ChatGPT 121 (an entry can come from more than one)

**Live demo rule:** Show Tech-Moms plus clearly labeled sample cards, and any other `demo_ok` row you have rechecked the same day. Do not present Fidelity, Goldman Sachs, Return Utah, ARUP, Learn & Work, or WOTC as a currently open / currently applicable program.

## By audience

### Caregivers and career-break returners

#### Returnship

- 16-Week Project Coordinator Returnship — Sample Co. - Lehi tech company. _sample, SAMPLE, demo-ok, Claude_
  Paid returnship for people with a 2+ year career break, with a mentor and a path to a full-time role.
- [iRelaunch Return to Work Programs](https://www.irelaunch.com/returnships) — iRelaunch (national). _ongoing, demo-ok, GrokBot_
  iRelaunch’s return-to-work / returnship program listings for professionals restarting after a career break. Application status is set by each employer.
- [Path Forward Returnships](https://pathforward.org/returnships/) — Path Forward (national). _ongoing, demo-ok, GrokBot+Claude_
  Path Forward’s returnship listings and matcher point caregivers and other career returners to employer return-to-work programs in the U.S. Individual employer programs open and close; confirm status on each listing.
- Amazon Returnship — Amazon (National/Remote). _unknown, not for live demo, Claude_
  16-week paid returnship for professionals who have been out of work for a year or more, with a path to a permanent role.
- [ARUP Laboratories Returnship](https://www.aruplab.com/careers/returnships) — ARUP Laboratories (Salt Lake City, UT). _interest_list, not for live demo, GrokBot+Claude+ChatGPT_
  Paid short-term returnship at ARUP in Salt Lake City for skilled people with at least a one-year employment gap, or who have been on active military duty. Tracks include technical (IT and lab work), business, and operations, with mentorship. The careers page invites applicants to browse open returnship jobs or submit a Returnship Interest Form if no current posting fits.
- [Fidelity RESUME Return-to-Work Program](https://jobs.fidelity.com/in/life-at-fidelity/resume-program/) — Fidelity Investments (national). _closed, not for live demo, GrokBot+ChatGPT_
  Fidelity’s RESUME program is described as a paid six-month internship with mentorship and training for women on a career break who want to re-enter the workforce, across areas such as operations, technology, analytics, research, data, and corporate services.
- [Goldman Sachs Returnship](https://www.goldmansachs.com/careers/programs-for-professionals/returnship) — Goldman Sachs (Salt Lake City, UT). _interest_list, not for live demo, GrokBot+Claude+ChatGPT_
  Paid 12-week returnship for experienced professionals who have been out of full-time work for two or more years and have at least three years of prior work experience. The official page lists Salt Lake City, UT among Americas locations (availability varies by division). The Americas cohort is described as January–March 2027; the page says to register to receive an invitation when applications open.
- Other corporate returnships (J.P. Morgan ReEntry, J&J Re-Ignite, Deloitte Encore, Intuit Again, Lockheed Martin Chapter Next, Fidelity RESUME, Dell Career ReStart, Cummins RePower, Chevron Welcome Back, and more) — Various employers (National). _unknown, not for live demo, Claude_
  Named employer return-to-work programs; check each one's status through the Path Forward Returnship Matcher.
- [Return Utah (State Government Returnship)](https://dhrm.utah.gov/hiring-pathways/return-utah/) — State of Utah / Division of Human Resource Management (Lt. Governor initiative) (Utah-statewide). _no_opening_seen, not for live demo, GrokBot+Claude+ChatGPT_
  A state government return-to-work program that fills mid-level public jobs with people who have had an extended career break (including parenthood, caregiving, military service, disability, education, or retirement). Participants may receive training, coaching, and development support. Utah residency and generally a one-year career break apply; military-connected applicants and some underemployed people have exceptions.
- Returnship partners: Women Back to Work, The Mom Project, reacHIRE — Various (National). _unknown, not for live demo, Claude_
  Organizations that run or list returner cohorts and openings with employer partners.
- [Wells Fargo Glide – Relaunch USA](https://www.wellsfargojobs.com/en/inclusion/return-to-work-programs/glide-relaunch-usa/) (United States, location varies). _interest_list, not for live demo, ChatGPT_
  Review the U.S. program and use the interest form for updates. Confirm the location of an individual posting.

#### Education

- [Coursera Financial Aid](https://www.coursera.org/about/financial-aid) — Coursera (remote). _ongoing, demo-ok, GrokBot_
  Coursera’s official financial aid information for learners who cannot afford a paid course or certificate. Apply from the individual course page following Coursera’s instructions.
- [Excel / spreadsheet basics](https://edu.gcfglobal.org/en/excel/) — GCFGlobal / LearnFree (remote). _ongoing, demo-ok, Claude_
  Short refresher course listed in Claude's seed data (GCFGlobal). Confirm current cost and enrollment on the provider site.
- [Google Career Certificates (Grow with Google)](https://grow.google/certificates/) — Google / Grow with Google (remote). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Online job-ready certificate programs from Grow with Google. The official certificates page is the place to confirm current offerings, cost, and how to enroll.
- [Inbound / CRM fundamentals](https://academy.hubspot.com/) — HubSpot Academy (remote). _ongoing, demo-ok, Claude_
  Short refresher course listed in Claude's seed data (HubSpot Academy). Confirm current cost and enrollment on the provider site.
- [Microsoft 365 and Excel modules](https://learn.microsoft.com/en-us/training/) — Microsoft Learn (remote). _ongoing, demo-ok, Claude_
  Short refresher course listed in Claude's seed data (Microsoft Learn). Confirm current cost and enrollment on the provider site.
- [Women’s Business Center of Utah](https://www.wbcutah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot+ChatGPT_
  Utah organization that helps women start and grow businesses. See the site for current counseling, training, and events.
- Medical terminology short course — Utah tech college (via Learn & Work) - verify (remote). _check_provider, not for live demo, Claude_
  Short refresher course listed in Claude's seed data (Utah tech college (via Learn & Work) - verify). Confirm current cost and enrollment on the provider site.
- QuickBooks Online training — Intuit (remote). _check_provider, not for live demo, Claude_
  Short refresher course listed in Claude's seed data (Intuit). Confirm current cost and enrollment on the provider site.
- [USU Extension Relaunching Your Career](https://extensioncourses.usu.edu/product/relaunching-your-career-bundle/) (Utah-based, online). _ongoing, not for live demo, ChatGPT_
  Review this self-paced course on career exploration, résumé writing, interviews, and networking. Check the listed price before enrolling.
- [Utah State University Learn and Work in Utah (historical page)](https://www.usu.edu/learnwork/) — Utah State University (Utah-statewide). _historical_only, not for live demo, GrokBot+Claude+ChatGPT_
  USU page describing Learn and Work short-term certificates (for example manufacturing, community health worker, and CDL) with tuition help that the page ties to COVID-era CARES Act funding for eligible unemployed or underemployed Utah residents.
- [Utah State University Online](https://www.usu.edu/online/) — Utah State University (remote). _historical_only, not for live demo, GrokBot_
  USU’s official online-education page for current distance-learning programs. Confirm current degrees, certificates, costs, and how to apply on the site.

#### Nonprofit

- [Dress for Success (national network)](https://dressforsuccess.org/) — Dress for Success Worldwide (national). _ongoing, demo-ok, GrokBot_
  Nonprofit network that helps women gain professional attire and career support. Use the national site to find a local affiliate.
- [Employment & Workforce Development Resource Kit](https://www.usu.edu/uwlp/resources/employment-workforce-development-resource-kit) — Utah Women & Leadership Project (USU) (Utah). _ongoing, demo-ok, Claude_
  Curated list of Utah and national return-to-work resources, research and organizations for women.
- [Family Caregiver Alliance Utah Resource Locator](https://www.caregiver.org/connecting-caregivers/services-by-state/utah/) (Utah). _ongoing, demo-ok, ChatGPT_
  Find caregiving and respite supports that may free up time for training or work.
- [Goodwill of Utah (Deseret Industries / Goodwill Utah)](https://goodwillutah.com/) — Goodwill Utah (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Utah Goodwill provides community employment and related services (see the official site for current programs, locations, and how to get help).
- [iRelaunch](https://www.irelaunch.com/) (national). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Organization focused on career reentry after a career break. The site offers return-to-work resources, a job board, and returnship program information.
- [Path Forward](https://pathforward.org/) (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Nonprofit that helps people restart careers after a caregiving break. The site includes return-to-work resources and a returnship matcher for U.S. programs.
- [People Helping People](https://www.phputah.org/become-a-client) (Utah). _ongoing, demo-ok, ChatGPT_
  Use the Become a Client page for intake, workshops, and employment coaching.
- [reacHIRE Returnship Programs](https://www.reachire.com/returnship-programs-for-returners) (United States, role-specific). _ongoing, demo-ok, ChatGPT_
  Browse programs or join the talent network. Confirm Utah or remote eligibility for each role.
- [Tech-Moms Tech Career Program](https://www.tech-moms.org/) — Tech-Moms (Utah nonprofit) (Utah-statewide). _check_provider, demo-ok, GrokBot+Claude+ChatGPT_
  Utah nonprofit that helps people, especially moms, transition into tech through a part-time technical skills course (the site describes a nine-week intro to web development and other tech careers), professional networking, and career exploration. The site also lists next-steps training and returnships.
- [Utah Women & Leadership Project](https://www.usu.edu/uwlp/) — Utah State University / Utah Women & Leadership Project (Utah-statewide). _ongoing, demo-ok, GrokBot_
  USU-based project that publishes research and resources on Utah women, work, and related issues, including family and childcare resource pages.
- [YWCA Utah](https://www.ywcautah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Utah nonprofit offering services that include child care, case management, and food services, among other community supports listed on its site.
- [Dress for Success Salt Lake City](https://saltlakecity.dressforsuccess.org/) (Salt Lake City, UT). _unknown, not for live demo, GrokBot_
  Salt Lake City affiliate of Dress for Success, which helps women with professional clothing and career services. Confirm hours and how to request services on the affiliate site.
- [Elavare Return-to-Work Coaching](https://elavare.com/) — Elavare / Elavare Foundation (Utah-statewide). _check_provider, not for live demo, GrokBot+Claude+ChatGPT_
  Elavare helps mothers return to the workforce through coaching, workshops, community, and free DIY resources. The related Elavare Foundation is described on the site as a 501(c)(3) that provides scholarships and free training.

#### Agency

- [American Job Center Finder (CareerOneStop)](https://www.careeronestop.org/LocalHelp/AmericanJobCenters/find-american-job-centers.aspx) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot_
  Official locator for American Job Centers, which provide locally available employment and training help, including services often funded under WIOA.
- [Salt Lake County Caregiver Resources](https://www.saltlakecounty.gov/aging-adult-services/support/caregiver-support/caregiver-resources/) (Salt Lake County). _ongoing, demo-ok, ChatGPT_
  Explore support and local resources while planning work or training.
- [Utah 211](https://211utah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Free, confidential help connecting Utahns to health, social, and government services. Dial 2-1-1 or use the website to find local resources.
- [Utah Aging & Adult Services Caregiver Support](https://daas.utah.gov/services/) — Utah Division of Aging and Adult Services (DHHS) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  State caregiver-support program for unpaid caregivers of older adults, people with dementia of any age, people with disabilities, and older adults caring for minor children. Services described include resources, counseling, education, support groups, respite care, and assistive supplies.
- [Utah Department of Workforce Services](https://jobs.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s workforce agency helps people find jobs, apply for assistance (including food, child care, Medicaid, and unemployment insurance), and connect to training and employment-center services.
- [Utah DWS Apply for Assistance](https://jobs.utah.gov/assistance/index.html) — Utah Department of Workforce Services (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Portal to DWS assistance programs, including food, child care, medical, financial, disability, and unemployment insurance help.
- [Utah DWS Rejoining the Workforce](https://jobs.utah.gov/jobseeker/career/rejoin.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Start with DWS reentry resources and request individual employment guidance.
- [Workforce Innovation and Opportunity Act (WIOA)](https://www.dol.gov/agencies/eta/wioa) — U.S. Department of Labor, Employment and Training Administration (national). _ongoing, demo-ok, GrokBot_
  Federal workforce law that funds employment and training services, typically accessed through American Job Centers and state workforce agencies such as Utah DWS.

#### Job Board

- Part-Time Bookkeeper (School Hours) — Sample Co. - Wasatch Family Dental. _sample, SAMPLE, demo-ok, Claude_
  Mon-Fri 9:00-2:00. Accounts payable/receivable and payroll prep.
- Patient Scheduler — Sample Co. - Utah County clinic. _sample, SAMPLE, demo-ok, Claude_
  Schedule appointments and handle front-desk calls. Day shifts only.
- Remote Customer Success Associate — Sample Co. - Silicon Slopes SaaS (remote). _sample, SAMPLE, demo-ok, Claude_
  Help customers onboard and solve problems by phone, chat, and email.
- School Paraprofessional — Sample Co. - Alpine-area school. _sample, SAMPLE, demo-ok, Claude_
  Support teachers and students in small groups. Same calendar as the school year.
- Volunteer Coordinator — Sample Co. - Salt Lake food pantry nonprofit. _sample, SAMPLE, demo-ok, Claude_
  Recruit, schedule, and lead volunteers; plan two fundraising events a year.
- [Fairygodboss](https://fairygodboss.com/) (national). _ongoing, demo-ok, GrokBot_
  Career community and job platform aimed at women, including company reviews and job listings.
- [PowerToFly](https://powertofly.com/) (remote). _ongoing, demo-ok, GrokBot_
  Job platform that connects candidates, including women and people seeking remote work, with employers.
- [The Mom Project](https://themomproject.com/) (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Talent marketplace connecting skilled parents and caregivers with employers for remote, hybrid, and in-person jobs.
- [FlexJobs](https://www.flexjobs.com/) (remote). _unknown, not for live demo, GrokBot_
  Job board that focuses on remote, flexible, and work-from-home roles, often used by caregivers and others who need schedule flexibility.

#### Childcare

- [Care About Childcare (Utah)](https://cac.utah.gov/) — Utah Department of Workforce Services, Office of Child Care (Utah-statewide). _ongoing, demo-ok, GrokBot+ChatGPT_
  Utah’s official tool for finding child care providers and related information. The DWS child care page points families to Care About Childcare (cac.utah.gov) to search for providers.
- [Head Start Center Locator](https://www.headstart.gov/center-locator) — U.S. Head Start / HeadStart.gov (national). _ongoing, demo-ok, GrokBot_
  Official federal locator for Head Start and Early Head Start programs, which provide early childhood education and family support for eligible households.
- [Utah Employment Support Child Care (DWS Child Care Assistance)](https://jobs.utah.gov/customereducation/services/childcare/employmentsupport.html) — Utah Department of Workforce Services, Office of Child Care (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s child care assistance program can help eligible families pay all or part of child care costs. Applicants must generally be a parent or legal caregiver, meet income rules, and work at least 15 hours a week (two-parent rules differ). Apply through myCase at jobs.utah.gov/mycase or with help at an employment center (1-866-435-7414).
- [Utah Head Start Association — Find a Program](https://www.uhsa.org/programs/find-a-program) — Utah Head Start Association (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Utah Head Start Association page to find Head Start and Early Head Start programs in the state.
- [Utah Office of Child Care](https://jobs.utah.gov/occ/) — Utah Department of Workforce Services, Office of Child Care (Utah-statewide). _ongoing, demo-ok, GrokBot_
  State office that administers child care assistance, provider resources, and related child care programs in Utah.

#### Legal Aid

- [Utah Legal Services](https://www.utahlegalservices.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Nonprofit civil legal aid organization that provides free help in civil matters (the site lists areas such as housing, family, domestic violence, public benefits including food stamps, financial assistance, Medicaid, and SSI/SSDI, consumer issues, and senior estate planning). Apply through the official site. This is not a criminal-defense office.

### People with justice involvement

#### Returnship

- [JPMorganChase ReEntry Program](https://www.jpmorganchase.com/careers/explore-opportunities/programs/reentry-program) (United States, location varies). _check_provider, not for live demo, ChatGPT_
  Check the employer's eligibility and location for the current cohort. Utah and remote status were unconfirmed.
- Other corporate returnships (J.P. Morgan ReEntry, J&J Re-Ignite, Deloitte Encore, Intuit Again, Lockheed Martin Chapter Next, Fidelity RESUME, Dell Career ReStart, Cummins RePower, Chevron Welcome Back, and more) — Various employers (National). _unknown, not for live demo, Claude_
  Named employer return-to-work programs; check each one's status through the Path Forward Returnship Matcher.

#### Education

- [Salt Lake Community College Prison Education Program](https://www.slcc.edu/prison-education/index.aspx) — Salt Lake Community College (Utah-statewide). _ongoing, demo-ok, GrokBot_
  SLCC’s Prison Education Program provides college coursework for incarcerated students. The college is identified in public higher-education materials as offering this programming in Utah.
- [The Last Mile](https://thelastmile.org/) (national). _ongoing, demo-ok, GrokBot_
  Organization that provides technology education, including web development, in prisons and supports fair-chance hiring of alumni.
- [The Other Side Academy](https://www.theothersideacademy.com/how-to-apply/) (Utah, Salt Lake City). _check_provider, not for live demo, ChatGPT_
  Read admissions and program commitments. This is a residential program with vocational training.

#### Nonprofit

- [CareerOneStop Justice-Impacted Toolkit and ReEntry Program Finder](https://www.careeronestop.org/JusticeImpacted/Toolkit/find-reentry-programs.aspx) — U.S. Department of Labor (National). _ongoing, demo-ok, Claude+ChatGPT_
  Tools for people with records: local reentry program finder, state resource finder, training finder, work-ready checklist and a 5-step 'Find a Job After Incarceration' guide. A separate ReEntry site is built for use inside correctional facilities.
- [Defy Ventures](https://defyventures.org/) (national). _ongoing, demo-ok, GrokBot_
  Nonprofit that provides entrepreneurship and employment-readiness programming for justice-involved people. Confirm current Utah program availability on the official site.
- [Fair Chance Hiring Guide](https://slchamber.com/fair-chance-hiring-guide/) — Salt Lake Chamber (Utah). _ongoing, demo-ok, Claude_
  Employer guide to hiring people with records in Utah - useful to share with prospective employers.
- [Goodwill of Utah (Deseret Industries / Goodwill Utah)](https://goodwillutah.com/) — Goodwill Utah (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Utah Goodwill provides community employment and related services (see the official site for current programs, locations, and how to get help).
- [Jails to Jobs - Resources](https://jailstojobs.org/resources/employer-incentives/) — Jails to Jobs (nonprofit) (National). _ongoing, demo-ok, Claude+ChatGPT_
  Nonprofit resource pages on job search after incarceration and employer incentives.
- [Library of Congress Reentry Employment Guide](https://guides.loc.gov/reentry-resources/employment) (United States online). _ongoing, demo-ok, ChatGPT_
  Browse employment and training resource links for justice-impacted people.
- [U.S. Probation District of Utah Workforce Resources](https://www.utp.uscourts.gov/workforce-resources) (Utah). _ongoing, demo-ok, ChatGPT_
  Browse the court's employment and training resource list. Check provider intake requirements.
- [Center for Employment Opportunities (CEO)](https://www.ceoworks.org/) — Center for Employment Opportunities (national). _check_provider, not for live demo, GrokBot+ChatGPT_
  National nonprofit that provides employment services for people with recent justice involvement. Confirm on the site whether programming is available in or near Utah.
- [Salt Lake County Jail Resource and Reentry Program](https://www.saltlakecounty.gov/criminal-justice-services/pretrial/jrrp---jail-re-entry-resource-program/) — Salt Lake County (Utah). _check_provider, not for live demo, Claude+ChatGPT_
  Reentry planning and referrals for treatment, housing, employment support, Medicaid help and transportation after jail release.
- [Utah County Reentry Resource – Employment](https://utahcountyreentry.org/employment/) (Utah County). _ongoing, not for live demo, ChatGPT_
  Browse the county-area employment resources and verify details with the listed provider.

#### Agency

- [American Job Center Finder (CareerOneStop)](https://www.careeronestop.org/LocalHelp/AmericanJobCenters/find-american-job-centers.aspx) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot_
  Official locator for American Job Centers, which provide locally available employment and training help, including services often funded under WIOA.
- [The Federal Bonding Program](https://bonds4jobs.com/) — The Federal Bonding Program (U.S. Department of Labor-related) (national). _ongoing, demo-ok, GrokBot+Claude_
  Provides no-cost fidelity bonding for employers who hire eligible job seekers with barriers to employment, such as a criminal record or limited work history. The bond is an employer tool, not a cash benefit to the worker.
- [Utah 211](https://211utah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Free, confidential help connecting Utahns to health, social, and government services. Dial 2-1-1 or use the website to find local resources.
- [Utah Corrections Workforce Development](https://corrections.utah.gov/about-us/workforce-development/) (Utah correctional system). _ongoing, demo-ok, ChatGPT_
  Ask corrections staff about credentials, training, and employer partnerships.
- [Utah Courts Adult Expungement Self-Help](https://www.utcourts.gov/en/self-help/case-categories/criminal-justice/expunge.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Read court instructions and use the listed self-help and legal resources.
- [Utah Department of Corrections Reentry and Rehabilitation](https://corrections.utah.gov/inmate-services/reentry-and-rehabilitation/) — Utah Department of Corrections (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  UDC’s Reentry and Rehabilitation services help people leaving incarceration plan for return to the community, including connections to workforce, vocational rehabilitation, and other supports.
- [Utah Department of Workforce Services](https://jobs.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s workforce agency helps people find jobs, apply for assistance (including food, child care, Medicaid, and unemployment insurance), and connect to training and employment-center services.
- [Utah DOPL Criminal History Determination](https://commerce.utah.gov/dopl/criminal-history-guidelines/application-for-criminal-history-determination/) (Utah). _ongoing, demo-ok, ChatGPT_
  Check whether the agency can review criminal history for the specific license before committing to training.
- [Utah DWS Federal Bonding Program](https://jobs.utah.gov/services/bond.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask Utah DWS if employer bonding can help with a specific hire.
- [Workforce Innovation and Opportunity Act (WIOA)](https://www.dol.gov/agencies/eta/wioa) — U.S. Department of Labor, Employment and Training Administration (national). _ongoing, demo-ok, GrokBot_
  Federal workforce law that funds employment and training services, typically accessed through American Job Centers and state workforce agencies such as Utah DWS.
- [Work Opportunity Tax Credit (WOTC)](https://www.dol.gov/agencies/eta/wotc) — U.S. Department of Labor, Employment and Training Administration (national). _check_provider, not for live demo, GrokBot+Claude_
  A federal tax credit for employers who hire people from targeted groups (including certain veterans, people with disabilities, and others with employment barriers). Job seekers do not apply for the credit themselves; employers and workforce agencies handle certification.

#### Job Board

- [Honest Jobs](https://www.honestjobs.com/) (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Online platform focused on fair-chance employment and reentry support for people with criminal records.
- [70 Million Jobs](https://www.70millionjobs.com/) (national). _unknown, not for live demo, GrokBot_
  Job platform historically focused on employment for people with criminal records. Confirm current services on the official site; this research environment could not complete a TLS connection.

#### Legal Aid

- [Clean Slate Utah Legal Resources](https://www.cleanslateutah.org/legal-resources) (Utah). _ongoing, demo-ok, ChatGPT_
  Find legal help and clinic referrals. A provider can assess eligibility.
- [Utah Legal Services](https://www.utahlegalservices.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Nonprofit civil legal aid organization that provides free help in civil matters (the site lists areas such as housing, family, domestic violence, public benefits including food stamps, financial assistance, Medicaid, and SSI/SSDI, consumer issues, and senior estate planning). Apply through the official site. This is not a criminal-defense office.

### People with disabilities

#### Returnship

- [ARUP Laboratories Returnship](https://www.aruplab.com/careers/returnships) — ARUP Laboratories (Salt Lake City, UT). _interest_list, not for live demo, GrokBot+Claude+ChatGPT_
  Paid short-term returnship at ARUP in Salt Lake City for skilled people with at least a one-year employment gap, or who have been on active military duty. Tracks include technical (IT and lab work), business, and operations, with mentorship. The careers page invites applicants to browse open returnship jobs or submit a Returnship Interest Form if no current posting fits.
- [BlackRock Career Returnship Programs](https://careers.blackrock.com/en/career-returnship-programs) (Multiple markets, location varies). _check_provider, not for live demo, ChatGPT_
  Check the current cohort, application window, and office or work style.
- [CDK Global Returnship](https://careers.cdkglobal.com/returnship/) (United States, role-specific). _interest_list, not for live demo, ChatGPT_
  Check CDK's program and talent community. Verify location and work style for each role.
- [Deloitte US Return to Work](https://www.deloitte.com/us/en/careers/join-deloitte/return-to-work.html) (United States, location varies). _check_provider, not for live demo, ChatGPT_
  Check the program page for the next opportunity and location.
- [Goldman Sachs Returnship](https://www.goldmansachs.com/careers/programs-for-professionals/returnship) — Goldman Sachs (Salt Lake City, UT). _interest_list, not for live demo, GrokBot+Claude+ChatGPT_
  Paid 12-week returnship for experienced professionals who have been out of full-time work for two or more years and have at least three years of prior work experience. The official page lists Salt Lake City, UT among Americas locations (availability varies by division). The Americas cohort is described as January–March 2027; the page says to register to receive an invitation when applications open.
- [JPMorganChase ReEntry Program](https://www.jpmorganchase.com/careers/explore-opportunities/programs/reentry-program) (United States, location varies). _check_provider, not for live demo, ChatGPT_
  Check the employer's eligibility and location for the current cohort. Utah and remote status were unconfirmed.
- [Lockheed Martin Chapter Next](https://lockheedmartincareers.com/en-us/careers/candidates/ex-pro/return-to-work.html) (United States, role-specific). _check_provider, not for live demo, ChatGPT_
  Review the employer program and verify the current requisition and work location.
- [Morgan Stanley Return to Work](https://www.morganstanley.com/people-opportunities/return-to-work) (South Jordan, Utah lead and other U.S. locations). _check_provider, not for live demo, ChatGPT_
  An employer-hosted South Jordan listing surfaced. Current application status could not be confirmed. Check the program page for current roles and locations.
- [Northrop Grumman iReturn](https://www.northropgrumman.com/careers/ireturn-the-northrop-grumman-returnship-program) (United States, role-specific). _check_provider, not for live demo, ChatGPT_
  Review the employer's eligibility and search for a current requisition.
- [Return Utah (State Government Returnship)](https://dhrm.utah.gov/hiring-pathways/return-utah/) — State of Utah / Division of Human Resource Management (Lt. Governor initiative) (Utah-statewide). _no_opening_seen, not for live demo, GrokBot+Claude+ChatGPT_
  A state government return-to-work program that fills mid-level public jobs with people who have had an extended career break (including parenthood, caregiving, military service, disability, education, or retirement). Participants may receive training, coaching, and development support. Utah residency and generally a one-year career break apply; military-connected applicants and some underemployed people have exceptions.
- [UBS Career Comeback](https://www.ubs.com/global/en/careers/professional-careers/career-comeback.html) (Multiple markets, location varies). _check_provider, not for live demo, ChatGPT_
  Review program requirements and search available roles. Local availability depends on the posting.
- [Wells Fargo Glide – Relaunch USA](https://www.wellsfargojobs.com/en/inclusion/return-to-work-programs/glide-relaunch-usa/) (United States, location varies). _interest_list, not for live demo, ChatGPT_
  Review the U.S. program and use the interest form for updates. Confirm the location of an individual posting.

#### Education

- [UVU Adult Learner Admissions](https://www.uvu.edu/admissions/adult-learners/index.html) (Utah County and available online programs). _ongoing, demo-ok, ChatGPT_
  Connect with adult admissions and ask about prior learning, program format, and support.
- [USU Master Remote Work Professional](https://extensioncourses.usu.edu/product/master-remote-work-professional-certificate-course/) (Utah-based, online). _check_provider, not for live demo, ChatGPT_
  Review dates, prerequisites, and current enrollment terms for the course.

#### Nonprofit

- [Goodwill of Utah (Deseret Industries / Goodwill Utah)](https://goodwillutah.com/) — Goodwill Utah (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Utah Goodwill provides community employment and related services (see the official site for current programs, locations, and how to get help).
- [iRelaunch](https://www.irelaunch.com/) (national). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Organization focused on career reentry after a career break. The site offers return-to-work resources, a job board, and returnship program information.
- [reacHIRE Returnship Programs](https://www.reachire.com/returnship-programs-for-returners) (United States, role-specific). _ongoing, demo-ok, ChatGPT_
  Browse programs or join the talent network. Confirm Utah or remote eligibility for each role.
- [U.S. SBA Local Assistance](https://www.sba.gov/counseling/local-assistance/) (United States). _ongoing, demo-ok, ChatGPT_
  Find nearby SBA partners including SCORE and Small Business Development Centers.
- [Upwardly Global Job Seeker Resources](https://www.upwardlyglobal.org/job-seeker-resources/) (United States online, eligibility varies). _ongoing, demo-ok, ChatGPT_
  Review job-search resources and check eligibility for individualized coaching.
- [Utah Centers for Independent Living](https://extension.usu.edu/agrability/utah-centers-for-independent-living) (Utah, regional). _ongoing, demo-ok, ChatGPT_
  Find a center for independent living and ask about referrals and workplace-related supports.
- [Utah Choose to Work](https://jobs.utah.gov/usor/vr/employer/choose.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask your VR counselor about referrals for job placement and employer connections.

#### Agency

- [American Job Center Finder (CareerOneStop)](https://www.careeronestop.org/LocalHelp/AmericanJobCenters/find-american-job-centers.aspx) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot_
  Official locator for American Job Centers, which provide locally available employment and training help, including services often funded under WIOA.
- [Job Accommodation Network (JAN)](https://askjan.org/about-us/) — U.S. Department of Labor (ODEP) / Job Accommodation Network (National). _ongoing, demo-ok, Claude+ChatGPT_
  Free guidance on workplace accommodations, including a Situations and Solutions Finder tool.
- [Social Security Ticket to Work](https://choosework.ssa.gov/) — U.S. Social Security Administration (national). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Ticket to Work offers free employment support for eligible Social Security disability beneficiaries who want to work, including help connecting to employment networks and related services.
- [USAJOBS Disability Hiring Path](https://www.usajobs.gov/hiringpath/individualswithdisabilities) (United States). _ongoing, demo-ok, ChatGPT_
  Review disability hiring routes and check each job announcement.
- [Utah 211](https://211utah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Free, confidential help connecting Utahns to health, social, and government services. Dial 2-1-1 or use the website to find local resources.
- [Utah Assistive Technology Program](https://idrpp.usu.edu/uatp/) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask about device demonstrations, loans, reuse, or technology support.
- [Utah Department of Workforce Services](https://jobs.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s workforce agency helps people find jobs, apply for assistance (including food, child care, Medicaid, and unemployment insurance), and connect to training and employment-center services.
- [Utah DSPD Services](https://dspd.utah.gov/services/) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask about employment supports and provider referrals for eligible participants.
- [Utah DWS Apply for Assistance](https://jobs.utah.gov/assistance/index.html) — Utah Department of Workforce Services (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Portal to DWS assistance programs, including food, child care, medical, financial, disability, and unemployment insurance help.
- [Utah DWS Career and Education Assistance](https://jobs.utah.gov/career/) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask about career counseling, training funding, work experience, and the Eligible Training Provider List.
- [Utah DWS Child Care Assistance](https://jobs.utah.gov/customereducation/services/childcare/) (Utah). _ongoing, demo-ok, ChatGPT_
  Read state program information and apply or ask DWS for an eligibility determination.
- [Utah Employment-related Personal Assistant Services](https://medicaid.utah.gov/ltc-2/epas/) (Utah). _ongoing, demo-ok, ChatGPT_
  Review the Medicaid service and ask the agency about eligibility.
- [Utah Medicaid Work Incentive Program](https://medicaid.utah.gov/medicaid-work-incentive-program/) (Utah). _ongoing, demo-ok, ChatGPT_
  Read the state overview and ask Medicaid or a benefits counselor about your situation.
- [Utah Services for Blind and Visually Impaired](https://jobs.utah.gov/usor/dsbvi/) (Utah). _ongoing, demo-ok, ChatGPT_
  Contact the division about rehabilitation, training, and job-related help.
- [Utah State Employment Pathways for People with Disabilities](https://jobs.utah.gov/usor/vr/pathways.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Explore state hiring pathways and how to contact the program.
- [Utah State Office of Rehabilitation](https://jobs.utah.gov/usor/index.html) — Utah State Office of Rehabilitation (DWS) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  USOR helps Utahns with disabilities obtain meaningful employment and increase independence, including vocational rehabilitation and related disability services.
- [Utah Vocational Rehabilitation](https://jobs.utah.gov/usor/vr/services/index.html) — Utah State Office of Rehabilitation (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Vocational Rehabilitation helps people with physical, intellectual, mental health, and sensory disabilities find competitive employment and address barriers to work. Apply after a short eligibility assessment; toll-free office help is 866-454-8397.
- [Utah VR Supported Employment](https://jobs.utah.gov/usor/vr/services/work.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask a VR counselor about supported employment and available services.
- [Utah Work Incentive Planning Services](https://jobs.utah.gov/usor/vr/services/uwips.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask a benefits counselor how earnings might affect your specific benefits.
- [VA Veteran Readiness and Employment (Chapter 31 / VR&E)](https://www.va.gov/careers-employment/vocational-rehabilitation/) — U.S. Department of Veterans Affairs (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Federal program (also called Chapter 31 or VR&E, formerly Vocational Rehabilitation and Employment) for service members and veterans with a service-connected disability that limits or prevents work. It can help with exploring employment options, training or education, returning to a former job, or related counseling. Apply through VA.
- [Workforce Innovation and Opportunity Act (WIOA)](https://www.dol.gov/agencies/eta/wioa) — U.S. Department of Labor, Employment and Training Administration (national). _ongoing, demo-ok, GrokBot_
  Federal workforce law that funds employment and training services, typically accessed through American Job Centers and state workforce agencies such as Utah DWS.
- [SSA Work Incentives Planning and Assistance](https://www.ssa.gov/work/WIPA.html) (United States). _ongoing, not for live demo, ChatGPT_
  Find individualized benefits counseling before changing earnings or hours.
- [Work Opportunity Tax Credit (WOTC)](https://www.dol.gov/agencies/eta/wotc) — U.S. Department of Labor, Employment and Training Administration (national). _check_provider, not for live demo, GrokBot+Claude_
  A federal tax credit for employers who hire people from targeted groups (including certain veterans, people with disabilities, and others with employment barriers). Job seekers do not apply for the credit themselves; employers and workforce agencies handle certification.

#### Job Board

- [abilityJOBS](https://abilityjobs.com/) (national). _ongoing, demo-ok, GrokBot_
  Job board connecting job seekers with disabilities to employers that post inclusive openings.
- [Getting Hired](https://www.gettinghired.com/) (national). _ongoing, demo-ok, GrokBot_
  Job portal and community focused on employment for people with disabilities.

#### Childcare

- [Utah Employment Support Child Care (DWS Child Care Assistance)](https://jobs.utah.gov/customereducation/services/childcare/employmentsupport.html) — Utah Department of Workforce Services, Office of Child Care (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s child care assistance program can help eligible families pay all or part of child care costs. Applicants must generally be a parent or legal caregiver, meet income rules, and work at least 15 hours a week (two-parent rules differ). Apply through myCase at jobs.utah.gov/mycase or with help at an employment center (1-866-435-7414).

#### Legal Aid

- [Disability Law Center – Utah Vocational Rehabilitation](https://disabilitylawcenter.org/resources/utah-vocational-rehabilitation/) (Utah). _ongoing, demo-ok, ChatGPT_
  Read the nonprofit's state VR guidance and contact it for available support.
- [Utah Legal Services](https://www.utahlegalservices.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Nonprofit civil legal aid organization that provides free help in civil matters (the site lists areas such as housing, family, domestic violence, public benefits including food stamps, financial assistance, Medicaid, and SSI/SSDI, consumer issues, and senior estate planning). Apply through the official site. This is not a criminal-defense office.

### Veterans

#### Returnship

- [ARUP Laboratories Returnship](https://www.aruplab.com/careers/returnships) — ARUP Laboratories (Salt Lake City, UT). _interest_list, not for live demo, GrokBot+Claude+ChatGPT_
  Paid short-term returnship at ARUP in Salt Lake City for skilled people with at least a one-year employment gap, or who have been on active military duty. Tracks include technical (IT and lab work), business, and operations, with mentorship. The careers page invites applicants to browse open returnship jobs or submit a Returnship Interest Form if no current posting fits.
- [Return Utah (State Government Returnship)](https://dhrm.utah.gov/hiring-pathways/return-utah/) — State of Utah / Division of Human Resource Management (Lt. Governor initiative) (Utah-statewide). _no_opening_seen, not for live demo, GrokBot+Claude+ChatGPT_
  A state government return-to-work program that fills mid-level public jobs with people who have had an extended career break (including parenthood, caregiving, military service, disability, education, or retirement). Participants may receive training, coaching, and development support. Utah residency and generally a one-year career break apply; military-connected applicants and some underemployed people have exceptions.

#### Education

- [Apprenticeship.gov](https://www.apprenticeship.gov/) — U.S. Department of Labor (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Official U.S. site to find registered apprenticeships, which combine paid work with structured training.

#### Nonprofit

- [Hire Heroes USA](https://www.hireheroesusa.org/) (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Nonprofit that provides career services and job-search support for veterans, transitioning service members, and military spouses.
- [Hiring Our Heroes](https://www.hiringourheroes.org/career-services/) (United States, options vary). _ongoing, demo-ok, ChatGPT_
  Review fellowships, career fairs, and education or networking options.

#### Agency

- [American Job Center Finder (CareerOneStop)](https://www.careeronestop.org/LocalHelp/AmericanJobCenters/find-american-job-centers.aspx) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot_
  Official locator for American Job Centers, which provide locally available employment and training help, including services often funded under WIOA.
- [CareerOneStop](https://www.careeronestop.org/) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot+Claude_
  A U.S. Department of Labor-sponsored site for career exploration, job search, training, and local help, including tools to find money for training.
- [Military OneSource Spouse Career and Education Support](https://www.militaryonesource.mil/education-employment/for-spouses/) (United States and eligible military communities). _ongoing, demo-ok, ChatGPT_
  Ask about career coaching, scholarships, and employer connections.
- [Utah 211](https://211utah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Free, confidential help connecting Utahns to health, social, and government services. Dial 2-1-1 or use the website to find local resources.
- [Utah Department of Veterans and Military Affairs](https://veterans.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  State agency that helps Utah veterans, service members, and their families with VA claims assistance, education-benefit information, and other state and federal benefits. The site also includes information for spouses and family members and a section for employers looking to hire veterans and military spouses.
- [Utah Department of Workforce Services](https://jobs.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s workforce agency helps people find jobs, apply for assistance (including food, child care, Medicaid, and unemployment insurance), and connect to training and employment-center services.
- [Utah DWS Veterans Employment](https://jobs.utah.gov/veteran/) (Utah). _ongoing, demo-ok, ChatGPT_
  Review Utah employment help and ask which specialized services apply.
- [Utah State Veteran Hiring Pathway](https://dhrm.utah.gov/hiring-pathways/veterans/) (Utah). _ongoing, demo-ok, ChatGPT_
  Review state hiring pathways and check current postings.
- [VA Veteran Readiness and Employment (Chapter 31 / VR&E)](https://www.va.gov/careers-employment/vocational-rehabilitation/) — U.S. Department of Veterans Affairs (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Federal program (also called Chapter 31 or VR&E, formerly Vocational Rehabilitation and Employment) for service members and veterans with a service-connected disability that limits or prevents work. It can help with exploring employment options, training or education, returning to a former job, or related counseling. Apply through VA.
- [Work Opportunity Tax Credit (WOTC)](https://www.dol.gov/agencies/eta/wotc) — U.S. Department of Labor, Employment and Training Administration (national). _check_provider, not for live demo, GrokBot+Claude_
  A federal tax credit for employers who hire people from targeted groups (including certain veterans, people with disabilities, and others with employment barriers). Job seekers do not apply for the credit themselves; employers and workforce agencies handle certification.

#### Legal Aid

- [Utah@EASE Veteran Legal Referral Program](https://attorneygeneral.utah.gov/utahease/) — Utah Attorney General’s Office, with Utah Department of Veterans and Military Affairs and the Utah State Bar (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A legal referral program for qualifying Utah active-duty service members, veterans (honorable or general discharge), and Guard or Reserve members. It tries to match volunteer attorneys for certain civil matters (the page lists issues such as SCRA, USERRA, tenant, debt, consumer fraud, predatory lending, immigration, and wills, with exceptions when the opposing party is a government entity).

### Military spouses and families

#### Returnship

- [Return Utah (State Government Returnship)](https://dhrm.utah.gov/hiring-pathways/return-utah/) — State of Utah / Division of Human Resource Management (Lt. Governor initiative) (Utah-statewide). _no_opening_seen, not for live demo, GrokBot+Claude+ChatGPT_
  A state government return-to-work program that fills mid-level public jobs with people who have had an extended career break (including parenthood, caregiving, military service, disability, education, or retirement). Participants may receive training, coaching, and development support. Utah residency and generally a one-year career break apply; military-connected applicants and some underemployed people have exceptions.

#### Nonprofit

- [Hire Heroes USA](https://www.hireheroesusa.org/) (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Nonprofit that provides career services and job-search support for veterans, transitioning service members, and military spouses.

#### Agency

- [Military OneSource Spouse Career and Education Support](https://www.militaryonesource.mil/education-employment/for-spouses/) (United States and eligible military communities). _ongoing, demo-ok, ChatGPT_
  Ask about career coaching, scholarships, and employer connections.
- [Utah Department of Veterans and Military Affairs](https://veterans.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  State agency that helps Utah veterans, service members, and their families with VA claims assistance, education-benefit information, and other state and federal benefits. The site also includes information for spouses and family members and a section for employers looking to hire veterans and military spouses.
- [Utah DWS Veterans Employment](https://jobs.utah.gov/veteran/) (Utah). _ongoing, demo-ok, ChatGPT_
  Review Utah employment help and ask which specialized services apply.

#### Legal Aid

- [Utah@EASE Veteran Legal Referral Program](https://attorneygeneral.utah.gov/utahease/) — Utah Attorney General’s Office, with Utah Department of Veterans and Military Affairs and the Utah State Bar (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A legal referral program for qualifying Utah active-duty service members, veterans (honorable or general discharge), and Guard or Reserve members. It tries to match volunteer attorneys for certain civil matters (the page lists issues such as SCRA, USERRA, tenant, debt, consumer fraud, predatory lending, immigration, and wills, with exceptions when the opposing party is a government entity).

### Older workers

#### Returnship

- [iRelaunch Return to Work Programs](https://www.irelaunch.com/returnships) — iRelaunch (national). _ongoing, demo-ok, GrokBot_
  iRelaunch’s return-to-work / returnship program listings for professionals restarting after a career break. Application status is set by each employer.
- [Return Utah (State Government Returnship)](https://dhrm.utah.gov/hiring-pathways/return-utah/) — State of Utah / Division of Human Resource Management (Lt. Governor initiative) (Utah-statewide). _no_opening_seen, not for live demo, GrokBot+Claude+ChatGPT_
  A state government return-to-work program that fills mid-level public jobs with people who have had an extended career break (including parenthood, caregiving, military service, disability, education, or retirement). Participants may receive training, coaching, and development support. Utah residency and generally a one-year career break apply; military-connected applicants and some underemployed people have exceptions.

#### Education

- [Weber State University Division of Online & Continuing Education](https://www.weber.edu/DOCE/default.html) — Weber State University (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Weber State’s Division of Online & Continuing Education offers nontraditional options, including noncredit professional education to upskill or reskill, microcredentials, online and independent study, and learning at off-campus centers (including a Center for Continuing Education in Clearfield and a bilingual Community Education Center).

#### Nonprofit

- [iRelaunch](https://www.irelaunch.com/) (national). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Organization focused on career reentry after a career break. The site offers return-to-work resources, a job board, and returnship program information.
- [U.S. Department of Labor SCSEP](https://www.dol.gov/agencies/eta/seniors) (United States). _ongoing, not for live demo, ChatGPT_
  Find the national program and local providers for paid community-service training.

#### Agency

- [AARP Foundation SCSEP](https://www.aarp.org/aarp-foundation/our-work/income/scsep/hire-an-older-worker.html) — AARP Foundation (National). _ongoing, demo-ok, Claude_
  Paid training placements and employer connections for low-income job seekers 55+.
- [American Job Center Finder (CareerOneStop)](https://www.careeronestop.org/LocalHelp/AmericanJobCenters/find-american-job-centers.aspx) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot_
  Official locator for American Job Centers, which provide locally available employment and training help, including services often funded under WIOA.
- [CareerOneStop](https://www.careeronestop.org/) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot+Claude_
  A U.S. Department of Labor-sponsored site for career exploration, job search, training, and local help, including tools to find money for training.
- [Utah Department of Workforce Services](https://jobs.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s workforce agency helps people find jobs, apply for assistance (including food, child care, Medicaid, and unemployment insurance), and connect to training and employment-center services.
- [Utah DWS Job Seeker Services](https://jobs.utah.gov/jobseeker/index.html) — Utah Department of Workforce Services (Utah-statewide). _ongoing, demo-ok, GrokBot+ChatGPT_
  Job-seeker services from Utah DWS, including the state job board and employment-center help for people looking for work or changing careers.
- [Utah Senior Community Service Employment Program (SCSEP)](https://daas.utah.gov/services/) — Utah Division of Aging and Adult Services (DHHS), with American Job Centers (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  SCSEP is described on the Utah Aging & Adult Services site as a community-service and work-based job-training program for older Americans, authorized by the Older Americans Act, that provides training for low-income, unemployed seniors. Participants may also get employment help through American Job Centers.
- [Workforce Innovation and Opportunity Act (WIOA)](https://www.dol.gov/agencies/eta/wioa) — U.S. Department of Labor, Employment and Training Administration (national). _ongoing, demo-ok, GrokBot_
  Federal workforce law that funds employment and training services, typically accessed through American Job Centers and state workforce agencies such as Utah DWS.
- [Easterseals-Goodwill SCSEP (Utah)](https://www.esgw.org/scsep/) — Easterseals-Goodwill Northern Rocky Mountain (Utah). _check_provider, not for live demo, Claude+ChatGPT_
  Paid on-the-job training and job placement for low-income adults over 55 in Utah, Idaho and Montana.

#### Job Board

- [AARP Work and Job Search Resources](https://www.aarp.org/work/) — AARP (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  AARP pages with work and job-search resources aimed at older workers. Confirm current tools, job listings, and any membership requirements on the official site.

#### Legal Aid

- [Utah Legal Services](https://www.utahlegalservices.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Nonprofit civil legal aid organization that provides free help in civil matters (the site lists areas such as housing, family, domestic violence, public benefits including food stamps, financial assistance, Medicaid, and SSI/SSDI, consumer issues, and senior estate planning). Apply through the official site. This is not a criminal-defense office.

### Long-term unemployed and general job seekers

#### Returnship

- [Fidelity RESUME Return-to-Work Program](https://jobs.fidelity.com/in/life-at-fidelity/resume-program/) — Fidelity Investments (national). _closed, not for live demo, GrokBot+ChatGPT_
  Fidelity’s RESUME program is described as a paid six-month internship with mentorship and training for women on a career break who want to re-enter the workforce, across areas such as operations, technology, analytics, research, data, and corporate services.
- [Return Utah (State Government Returnship)](https://dhrm.utah.gov/hiring-pathways/return-utah/) — State of Utah / Division of Human Resource Management (Lt. Governor initiative) (Utah-statewide). _no_opening_seen, not for live demo, GrokBot+Claude+ChatGPT_
  A state government return-to-work program that fills mid-level public jobs with people who have had an extended career break (including parenthood, caregiving, military service, disability, education, or retirement). Participants may receive training, coaching, and development support. Utah residency and generally a one-year career break apply; military-connected applicants and some underemployed people have exceptions.

#### Education

- [Apprenticeship Utah](https://apprenticeship.utah.gov) — State of Utah (Utah). _ongoing, demo-ok, Claude+ChatGPT_
  State hub for registered apprenticeships and pre-apprenticeships - earn while you learn in trades and other fields.
- [Apprenticeship.gov](https://www.apprenticeship.gov/) — U.S. Department of Labor (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Official U.S. site to find registered apprenticeships, which combine paid work with structured training.
- [Bridgerland Technical College](https://btech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering career and technical training. Confirm current programs and costs on the official site.
- [Coursera Financial Aid](https://www.coursera.org/about/financial-aid) — Coursera (remote). _ongoing, demo-ok, GrokBot_
  Coursera’s official financial aid information for learners who cannot afford a paid course or certificate. Apply from the individual course page following Coursera’s instructions.
- [Davis Technical College](https://www.davistech.edu/) — Davis Technical College (USHE technical college) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering short-term career and technical programs. Check the site for current certificates, schedules, and tuition or aid.
- [Dixie Technical College](https://www.dixietech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering career training programs in southern Utah. Confirm current programs and costs on the official site.
- [Federal Pell Grants](https://studentaid.gov/articles/dont-miss-out-on-pell-grants/?s6=CK) (United States, participating schools). _ongoing, demo-ok, ChatGPT_
  Check federal student-aid sources and ask the school's aid office about eligibility.
- [Google Career Certificates (Grow with Google)](https://grow.google/certificates/) — Google / Grow with Google (remote). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Online job-ready certificate programs from Grow with Google. The official certificates page is the place to confirm current offerings, cost, and how to enroll.
- [Job Corps](https://www.jobcorps.gov/) — U.S. Department of Labor / Job Corps (national). _ongoing, demo-ok, GrokBot_
  A tuition-free federal career-training program. Eligibility is generally limited to eligible young people (commonly ages 16–24; confirm current rules on the official site).
- [Mountainland Technical College (MTECH)](https://mtec.edu/) — Mountainland Technical College (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering short-term career and technical training. Confirm current programs and costs on the official site.
- [Ogden-Weber Technical College (OTECH)](https://www.otech.edu/) — Ogden-Weber Technical College (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering affordable career and technical programs. Confirm current certificates, schedules, and costs on the official site.
- [Salt Lake Community College Utah Works](https://www.slcc.edu/utahworks/) — Salt Lake Community College / Talent Ready Utah (Salt Lake City, UT). _ongoing, demo-ok, GrokBot_
  SLCC’s Utah Works page describes short-term workforce training connected to Talent Ready Utah. Confirm current courses, eligibility, and any tuition assistance on the SLCC page before enrollment.
- [SLCC Workforce Training with DWS Funding Help](https://www.slcc.edu/dws/index.aspx) — Salt Lake Community College / Utah Department of Workforce Services (Salt Lake City, UT). _ongoing, demo-ok, GrokBot_
  SLCC page that walks DWS customers through choosing an approved workforce-training program, applying for DWS training funds, and registering if funding is approved. The page lists many short certificate programs (for example IT, administrative, health, trades, and business skills) with costs and lengths. An employment counselor typically contacts applicants after the DWS application is submitted.
- [Snow College](https://www.snow.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah public college. Use the official site to review current academic, technical, and continuing-education programs and any available aid.
- [Southwest Technical College](https://stech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering career training in southwestern Utah. Confirm current programs and costs on the official site.
- [Talent Ready Utah Programs (including Utah Works)](https://talentready.ushe.edu/programs/) — Talent Ready Utah / USHE (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Program listing for Talent Ready Utah initiatives, including short-term technical skills training (Utah Works) and other education–industry pathways.
- [Tooele Technical College](https://www.tooeletech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering hands-on career and technical programs. Confirm current certificates, schedules, and tuition or aid on the official site.
- [Uintah Basin Technical College](https://www.ubtech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college serving the Uintah Basin with career and technical programs. Confirm current offerings and costs on the official site.
- [Utah DWS Career and Employment Workshops](https://jobs.utah.gov/jobseeker/workshops/) (Utah). _ongoing, demo-ok, ChatGPT_
  Find résumé, interview, and job-search workshops.
- [Utah Tech University](https://utahtech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Public university in St. George, Utah. Use the official site to review current degree, certificate, and workforce-related offerings. Do not confuse this homepage with the earlier CARES-era Learn & Work / Utah Tech CARES program, which was not included because of an invalid SSL certificate and a public description that the program ended 31 August 2026.
- [Utah Valley University Workforce Alignment](https://www.uvu.edu/workforce/) — Utah Valley University (Utah-statewide). _ongoing, demo-ok, GrokBot_
  UVU’s Workforce Alignment office coordinates campus and regional workforce efforts. The page points to career and technical education, credit for prior learning, regional pathways, and technical-college transfer options. It is a coordination office, not a single open-enrollment course catalog.
- [Weber State University Division of Online & Continuing Education](https://www.weber.edu/DOCE/default.html) — Weber State University (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Weber State’s Division of Online & Continuing Education offers nontraditional options, including noncredit professional education to upskill or reskill, microcredentials, online and independent study, and learning at off-campus centers (including a Center for Continuing Education in Clearfield and a bilingual Community Education Center).
- [Talent Ready Utah](https://talentready.ushe.edu/) — Utah System of Higher Education / Talent Ready Utah (Utah-statewide). _historical_only, not for live demo, GrokBot+Claude_
  USHE initiative that coordinates education–industry workforce programs, including short-term training pathways such as Utah Works and related resources.
- [Utah State University Learn and Work in Utah (historical page)](https://www.usu.edu/learnwork/) — Utah State University (Utah-statewide). _historical_only, not for live demo, GrokBot+Claude+ChatGPT_
  USU page describing Learn and Work short-term certificates (for example manufacturing, community health worker, and CDL) with tuition help that the page ties to COVID-era CARES Act funding for eligible unemployed or underemployed Utah residents.
- [Utah State University Online](https://www.usu.edu/online/) — Utah State University (remote). _historical_only, not for live demo, GrokBot_
  USU’s official online-education page for current distance-learning programs. Confirm current degrees, certificates, costs, and how to apply on the site.

#### Nonprofit

- [Church Employment Services](https://www.churchofjesuschrist.org/serve/caring/employment?lang=eng) (Utah and participating locations). _ongoing, demo-ok, ChatGPT_
  See job-search support and employer connections available locally or online.
- [Dress for Success (national network)](https://dressforsuccess.org/) — Dress for Success Worldwide (national). _ongoing, demo-ok, GrokBot_
  Nonprofit network that helps women gain professional attire and career support. Use the national site to find a local affiliate.
- [Family Caregiver Alliance Utah Resource Locator](https://www.caregiver.org/connecting-caregivers/services-by-state/utah/) (Utah). _ongoing, demo-ok, ChatGPT_
  Find caregiving and respite supports that may free up time for training or work.
- [Goodwill of Utah (Deseret Industries / Goodwill Utah)](https://goodwillutah.com/) — Goodwill Utah (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Utah Goodwill provides community employment and related services (see the official site for current programs, locations, and how to get help).
- [Hiring Our Heroes](https://www.hiringourheroes.org/career-services/) (United States, options vary). _ongoing, demo-ok, ChatGPT_
  Review fellowships, career fairs, and education or networking options.
- [Library of Congress Reentry Employment Guide](https://guides.loc.gov/reentry-resources/employment) (United States online). _ongoing, demo-ok, ChatGPT_
  Browse employment and training resource links for justice-impacted people.
- [Upwardly Global Job Seeker Resources](https://www.upwardlyglobal.org/job-seeker-resources/) (United States online, eligibility varies). _ongoing, demo-ok, ChatGPT_
  Review job-search resources and check eligibility for individualized coaching.
- [Utah DWS Office and Contact Finder](https://jobs.utah.gov/department/contact/) (Utah). _ongoing, demo-ok, ChatGPT_
  Find a local office or contact the agency about services.
- [Utah Small Business Development Center](https://utahsbdc.org/) (Utah). _ongoing, demo-ok, ChatGPT_
  Find a local center for advising and training.
- [CareerOneStop American Job Center Finder](https://cloudfront.careeronestop.org/LocalHelp/AmericanJobCenters/american-job-centers.aspx) (United States). _ongoing, not for live demo, ChatGPT_
  Enter a ZIP code for a public workforce center.
- [Dress for Success Salt Lake City](https://saltlakecity.dressforsuccess.org/) (Salt Lake City, UT). _unknown, not for live demo, GrokBot_
  Salt Lake City affiliate of Dress for Success, which helps women with professional clothing and career services. Confirm hours and how to request services on the affiliate site.
- [U.S. Department of Labor Job Seeker Resources](https://www.dol.gov/agencies/eta/job-seekers) (United States). _ongoing, not for live demo, ChatGPT_
  Find workforce services, training, and federal job-search resources.
- [U.S. Department of Labor SCSEP](https://www.dol.gov/agencies/eta/seniors) (United States). _ongoing, not for live demo, ChatGPT_
  Find the national program and local providers for paid community-service training.
- [U.S. DOL Indian and Native American Programs](https://www.dol.gov/agencies/eta/dinap) (United States, grantee coverage varies). _ongoing, not for live demo, ChatGPT_
  Identify workforce grantees and contact the appropriate local provider.

#### Agency

- [American Job Center Finder (CareerOneStop)](https://www.careeronestop.org/LocalHelp/AmericanJobCenters/find-american-job-centers.aspx) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot_
  Official locator for American Job Centers, which provide locally available employment and training help, including services often funded under WIOA.
- [CareerOneStop](https://www.careeronestop.org/) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot+Claude_
  A U.S. Department of Labor-sponsored site for career exploration, job search, training, and local help, including tools to find money for training.
- [Job Accommodation Network (JAN)](https://askjan.org/about-us/) — U.S. Department of Labor (ODEP) / Job Accommodation Network (National). _ongoing, demo-ok, Claude+ChatGPT_
  Free guidance on workplace accommodations, including a Situations and Solutions Finder tool.
- [SNAP Employment and Training (SNAP E&T)](https://www.fna.usda.gov/snap-et) — U.S. Department of Agriculture, Food and Nutrition Service (national). _ongoing, demo-ok, GrokBot_
  Federal SNAP Employment and Training helps SNAP participants prepare for and find work. Services are run through states and may include training, job search, and support services.
- [The Federal Bonding Program](https://bonds4jobs.com/) — The Federal Bonding Program (U.S. Department of Labor-related) (national). _ongoing, demo-ok, GrokBot+Claude_
  Provides no-cost fidelity bonding for employers who hire eligible job seekers with barriers to employment, such as a criminal record or limited work history. The bond is an employer tool, not a cash benefit to the worker.
- [Utah 211](https://211utah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Free, confidential help connecting Utahns to health, social, and government services. Dial 2-1-1 or use the website to find local resources.
- [Utah Department of Workforce Services](https://jobs.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s workforce agency helps people find jobs, apply for assistance (including food, child care, Medicaid, and unemployment insurance), and connect to training and employment-center services.
- [Utah DWS Apply for Assistance](https://jobs.utah.gov/assistance/index.html) — Utah Department of Workforce Services (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Portal to DWS assistance programs, including food, child care, medical, financial, disability, and unemployment insurance help.
- [Utah DWS Career and Education Assistance](https://jobs.utah.gov/career/) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask about career counseling, training funding, work experience, and the Eligible Training Provider List.
- [Utah DWS Federal Bonding Program](https://jobs.utah.gov/services/bond.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask Utah DWS if employer bonding can help with a specific hire.
- [Utah DWS Job Seeker Services](https://jobs.utah.gov/jobseeker/index.html) — Utah Department of Workforce Services (Utah-statewide). _ongoing, demo-ok, GrokBot+ChatGPT_
  Job-seeker services from Utah DWS, including the state job board and employment-center help for people looking for work or changing careers.
- [Utah Senior Community Service Employment Program (SCSEP)](https://daas.utah.gov/services/) — Utah Division of Aging and Adult Services (DHHS), with American Job Centers (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  SCSEP is described on the Utah Aging & Adult Services site as a community-service and work-based job-training program for older Americans, authorized by the Older Americans Act, that provides training for low-income, unemployed seniors. Participants may also get employment help through American Job Centers.
- [Utah Services for Blind and Visually Impaired](https://jobs.utah.gov/usor/dsbvi/) (Utah). _ongoing, demo-ok, ChatGPT_
  Contact the division about rehabilitation, training, and job-related help.
- [Utah State Employment Pathways for People with Disabilities](https://jobs.utah.gov/usor/vr/pathways.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Explore state hiring pathways and how to contact the program.
- [Workforce Innovation and Opportunity Act (WIOA)](https://www.dol.gov/agencies/eta/wioa) — U.S. Department of Labor, Employment and Training Administration (national). _ongoing, demo-ok, GrokBot_
  Federal workforce law that funds employment and training services, typically accessed through American Job Centers and state workforce agencies such as Utah DWS.
- [Easterseals-Goodwill SCSEP (Utah)](https://www.esgw.org/scsep/) — Easterseals-Goodwill Northern Rocky Mountain (Utah). _check_provider, not for live demo, Claude+ChatGPT_
  Paid on-the-job training and job placement for low-income adults over 55 in Utah, Idaho and Montana.
- [Navajo Department of Workforce Development](https://www.ndwd.org/) (Navajo Nation, including Utah service areas as applicable). _check_provider, not for live demo, ChatGPT_
  Use the official application and confirm the service region, eligibility, and program availability.
- [Work Opportunity Tax Credit (WOTC)](https://www.dol.gov/agencies/eta/wotc) — U.S. Department of Labor, Employment and Training Administration (national). _check_provider, not for live demo, GrokBot+Claude_
  A federal tax credit for employers who hire people from targeted groups (including certain veterans, people with disabilities, and others with employment barriers). Job seekers do not apply for the credit themselves; employers and workforce agencies handle certification.

#### Job Board

- [AARP Work and Job Search Resources](https://www.aarp.org/work/) — AARP (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  AARP pages with work and job-search resources aimed at older workers. Confirm current tools, job listings, and any membership requirements on the official site.
- [Honest Jobs](https://www.honestjobs.com/) (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Online platform focused on fair-chance employment and reentry support for people with criminal records.
- [Zions Bancorporation Careers](https://careers.zionsbancorporation.com/) (Utah and other states). _local_returnship_unverified, not for live demo, ChatGPT_
  Use the employer's general careers site. A Utah returnship was unverified in the sources reviewed.

#### Legal Aid

- [Utah Legal Services](https://www.utahlegalservices.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Nonprofit civil legal aid organization that provides free help in civil matters (the site lists areas such as housing, family, domestic violence, public benefits including food stamps, financial assistance, Medicaid, and SSI/SSDI, consumer issues, and senior estate planning). Apply through the official site. This is not a criminal-defense office.

### General / any audience

#### Returnship

- 16-Week Project Coordinator Returnship — Sample Co. - Lehi tech company. _sample, SAMPLE, demo-ok, Claude_
  Paid returnship for people with a 2+ year career break, with a mentor and a path to a full-time role.
- [iRelaunch Return to Work Programs](https://www.irelaunch.com/returnships) — iRelaunch (national). _ongoing, demo-ok, GrokBot_
  iRelaunch’s return-to-work / returnship program listings for professionals restarting after a career break. Application status is set by each employer.
- [ARUP Laboratories Returnship](https://www.aruplab.com/careers/returnships) — ARUP Laboratories (Salt Lake City, UT). _interest_list, not for live demo, GrokBot+Claude+ChatGPT_
  Paid short-term returnship at ARUP in Salt Lake City for skilled people with at least a one-year employment gap, or who have been on active military duty. Tracks include technical (IT and lab work), business, and operations, with mentorship. The careers page invites applicants to browse open returnship jobs or submit a Returnship Interest Form if no current posting fits.
- [Goldman Sachs Returnship](https://www.goldmansachs.com/careers/programs-for-professionals/returnship) — Goldman Sachs (Salt Lake City, UT). _interest_list, not for live demo, GrokBot+Claude+ChatGPT_
  Paid 12-week returnship for experienced professionals who have been out of full-time work for two or more years and have at least three years of prior work experience. The official page lists Salt Lake City, UT among Americas locations (availability varies by division). The Americas cohort is described as January–March 2027; the page says to register to receive an invitation when applications open.

#### Education

- [Apprenticeship Utah](https://apprenticeship.utah.gov) — State of Utah (Utah). _ongoing, demo-ok, Claude+ChatGPT_
  State hub for registered apprenticeships and pre-apprenticeships - earn while you learn in trades and other fields.
- [Apprenticeship.gov](https://www.apprenticeship.gov/) — U.S. Department of Labor (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Official U.S. site to find registered apprenticeships, which combine paid work with structured training.
- [Bridgerland Technical College](https://btech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering career and technical training. Confirm current programs and costs on the official site.
- [Coursera Financial Aid](https://www.coursera.org/about/financial-aid) — Coursera (remote). _ongoing, demo-ok, GrokBot_
  Coursera’s official financial aid information for learners who cannot afford a paid course or certificate. Apply from the individual course page following Coursera’s instructions.
- [Davis Technical College](https://www.davistech.edu/) — Davis Technical College (USHE technical college) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering short-term career and technical programs. Check the site for current certificates, schedules, and tuition or aid.
- [Dixie Technical College](https://www.dixietech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering career training programs in southern Utah. Confirm current programs and costs on the official site.
- [Excel / spreadsheet basics](https://edu.gcfglobal.org/en/excel/) — GCFGlobal / LearnFree (remote). _ongoing, demo-ok, Claude_
  Short refresher course listed in Claude's seed data (GCFGlobal). Confirm current cost and enrollment on the provider site.
- [Google Career Certificates (Grow with Google)](https://grow.google/certificates/) — Google / Grow with Google (remote). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Online job-ready certificate programs from Grow with Google. The official certificates page is the place to confirm current offerings, cost, and how to enroll.
- [IBM SkillsBuild for Adult Learners](https://skillsbuild.org/adult-learners) (Online). _ongoing, demo-ok, ChatGPT_
  Explore free self-paced learning and compare course or credential requirements.
- [Inbound / CRM fundamentals](https://academy.hubspot.com/) — HubSpot Academy (remote). _ongoing, demo-ok, Claude_
  Short refresher course listed in Claude's seed data (HubSpot Academy). Confirm current cost and enrollment on the provider site.
- [Job Corps](https://www.jobcorps.gov/) — U.S. Department of Labor / Job Corps (national). _ongoing, demo-ok, GrokBot_
  A tuition-free federal career-training program. Eligibility is generally limited to eligible young people (commonly ages 16–24; confirm current rules on the official site).
- [Microsoft 365 and Excel modules](https://learn.microsoft.com/en-us/training/) — Microsoft Learn (remote). _ongoing, demo-ok, Claude_
  Short refresher course listed in Claude's seed data (Microsoft Learn). Confirm current cost and enrollment on the provider site.
- [Mountainland Technical College (MTECH)](https://mtec.edu/) — Mountainland Technical College (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering short-term career and technical training. Confirm current programs and costs on the official site.
- [My Next Move (O*NET)](https://www.mynextmove.org/) (United States online). _ongoing, demo-ok, ChatGPT_
  Explore occupations and use the Interest Profiler.
- [Northstar Digital Literacy](https://www.digitalliteracyassessment.org/build-skills) (Online and participating sites). _ongoing, demo-ok, ChatGPT_
  Try foundational skill assessments and find a participating site if needed.
- [Ogden-Weber Technical College (OTECH)](https://www.otech.edu/) — Ogden-Weber Technical College (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering affordable career and technical programs. Confirm current certificates, schedules, and costs on the official site.
- [Salt Lake Community College Utah Works](https://www.slcc.edu/utahworks/) — Salt Lake Community College / Talent Ready Utah (Salt Lake City, UT). _ongoing, demo-ok, GrokBot_
  SLCC’s Utah Works page describes short-term workforce training connected to Talent Ready Utah. Confirm current courses, eligibility, and any tuition assistance on the SLCC page before enrollment.
- [Salt Lake Community College Workforce Training](https://www.slcc.edu/workforce-training/index.aspx) (Salt Lake area and online options). _ongoing, demo-ok, ChatGPT_
  Browse workforce courses and verify costs, schedules, and financial assistance.
- [SLCC Workforce Training with DWS Funding Help](https://www.slcc.edu/dws/index.aspx) — Salt Lake Community College / Utah Department of Workforce Services (Salt Lake City, UT). _ongoing, demo-ok, GrokBot_
  SLCC page that walks DWS customers through choosing an approved workforce-training program, applying for DWS training funds, and registering if funding is approved. The page lists many short certificate programs (for example IT, administrative, health, trades, and business skills) with costs and lengths. An employment counselor typically contacts applicants after the DWS application is submitted.
- [Snow College](https://www.snow.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah public college. Use the official site to review current academic, technical, and continuing-education programs and any available aid.
- [Southwest Technical College](https://stech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering career training in southwestern Utah. Confirm current programs and costs on the official site.
- [Talent Ready Utah Programs (including Utah Works)](https://talentready.ushe.edu/programs/) — Talent Ready Utah / USHE (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Program listing for Talent Ready Utah initiatives, including short-term technical skills training (Utah Works) and other education–industry pathways.
- [Tooele Technical College](https://www.tooeletech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college offering hands-on career and technical programs. Confirm current certificates, schedules, and tuition or aid on the official site.
- [Uintah Basin Technical College](https://www.ubtech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  A Utah technical college serving the Uintah Basin with career and technical programs. Confirm current offerings and costs on the official site.
- [Utah System of Higher Education](https://ushe.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Official system site for Utah’s public colleges, universities, and technical colleges. Use it to find institutions and system-level workforce initiatives.
- [Utah Tech University](https://utahtech.edu/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Public university in St. George, Utah. Use the official site to review current degree, certificate, and workforce-related offerings. Do not confuse this homepage with the earlier CARES-era Learn & Work / Utah Tech CARES program, which was not included because of an invalid SSL certificate and a public description that the program ended 31 August 2026.
- [Utah Valley University Workforce Alignment](https://www.uvu.edu/workforce/) — Utah Valley University (Utah-statewide). _ongoing, demo-ok, GrokBot_
  UVU’s Workforce Alignment office coordinates campus and regional workforce efforts. The page points to career and technical education, credit for prior learning, regional pathways, and technical-college transfer options. It is a coordination office, not a single open-enrollment course catalog.
- [Weber State University Division of Online & Continuing Education](https://www.weber.edu/DOCE/default.html) — Weber State University (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Weber State’s Division of Online & Continuing Education offers nontraditional options, including noncredit professional education to upskill or reskill, microcredentials, online and independent study, and learning at off-campus centers (including a Center for Continuing Education in Clearfield and a bilingual Community Education Center).
- [Women’s Business Center of Utah](https://www.wbcutah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot+ChatGPT_
  Utah organization that helps women start and grow businesses. See the site for current counseling, training, and events.
- [Year Up United Salt Lake City](https://www.yearup.org/locations/salt-lake-city-ut) (Salt Lake City). _cohort_listed, demo-ok, ChatGPT_
  The local provider page lists tuition-free pathways and February and April 2027 starts. Use the application link to confirm intake.
- [Clearfield Job Corps](https://clearfield.jobcorps.gov/) (Clearfield, Utah). _check_provider, not for live demo, ChatGPT_
  Check current admissions and training tracks through the center.
- [Deseret Industries Humanitarian Center](https://www.deseretindustries.org/work-at-the-humanitarian-center) (Salt Lake City). _check_provider, not for live demo, ChatGPT_
  Ask about temporary training, English instruction, and current positions.
- [Goodwill Digital Career Accelerator](https://www.goodwill.org/how-we-work-with-you/dca/) (Participating U.S. Goodwill locations). _ongoing, not for live demo, ChatGPT_
  Check a local partner for services, training, and enrollment.
- Medical terminology short course — Utah tech college (via Learn & Work) - verify (remote). _check_provider, not for live demo, Claude_
  Short refresher course listed in Claude's seed data (Utah tech college (via Learn & Work) - verify). Confirm current cost and enrollment on the provider site.
- [Merit America Career Tracks](https://meritamerica.org/career-track/) (United States online, eligibility varies). _check_provider, not for live demo, ChatGPT_
  Compare tracks and review tuition and financing terms before enrolling.
- [Per Scholas National Remote Training](https://www.perscholas.org/locations/national/) (United States, cohort location restrictions may apply). _check_provider, not for live demo, ChatGPT_
  Check location eligibility, schedule, and the current training track before applying.
- QuickBooks Online training — Intuit (remote). _check_provider, not for live demo, Claude_
  Short refresher course listed in Claude's seed data (Intuit). Confirm current cost and enrollment on the provider site.
- [Talent Ready Utah](https://talentready.ushe.edu/) — Utah System of Higher Education / Talent Ready Utah (Utah-statewide). _historical_only, not for live demo, GrokBot+Claude_
  USHE initiative that coordinates education–industry workforce programs, including short-term training pathways such as Utah Works and related resources.
- [Utah Promise Grant](https://ushe.edu/utah-promise-grant/) (Utah, participating institutions). _check_provider, not for live demo, ChatGPT_
  Ask the participating school's financial aid office about eligibility and current availability.
- [Utah State University Learn and Work in Utah (historical page)](https://www.usu.edu/learnwork/) — Utah State University (Utah-statewide). _historical_only, not for live demo, GrokBot+Claude+ChatGPT_
  USU page describing Learn and Work short-term certificates (for example manufacturing, community health worker, and CDL) with tuition help that the page ties to COVID-era CARES Act funding for eligible unemployed or underemployed Utah residents.
- [Utah State University Online](https://www.usu.edu/online/) — Utah State University (remote). _historical_only, not for live demo, GrokBot_
  USU’s official online-education page for current distance-learning programs. Confirm current degrees, certificates, costs, and how to apply on the site.
- Utah Women in Trades (Utah). _closed, not for live demo, Claude_
  Supports women exploring skilled-trades careers with programs and resources; previously ran a 120-hour pre-apprenticeship with Salt Lake County.
- [Weber Basin Job Corps](https://weberbasin.jobcorps.gov/) (Ogden area, Utah). _check_provider, not for live demo, ChatGPT_
  Check admissions, residency, and career training tracks.

#### Nonprofit

- [Catholic Community Services of Utah Refugee Resettlement](https://ccsutah.org/programs/refugee-resettlement) (Salt Lake City area). _ongoing, demo-ok, ChatGPT_
  Ask about case management, workforce referrals, and other support.
- [Deseret Industries Job Training](https://www.deseretindustries.org/faqs) (Utah and participating locations). _ongoing, demo-ok, ChatGPT_
  Ask about associate training, job coaching, and local referral requirements.
- [Dress for Success (national network)](https://dressforsuccess.org/) — Dress for Success Worldwide (national). _ongoing, demo-ok, GrokBot_
  Nonprofit network that helps women gain professional attire and career support. Use the national site to find a local affiliate.
- [Employment & Workforce Development Resource Kit](https://www.usu.edu/uwlp/resources/employment-workforce-development-resource-kit) — Utah Women & Leadership Project (USU) (Utah). _ongoing, demo-ok, Claude_
  Curated list of Utah and national return-to-work resources, research and organizations for women.
- [Goodwill of Utah (Deseret Industries / Goodwill Utah)](https://goodwillutah.com/) — Goodwill Utah (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Utah Goodwill provides community employment and related services (see the official site for current programs, locations, and how to get help).
- [International Rescue Committee in Salt Lake City](https://welcome.rescue.org/us/en/salt-lake-city-ut) (Salt Lake City area). _ongoing, demo-ok, ChatGPT_
  Review local support and ask about employment and economic-wellbeing services.
- [iRelaunch](https://www.irelaunch.com/) (national). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Organization focused on career reentry after a career break. The site offers return-to-work resources, a job board, and returnship program information.
- [Job Corps Center Locator](https://www.jobcorps.gov/explore/center-locations) (United States). _ongoing, demo-ok, ChatGPT_
  Find a center and verify current local intake and training.
- [Salt Lake City English and Digital Literacy Directory](https://www.slc.gov/access-belonging/free-and-low-cost-english-classes-in-salt-lake-city/) (Salt Lake City area). _ongoing, demo-ok, ChatGPT_
  Check the city's provider list for free and low-cost options and confirm availability.
- [USAHello Work Guides](https://usahello.org/work/find-a-job/job-opportunities/) (United States online). _ongoing, demo-ok, ChatGPT_
  Use the plain-language employment guides and language options.
- [USARA Recovery Community Centers](https://myusara.com/locations/) (Utah, multiple sites). _ongoing, demo-ok, ChatGPT_
  Browse local peer recovery supports. Ask about workforce referrals in your area.
- [Utah Adult Education](https://schools.utah.gov/adulteducation/index) (Utah). _ongoing, demo-ok, ChatGPT_
  Find an adult education provider and ask about placement and schedules.
- [Utah Community Action Workforce Development](https://utahca.org/workforce-development/) (Utah, Salt Lake area). _ongoing, demo-ok, ChatGPT_
  Review current training options and ask about intake.
- [Utah DWS English Class Directory](https://jobs.utah.gov/refugee/resources/english.html) (Utah, regional providers). _ongoing, demo-ok, ChatGPT_
  Find classes and ask providers about scheduling and enrollment.
- [Utah System of Higher Education College Directory](https://ushe.edu/k-12-outreach/college-directory/) (Utah). _ongoing, demo-ok, ChatGPT_
  Find public college and technical college options by area.
- [Utah Women & Leadership Project](https://www.usu.edu/uwlp/) — Utah State University / Utah Women & Leadership Project (Utah-statewide). _ongoing, demo-ok, GrokBot_
  USU-based project that publishes research and resources on Utah women, work, and related issues, including family and childcare resource pages.
- [YWCA Utah](https://www.ywcautah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Utah nonprofit offering services that include child care, case management, and food services, among other community supports listed on its site.
- [YWCA Utah Survivor Services](https://www.ywcautah.org/survivor-services) (Utah, Salt Lake area). _ongoing, demo-ok, ChatGPT_
  Contact the provider about case management and available child care or other supports.
- [Dress for Success Salt Lake City](https://saltlakecity.dressforsuccess.org/) (Salt Lake City, UT). _unknown, not for live demo, GrokBot_
  Salt Lake City affiliate of Dress for Success, which helps women with professional clothing and career services. Confirm hours and how to request services on the affiliate site.
- [U.S. Department of Labor YouthBuild](https://www.dol.gov/agencies/eta/youth/youthbuild) (Participating U.S. communities). _ongoing, not for live demo, ChatGPT_
  Find a local program and confirm its admissions process.

#### Agency

- [American Job Center Finder (CareerOneStop)](https://www.careeronestop.org/LocalHelp/AmericanJobCenters/find-american-job-centers.aspx) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot_
  Official locator for American Job Centers, which provide locally available employment and training help, including services often funded under WIOA.
- [CareerOneStop](https://www.careeronestop.org/) — U.S. Department of Labor / CareerOneStop (national). _ongoing, demo-ok, GrokBot+Claude_
  A U.S. Department of Labor-sponsored site for career exploration, job search, training, and local help, including tools to find money for training.
- [Indian Training and Education Center](https://itecutah.org/) (Utah, confirm service area). _ongoing, demo-ok, ChatGPT_
  Ask about education and employment support. The provider says eligible Utah residents may apply year-round.
- [SNAP Employment and Training (SNAP E&T)](https://www.fna.usda.gov/snap-et) — U.S. Department of Agriculture, Food and Nutrition Service (national). _ongoing, demo-ok, GrokBot_
  Federal SNAP Employment and Training helps SNAP participants prepare for and find work. Services are run through states and may include training, job search, and support services.
- [The Federal Bonding Program](https://bonds4jobs.com/) — The Federal Bonding Program (U.S. Department of Labor-related) (national). _ongoing, demo-ok, GrokBot+Claude_
  Provides no-cost fidelity bonding for employers who hire eligible job seekers with barriers to employment, such as a criminal record or limited work history. The bond is an employer tool, not a cash benefit to the worker.
- [Utah 211](https://211utah.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude+ChatGPT_
  Free, confidential help connecting Utahns to health, social, and government services. Dial 2-1-1 or use the website to find local resources.
- [Utah Behavioral Health Supported Employment](https://sumh.utah.gov/services/recovery-supports/supported-employment/) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask the state or a participating provider about supported employment access.
- [Utah DCFS Youth Education and Employment](https://dcfs.utah.gov/services/youth-services/education-employment/) (Utah). _ongoing, demo-ok, ChatGPT_
  Ask DCFS about education, job preparation, and training referrals.
- [Utah Department of Workforce Services](https://jobs.utah.gov/) (Utah-statewide). _ongoing, demo-ok, GrokBot+Claude_
  Utah’s workforce agency helps people find jobs, apply for assistance (including food, child care, Medicaid, and unemployment insurance), and connect to training and employment-center services.
- [Utah DWS Apply for Assistance](https://jobs.utah.gov/assistance/index.html) — Utah Department of Workforce Services (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Portal to DWS assistance programs, including food, child care, medical, financial, disability, and unemployment insurance help.
- [Utah DWS Job Seeker Services](https://jobs.utah.gov/jobseeker/index.html) — Utah Department of Workforce Services (Utah-statewide). _ongoing, demo-ok, GrokBot+ChatGPT_
  Job-seeker services from Utah DWS, including the state job board and employment-center help for people looking for work or changing careers.
- [Utah Family Employment Program](https://jobs.utah.gov/customereducation/services/financialhelp/family/program.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Review the program and ask DWS about eligibility and services.
- [Utah Refugee Case Management and Provider Directory](https://jobs.utah.gov/refugee/resettle/case.html) (Utah, regional providers). _ongoing, demo-ok, ChatGPT_
  Find providers in Salt Lake, Cache, the Bear River area, and Utah County. Ask about employment and English support.
- [Utah Refugee Center Find a Job](https://jobs.utah.gov/refugee/resources/job.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Use the state job guidance and request a counselor or provider referral.
- [Utah SNAP Employment and Training information](https://jobs.utah.gov/customereducation/services/foodstamps/work_adults.html) (Utah). _ongoing, demo-ok, ChatGPT_
  Review the state employment and training information and ask DWS which services are available to you.
- [Workforce Innovation and Opportunity Act (WIOA)](https://www.dol.gov/agencies/eta/wioa) — U.S. Department of Labor, Employment and Training Administration (national). _ongoing, demo-ok, GrokBot_
  Federal workforce law that funds employment and training services, typically accessed through American Job Centers and state workforce agencies such as Utah DWS.
- Utah Transit Authority Reduced Fare (UTA service area). _ongoing, not for live demo, ChatGPT_
  Check program requirements and routes before planning a commute.
- [Work Opportunity Tax Credit (WOTC)](https://www.dol.gov/agencies/eta/wotc) — U.S. Department of Labor, Employment and Training Administration (national). _check_provider, not for live demo, GrokBot+Claude_
  A federal tax credit for employers who hire people from targeted groups (including certain veterans, people with disabilities, and others with employment barriers). Job seekers do not apply for the credit themselves; employers and workforce agencies handle certification.

#### Job Board

- Part-Time Bookkeeper (School Hours) — Sample Co. - Wasatch Family Dental. _sample, SAMPLE, demo-ok, Claude_
  Mon-Fri 9:00-2:00. Accounts payable/receivable and payroll prep.
- Patient Scheduler — Sample Co. - Utah County clinic. _sample, SAMPLE, demo-ok, Claude_
  Schedule appointments and handle front-desk calls. Day shifts only.
- Remote Customer Success Associate — Sample Co. - Silicon Slopes SaaS (remote). _sample, SAMPLE, demo-ok, Claude_
  Help customers onboard and solve problems by phone, chat, and email.
- School Paraprofessional — Sample Co. - Alpine-area school. _sample, SAMPLE, demo-ok, Claude_
  Support teachers and students in small groups. Same calendar as the school year.
- Volunteer Coordinator — Sample Co. - Salt Lake food pantry nonprofit. _sample, SAMPLE, demo-ok, Claude_
  Recruit, schedule, and lead volunteers; plan two fundraising events a year.
- [AARP Work and Job Search Resources](https://www.aarp.org/work/) — AARP (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  AARP pages with work and job-search resources aimed at older workers. Confirm current tools, job listings, and any membership requirements on the official site.
- [Fairygodboss](https://fairygodboss.com/) (national). _ongoing, demo-ok, GrokBot_
  Career community and job platform aimed at women, including company reviews and job listings.
- [PowerToFly](https://powertofly.com/) (remote). _ongoing, demo-ok, GrokBot_
  Job platform that connects candidates, including women and people seeking remote work, with employers.
- [The Mom Project](https://themomproject.com/) (national). _ongoing, demo-ok, GrokBot+ChatGPT_
  Talent marketplace connecting skilled parents and caregivers with employers for remote, hybrid, and in-person jobs.
- [FlexJobs](https://www.flexjobs.com/) (remote). _unknown, not for live demo, GrokBot_
  Job board that focuses on remote, flexible, and work-from-home roles, often used by caregivers and others who need schedule flexibility.

#### Childcare

- [Care About Childcare (Utah)](https://cac.utah.gov/) — Utah Department of Workforce Services, Office of Child Care (Utah-statewide). _ongoing, demo-ok, GrokBot+ChatGPT_
  Utah’s official tool for finding child care providers and related information. The DWS child care page points families to Care About Childcare (cac.utah.gov) to search for providers.

#### Legal Aid

- [Utah Legal Services](https://www.utahlegalservices.org/) (Utah-statewide). _ongoing, demo-ok, GrokBot_
  Nonprofit civil legal aid organization that provides free help in civil matters (the site lists areas such as housing, family, domestic violence, public benefits including food stamps, financial assistance, Medicaid, and SSI/SSDI, consumer issues, and senior estate planning). Apply through the official site. This is not a criminal-defense office.

## Data sources (for README / MLH field 8)

Public official websites and directories, compiled on 2026-11-14 from three teammate catalogs (GrokBot, Claude, ChatGPT) and rechecked by HTTP GET where noted in `url_check_status`. Sample job cards are synthetic and labeled `type: sample`. Child-care income rules, when used in the app, come from the team's encoding of Utah DWS Table 4 (effective Oct 1, 2026) and should be described as an estimate. This catalog is not an endorsement of any program.

## Notable flags

- **Fidelity RESUME:** applications closed; ChatGPT reports the program page is India-specific. Do not present a Utah Fidelity returnship.
- **Goldman Sachs Returnship:** Salt Lake City is listed; Americas cohort January–March 2027; register interest only.
- **ARUP Returnship:** program page is live; use the interest form or job board; individual openings unconfirmed.
- **Return Utah:** official program; postings board showed no current jobs in ChatGPT's snapshot.
- **Learn & Work in Utah:** historical / CARES Act-era. The inutah.org link 404s.
- **WOTC:** a U.S. Chamber guide says the credit was set to expire December 31, 2025. Confirm reauthorization before telling users it applies.
- **Utah Women in Trades pre-apprenticeship:** reported no longer active; county URL 404.
- **USU Extension Relaunching Your Career:** official product URL did not complete a fetch in this environment (`unverified-blocked`); do not treat as URL-verified until someone opens the page.

