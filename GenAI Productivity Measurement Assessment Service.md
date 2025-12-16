# GenAI Productivity Measurement Assessment Service
## Self-Assessment Framework Based on DORA 2025
**VERSION 4.6 - DORA OPTIMIZED + DEVELOPER-FRIENDLY (39 Questions)**

---

## TABLE OF CONTENTS

1. Assessment Framework Overview
2. Self-Assessment Questionnaire
3. Scoring & Maturity Levels
4. Appendix: Objective Metrics
5. Next Steps

---

## ASSESSMENT FRAMEWORK OVERVIEW

### What Changed in v4.5

| Change | Removed Questions | Reason |
|--------|-------------------|--------|
| Removed redundancy | Q3 (Reliance), Q11 (Dev Velocity), Q16 (QA Productivity) | Overlap with other questions |
| Removed too specific | Q18 (BDD), Q32 (Prompt Engineering) | Practice-specific, not capability |
| Removed redundancy | Q41 (Standards), Q47 (Rejection Rate) | Overlap with Q33, Q38 |
| Removed wrong scope | Q44, Q45, Q46 (Finance metrics) | Finance, not engineering |

### Assessment Structure (Optimized)

| Section | Questions | Focus Area | Score Range |
|---------|-----------|-----------|-------------|
| AI Adoption & Usage | 5 | Reflexive use, trust, tools, core tasks | 0-20 |
| Development Activities | 4 | Coding, testing, review, quality | 0-16 |
| QA Activities | 4 | Manual QA, automation, bugs, test data | 0-16 |
| Requirements & Planning | 2 | User stories, test strategy | 0-8 |
| SDLC Velocity | 4 | Cycle time, release freq, bug resolution, CFR | 0-16 |
| System & Process | 4 | CI/CD, version control, data access, workflows | 0-16 |
| Organizational Outcomes | 3 | DORA metrics, team well-being, ROI | 0-12 |
| Learning & Enablement | 3 | Training, knowledge sharing, error recovery | 0-12 |
| Security & Compliance | 3 | Privacy, licenses, vulnerabilities | 0-12 |
| Team Dynamics | 3 | Skill distribution, reviews, Dev-QA collab | 0-12 |
| Cost & ROI | 2 | Cost tracking, time savings | 0-8 |
| AI Code Quality | 2 | Manual fix rate, hallucinations | 0-8 |
| **TOTAL** | **39** | **DORA-Aligned Assessment** | **0-156** |

---

## SELF-ASSESSMENT QUESTIONNAIRE

### Scoring Scale: 0-4 points per question

| Score | Interpretation |
|-------|----------------|
| 0 | Not implemented |
| 1 | Initial stage / Experimental |
| 2 | Partially implemented |
| 3 | Implemented across majority |
| 4 | Fully implemented and optimized |
| **N/A** | **Not applicable** |

---

## SECTION 1: AI ADOPTION & USAGE (5 Questions)

### Q1: AI Tools Integration in Daily Workflow

**What This Measures**: Adoption breadth across Dev + QA teams.

**DORA Insight**: 90% of developers use AI; median 2 hours per day

- [ ] 0 - No AI usage in Dev or QA
- [ ] 1 - Individual team members experimenting
- [ ] 2 - ~50% of Dev + QA teams use AI regularly
- [ ] 3 - ~75% of both teams use AI by default
- [ ] 4 - 90%+ across Dev and QA; AI is standard workflow
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q2: AI as First Choice (How Often Do You Start with AI?)

**What This Measures**: When you face a new task, do you naturally reach for AI first? This captures behavioral habit, not just tool availability.

**DORA Insight**: 60% use AI "about half the time" or more

- [ ] 0 - Never start with AI; always code manually first
- [ ] 1 - Rarely (< 25% of new tasks start with AI)
- [ ] 2 - Sometimes (~50% of new tasks start with AI)
- [ ] 3 - Usually (60-80% of new tasks start with AI)
- [ ] 4 - Almost always (~80%+ of tasks—I ask AI before writing code)
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q3: Trust in AI-Generated Code

**What This Measures**: Team confidence in AI outputs. Trust → less review → faster delivery.

**DORA Insight**: 70% have some trust; 30% have low trust

- [ ] 0 - No trust in AI output
- [ ] 1 - Very low trust
- [ ] 2 - Moderate trust, thorough review required
- [ ] 3 - High trust with spot-checks
- [ ] 4 - High trust; minimal additional review
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q4: AI Usage Modes Coverage

**What This Measures**: Diversity of AI tool usage across different interaction patterns.

**DORA Insight**: Chat/IDE (55%), Predictive (41%), Collaborative (18%), Agent (12%)

**Mode Examples**:
- **Chat**: ChatGPT, Claude, Gemini (web interface)
- **IDE**: GitHub Copilot, Cursor, Tabnine (inline in editor)
- **Predictive**: Copilot autocomplete, code suggestions as you type
- **Collaborative**: Cursor Composer, Copilot Workspace (multi-file edits)
- **Agent**: Devin, Claude Computer Use, GPT Engineer (autonomous tasks)

- [ ] 0 - Single mode only (e.g., only ChatGPT web)
- [ ] 1 - Chat + IDE (e.g., ChatGPT + Copilot)
- [ ] 2 - Chat + IDE + Predictive (autocomplete suggestions)
- [ ] 3 - Chat + IDE + Predictive + Collaborative (multi-file AI edits)
- [ ] 4 - All modes including Agent (AI performs multi-step tasks autonomously)
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q5: AI for Core Dev & QA Tasks

**What This Measures**: Whether AI is used for core work vs. peripheral tasks.

**DORA Insight**: 71% for writing code, 66% modifying code, 62% for tests

- [ ] 0 - Only for auxiliary tasks (docs, comments)
- [ ] 1 - For simple tasks (boilerplate, basic tests)
- [ ] 2 - For main work (~30-40% of tasks)
- [ ] 3 - For majority (~60% of core work)
- [ ] 4 - Primary workflow for both Dev and QA
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 1 TOTAL: _____ / 20**

---

## SECTION 2: DEVELOPMENT ACTIVITIES (4 Questions)

### Q6: Coding & Development

**What This Measures**: Volume of AI-assisted code generation.

**DORA Insight**: 71% use AI for writing code, 66% for modifying code

- [ ] 0 - No AI for coding activities
- [ ] 1 - Occasional AI hints for simple code
- [ ] 2 - AI generates 30-40% of code
- [ ] 3 - AI generates 60-70% of code
- [ ] 4 - AI is primary coding assistant; 80%+ generation
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q7: Developer Testing (Unit & Integration)

**What This Measures**: AI usage for test code generation.

**DORA Insight**: 62% use AI for creating test cases

- [ ] 0 - Developers do not use AI for test writing
- [ ] 1 - Manual test writing with occasional AI hints
- [ ] 2 - AI generates 20-30% of unit/integration tests
- [ ] 3 - AI generates 50-70% of tests
- [ ] 4 - AI generates 80%+ of tests with high coverage
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q8: Code Review Process

**What This Measures**: Quality assurance process for AI-generated code.

**DORA Insight**: 30% do not trust AI code; validation is critical

- [ ] 0 - No special process for AI-generated code
- [ ] 1 - Manual review of all AI-generated code (human reads every line)
- [ ] 2 - Linting (ESLint, Prettier) + manual review
- [ ] 3 - Automated tests run + selective manual review (focus on logic)
- [ ] 4 - Full pipeline: automated tests + AI code review tools (CodeRabbit, Codium, SonarQube) + security scanning
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q9: Code Quality & Standards

**What This Measures**: Perceived impact of AI on code quality (readability, maintainability, bugs).

**DORA Insight**: 59% see positive impact; 10% see negative

- [ ] 0 - Negative impact (more bugs, worse readability)
- [ ] 1 - No change in quality
- [ ] 2 - Slight improvement (cleaner code sometimes)
- [ ] 3 - Noticeable improvement (better code in ~30-50% of cases)
- [ ] 4 - Significant improvement (AI code is often cleaner than manual code)
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 2 TOTAL: _____ / 16**

---

## SECTION 3: QA ACTIVITIES (4 Questions)

### Q10: Manual QA & Test Case Design

**What This Measures**: AI usage for test case design by QA teams.

- [ ] 0 - Manual QA does not use AI at all
- [ ] 1 - AI assists with test documentation only
- [ ] 2 - AI helps design 20-30% of test cases
- [ ] 3 - AI helps design 50-70% of test cases
- [ ] 4 - AI generates 80%+ of test cases
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q11: Test Automation (E2E, API, UI)

**What This Measures**: AI assistance with automation scripts (Selenium, Playwright, Cypress).

- [ ] 0 - Test automation does not use AI
- [ ] 1 - AI assists with test planning/setup
- [ ] 2 - AI generates 20-30% of automation scripts
- [ ] 3 - AI generates 50-70% of automated tests
- [ ] 4 - AI generates 80%+ of test automation
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q12: Bug Detection & Analysis

**What This Measures**: AI role in bug detection, triage, and root cause analysis.

- [ ] 0 - No AI for bug-related activities
- [ ] 1 - AI assists with bug report writing
- [ ] 2 - AI helps with bug triage and categorization
- [ ] 3 - AI assists with root cause analysis for 50%+
- [ ] 4 - AI automates bug detection and suggests fixes
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q13: Test Data Management

**What This Measures**: AI assistance in generating diverse test data.

- [ ] 0 - No AI for test data activities
- [ ] 1 - AI generates simple test data occasionally
- [ ] 2 - AI generates 30-40% of test data
- [ ] 3 - AI generates comprehensive test data
- [ ] 4 - AI fully automates test data generation
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 3 TOTAL: _____ / 16**

---

## SECTION 4: REQUIREMENTS & PLANNING (2 Questions)

### Q14: Requirements & User Stories

**What This Measures**: AI assistance in requirements phase.

- [ ] 0 - No AI in requirements phase
- [ ] 1 - AI assists with formatting/templates
- [ ] 2 - AI helps draft 30-40% of user stories
- [ ] 3 - AI helps with 60%+ of requirements
- [ ] 4 - AI fully assists with requirements & criteria
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q15: Test Strategy & Planning

**What This Measures**: AI assistance in creating test strategies and identifying what to test.

- [ ] 0 - No AI in test planning
- [ ] 1 - AI suggests what areas to test
- [ ] 2 - AI helps identify 30-40% of test scenarios
- [ ] 3 - AI helps prioritize tests and identify high-risk areas (e.g., "this feature has many edge cases")
- [ ] 4 - AI generates comprehensive test plans with priorities and coverage recommendations
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 4 TOTAL: _____ / 8**

---

## SECTION 5: SDLC VELOCITY & CYCLE TIME (4 Questions)

### Q16: End-to-End Cycle Time

**What This Measures**: Cycle time improvement from idea to production. **DORA: Lead Time**

- [ ] 0 - No improvement in cycle time
- [ ] 1 - 5-10% faster cycle time
- [ ] 2 - 15-25% faster cycle time
- [ ] 3 - 30-45% faster cycle time
- [ ] 4 - 50%+ faster cycle time
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q17: Release Frequency & Deployment

**What This Measures**: Deployment frequency improvement. **DORA: Deployment Frequency**

- [ ] 0 - No change in release frequency
- [ ] 1 - 10-20% increase in deployments/month
- [ ] 2 - 25-40% increase in deployments/month
- [ ] 3 - 50-75% increase in deployments/month
- [ ] 4 - 100%+ increase; on-demand deployments
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q18: Bug Resolution Time

**What This Measures**: Speed of bug fixes. **DORA: Mean Time to Recovery (MTTR)**

- [ ] 0 - No improvement in bug resolution time
- [ ] 1 - 10-15% faster bug resolution
- [ ] 2 - 20-30% faster bug resolution
- [ ] 3 - 35-50% faster bug resolution
- [ ] 4 - 60%+ faster bug resolution
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q19: Change Failure Rate & Rollbacks

**What This Measures**: Release stability. **DORA: Change Failure Rate (CFR)**

- [ ] 0 - Increased failures since AI adoption
- [ ] 1 - No change in failure rate
- [ ] 2 - 10-20% reduction in failures
- [ ] 3 - 25-40% reduction in failures
- [ ] 4 - 50%+ reduction in change failure rate
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 5 TOTAL: _____ / 16**

---

## SECTION 6: SYSTEM & PROCESS (4 Questions)

### Q20: CI/CD Pipeline Integration

**What This Measures**: How automated is your deployment process for AI-generated code?

- [ ] 0 - Manual deployment only (no CI/CD)
- [ ] 1 - Basic CI/CD (builds and tests run, but no AI-specific checks)
- [ ] 2 - CI/CD with manual approval step before merging AI-generated code
- [ ] 3 - Automated quality gates (tests, linting, security checks) for all code including AI
- [ ] 4 - Fully automated pipeline with fast rollback (can revert bad deploys in minutes)
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q21: Version Control Practices

**What This Measures**: Commit discipline and rollback capability.

- [ ] 0 - Infrequent commits; no rollback
- [ ] 1 - Manual commit discipline
- [ ] 2 - Regular commits (1x per day)
- [ ] 3 - Frequent commits; rollback exists
- [ ] 4 - Atomic commits; instant rollback capability
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q22: Data Accessibility for AI

**What This Measures**: Can your AI tools access internal context to give better suggestions?

**Examples of internal context**: Your codebase, Confluence/Notion docs, Jira tickets, database schemas, API documentation, architecture diagrams

- [ ] 0 - AI has no access to internal data (only public knowledge)
- [ ] 1 - AI can see current file only
- [ ] 2 - AI can access your codebase (repos) and basic docs
- [ ] 3 - AI connected to multiple internal systems (repos + docs + tickets)
- [ ] 4 - Full context: AI sees your codebase, documentation, wikis, schemas, and historical decisions
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q23: Developer Workflow Quality

**What This Measures**: Ease of building, testing, and deploying software.

- [ ] 0 - Daily work is mostly manual or painful
- [ ] 1 - Basic workflows exist, frequent friction
- [ ] 2 - Workflows exist; ~50% of teams benefit
- [ ] 3 - Well-defined workflows; solid developer experience
- [ ] 4 - Highly efficient workflows; teams deliver independently
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 6 TOTAL: _____ / 16**

---

## SECTION 7: ORGANIZATIONAL OUTCOMES (3 Questions)

### Q24: Software Delivery Performance (DORA Metrics)

**What This Measures**: How often you deploy AND how stable those deployments are.

**Key terms**:
- **Deployment frequency**: How often code goes to production
- **Change Failure Rate (CFR)**: % of deployments that cause problems (rollbacks, hotfixes, incidents)

- [ ] 0 - Deploy less than monthly OR many deployments fail/need rollback
- [ ] 1 - Deploy monthly; roughly 1 in 3-5 deployments causes issues
- [ ] 2 - Deploy weekly; roughly 1 in 10 deployments causes issues
- [ ] 3 - Deploy multiple times per week; deployments rarely fail
- [ ] 4 - Deploy multiple times per day; almost never fail (<4% failure rate) — **Elite level**
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q25: Team Performance & Well-being

**What This Measures**: Has AI adoption improved or harmed team morale and collaboration?

**DORA Insight**: Burnout and friction are cultural issues, not technical—AI doesn't automatically fix them.

- [ ] 0 - High burnout; frequent conflicts; team struggles
- [ ] 1 - Noticeable stress or friction since AI adoption
- [ ] 2 - Average levels—similar to before AI
- [ ] 3 - Low friction; team works well together; good productivity
- [ ] 4 - High team satisfaction; effective collaboration; no burnout; AI makes work more enjoyable
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q26: Organizational Performance & ROI

**What This Measures**: Business ROI from AI investment.

- [ ] 0 - Negative/no ROI from AI investment
- [ ] 1 - Unproven ROI; chaotic results
- [ ] 2 - Some ROI; localized gains
- [ ] 3 - Clear ROI; measurable impact
- [ ] 4 - Strong ROI; strategic advantage
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 7 TOTAL: _____ / 12**

---

## SECTION 8: LEARNING & ENABLEMENT (3 Questions)

### Q27: AI Tools Training & Onboarding

**What This Measures**: Formal training on AI tools.

- [ ] 0 - No formal training provided
- [ ] 1 - Ad-hoc self-learning only
- [ ] 2 - Basic documentation/tutorials available
- [ ] 3 - Structured training program + peer support
- [ ] 4 - Comprehensive training + mentorship
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q28: Knowledge Sharing & Community

**What This Measures**: Team knowledge sharing and collective learning.

- [ ] 0 - No knowledge sharing
- [ ] 1 - Informal conversations only
- [ ] 2 - Occasional team meetings/demos
- [ ] 3 - Regular demos + shared documentation
- [ ] 4 - Active community; retrospectives; learnings
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q29: Error Recovery & Learning from Failures

**What This Measures**: Systematic learning from AI-related failures.

- [ ] 0 - No process for handling AI errors
- [ ] 1 - Manual detection and fixing
- [ ] 2 - Basic error tracking
- [ ] 3 - Systematic error review + learnings
- [ ] 4 - Automated detection + feedback loop
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 8 TOTAL: _____ / 12**

---

## SECTION 9: SECURITY & COMPLIANCE (3 Questions)

### Q30: Data Privacy & Confidentiality

**What This Measures**: Data privacy safeguards for AI prompts.

- [ ] 0 - No awareness/policy for sensitive data
- [ ] 1 - Informal "be careful" guidance
- [ ] 2 - Written policy; manual review
- [ ] 3 - Automated scanning for secrets/PII
- [ ] 4 - Full data governance: prevention + detection
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q31: License & IP Compliance

**What This Measures**: Do you check if AI-generated code has licensing issues? (AI might suggest code copied from open-source with restrictive licenses)

- [ ] 0 - No license checking for AI code
- [ ] 1 - Manual review when code looks suspicious
- [ ] 2 - Basic license scanning tools (e.g., FOSSA, Snyk)
- [ ] 3 - Automated license checking in CI/CD pipeline
- [ ] 4 - Automated scanning + clear policy + team training on license risks
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q32: Security Vulnerabilities in AI Code

**What This Measures**: Do you scan AI-generated code for security vulnerabilities? (AI can introduce SQL injection, XSS, insecure dependencies)

- [ ] 0 - No security scanning for AI code
- [ ] 1 - Manual code review for security issues
- [ ] 2 - Basic security scanning tools (Snyk, SonarQube, Dependabot, npm audit)
- [ ] 3 - Automated security scanning in CI/CD for every PR
- [ ] 4 - Full security pipeline: static analysis + dependency scanning + secret detection + runtime checks
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 9 TOTAL: _____ / 12**

---

## SECTION 10: TEAM DYNAMICS (3 Questions)

### Q33: Skill Level Distribution Impact

**What This Measures**: Does AI help everyone on the team, or only certain skill levels?

- [ ] 0 - AI benefits only a few team members; others struggle or don't use it
- [ ] 1 - Mainly senior developers benefit; juniors find it confusing
- [ ] 2 - Mixed results—some benefit more than others
- [ ] 3 - Most team members benefit from AI regardless of experience level
- [ ] 4 - Everyone benefits: juniors learn faster with AI; seniors are more productive
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q34: Review Dynamics (Code & Test Reviews)

**What This Measures**: Code review efficiency with AI.

- [ ] 0 - Reviews unchanged/degraded
- [ ] 1 - More time spent on AI artifact review
- [ ] 2 - Similar review time; different focus
- [ ] 3 - Reviews more efficient; focus on logic
- [ ] 4 - AI-assisted reviews; higher quality feedback
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q35: Dev-QA Collaboration

**What This Measures**: Has AI improved collaboration between developers and QA?

**Shift-left testing** = QA gets involved earlier in the development cycle (not just at the end)

- [ ] 0 - AI creates friction between Dev and QA
- [ ] 1 - No change in Dev-QA collaboration
- [ ] 2 - Slight improvement in communication
- [ ] 3 - Better alignment; Dev and QA share AI practices and tools
- [ ] 4 - Seamless workflows; QA involved early; shared test generation with AI
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 10 TOTAL: _____ / 12**

---

## SECTION 11: COST & ROI (2 Questions)

### Q36: Cost Tracking

**What This Measures**: Do you track the Total Cost of Ownership (TCO) for AI tools?

**TCO includes**: Tool subscriptions (Copilot, ChatGPT Pro) + training time + infrastructure + time spent fixing AI mistakes

- [ ] 0 - No cost tracking
- [ ] 1 - Know subscription costs only (e.g., "$19/month for Copilot")
- [ ] 2 - Track tool subscriptions + license counts
- [ ] 3 - Track tools + training time + setup costs
- [ ] 4 - Full TCO analysis: cost per developer, productivity gains, ROI calculation
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q37: Quantified Time Savings

**What This Measures**: Data-driven measurement of time savings.

- [ ] 0 - No measurement of time savings
- [ ] 1 - Anecdotal feedback only
- [ ] 2 - Survey-based perception data
- [ ] 3 - Time tracking for specific tasks
- [ ] 4 - Comprehensive metrics; A/B testing
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 11 TOTAL: _____ / 8**

---

## SECTION 12: AI CODE QUALITY (2 Questions)

### Q38: Manual Fix Rate (Post-AI)

**What This Measures**: Manual work needed to fix AI-generated code.

- [ ] 0 - >50% time fixing AI code vs creating
- [ ] 1 - 35-50% time on fixing
- [ ] 2 - 20-35% time on fixing
- [ ] 3 - 10-20% time on fixing
- [ ] 4 - <10% time on fixes; production-ready AI code
- [ ] N/A - Not applicable

**Your Score: _____**

---

### Q39: AI Hallucination Impact

**What This Measures**: Impact of AI hallucinations (fake APIs, incorrect methods).

- [ ] 0 - Frequent hallucinations causing production issues
- [ ] 1 - Regular hallucinations caught in review
- [ ] 2 - Occasional hallucinations detected
- [ ] 3 - Rare hallucinations; caught consistently
- [ ] 4 - Hallucinations prevented; validation processes work
- [ ] N/A - Not applicable

**Your Score: _____**

**SECTION 12 TOTAL: _____ / 8**

---

## SCORING SUMMARY

### Calculate Your Total Score

| Section | Your Score | Maximum |
|---------|-----------|---------|
| 1. AI Adoption & Usage | _____ | 20 |
| 2. Development Activities | _____ | 16 |
| 3. QA Activities | _____ | 16 |
| 4. Requirements & Planning | _____ | 8 |
| 5. SDLC Velocity (DORA) | _____ | 16 |
| 6. System & Process | _____ | 16 |
| 7. Organizational Outcomes | _____ | 12 |
| 8. Learning & Enablement | _____ | 12 |
| 9. Security & Compliance | _____ | 12 |
| 10. Team Dynamics | _____ | 12 |
| 11. Cost & ROI | _____ | 8 |
| 12. AI Code Quality | _____ | 8 |
| **TOTAL SCORE** | **_____** | **156** |

**Percentage**: _____ / 156 = _____%

---

## MATURITY LEVELS

| Level | Score | % | Color | Status | Profile |
|-------|-------|---|-------|--------|---------|
| **Level 0** | 0-31 | 0-20% | 🔴 Red | No AI Adoption | Unaware or resistant |
| **Level 1** | 32-62 | 20-40% | 🟠 Orange | Experimental | Early adopters present |
| **Level 2** | 63-93 | 40-60% | 🟡 Yellow | Integrated | 50-70% adoption |
| **Level 3** | 94-117 | 60-75% | 🟢 Light Green | Mature | 80%+ adoption, clear ROI |
| **Level 4** | 118-140 | 75-90% | 🟢 Green | Advanced | Strong practices |
| **Level 5** | 141-156+ | 90-100%+ | 🟢 Dark Green | AI Excellence | Industry leaders |

---

## DORA METRICS ALIGNMENT

### This assessment directly measures DORA's 4 Key Metrics:

| DORA Metric | Questions | Section |
|-------------|-----------|---------|
| **Deployment Frequency** | Q17, Q24 | 5, 7 |
| **Lead Time for Changes** | Q16, Q23 | 5, 6 |
| **Change Failure Rate** | Q19, Q24 | 5, 7 |
| **Mean Time to Recovery** | Q18, Q21 | 5, 6 |

---

## APPENDIX: OBJECTIVE METRICS

### Git-Based Metrics (Automated Tracking)

| Metric | Track Via | Target |
|--------|-----------|--------|
| Commits Per Day | GitHub/GitLab API | 15-30% increase post-AI |
| PR Merge Time | Webhook events | <4 hours median |
| Test Execution Time | CI/CD logs | <5 minutes |
| Code Review Duration | PR timeline | <2 hours |
| Deployment Frequency | CD platform | >1 per week |
| Change Failure Rate | Incident tracking | <5% (DORA elite) |

---

## NEXT STEPS

### Phase 1: Quick Wins (0-30 Days)
- [ ] Complete assessment (39 questions)
- [ ] Identify 3 priority gaps
- [ ] Start tracking objective metrics

### Phase 2: Build Foundation (30-90 Days)
- [ ] Strengthen System & Process (Section 6)
- [ ] Expand training program
- [ ] Re-assess priority sections

### Phase 3: Scale (90-180 Days)
- [ ] Target Level 3 maturity
- [ ] Achieve <5-min feedback loops
- [ ] Integrate metrics dashboard

### Phase 4: Optimize (6-12 Months)
- [ ] Target Level 4-5 maturity
- [ ] Achieve DORA elite performance
- [ ] Build organizational AI CoE

---

## VERSION COMPARISON

| Aspect | v4.4 | v4.5 |
|--------|------|------|
| Questions | 49 | **39** |
| Max Score | 196 | **156** |
| Time to complete | ~60 min | **~45 min** |
| Redundancy | Some overlap | **No redundancy** |
| DORA Alignment | Good | **Optimized** |

**Removed Questions**:
- Q3 (Reliance) → covered by Q1+Q2
- Q11 (Dev Velocity) → covered by Section 5
- Q16 (QA Productivity) → covered by Q10-Q13
- Q18 (BDD) → too practice-specific
- Q32 (Prompt Engineering) → ephemeral skill
- Q41 (Standards) → covered by Q28
- Q44-Q46 (Finance) → out of scope
- Q47 (Rejection Rate) → covered by Q38

---

**Document Version**: 4.6 - DORA OPTIMIZED + DEVELOPER-FRIENDLY
**Last Updated**: December 2025
**Questions**: 39 core
**Max Score**: 156 points
**Maturity Levels**: 6 (0-5)
**Key Improvements**: 
- 20% fewer questions than v4.4
- Zero loss of DORA insights
- All questions clear to regular developers
- Examples added for technical terms
- Abbreviations explained (CFR, TCO, SAST/DAST)

