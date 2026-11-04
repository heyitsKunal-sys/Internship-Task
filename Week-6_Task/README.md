# TaskFlow – Final Project Evaluation, Retrospective & Future Roadmap

![Project](https://img.shields.io/badge/Project-TaskFlow-blue)
![Internship](https://img.shields.io/badge/Internship-Week%206-green)
![Deliverable](https://img.shields.io/badge/Deliverable-Final%20Evaluation-orange)
![Focus](https://img.shields.io/badge/Focus-Continuous%20Improvement-purple)

## Project Overview

TaskFlow is a proposed web-based project and task management platform for small teams and organizations. It centralizes workspaces, projects, single-member task assignment, task status tracking, manager review and approval, comments, dashboards, and notifications.

This repository contains the **Week 6 Final Project Evaluation, Retrospective and Future Improvement Roadmap**, prepared as the final documentation assignment for the Junior Software Developer Internship at Yuva Intern.

The report reviews the planning work completed across Weeks 1–5, analyses the evaluator feedback supplied for earlier submissions, defines a measurable KPI framework, records lessons learned, and proposes a prioritized 12-month improvement roadmap.

## Internship Information

- **Organization:** Yuva Intern
- **Role:** Junior Software Developer Intern
- **Assignment:** Week 6 – Final Project Evaluation, Retrospective, and Future Roadmap
- **Project:** TaskFlow – Team Project and Task Management Platform
- **Project Status:** Hypothetical project; planning and documentation package, not a deployed product.

## Evaluation Evidence and Transparency

| Deliverable | Evaluation evidence supplied | Key learning |
|---|---|---|
| Week 1 – Requirements | Qualitative feedback: comprehensive, but needed more specific data and examples | Add measurable criteria and concrete scenarios |
| Week 2 – Architecture | **41/100**; feedback requested greater depth, concrete examples, scalability/security strategies, and interaction flows | Define component contracts, failure paths, security controls, and measurable scale triggers |
| Week 3 – Development roadmap | **52.4/100**; feedback requested finer task-level estimates and more granular challenges/mitigations | Break sprint work into estimates, dependencies, owners, and exit criteria |
| Week 4 – QA plan | No score supplied | Do not infer a score or acceptance result |
| Week 5 – Code review/debugging | No score supplied | Continue measuring review and defect processes when implemented |

The 11.4-point difference between the Week 2 and Week 3 scores is a change in document evaluation score, not a measure of application quality.

TaskFlow has no supplied production telemetry, real-user survey, deployed runtime, or completed test execution results.

## Project Baseline

- **Users:** Workspace Owner, Project Manager, Team Member
- **Proposed stack:** React.js, Tailwind CSS, Node.js, Express.js, MongoDB
- **Architecture direction:** Layered modular monolith
- **Requirements baseline:** 50 functional requirements and 56 non-functional requirements
- **Development plan:** 16-week indicative roadmap, six two-week sprints
- **Effort estimate:** 434 core development hours + 46-hour contingency = 480 development hours; 626 hours including supporting roles
- **Initial test profile:** 500 registered users, 100 concurrent simulated users, 50,000 tasks (proposed assumptions, not measured capacity)

## KPI and Quality Framework

The report defines 24 KPIs with formulas, owners, data sources, review cadence, proposed thresholds, and evidence status.

Areas include:

- Requirements traceability and sprint goal success.
- Estimation variance and pull-request review time.
- DORA delivery metrics.
- Critical business-rule and backend test coverage.
- Regression pass rate, defect escape rate, and defect reopen rate.
- API and dashboard p95 latency, monthly availability, and backup/restore evidence.
- Task workflow completion, System Usability Scale (SUS), user satisfaction, and security findings.

All product and delivery metrics are marked **Not Measured** until a working implementation generates reliable evidence.

## Retrospective Highlights

### What worked in the planning work

- A consistent product concept, roles, and primary task lifecycle across deliverables.
- A requirements baseline with traceability and acceptance criteria.
- A modular-monolith direction appropriate for an initial small-team product.
- Defined QA, code-review, debugging, and risk-management practices.
- Earlier evaluator feedback converted into specific corrective practices.

### What must improve next

- Validate requirements with real users before expanding scope.
- Replace assumptions with test, telemetry, security, recovery, and usability evidence.
- Estimate work at task level and track actual-versus-estimated effort.
- Measure delivery and quality trends without using metrics to rank individuals.
- Scale infrastructure only when a measured bottleneck justifies it.

## Future Roadmap

The report proposes five gated phases across 12 months:

1. **Months 0–2 – Validate and pilot:** User interviews, core workflow validation, MVP vertical slice, and baseline instrumentation.
2. **Months 2–4 – Security and reliability:** Owner MFA, authorization tests, audit events, backup restore drills, and notification idempotency.
3. **Months 4–6 – Performance and scale:** Endpoint profiling, indexing, pagination, selective caching, and background workers when justified by thresholds.
4. **Months 6–9 – Collaboration and integrations:** Calendar or team-chat integrations, selective real-time updates, and exports based on user demand.
5. **Months 9–12 – Insights and governance:** Project analytics, audit exports, data-retention controls, and organization features where validated.

Each phase includes owners, person-day estimates, dependencies, and evidence-based exit gates.

## Risk Management

The report includes 14 risks with likelihood and impact scoring, owners, warning triggers, mitigations, and response actions.

Priority risks include cross-workspace data exposure, task approval race conditions, unreliable notifications, data recovery failure, insufficient user validation, and overengineering.

## Document Deliverable

The complete Week 6 report is available here:

**[Download TaskFlow – Week 6 Final Project Evaluation and Future Roadmap](docs/TaskFlow_Week6_Final_Report.docx)**

## Internship Documentation Progress

| Week | Assignment | Status |
|---|---|---|
| Week 1 | Project Scoping and Software Requirements Documentation | Completed |
| Week 2 | System Architecture Design and Module Breakdown | Completed |
| Week 3 | Development Roadmap and Implementation Strategy | Completed |
| Week 4 | Comprehensive Testing Strategy and QA Plan | Completed |
| Week 5 | Code Review Process and Debugging Strategy | Completed |
| Week 6 | Final Project Evaluation, Retrospective and Future Roadmap | Completed |

## Public References

- [ISO/IEC 25010:2023 – Product Quality Model](https://www.iso.org/standard/78176.html)
- [DORA – Software Delivery Performance Metrics](https://dora.dev/guides/dora-metrics/)
- [NIST SP 800-218 – Secure Software Development Framework](https://csrc.nist.gov/pubs/sp/800/218/final)
- [OWASP Application Security Verification Standard 5.0](https://asvs.owasp.org/)
- [The Scrum Guide – Official Download](https://scrumguides.org/download.html)
- [Test Science – Validated Scales Repository (SUS)](https://testscience.org/validated-scales-repository/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

## Scope and Evidence Note

This is a documentation-based internship project. The roadmap, technical controls, workload assumptions, KPI thresholds, and case examples are proposals for a future implementation.

The report does not claim TaskFlow has been developed, deployed, load-tested, security-certified, or validated with actual users.

---

**Project:** TaskFlow  
**Organization:** Yuva Intern  
**Role:** Junior Software Developer Intern  
**Assignment:** Week 6 – Final Project Evaluation, Retrospective and Future Roadmap