diff --git a/docs/README.md b/docs/README.md
new file mode 100644
--- /dev/null
+++ b/docs/README.md
@@ -0,0 +1,23 @@
+# OctoAcme Project Management — Overview
+  
+OctoAcme runs work through a structured, iterative lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation captures the problem, stakeholders, success metrics, and a go/no‑go decision using a lightweight Project One‑pager. Planning turns approved initiatives into a prioritized, estimated backlog, defines a Definition of Done, and maps releases and milestones. Execution is timeboxed into sprints/iterations and tracked on a standard project board (Backlog → Ready → In Progress → In Review → QA → Done). Releases follow pre‑release checks, staged verification, rollback plans, and post‑deploy validation.
+
+Work is organized via documented workflows and artifacts: backlog items with acceptance criteria and owners, a Risk Register to track issues and mitigations, small pull requests with CI checks and mandatory reviews, and release notes and checklists. The repo serves as the single source of truth — project charters, release plans, and retrospective actions are kept in docs/ so they remain discoverable and versioned.
+
+Roles and responsibilities are explicit to reduce ambiguity: Product Managers set outcomes and prioritize the roadmap; Project Managers coordinate schedules, risks, and stakeholder communications; Developers deliver code, tests, and documentation; QA validates against acceptance criteria; and Stakeholders provide approvals and input. Personas, templates, and checklists are available in the docs/ folder to speed onboarding and keep handoffs consistent.
+
+Communication and quality assurance are baked into the cadence: daily standups and delivery syncs, weekly PM+PdM alignment, and monthly stakeholder updates; CI test suites and security scans; unit, integration, and E2E smoke tests for critical flows; blameless retrospectives to convert learnings into tracked action items. Together these practices support repeatable delivery, reduce single-person risks, and enable continuous improvement.
+
