# Chapter 3 — Managing Systems Projects (Final Draft)

> **Format notes (from you):**
>
> * Markdown, with a **navigation panel** and deep links
> * **SDLC Phase Tracker** at the top of each major section
> * **Timeline Log** (typical real-world time)
> * **Cross-Reference Map** links
> * **Deliverable Checklist** and **Common Pitfalls** at the end of each section
> * **Learning Objectives Tracker** with links and mini-summaries
> * **Key Term Lifecycle Map** at the end
> * Include **review questions** blocks

---

## Navigation Panel

* [Chapter Introduction](#chapter-introduction)
* [3.1 Project Management](#31-project-management)

  * [3.1.1 What Shapes a Project?](#311-what-shapes-a-project)
  * [3.1.2 Project Triangle](#312-project-triangle)
  * [3.1.3 What Does a Project Manager Do?](#313-what-does-a-project-manager-do)
* [3.2 Task Management](#32-task-management)

  * [3.2.1 Work Breakdown Structure (WBS)](#321-work-breakdown-structure-wbs)
  * [3.2.2 Task Patterns](#322-task-patterns)
  * [3.2.3 The Critical Path](#323-the-critical-path)
* [3.3 People Management](#33-people-management)

  * [3.3.1 Human Element](#331-understanding-the-human-element)
  * [3.3.2 Team Dynamics & Collaboration](#332-team-dynamics--collaboration)
  * [3.3.3 Nurturing Growth](#333-nurturing-growth)
  * [3.3.4 Dealing with Change](#334-dealing-with-change)
  * [3.3.5 Trust](#335-the-role-of-trust)
* [3.4 Communications Management](#34-communications-management)

  * [3.4.1 Requirements Miscommunication](#341-miscommunication-of-requirements)
  * [3.4.2 Project Updates & Reporting](#342-lack-of-regular-project-updates)
  * [3.4.3 Change Communication](#343-ineffective-change-communication)
  * [3.4.4 Cultural & Language Barriers](#344-cultural-and-language-barriers)
  * [3.4.5 Dealing with Problems (Escalation)](#345-dealing-with-problems)
* [3.5 Technology Management](#35-technology-management)

  * [3.5.1 Selection](#351-technology-selection)
  * [3.5.2 Implementation](#352-technology-implementation)
  * [3.5.3 Review](#353-technology-review)
* [3.7 Risk Management](#37-risk-management)

  * [3.7.1 Importance](#371-the-importance-of-risk-management)
  * [3.7.2 Origins of Risks](#372-the-origin-of-risks)
  * [3.7.3 Risk Tasks](#373-risk-management-tasks)
  * [3.7.4 Risk Management Plan](#374-the-risk-management-plan)
  * [3.7.5 Risk Management Issues](#375-risk-managrmrnt-issues)
* [3.8 Project Management Software](#38-project-management-software)

  * [3.8.1 Areas of Support](#381-aread-of-support)
  * [3.8.2 Examples](#382-examples-of-project-management-software)
  * [3.8.3 Using PM Software](#383-using-project-management-software)
* [3.9 Managing for Success](#39-managing-success)

  * [3.9.1 Monitoring & Control](#391-project-monitoring-and-control)
  * [3.9.2 Issue Resolution](#392-issue-resolution)
  * [3.9.3 Agile Mindset](#393-adopting-an-agile-mindset)
* [Figures & Tables Navigation](#figures--tables-navigation)
* [Learning Objectives Tracker](#learning-objectives-tracker)
* [Key Terms](#key-terms) & [Key Term Lifecycle Map](#key-term-lifecycle-map)
* [Chapter Summary](#chapter-summary)
* [Review Questions](#review-questions)
* [Discussion Topics](#discussion-topics)
* [Hands-On Projects](#hands-on-projects)
* [Ethical Issues](#ethical-issues)

---

## SDLC Timeline Log (typical real-world ranges)

| Phase                       | Typical Span* | Notes                                |
| --------------------------- | ------------: | ------------------------------------ |
| Preliminary Investigation   |     1–2 weeks | Problem framing, feasibility signal. |
| Analysis                    |     2–6 weeks | Requirements, process study.         |
| **Planning (this chapter)** | **2–4 weeks** | Project plan, people, risk, tools.   |
| Design                      |    4–12 weeks | Logical → physical design.           |
| Implementation              |   8–24+ weeks | Build, test, deploy.                 |
| Support                     |       Ongoing | Ops, fixes, enhancements.            |

*Rough ranges for a medium complexity IS project.

---

# Chapter Introduction

**Goal:** Manage systems projects so they deliver **on time, within budget, and to required quality**. This chapter covers project management basics (planning, scheduling, monitoring, reporting), **task management** (WBS → patterns → critical path), **people & communications**, **technology**, **risk**, **software tools**, and **managing for success**.

---

## 3.1 Project Management

**SDLC Phase Tracker:** Preliminary Investigation → Analysis → **[Planning]** → Design → Implementation → Support

Project management for IT means **planning**, **scheduling**, **monitoring & controlling**, and **reporting** the work that builds an information system.

### 3.1.1 What Shapes a Project?

* Success requires: **time**, **budget**, **quality/fit to requirements**.
* Formal project management can start as early as **preliminary investigation** and continues through analysis, design, and implementation.
* Constraints interact (cost, scope, time).

**Deliverables:** Project charter, scope statement, high-level schedule, stakeholder list.

**Common Pitfalls:** Undefined scope; assumptions not recorded; no baseline schedule.

---

### 3.1.2 Project Triangle

* Trade-off between **Cost**, **Scope**, and **Time**. Changing one affects the other two.
* Practical moves when slipping: **trim features**, **increase budget**, **add staff** (careful; see [3.9.2](#392-issue-resolution))—or a combination.

**Cross-Refs:** See **Critical Path** ([3.2.3](#323-the-critical-path)) and **Issue Resolution** ([3.9.2](#392-issue-resolution)).

**Deliverables:** Prioritized scope, constraint declarations (which side is fixed).

**Common Pitfalls:** Pretending all three are fixed; silent constraint changes.

---

### 3.1.3 What Does a Project Manager Do?

* **Plan:** identify tasks; estimate time/cost.
* **Schedule:** build timetable (Gantt, PERT/CPM); staff and assign.
* **Monitor & Control:** track progress, manage risks, correct course.
* **Report:** communicate status to management, users, team.
* Focus attention on **critical path tasks**.

**Deliverables:** WBS, schedule, communications plan, status reports.

**Common Pitfalls:** Tracking everything equally; weak status communication.

---

## 3.2 Task Management

**SDLC Phase Tracker:** Preliminary Investigation → Analysis → **[Planning]** → Design → Implementation → Support

**Three activities:** **WBS**, **Task Patterns (dependencies)**, and **Critical Path**.

### 3.2.1 Work Breakdown Structure (WBS)

* WBS = list of **manageable tasks** with durations and predecessors.
* **Gantt** gives calendar view; useful for status.
* **PERT/CPM** shows the logic network; useful for sequencing and CP calc.
* **Events/Milestones** are **0-duration checkpoints**.

**Deliverables:** Numbered task list (ID, name, duration, predecessors), milestone list.

**Common Pitfalls:** Tasks too big or too tiny; missing predecessors; vague milestones.

---

### 3.2.2 Task Patterns

* **Dependent tasks (FS)**: one must finish before the next starts.
* **Multiple successors**: one predecessor fans out to several tasks.
* **Multiple predecessors**: a task starts only when **all** inputs finish (start controlled by the **latest** finish).
* Use consistent time units; inclusive day counting (5-day task starting Day 10 finishes **Day 14**; next task may start **Day 15**).

**Deliverables:** Network diagram with FS/SS/FF (and lags/leads if used).

**Common Pitfalls:** Orphan tasks; ambiguous wording; ignoring merges.

---

### 3.2.3 The Critical Path

* **Critical Path = longest dependent chain** from start to finish. Tasks on it have **zero slack**; delays push the project end.
* Compute via forward pass (ES/EF) and backward pass (LS/LF); **Slack = LS−ES**.
* Example result (Fig. 3-17): CP = **1–2–4–5**; task 3 had **20 days** slack.

**Deliverables:** CP listing, slack report, protected buffer.

**Common Pitfalls:** Recomputing too rarely; focusing on noncritical delays.

---

## 3.3 People Management

**SDLC Phase Tracker:** Preliminary Investigation → Analysis → **[Planning]** → Design → Implementation → Support

### 3.3.1 Understanding the Human Element

Translate between users and technology; gather goals/constraints; communicate in plain language.

**Deliverables:** Stakeholder map, personas/user stories, acceptance criteria.

**Common Pitfalls:** Designing for the loudest stakeholder; jargon.

---

### 3.3.2 Team Dynamics & Collaboration

Set roles and decision rights (RACI); create working agreements; keep lightweight ceremonies (stand-ups, demos, retros).

**Deliverables:** Team charter, RACI, decision log.

**Common Pitfalls:** Ownership ambiguity; debates without closure.

---

### 3.3.3 Nurturing Growth

Training, code/design reviews, postmortems; safe stretch assignments.

**Deliverables:** Learning plan, review cadence.

**Common Pitfalls:** No feedback loops; skill gaps unmanaged.

---

### 3.3.4 Dealing with Change

Explain why/what/how; change impacts; training and phased rollouts.

**Deliverables:** Change impact assessment, training plan.

**Common Pitfalls:** “Install without adoption.”

---

### 3.3.5 The Role of Trust

Built through competence, reliability, and integrity; enables early risk surfacing.

**Deliverables:** Transparent status, consistent follow-through.

**Common Pitfalls:** Optimism theater; hiding bad news.

---

## 3.4 Communications Management

**SDLC Phase Tracker:** Preliminary Investigation → Analysis → **[Planning]** → Design → Implementation → Support

**Throughline:** Build a reliable “communication grid”: clarify requirements → maintain update cadence → communicate change visibly → bridge cultural differences → escalate problems early with options.

### 3.4.1 Miscommunication of Requirements

Use **plain-language user stories with acceptance criteria**, quick **prototypes**, and a **shared glossary**; BA bridges business ↔ tech.

**Deliverables:** Story/criteria set, glossary, playback notes.

---

### 3.4.2 Lack of Regular Project Updates

Define a **cadence** (daily team, weekly status, monthly steering) and a **single source of truth** (hub). Include RAG with criteria.

**Deliverables:** Communication plan, status templates, dashboard.

---

### 3.4.3 Ineffective Change Communication

Every significant change gets a **Change Request (CR)** (what/why/impact/owner/date) and **change log** entry; update artifacts and brief for major shifts.

**Deliverables:** CR template & log; updated specs/designs/tests.

---

### 3.4.4 Cultural and Language Barriers

Plain English; visuals; rotate meeting times; async summaries; invite clarifying questions.

**Deliverables:** Working language guide; inclusive meeting norms.

---

### 3.4.5 Dealing with Problems

Define **escalation thresholds**; use a **RAID log**; “bad news early, options always.”

**Deliverables:** RAID log with owners; escalation ladder.

---

**Common Pitfalls (3.4):** Squishy requirements; channel sprawl; undocumented changes; imagined agreement; wrong-altitude escalation.

---

## 3.5 Technology Management

**SDLC Phase Tracker:** Preliminary Investigation → Analysis → **[Planning]** → Design → Implementation → Support

### 3.5.1 Technology Selection

Choose for **functionality**, **scalability**, **compatibility**, **learnability**, and **total cost**.

**Deliverables:** Tooling inventory; selection rationale.

---

### 3.5.2 Technology Implementation

Two tracks: **technical setup** (install/integrate/configure/backup/monitor) and **human adoption** (why, training, usage norms).

**Deliverables:** Implementation plan; runbooks; quick-start guides.

---

### 3.5.3 Technology Review

Maintain, observe, reassess, and communicate changes; prevent tool sludge.

**Deliverables:** Review cadence & criteria; update records.

---

**Common Pitfalls (3.5):** Shiny-object selection; “install and forget”; tool sprawl; under-communicated change; ignoring total cost.

---

## 3.7 Risk Management

**SDLC Phase Tracker:** Preliminary Investigation → Analysis → **[Planning]** → Design → Implementation → Support

### 3.7.1 The Importance of Risk Management

Reduce uncertainty, improve planning, build confidence, limit losses, enable decisions.

---

### 3.7.2 The Origin of Risks

**Technology, evolving requirements, team/process, external factors, size/complexity**; watch for **risk chains**.

---

### 3.7.3 Risk Management Tasks

**Loop:** Identify → Analyze → Respond → Monitor/Communicate → Repeat.
Artifacts: **Risk Register**, defined **scales**, **Risk Matrix/Heatmap**, **responses** (avoid/transfer/mitigate/accept) with **owners** and **triggers**.

---

### 3.7.4 The Risk Management Plan

Playbook covering context, process, monitoring/control, roles, and communication.

---

### 3.7.5 Risk Management Issues

Common failures: inadequate identification, poor assessment (no objective criteria), ineffective responses.

---

**Common Pitfalls (3.7):** Stale registers; rating by gut; no owners/triggers; mixing risks with issues; mitigations not scheduled; ignoring chains.

---

## 3.8 Project Management Software

**SDLC Phase Tracker:** Preliminary Investigation → Analysis → **[Planning]** → Design → Implementation → Support

### 3.8.1 Aread of Support

Planning/scheduling, resource mgmt, comms/collab, docs/knowledge, risk, monitoring/control, integrations.
**PPM = project portfolio management** (choose/prioritize/balance projects across the org).

---

### 3.8.2 Examples of Project Management Software

* **PM suites:** Microsoft Project; GanttProject, Gantter, Smartsheet, Apptivo.
* **monday.com:** platform; **monday work management** is its PM product.
* **Trello (Atlassian):** Kanban boards (columns/cards) tailored to agile flow.
* **Resource tools:** Resource Guru, Float, Smartsheet.
* **Task & time:** Asana, monday.com, Trello; Harvest, Toggl, TimeCamp.
* **Collab/Docs/Issues:** Teams/Slack/Google Workspace; SharePoint/Confluence; Jira/Bugzilla/GitHub Issues.

---

### 3.8.3 Using Project Management Software

Enter **WBS** → tool builds **Gantt** (respects calendars) → view **Network Diagram** for logic → **Calendar View** = tasks overlaid on real calendar days/weeks; critical path highlighted for daily priorities. Software **recalculates automatically** after changes; supports rapid replanning.

---

**Common Pitfalls (3.8):** Tool-first thinking; no baseline; resource overallocations; split truth across tools; dependency blindness in Kanban-only; notification fatigue; calendar/time-zone errors; over-automation; portfolio blindness.

---

## 3.9 Managing Success

**SDLC Phase Tracker:** Preliminary Investigation → Analysis → **[Planning]** → Design → Implementation → Support

### 3.9.1 Project Monitoring and Control

**Track → Review → Regulate**, with strong stakeholder communication and continuous risk management. Use **structured walkthroughs** (design/code/test reviews) throughout the SDLC.

---

### 3.9.2 Issue Resolution

Trade-offs: **trim scope**, **shift resources**, **move dates**, **tighten controls**.
**Brooks’s Law:** adding people late often makes it later—prefer scope slicing and targeted expertise.

---

### 3.9.3 Adopting an Agile Mindset

Short iterations, thin slices, demo/feedback, retrospectives, limited WIP, feature flags, risk-first sequencing. Agile can live inside traditional governance.

---

**Common Pitfalls (3.9):** Green-by-default reporting; tracking without acting; scope thrash; big-bang testing; heroics; dependency blindness; optimism bias; security bolted on late; frozen plan in dynamic reality.

---

## Figures & Tables Navigation

* **Fig. 3-1 / 3-2** — Project triangle (Cost/Scope/Time). See [3.1.2](#312-project-triangle).
* **Fig. 3-3 / 3-4** — Gantt vs. PERT; task details. See [3.2.1](#321-work-breakdown-structure-wbs) & [3.2.2](#322-task-patterns).
* **Fig. 3-5 / 3-6 / Tables 3-1, 3-2 / Fig. 3-7** — WBS identification → table → Project view. See [3.2.1](#321-work-breakdown-structure-wbs).
* **Figs. 3-8 to 3-15** — Task boxes; dependency patterns. See [3.2.2](#322-task-patterns).
* **Figs. 3-16 / 3-17** — Critical path example. See [3.2.3](#323-the-critical-path).
* **Risk Matrix** — Qualitative analysis. See [3.7.3](#373-risk-management-tasks).

---

## Learning Objectives Tracker

* **LO1** — Explain planning, scheduling, monitoring & controlling, reporting → **Covered in [3.1](#31-project-management)**.
  *Summary:* Defined core PM functions and artifacts; linked to WBS/Gantt/PERT and status reporting.

* **LO2** — Demonstrate the three activities of task management → **Covered in [3.2](#32-task-management)**.
  *Summary:* Built WBS; modeled dependencies; identified **critical path** and slack.

* **LO3** — Summarize the five key elements of people management → **Covered in [3.3](#33-people-management)**.
  *Summary:* Human element, collaboration, growth, change, trust.

* **LO4** — Discuss the five key issues in communications management → **Covered in [3.4](#34-communications-management)**.
  *Summary:* Requirements clarity, update cadence, change comms, culture/language, escalation.

* **LO5** — Describe the importance of technology management → **Covered in [3.5](#35-technology-management)**.
  *Summary:* Selection → implementation → review; keep toolchain secure and useful.

* **LO7** — Explain why risk management is crucial → **Covered in [3.7](#37-risk-management)**.
  *Summary:* Identify/analyze/respond/monitor with a living plan; use risk matrix & register.

* **LO8** — State key benefits of project management software → **Covered in [3.8](#38-project-management-software)**.
  *Summary:* Centralized plan/resources/risks, automated recalculation, integrations, dashboards.

* **LO9** — Describe three areas to manage for success → **Covered in [3.9](#39-managing-success)**.
  *Summary:* Monitoring & control, issue resolution trade-offs, agile mindset.

---

## Key Terms

* **Baseline** — Frozen reference plan for scope/schedule/cost to measure variance.
* **Brooks’s Law** — Adding staff to a late software project makes it later.
* **Change Request (CR)** — Formal record of a requested change with impact analysis.
* **Critical Path** — Longest required chain of tasks; zero slack.
* **Gantt Chart** — Calendar-based bar chart of tasks with dependencies.
* **Milestone** — Zero-duration checkpoint; evidence of progress.
* **PERT/CPM** — Network method for dependency modeling and CP calculation.
* **Portfolio (PPM)** — Organization-level selection/prioritization of projects.
* **RAID Log** — Risks, Assumptions, Issues, Dependencies tracker.
* **Risk Matrix** — Probability vs. Impact grid for qualitative prioritization.
* **Risk Register** — Canonical list of risks with attributes and responses.
* **Structured Walkthrough** — Peer review of artifacts (design/code/test).
* **Task Pattern** — Dependency structure (FS/SS/FF; multiple predecessors/successors).
* **WBS (Work Breakdown Structure)** — Hierarchical list of tasks with durations and predecessors.

---

## Key Term Lifecycle Map

| Term                    | Planning (Ch. 3)                                                    | Design                                    | Implementation                            | Support                         |
| ----------------------- | ------------------------------------------------------------------- | ----------------------------------------- | ----------------------------------------- | ------------------------------- |
| **WBS**                 | Created and baselined ([3.2.1](#321-work-breakdown-structure-wbs)). | Refined as design tasks elaborate.        | Updated with execution actuals.           | Archived for lessons learned.   |
| **Task Patterns**       | Modeled in network ([3.2.2](#322-task-patterns)).                   | Adds technical build/test dependencies.   | Drives daily sequencing.                  | N/A.                            |
| **Critical Path**       | Identified and protected ([3.2.3](#323-the-critical-path)).         | Recomputed if design shifts.              | Watched tightly; buffers consumed.        | N/A.                            |
| **Risk Register**       | Created and prioritized ([3.7.3](#373-risk-management-tasks)).      | Updated for design risks.                 | Promoted risks → issues as realized.      | Feeds ops risk catalog.         |
| **CR (Change Request)** | Process defined ([3.4.3](#343-ineffective-change-communication)).   | Used for design deltas.                   | Used for scope/timeline/resource changes. | Used for enhancements.          |
| **Baseline**            | Set after plan approval.                                            | Re-baselined after major approved change. | Variance tracked against it.              | Used for post-project analysis. |

---

## Chapter Summary

This chapter operationalizes **planning**: build a WBS and dependency network; find and protect the **critical path**; lead people with clarity, feedback, and trust; keep the **communication grid** healthy; choose, implement, and review technology wisely; manage **risk** with a living register and plan; leverage **software** that centralizes truth and recalculates fast; and, day-to-day, **monitor & control**, resolve issues with explicit trade-offs, and use an **agile mindset** to adapt.

---

## Review Questions

1. Why is the **critical path** the earliest possible finish date for a project, and how can slack exist off the path?
2. Give two examples each of **multiple successor** and **multiple predecessor** patterns.
3. What belongs in a **Change Request**, and why must artifacts be updated immediately after approval?
4. List five criteria for **technology selection** and give one trade-off example.
5. How do **risk identification** and **risk analysis** differ? What is an **objective rating scale**?
6. Explain **Brooks’s Law** and give a case where adding people *does* help.
7. What does **PPM** add that task or project tracking does not?
8. Describe a minimal **communications cadence** for a medium project (audiences & artifacts).

---

## Discussion Topics

* When should a team **re-baseline** a project, and what are the risks of doing it too often or too rarely?
* Debate: Kanban boards vs. Gantt/PERT for planning and control—where does each shine?
* How would you design a **risk indicator** set for an AI-heavy project?
* “Transparency builds trust”—where is the line between transparency and noise?

---

## Hands-On Projects

1. **Build a WBS & Network:** From a simple case, enumerate tasks, set durations, add predecessors; compute CP and slack.
2. **Risk Register:** Populate 12 risks, define probability/impact scales (1–5), place on a matrix, pick responses with owners.
3. **Status Toolkit:** Create a one-page status template (RAG with criteria), a decision log, and a change log; run a mock review.
4. **Tool Integration:** Configure a PM tool to sync with a dev repo; link commits/issues to tasks; demo the flow.

---

## Ethical Issues

A project manager sees schedule risk that leadership resists acknowledging. What are the ethical obligations regarding **truthful reporting**, and how do you escalate while preserving team credibility? Consider impacts on customers, employees, and compliance when delays are hidden.

---

### Deliverable Checklists (per major section)

* **3.1–3.2 (Plan & Schedule):** Charter, scope, WBS, network, baseline schedule, milestone list.
* **3.3–3.4 (People & Comms):** Team charter/RACI, comms plan, status pack templates, change process.
* **3.5 (Technology):** Tool inventory & rationale, implementation plan, runbooks.
* **3.7 (Risk):** Risk register, matrix, response plan, RAID log, risk management plan.
* **3.8 (Software):** Configured PM workspace, integrations, dashboards, permissions model.
* **3.9 (Success):** Structured review cadence, decision log, scope trim list, iteration assets.

---

**End of Chapter 3 — Final Draft**
