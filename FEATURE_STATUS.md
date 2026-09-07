# Feature status — HR, workforce & talent operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 309 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 3 | 0 | Native records/view |
| Reports & analytics | report | 7 | 0 | Native records/view |
| Activity & audit trail | audit | 4 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Plan and rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employee dependent census | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Enrollment ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier invoice ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retro enrollment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Terminated member detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Life-event effective dates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| COBRA reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leave-of-absence billing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Age-banded premium validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Self-billed premium calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier discrepancy workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Premium credit tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payroll deduction reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan and carrier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exposure | records | 1 | 0 | Native records/view |
| Scenarios | records | 1 | 0 | Native records/view |
| Redeployment | records | 1 | 0 | Native records/view |
| Communication | records | 1 | 0 | Native records/view |
| Business Unit | records | 1 | 0 | Native records/view |
| Role Exposure | records | 1 | 0 | Native records/view |
| Task Profile | records | 1 | 0 | Native records/view |
| Scenario Model | records | 1 | 0 | Native records/view |
| Redeployment Option | records | 1 | 0 | Native records/view |
| Vacancy Match | records | 1 | 0 | Native records/view |
| Cost Comparison | records | 1 | 0 | Native records/view |
| Communication Pack | records | 1 | 0 | Native records/view |
| Attrition Plan | records | 1 | 0 | Native records/view |
| Skill Checkpoint | records | 1 | 0 | Native records/view |
| Manager Alert | records | 1 | 0 | Native records/view |
| Program Metric | records | 1 | 0 | Native records/view |
| Draft: Exposure Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Scenario Modeler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Redeployment Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Post order registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Guard credential validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Time punch matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regular hour calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overtime responsibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Holiday premium audit | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Vacant post detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supervisor markup control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident coverage validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice recalculation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Vendor dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Location post analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staffing agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Worker assignment registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Approved pay rate control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Markup calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Timecard ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overtime rate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tenure discount tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Conversion fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expense policy validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate worker billing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency role analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Roles & Tasks | records | 1 | 0 | Native records/view |
| Automation | records | 1 | 0 | Native records/view |
| Reskilling | records | 1 | 0 | Native records/view |
| Governance | records | 1 | 0 | Native records/view |
| Role | records | 1 | 0 | Native records/view |
| Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reskilling Plan | records | 1 | 0 | Native records/view |
| Transition Path | records | 1 | 0 | Native records/view |
| Productivity Target | records | 1 | 0 | Native records/view |
| Displacement Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employee | records | 1 | 0 | Native records/view |
| Skill Gap | records | 1 | 0 | Native records/view |
| Scenario | records | 1 | 0 | Native records/view |
| Governance Action | records | 1 | 0 | Native records/view |
| Learning Resource | records | 1 | 0 | Native records/view |
| Draft: Task Classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Exposure Forecaster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Reskilling Plan Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Diversity Metrics | records | 1 | 0 | Native records/view |
| Pay Equity Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hiring Bias Detection | records | 1 | 0 | Native records/view |
| Promotion Bias Detection | records | 1 | 0 | Native records/view |
| Compliance Reporting | records | 1 | 0 | Native records/view |
| Industry Benchmarking | records | 1 | 0 | Native records/view |
| Employee Surveys | records | 2 | 0 | Native records/view |
| Training Programs | records | 1 | 0 | Native records/view |
| Retention Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leadership Pipeline | records | 1 | 0 | Native records/view |
| Supplier Diversity | records | 1 | 0 | Native records/view |
| ERG Management | records | 1 | 0 | Native records/view |
| Incident Reports | records | 1 | 0 | Native records/view |
| Accessibility Compliance | records | 1 | 0 | Native records/view |
| Workforce Demographics | records | 1 | 0 | Native records/view |
| Predictive equity forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bias mitigation playbook | records | 1 | 0 | Native records/view |
| Intersectionality analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Talent pipeline simulation | records | 1 | 0 | Native records/view |
| Peer benchmarking | records | 1 | 0 | Native records/view |
| None significant excellent ai to route alignment 16 ai endpo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Alerts lacks ai prioritization endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Usermanagement lacks ai access pattern anomaly detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Limited hris integration no workday successfactors bamboohr | integration | 1 | 0 | Provider request records only |
| Limited real time alerting beyond alerts js storage | records | 1 | 0 | Native records/view |
| No action plan automation or tracking workflow | records | 1 | 0 | Native records/view |
| No webhooks | integration | 1 | 0 | Provider request records only |
| No payment billing module | records | 1 | 0 | Native records/view |
| Employee benefits optimizer work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Department Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pulse Checks | records | 1 | 0 | Native records/view |
| Feedback Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retention Risks | records | 1 | 0 | Native records/view |
| Engagement Scores | records | 1 | 0 | Native records/view |
| Team Morale | records | 1 | 0 | Native records/view |
| Exit Interviews | records | 2 | 0 | Native records/view |
| Anonymous Reports | records | 1 | 0 | Native records/view |
| Performance Reviews | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Onboarding Feedback | records | 1 | 0 | Native records/view |
| Benefits Satisfaction | records | 1 | 0 | Native records/view |
| Work-Life Balance | records | 1 | 0 | Native records/view |
| Leadership Ratings | records | 1 | 0 | Native records/view |
| Culture Index | records | 1 | 0 | Native records/view |
| Sentiment analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retention predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Enps improve | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leadership feedback extract | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Culture health score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross module correlation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment trend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Intervention planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retaliation risk sentinel | records | 1 | 0 | Native records/view |
| Onboarding Flows | records | 1 | 0 | Native records/view |
| User Segments | records | 1 | 0 | Native records/view |
| AI Content | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tooltips | records | 1 | 0 | Native records/view |
| Checklists | records | 2 | 0 | Native records/view |
| Progress Tracking | records | 2 | 0 | Native records/view |
| A/B Tests | records | 1 | 0 | Native records/view |
| Triggers | records | 1 | 0 | Native records/view |
| Personalization | records | 1 | 0 | Native records/view |
| AI PTO Scheduler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Mentor Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Feedback | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Training | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manager Readiness | records | 1 | 0 | Native records/view |
| Funnel Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SDK Docs | records | 1 | 0 | Native records/view |
| AI flow generator from JD | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Real-time feedback loop | records | 1 | 0 | Native records/view |
| Adaptive pacing | records | 1 | 0 | Native records/view |
| Department-specific content recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Onboarding compliance auditing | records | 1 | 0 | Native records/view |
| No `/cohort | records | 1 | 0 | Native records/view |
| No `/sentiment | records | 1 | 0 | Native records/view |
| No `/auto | records | 1 | 0 | Native records/view |
| No `/role | records | 1 | 0 | Native records/view |
| Backend logic concentrated in single index.js | records | 1 | 0 | Native records/view |
| Missing dedicated checklist routes (only AI generation, not CRUD) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No HR system integrations (Workday, BambooHR) | integration | 1 | 0 | Provider request records only |
| No webhooks for outbound triggers to customer systems | integration | 1 | 0 | Provider request records only |
| Limited reporting export (PDF/CSV) | records | 1 | 0 | Native records/view |
| No RBAC granularity beyond admin/manager | records | 1 | 0 | Native records/view |
| No file upload for onboarding documents/videos | records | 1 | 0 | Native records/view |
| Compliance audit | records | 1 | 0 | Native records/view |
| Job Postings | records | 2 | 0 | Native records/view |
| Candidates | records | 1 | 0 | Native records/view |
| Interviews | records | 2 | 0 | Native records/view |
| Assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pipeline | records | 1 | 0 | Native records/view |
| HR AI Tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Slate Balance | records | 1 | 0 | Native records/view |
| Resume Screener | records | 1 | 0 | Native records/view |
| Interview Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Culture Fit | records | 2 | 0 | Native records/view |
| Bias Detection | records | 1 | 0 | Native records/view |
| Salary Benchmark | records | 1 | 0 | Native records/view |
| Skills Gap Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Resume Parser | records | 1 | 0 | Native records/view |
| Calendar Integration | integration | 1 | 0 | Provider request records only |
| Offer Letter Gen | records | 1 | 0 | Native records/view |
| Onboarding Workflow | records | 1 | 0 | Native records/view |
| Performance Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DEI Metrics | records | 3 | 0 | Native records/view |
| Job Board Posting | records | 1 | 0 | Native records/view |
| Email Automation | records | 1 | 0 | Native records/view |
| AI Bias Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Job Description Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Skills Assessor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Employee Sentiment Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Culture Fit Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Performance Review Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Salary Benchmarker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Exit Interview Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Interview Scheduler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Org Chart Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Offer Letter Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI DEI Metrics Aggregator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bias detector | records | 1 | 0 | Native records/view |
| Sentiment analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Salary benchmarker | records | 1 | 0 | Native records/view |
| Interview scheduler | records | 1 | 0 | Native records/view |
| Org chart | records | 1 | 0 | Native records/view |
| Skills assessor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Job description writer | records | 1 | 0 | Native records/view |
| Retention risk | records | 1 | 0 | Native records/view |
| Offer letter | records | 1 | 0 | Native records/view |
| unbiased resume ranking | records | 1 | 0 | Native records/view |
| interview intelligence | records | 1 | 0 | Native records/view |
| peer feedback aggregator | records | 1 | 0 | Native records/view |
| retention risk prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| skillstorole matcher | records | 1 | 0 | Native records/view |
| Resumes | records | 1 | 0 | Native records/view |
| Cover Letters | records | 1 | 0 | Native records/view |
| Applications | records | 1 | 0 | Native records/view |
| Skills | records | 1 | 0 | Native records/view |
| Salary | records | 1 | 0 | Native records/view |
| Companies | records | 1 | 0 | Native records/view |
| Network | records | 1 | 0 | Native records/view |
| Resume Views | records | 1 | 0 | Native records/view |
| Job Matcher | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Keyword Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cover Letter AI | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Interview Prep | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Salary Negotiator | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Resume Upload (PDF/DOCX) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Application Autopilot | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| LinkedIn Sync | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compensation Tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voice Interview Prep | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Application Tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interview Scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Verify email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rejection analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Offer negotiation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Career trajectory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic application suite | records | 1 | 0 | Native records/view |
| interview coaching with recording | records | 1 | 0 | Native records/view |
| offer negotiation coach | records | 1 | 0 | Native records/view |
| career goal roadmap | records | 1 | 0 | Native records/view |
| company culture fit assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| recruiter relationship builder | records | 1 | 0 | Native records/view |
| rejectionanalysis why rejected | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| interviewschedulingoptimizer | records | 1 | 0 | Native records/view |
| offernegotiationsimulator | records | 1 | 0 | Native records/view |
| careertrajectoryanalyzer path prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| videorecording analysis eye contact pace | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited linkedin integration stub only no re | integration | 1 | 0 | Provider request records only |
| interview panel feedback collection | records | 1 | 0 | Native records/view |
| offer comparison tool benefits equity | records | 1 | 0 | Native records/view |
| background check status tracker | records | 1 | 0 | Native records/view |
| browser extension for oneclick apply | records | 1 | 0 | Native records/view |
| notificationsemail automation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| public webhooks | integration | 1 | 0 | Provider request records only |
| Employees | records | 1 | 0 | Native records/view |
| Shifts | records | 1 | 0 | Native records/view |
| Locations | records | 1 | 0 | Native records/view |
| Shift Swaps | records | 1 | 0 | Native records/view |
| Time Off | records | 1 | 0 | Native records/view |
| Availability | records | 1 | 0 | Native records/view |
| Break Management | records | 1 | 0 | Native records/view |
| Overtime | records | 1 | 0 | Native records/view |
| Payroll | records | 1 | 0 | Native records/view |
| Compliance | records | 1 | 0 | Native records/view |
| Demand Forecasts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No show prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fairness audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Burnout risk | records | 1 | 0 | Native records/view |
| Gig preferences | records | 1 | 0 | Native records/view |
| External fill in | records | 1 | 0 | Native records/view |
| Wage compression | records | 1 | 0 | Native records/view |
| Capacity plan | records | 1 | 0 | Native records/view |
| Productivity anomaly | records | 1 | 0 | Native records/view |
| Departments | records | 1 | 0 | Native records/view |
| Shift templates | records | 1 | 0 | Native records/view |
| Time clock | records | 1 | 0 | Native records/view |
| Announcements | records | 1 | 0 | Native records/view |
| Predictive no show modeling with ai driven reminder timing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fairness audit by demographic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gig worker preference learning | records | 1 | 0 | Native records/view |
| External labor market integration for fill ins | integration | 1 | 0 | Provider request records only |
| Wage compression detection internal equity alerts | records | 1 | 0 | Native records/view |
| Workforce capacity planning with turnover prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Productivity per shift analysis with anomaly flags | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Burnout fatigue risk modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fairness auditor for schedule equity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive turnover and retention modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Candidate to shift matching for gig workers | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benefits management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance review module | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training and lms integration | integration | 1 | 0 | Provider request records only |
| Certification expiration alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Geofenced clock in mobile attendance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tip pool and tip out calculations | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 309 feature pages were visited in the browser; 307 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 139 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

139 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
