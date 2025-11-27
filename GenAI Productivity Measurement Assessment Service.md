# GenAI Productivity Measurement Assessment Service  
## Self-Assessment Framework Based on DORA 2025  
### ✨ IMPROVED VERSION v4.0  
⸻  
## TABLE OF CONTENTS  
  
1. Assessment Framework Overview  
2. Self-Assessment Questionnaire  
3. Scoring & Maturity Levels  
4. DORA Metrics Baseline  
5. DORA AI Capabilities Model  
6. Implementation Roadmap  
⸻  
## ASSESSMENT FRAMEWORK OVERVIEW  
  
**Assessment Structure**  

| Section | Questions | Focus Area | Score Range | Status |
| ----------------------------- | --------- | ---------------------------------------------------- | ----------- | ------ |
| AI Adoption & Usage | 6 | Dev + QA: Reflexive use, trust, tools | 0-24 | ✅ |
| Development Activities | 5 | Coding, unit testing, code review | 0-20 | ✅ |
| QA Activities | 5 | Manual testing, automation, bug management | 0-20 | ✅ |
| Requirements & Planning | 3 | User stories, acceptance criteria, BDD | 0-12 | ✅ |
| SDLC Velocity | 4 | Cycle time, release frequency, bug resolution | 0-16 | ✅ |
| System & Process | 4 | CI/CD, version control, platform, data | 0-16 | ✅ |
| Organizational Outcomes | 3 | DORA metrics, team performance, ROI | 0-12 | ✅ |
| Learning & Enablement | 4 | Training, skills, knowledge sharing | 0-16 | ✅ |
| Security & Compliance | 3 | Privacy, licenses, vulnerabilities | 0-12 | ✅ |
| Team Dynamics & Collaboration | 4 | Dev-QA collaboration, reviews, skill levels | 0-16 | ✅ |
| Cost & ROI Metrics | 5 | Cost tracking, time savings, license management | 0-20 | ✅ |
| AI Code Quality | 3 | Code rejection rate, hallucinations, manual fix rate | 0-12 | ✅ |
| TOTAL | 49 | Full SDLC: Dev + QA + Quality + Cost | 0-196 | ✅ |
  
⸻  
## SELF-ASSESSMENT QUESTIONNAIRE  
  
**Scoring Scale: 0-4 points per question**  

| Score | Interpretation                         |
| ----- | -------------------------------------- |
| 0     | Not implemented                        |
| 1     | Initial stage / Experimental approach  |
| 2     | Partially implemented                  |
| 3     | Implemented across majority of team    |
| 4     | Fully implemented and optimized        |
| N/A   | Not applicable to this project/account |
  
⸻  
## SECTION 1: AI ADOPTION & USAGE (6 Questions)  
  
### Q1: AI Tools Integration in Daily Workflow  
**DORA Insight**: 90% of developers use AI; median 2 hours per day  
  
- [ ] 0 - No AI usage in Dev or QA  
- [ ] 1 - Individual team members (Dev or QA) experimenting  
- [ ] 2 - ~50% of Dev + QA teams use AI regularly  
- [ ] 3 - ~75% of both Dev and QA teams use AI by default  
- [ ] 4 - 90%+ across Dev and QA; AI is standard workflow  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q2: Reflexive AI Use (Frequency)  
**DORA Insight**: 60% of developers use AI "about half the time" or more  
  
- [ ] 0 - Never use AI for new tasks  
- [ ] 1 - Occasionally (< 25% of time)  
- [ ] 2 - Approximately half the time (~50%)  
- [ ] 3 - Most of the time (60-80%)  
- [ ] 4 - By default (~80%+ of tasks start with AI)  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q3: AI Reliance Level (Dependency)  
**DORA Insight**: 65% of developers rely on AI "moderately" or more  
  
- [ ] 0 - Not at all  
- [ ] 1 - Minimal  
- [ ] 2 - Moderate  
- [ ] 3 - Significant  
- [ ] 4 - Very significant (critical part of work)  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q4: Trust in AI-Generated Code  
**DORA Insight**: 70% have some trust; 30% have low trust  
  
- [ ] 0 - No trust in AI output (30% of developers)  
- [ ] 1 - Very low trust  
- [ ] 2 - Moderate trust, but thorough review required  
- [ ] 3 - High trust with spot-checks  
- [ ] 4 - High trust; minimal additional review  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q5: AI Usage Modes Coverage  
**DORA Insight**: Chat/IDE (55%), Predictive text (41%), Collaborative (18%), Agent (12%)  
  
- [ ] 0 - Single mode (chat or IDE)  
- [ ] 1 - Chat + IDE (basic)  
- [ ] 2 - Chat + IDE + Predictive text  
- [ ] 3 - Chat + IDE + Predictive + Collaborative  
- [ ] 4 - All modes; Agent mode used regularly  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q6: AI for Core Dev & QA Tasks  
**DORA Insight**: 71% for writing code, 66% modifying code, 62% for creating tests  
  
- [ ] 0 - Only for auxiliary tasks (docs, comments, emails)  
- [ ] 1 - For simple tasks (boilerplate code, basic test steps)  
- [ ] 2 - For main work (~30-40% of Dev/QA tasks)  
- [ ] 3 - For majority of tasks (~60% of core Dev/QA work)  
- [ ] 4 - Primary workflow for both Dev and QA teams  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 1 TOTAL: _____ / 24**  
⸻  
## SECTION 2: DEVELOPMENT ACTIVITIES (5 Questions)  
  
### Q7: Coding & Development  
**DORA Insight**: 71% use AI for writing code, 66% for modifying code  
  
- [ ] 0 - No AI for coding activities  
- [ ] 1 - Occasional AI hints for simple code  
- [ ] 2 - AI generates 30-40% of code  
- [ ] 3 - AI generates 60-70% of code  
- [ ] 4 - AI is primary coding assistant; 80%+ code generation  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q8: Developer Testing (Unit & Integration)  
**DORA Insight**: 62% use AI for creating test cases  
  
- [ ] 0 - Developers do not use AI for test writing  
- [ ] 1 - Manual test writing with occasional AI hints  
- [ ] 2 - AI generates 20-30% of unit/integration tests  
- [ ] 3 - AI generates 50-70% of unit/integration tests  
- [ ] 4 - AI generates 80%+ of tests with high coverage  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q9: Code Review Process  
**DORA Insight**: 30% do not trust AI code review; validation is critical  
  
- [ ] 0 - No special process for AI-generated code  
- [ ] 1 - Manual review of all AI-generated code  
- [ ] 2 - Basic linting + manual review  
- [ ] 3 - Automated quality checks + selective manual review  
- [ ] 4 - Full automated testing + AI-assisted review + security scanning  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q10: Code Quality & Standards  
**DORA Insight**: 59% see positive impact on quality; 10% see negative  
  
- [ ] 0 - Negative impact on code quality  
- [ ] 1 - No change in quality  
- [ ] 2 - Slight improvement in code quality  
- [ ] 3 - Noticeable improvement (~30% of team)  
- [ ] 4 - Significant improvement; AI code often superior  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q11: Development Velocity  
**DORA Insight**: 80%+ report productivity increase; 41% say "modest"  
  
- [ ] 0 - No increase or decrease in Dev velocity  
- [ ] 1 - Minimal increase (~5-10%)  
- [ ] 2 - Noticeable increase (~15-25%)  
- [ ] 3 - Significant increase (~35-45%)  
- [ ] 4 - Substantial increase (>45%)  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 2 TOTAL: _____ / 20**  
⸻  
## SECTION 3: QA ACTIVITIES (5 Questions)  
  
### Q12: Manual QA & Test Case Design  
  
- [ ] 0 - Manual QA does not use AI at all  
- [ ] 1 - AI assists with test documentation only  
- [ ] 2 - AI helps design 20-30% of test cases  
- [ ] 3 - AI helps design 50-70% of test cases  
- [ ] 4 - AI generates 80%+ of test cases  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q13: Test Automation (E2E, API, UI)  
  
- [ ] 0 - Test automation does not use AI  
- [ ] 1 - AI assists with test planning/setup  
- [ ] 2 - AI generates 20-30% of automation scripts  
- [ ] 3 - AI generates 50-70% of automated tests  
- [ ] 4 - AI generates 80%+ of test automation  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q14: Bug Detection & Analysis  
  
- [ ] 0 - No AI for bug-related activities  
- [ ] 1 - AI assists with bug report writing  
- [ ] 2 - AI helps with bug triage and categorization  
- [ ] 3 - AI assists with root cause analysis for 50%+  
- [ ] 4 - AI automates bug detection and suggests fixes  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q15: Test Data Management  
  
- [ ] 0 - No AI for test data activities  
- [ ] 1 - AI generates simple test data occasionally  
- [ ] 2 - AI generates 30-40% of test data  
- [ ] 3 - AI generates comprehensive test data  
- [ ] 4 - AI fully automates test data generation  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q16: QA Productivity & Test Coverage  
  
- [ ] 0 - No improvement in QA productivity  
- [ ] 1 - Minimal improvement (~5-10%)  
- [ ] 2 - Noticeable improvement (~15-25%)  
- [ ] 3 - Significant improvement (~35-45%)  
- [ ] 4 - Substantial improvement (>45%); higher coverage  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 3 TOTAL: _____ / 20**  
⸻  
## SECTION 4: REQUIREMENTS & PLANNING (3 Questions)  
  
### Q17: Requirements & User Stories  
  
- [ ] 0 - No AI in requirements phase  
- [ ] 1 - AI assists with formatting/templates  
- [ ] 2 - AI helps draft 30-40% of user stories  
- [ ] 3 - AI helps with 60%+ of requirements  
- [ ] 4 - AI fully assists with requirements & criteria  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q18: BDD Scenarios & Gherkin (Elaborate on Cucumber, Gherkin, BDD)  
  
- [ ] 0 - No BDD or AI not used  
- [ ] 1 - AI assists with basic scenario formatting  
- [ ] 2 - AI generates 30-40% of BDD scenarios  
- [ ] 3 - AI generates 60%+ of Gherkin scenarios  
- [ ] 4 - AI fully automates BDD from requirements  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q19: Test Strategy & Planning  
  
- [ ] 0 - No AI in test planning  
- [ ] 1 - AI provides suggestions for test scope  
- [ ] 2 - AI helps identify 30-40% of test areas  
- [ ] 3 - AI assists with risk analysis  
- [ ] 4 - AI generates comprehensive test strategy  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 4 TOTAL: _____ / 12**  
⸻  
## SECTION 5: SDLC VELOCITY & CYCLE TIME (4 Questions)  
  
### Q20: End-to-End Cycle Time  
  
- [ ] 0 - No improvement in cycle time  
- [ ] 1 - 5-10% faster cycle time  
- [ ] 2 - 15-25% faster cycle time  
- [ ] 3 - 30-45% faster cycle time  
- [ ] 4 - 50%+ faster cycle time  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q21: Release Frequency & Deployment  
  
- [ ] 0 - No change in release frequency  
- [ ] 1 - 10-20% increase in deployments/month  
- [ ] 2 - 25-40% increase in deployments/month  
- [ ] 3 - 50-75% increase in deployments/month  
- [ ] 4 - 100%+ increase; on-demand deployments  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q22: Bug Resolution Time  
  
- [ ] 0 - No improvement in bug resolution time  
- [ ] 1 - 10-15% faster bug resolution  
- [ ] 2 - 20-30% faster bug resolution  
- [ ] 3 - 35-50% faster bug resolution  
- [ ] 4 - 60%+ faster bug resolution  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q23: Change Failure Rate & Rollbacks  
  
- [ ] 0 - Increased failures  
- [ ] 1 - No change in failure rate  
- [ ] 2 - 10-20% reduction in failures  
- [ ] 3 - 25-40% reduction in failures  
- [ ] 4 - 50%+ reduction in change failure rate  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 5 TOTAL: _____ / 16**  
⸻  
## SECTION 6: SYSTEM & PROCESS (4 Questions)  
  
## Why This Section Matters  
  
This section measures whether your **INFRASTRUCTURE supports AI development speed**. Without proper systems and processes, even excellent Dev teams cannot realize AI velocity gains.  
  
**Core Principle**: Good people + AI tools + weak infrastructure = frustrated team + negative ROI  
  
**Real Impact**: The difference between a team that gains +40% velocity from AI vs a team that gains only +5% often comes down to Section 6, not Section 2 (Dev skills).  
⸻  
  
## Q24: CI/CD Pipeline Integration  
  
**INSIGHT**: AI generates code in MINUTES. If you need manual approval for every deployment, you lose 70% of speed advantage. Your infrastructure must match AI's pace, or the entire velocity gain disappears.  
  
**What This Measures**: Can code flow automatically from Dev → Production?  
  
- [ ] 0 - Manual deployment only  
- [ ] 1 - Basic CI/CD without AI-specific checks  
- [ ] 2 - CI/CD with manual gate for AI-generated code  
- [ ] 3 - Automated quality gates for AI code  
- [ ] 4 - Fully automated pipeline with fast rollback  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
⸻  
## Q25: Version Control Practices  
  
**INSIGHT**: More AI code = higher risk. One bad deploy without rollback = 4-hour crisis = negative ROI. You need instant undo capability. With AI velocity, failures happen faster too, so recovery must be immediate.  
  
**What This Measures**: Can you track every change? Can you instantly undo a bad deploy?  
  
- [ ] 0 - Infrequent commits; no rollback  
- [ ] 1 - Manual commit discipline  
- [ ] 2 - Regular commits (1x per day)  
- [ ] 3 - Frequent commits; rollback exists  
- [ ] 4 - Atomic commits; instant rollback capability  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
⸻  
## Q26: Data Accessibility for AI  
  
**INSIGHT**: AI without context generates generic code. AI with context (repos, docs, schemas) generates 90% correctly. The difference between 50% manual rework (no context) and <5% manual rework (full context) is whether your AI tools can see your internal systems.  
  
**What This Measures**: Can AI tools access your internal systems? (Repos, docs, wikis, database schemas?)  
  
- [ ] 0 - Data not accessible to AI tools  
- [ ] 1 - Minimal internal data integration  
- [ ] 2 - Basic access to documentation/schema  
- [ ] 3 - AI connected to internal systems  
- [ ] 4 - Full context: repos + docs + wikis + schemas  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
⸻  
## Q27: Platform Quality & Developer Experience  
  
**INSIGHT**: Good platform = less friction = teams focus on AI. Bad platform = developers spend 40% of time fighting tools instead of building features. Platform friction multiplies across the team. When developers waste time on deployment/setup, they can't leverage AI effectively.  
  
**What This Measures**: Is your internal developer platform mature?  
  
- [ ] 0 - No internal platform or low quality  
- [ ] 1 - Basic platform, but with friction  
- [ ] 2 - Platform exists; ~50% coverage  
- [ ] 3 - Good platform; solid DX  
- [ ] 4 - High-quality platform; independent development  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
⸻  
## SECTION 6 TOTAL: _____ / 16  
⸻  
## SECTION 7: ORGANIZATIONAL OUTCOMES (3 Questions)  
  
### Q28: Software Delivery Performance (DORA Metrics)  
  
- [ ] 0 - Low throughput OR very high instability  
- [ ] 1 - Monthly deployments; 16-45% CFR (change failure rate)  
- [ ] 2 - Weekly deployments; 8-15% CFR  
- [ ] 3 - Multiple per week; 4-8% CFR  
- [ ] 4 - Multiple per day; < 4% CFR (Elite)  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q29: Team Performance & Well-being  
  
- [ ] 0 - High burnout; high friction  
- [ ] 1 - Noticeable burnout/friction  
- [ ] 2 - Average burnout/friction levels  
- [ ] 3 - Low friction/burnout; good effectiveness  
- [ ] 4 - Harmonious: low friction, high effectiveness  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q30: Organizational Performance & ROI  
  
- [ ] 0 - Negative/no ROI from AI investment  
- [ ] 1 - Unproven ROI; chaotic results  
- [ ] 2 - Some ROI; localized gains  
- [ ] 3 - Clear ROI; measurable impact  
- [ ] 4 - Strong ROI; strategic advantage  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 7 TOTAL: _____ / 12**  
⸻  
## SECTION 8: LEARNING & ENABLEMENT (4 Questions)  
  
### Q31: AI Assisted Tools Training & Onboarding  
  
- [ ] 0 - No formal training provided  
- [ ] 1 - Ad-hoc self-learning only  
- [ ] 2 - Basic documentation/tutorials available  
- [ ] 3 - Structured training program + peer support  
- [ ] 4 - Comprehensive training + mentorship  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q32: Prompt Engineering Skills  
  
- [ ] 0 - No awareness of prompt engineering  
- [ ] 1 - Basic trial-and-error approach  
- [ ] 2 - Some team members use structured prompts  
- [ ] 3 - Team has documented prompt patterns  
- [ ] 4 - Advanced: internal library + A/B testing  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q33: Knowledge Sharing & Community  
  
- [ ] 0 - No knowledge sharing  
- [ ] 1 - Informal conversations only  
- [ ] 2 - Occasional team meetings/demos  
- [ ] 3 - Regular demos + shared documentation  
- [ ] 4 - Active community; retrospectives; learnings  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q34: Error Recovery & Learning from Failures  
  
- [ ] 0 - No process for handling AI errors  
- [ ] 1 - Manual detection and fixing  
- [ ] 2 - Basic error tracking  
- [ ] 3 - Systematic error review + learnings  
- [ ] 4 - Automated detection + feedback loop  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 8 TOTAL: _____ / 16**  
⸻  
## SECTION 9: SECURITY & COMPLIANCE (3 Questions)  
  
### Q35: Data Privacy & Confidentiality  
  
- [ ] 0 - No awareness/policy for sensitive data  
- [ ] 1 - Informal "be careful" guidance  
- [ ] 2 - Written policy; manual review  
- [ ] 3 - Automated scanning for secrets/PII  
- [ ] 4 - Full data governance: prevention + detection  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q36: License & IP Compliance  
- [ ] 0 - No license checking for AI code  
- [ ] 1 - Manual review of suspicious code  
- [ ] 2 - Basic license scanning tools  
- [ ] 3 - Automated checking in CI/CD  
- [ ] 4 - Full IP review + legal oversight + training  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q37: Security Vulnerabilities in AI Code  
  
- [ ] 0 - No security scanning for AI code  
- [ ] 1 - Manual code review for security  
- [ ] 2 - Basic SAST/DAST tools  
- [ ] 3 - Automated security scanning  
- [ ] 4 - Full security pipeline + AI-specific detection  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 9 TOTAL: _____ / 12**  
⸻  
## SECTION 10: TEAM DYNAMICS & COLLABORATION (4 Questions)  
  
### Q38: Skill Level Distribution Impact  
  
- [ ] 0 - Significant skill gap issues  
- [ ] 1 - Uneven benefits across seniority  
- [ ] 2 - Junior devs benefit; seniors skeptical  
- [ ] 3 - Benefits distributed across all levels  
- [ ] 4 - AI amplifies all levels; accelerated learning  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q39: Review Dynamics (Code & Test Reviews)  
  
- [ ] 0 - Reviews unchanged/degraded  
- [ ] 1 - More time spent on AI artifact review  
- [ ] 2 - Similar review time; different focus  
- [ ] 3 - Reviews more efficient; focus on logic  
- [ ] 4 - AI-assisted reviews; higher quality feedback  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q40: Dev-QA Collaboration  
  
- [ ] 0 - AI creates friction  
- [ ] 1 - No change in Dev-QA collaboration  
- [ ] 2 - Slight improvement in communication  
- [ ] 3 - Better alignment; shared practices  
- [ ] 4 - Seamless workflows; true shift-left testing  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q41: Cross-Team AI Standards & Practices  
  
- [ ] 0 - No coordination; each team uses differently  
- [ ] 1 - Informal knowledge sharing only  
- [ ] 2 - Basic documentation per team  
- [ ] 3 - Cross-team AI guidelines  
- [ ] 4 - Unified AI CoE for Dev+QA  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 10 TOTAL: _____ / 16**  
⸻  
## SECTION 11: COST & ROI METRICS - EXPANDED (5 Questions)   
  
### Q42: Cost Tracking  
  
- [ ] 0 - No cost tracking  
- [ ] 1 - Aware of subscription costs only  
- [ ] 2 - Track tool subscriptions + licenses  
- [ ] 3 - Track tools + training + setup costs  
- [ ] 4 - Full TCO (Total Cost Ownership)analysis; cost per developer; ROI  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q43: Quantified Time Savings  
  
- [ ] 0 - No measurement of time savings  
- [ ] 1 - Anecdotal feedback only  
- [ ] 2 - Survey-based perception data  
- [ ] 3 - Time tracking for specific tasks  
- [ ] 4 - Comprehensive metrics; A/B testing  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q44: License Cost Efficiency   
  
**What we measure**: How efficiently is AI license cost managed per developer  
  
- [ ] 0 - No tracking of license spend  
- [ ] 1 - Cost awareness but no optimization  
- [ ] 2 - Some cost controls implemented  
- [ ] 3 - Cost per developer regularly reviewed  
- [ ] 4 - Dynamic licensing; seat optimization; ROI justified  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q45: Time-to-Value   
  
**What we measure**: Time elapsed from AI adoption to measurable business impact  
  
- [ ] 0 - Not measured or no value yet  
- [ ] 1 - >6 months to see first impact  
- [ ] 2 - 3-6 months to measurable impact  
- [ ] 3 - 1-3 months to clear ROI  
- [ ] 4 - <1 month; quick wins achieved  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q46: Budget vs Actual (Variance Analysis)   
  
**What we measure**: Tracking planned vs actual ROI and cost performance  
  
- [ ] 0 - No budget planning for AI  
- [ ] 1 - Budget exists but no tracking  
- [ ] 2 - Basic variance tracking  
- [ ] 3 - Monthly variance reviews; adjustments made  
- [ ] 4 - Real-time tracking; predictive analytics  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 11 TOTAL: _____ / 20**  
⸻  
## SECTION 12: AI CODE QUALITY (3 Questions)   
  
### Comprehensive AI output quality assessment  
  
### Q47: AI Code Rejection Rate   
  
**What we measure**: Percentage of AI-generated code that gets rejected in review/testing  
  
**Context**: High rejection indicates quality issues; low rejection indicates effective AI usage  
  
- [ ] 0 - >40% rejection rate  
- [ ] 1 - 25-40% rejection rate  
- [ ] 2 - 15-25% rejection rate  
- [ ] 3 - 5-15% rejection rate (acceptable)  
- [ ] 4 - <5% rejection rate; high-quality AI output  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q48: Manual Fix Rate (Post-AI)   
  
**What we measure**: Time spent fixing/refactoring AI-generated code vs manual changes  
  
- [ ] 0 - >50% time fixing AI code vs creating  
- [ ] 1 - 35-50% time on fixing  
- [ ] 2 - 20-35% time on fixing  
- [ ] 3 - 10-20% time on fixing  
- [ ] 4 - <10% time on fixes; production-ready AI code  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
### Q49: AI Hallucination Impact   
  
**What we measure**: Critical bugs or security issues caused by AI hallucinations/false outputs  
  
**Hallucination examples**: Non-existent APIs, incorrect algorithm logic, security mistakes  
  
- [ ] 0 - Frequent hallucinations causing production issues  
- [ ] 1 - Regular hallucinations caught in review  
- [ ] 2 - Occasional hallucinations detected  
- [ ] 3 - Rare hallucinations; caught consistently  
- [ ] 4 - Hallucinations prevented; validation processes work  
- [ ] N/A - Not applicable  
  
**Your Score: _____**  
  
**SECTION 12 TOTAL: _____ / 12**  
⸻  
## SCORING SUMMARY  
  
**Calculate Your Total Score**  

| Section                    | Your Score | Maximum | Status |
| -------------------------- | ---------- | ------- | ------ |
| 1. AI Adoption & Usage     | _____      | 24      | ✅      |
| 2. Development Activities  | _____      | 20      | ✅      |
| 3. QA Activities           | _____      | 20      | ✅      |
| 4. Requirements & Planning | _____      | 12      | ✅      |
| 5. SDLC Velocity           | _____      | 16      | ✅      |
| 6. System & Process        | _____      | 16      | ✅      |
| 7. Organizational Outcomes | _____      | 12      | ✅      |
| 8. Learning & Enablement   | _____      | 16      | ✅      |
| 9. Security & Compliance   | _____      | 12      | ✅      |
| 10. Team Dynamics          | _____      | 16      | ✅      |
| 11. Cost & ROI Metrics     | _____      | 20      | ✅      |
| 12. AI Code Quality        | _____      | 12      | ✅      |
| TOTAL SCORE                | _____      | 196     | ✅      |
  
  
**Percentage**: _____ / 196 = _____%  
⸻  
## MATURITY LEVELS   
  
**UPDATED: More realistic thresholds with new Level 5**  

| Level | Score | % | Color | Status | Profile |
| --------- | -------- | -------- | ------------- | -------------- | ------------------------ |
| Level 0 | 0-39 | 0-20% | 🔴 Red | No AI Adoption | Unaware or resistant |
| Level 1 | 40-78 | 20-40% | 🟠 Orange | Experimental | Early adopters present |
| Level 2 | 79-117 | 40-60% | 🟡 Yellow | Integrated | 50-70% adoption |
| Level 3 | 118-146 | 60-75% | 🟢 Light Green | Mature | 80%+ adoption, clear ROI |
| Level 4 | 147-176 | 75-90% | 🟢 Green | Advanced | Strong practices |
| Level 5 🆕 | 177-196+ | 90-100%+ | 🟢 Dark Green | AI Excellence | Industry leaders |
  
⸻  
## APPENDIX: OBJECTIVE METRICS   
  
### ⬆️ VALIDATION: Complement self-assessment with git-based metrics  
  
To reduce perception vs reality gap (DORA 2025 finding: gap can exceed 50%), track:  
  
### Git-Based Metrics (Automated Tracking)  
  
**Metric 1: Commits Per Day (Before/After AI)**  
- Track via: GitHub API, GitLab API  
- Calculation: Total commits / total developers / days  
- Target improvement: 15-30% increase post-AI  
  
**Metric 2: PR Merge Time**  
- Track via: GitHub/GitLab webhook events  
- Calculation: Time from PR creation to merge (hours)  
- Target: <4 hours median (enabling fast feedback)  
  
**Metric 3: Test Execution Time**  
- Track via: CI/CD pipeline logs  
- Calculation: Total test suite duration (minutes)  
- Target: <5 minutes for Nyquist criterion  
  
**Metric 4: Code Review Duration**  
- Track via: PR timeline analysis  
- Calculation: Time from PR creation to first review (hours)  
- Target: <2 hours for effective feedback  
  
**Metric 5: Deployment Frequency**  
- Track via: CD platform logs  
- Calculation: Deployments per day/week  
- Target: >1 per week (ideal)  
  
**Metric 6: Change Failure Rate**  
- Track via: Incident tracking + git correlation  
- Calculation: Failed deployments / total deployments (%)  
- Target: <5% (DORA elite)  
  
### How to Implement  
  
1. **Integration**: Connect GitHub/GitLab/Jira/SonarQube to central dashboard  
2. **Baseline**: Measure metrics for 2 weeks pre-AI, then post-AI  
3. **Comparison**: Calculate before/after delta for each metric  
4. **Reporting**: Include in quarterly reviews alongside self-assessment  
  
### Sample Dashboard  
  
```
Metric              | Before AI | After AI | Delta   | Status
-----------------------------------------------------------------
Commits/Day         | 45        | 58       | +28%    | ✅ Improved
PR Merge Time       | 5.2h      | 3.1h     | -40%    | ✅ Improved
Test Duration       | 8 min     | 4.5 min  | -44%    | ✅ Improved
Code Review Time    | 4.5h      | 2.1h     | -53%    | ✅ Improved
Deployments/Week    | 2.1       | 3.8      | +81%    | ✅ Improved
Change Failure Rate | 12%       | 8%       | -4pp    | ✅ Improved

```
  
⸻  
## NEXT STEPS  
  
### Phase 1: Quick Wins (0-30 Days)  
- [ ] Complete full assessment (49 questions)  
- [ ] Identify 3 priority gaps  
- [ ] Start tracking objective metrics  
- [ ] Implement Cost & ROI tracking (Q42-Q46)  
  
### Phase 2: Build Foundation (30-90 Days)  
- [ ] Strengthen System & Process (Section 6)  
- [ ] Expand training program  
- [ ] Establish AI governance  
- [ ] Re-assess 3 priority sections  
  
### Phase 3: Scale (90-180 Days)  
- [ ] Target Level 3 maturity across all sections  
- [ ] Achieve <5-min feedback loops (Nyquist criterion)  
- [ ] Integrate objective metrics dashboard  
- [ ] Full re-assessment + roadmap update  
  
### Phase 4: Optimize (6-12 Months)  
- [ ] Target Level 4-5 maturity  
- [ ] Achieve DORA elite performance  
- [ ] Build organizational AI CoE  
- [ ] Share best practices  
⸻  
