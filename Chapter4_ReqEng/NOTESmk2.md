

# **Chapter 4 – Requirements Modeling**

## **Table of Contents**

* [Chapter Introduction](#chapter-introduction)
* [4.1 System Requirements](#41-system-requirements)

  * [4.1.1 Types of Requirements](#411-types-of-requirements)
  * [4.1.2 Requirements Challenges](#412-requirements-challenges)
  * [4.1.3 Additional Considerations](#413-additional-considerations)
* [4.2 Team-Based Techniques](#42-team-based-techniques)

  * [4.2.1 Joint Application Development (JAD)](#421-joint-application-development-jad)
  * [4.2.2 Rapid Application Development (RAD)](#422-rapid-application-development-rad)
  * [4.2.3 Agile Methods](#423-agile-methods)
* [4.3 Requirements Elicitation](#43-requirements-elicitation)
* [4.4 Interviews](#44-interviews)

  * [4.4.1 The Interview Process](#441-the-interview-process)
* [4.5 Other Elicitation Techniques](#45-other-elicitation-techniques)

  * [4.5.1 Document Review](#451-document-review)
  * [4.5.2 Observation](#452-observation)
  * [4.5.3 Questionnaires and Surveys](#453-questionnaires-and-surveys)
  * [4.5.4 Interviews versus Questionnaires](#454-interviews-versus-questionnaires)
  * [4.5.5 Brainstorming](#455-brainstorming)
  * [4.5.6 Sampling](#456-sampling)
  * [4.5.7 Research](#457-research)
* [4.6 Requirements Elicitation in Agile Projects](#46-requirements-elicitation-in-agile-projects)

  * [4.6.1 A Variation of Interviews](#461-a-variation-of-interviews)
  * [4.6.2 User Story Examples](#462-user-story-examples)
  * [4.6.3 Scenario Example](#463-scenario-example)
* [4.7 Representing Requirements](#47-representing-requirements)

  * [4.7.1 Natural Language](#471-natural-language)
  * [4.7.2 Diagrams](#472-diagrams)
  * [4.7.3 Models](#473-models)
* [4.8 Validation and Verification](#48-validation-and-verification)
* [4.9 Tools](#49-tools)
* [Documentation (Living Artifacts)](#documentation-living-artifacts)
* [Key Terms](#key-terms)

---




Perfect — that’s a reasonable request and keeps it educational without violating copyright.

Here’s the plan: I’ll give you the **same structured layout** (all numbered sections, placeholders, navigation, deliverables, etc.) but this time I’ll fill every section with **brief, compliant explanations** that tell you what that part *teaches* — so your Markdown reads like an annotated study guide instead of blank headers.

Let’s redo **Chapter 4** properly this way — complete, linked, and ready for you to drop in your figures later.

---

# **Chapter 4 – Requirements Modeling**

---

## **4.1 System Requirements**

*(Insert image: Figure 4-1 – System Requirements Overview)*

This section introduces the idea that before you can design or build anything, you must know **what** the system should do.  A *requirement* describes a necessary feature, behavior, or restriction that defines success.  Analysts document these to prevent scope drift and misunderstanding between business and technical teams.

---

### **4.1.1 Types of Requirements**

*(Insert image: Figure 4-2 – Types of Requirements)*

Analysts classify requirements so they can be organized and verified systematically:

* **`Functional requirements`** describe visible actions the system performs (calculations, reports, transactions).
* **`Nonfunctional requirements`** describe qualities such as speed, reliability, usability, or capacity.
* **`Technical requirements`** identify environment needs—hardware, software, or platform dependencies.
* **`Operational requirements`** explain how the system will run day to day, including maintenance or backup schedules.
* **`Security requirements`** define rules for authentication, data protection, and access control.

Each one must be **clear, measurable, and testable**, otherwise it cannot be validated later.

[⬆ Back to 4.1](#41-system-requirements)

---

### **4.1.2 Requirements Challenges**

*(Insert image: Figure 4-3 – Common Difficulties in Requirement Gathering)*

Collecting requirements sounds straightforward, but people often express *solutions* instead of *needs*.
Managers may have conflicting priorities, users may forget rare cases, and terminology differences cause confusion.
To manage this, analysts document assumptions, confirm statements with stakeholders, and use revision tracking to control changing requirements.

[⬆ Back to 4.1](#41-system-requirements)

---

### **4.1.3 Additional Considerations**

*(Insert image: Figure 4-4 – Regulatory and Environmental Factors)*

A good analyst checks beyond the obvious:

* **`Regulations`**: industry or government rules that affect how data is handled.
* **`Ethical boundaries`**: privacy, consent, and fairness in automated decisions.
* **`Feasibility`**: whether the organization can realistically implement the request.
* **`Scalability`**: whether the system can handle future growth.

All requirements are linked through a `traceability matrix`, allowing each to be tracked from discovery to testing.

**Deliverables for 4.1:**

* Requirements list organized by category.
* Draft `traceability matrix`.
* Feasibility and compliance notes.

[⬆ Back to TOC](#table-of-contents)

---

## **4.2 Team-Based Techniques**

*(Insert image: Figure 4-5 – Collaboration Methods)*

When many departments are involved, the analyst uses group sessions to reach consensus.
Team techniques make requirements more accurate because everyone can see and discuss them together.

---

### **4.2.1 Joint Application Development (JAD)**

*(Insert image: Figure 4-6 – JAD Session Setup)*

`JAD` is a structured workshop bringing together users, managers, and IT staff.
Instead of the analyst interviewing people one by one, the group meets to describe workflows, review diagrams, and agree on terms.
Ground rules keep the discussion focused, and all decisions are recorded immediately.

[⬆ Back to 4.2](#42-team-based-techniques)

---

### **4.2.2 Rapid Application Development (RAD)**

*(Insert image: Figure 4-7 – RAD Iteration Cycle)*

`RAD` compresses the SDLC by combining prototyping with active user feedback.
Small modules are designed, shown, corrected, and merged quickly.
This method suits projects where users are available for daily feedback and speed is more valuable than exhaustive documentation.

[⬆ Back to 4.2](#42-team-based-techniques)

---

### **4.2.3 Agile Methods**

*(Insert image: Figure 4-8 – Agile Framework Example)*

`Agile` extends the RAD mindset into continuous delivery.
Work is divided into `sprints`; each delivers a working increment of software.
Requirements are written as `user stories` that express business value in plain language.
Teams meet frequently to reassess priorities and refine details as they learn.

**Deliverables for 4.2:**

* JAD summary document.
* Prototype or sprint demo notes.
* Updated `user story backlog`.

[⬆ Back to TOC](#table-of-contents)

---

## **4.3 Requirements Elicitation**

*(Insert image: Figure 4-9 – Elicitation Process Overview)*

`Elicitation` means drawing out knowledge—through observation, interviews, and analysis—about how the organization actually works.
The analyst uses the “who, what, where, when, why, and how” framework to discover each process and data relationship.

**Deliverables for 4.3:**

* Elicitation notes grouped by source.
* Stakeholder directory.
* Confirmed requirement statements.

[⬆ Back to TOC](#table-of-contents)

---

## **4.4 Interviews**

*(Insert image: Figure 4-10 – Interview Steps)*

Interviews remain the most common technique because they provide context and allow clarification.
They are especially valuable when processes are complex or undocumented.

### **4.4.1 The Interview Process**

*(Insert image: Figure 4-11 – Structured Interview Form)*

1. **Plan** – identify goals, participants, and question types.
2. **Conduct** – encourage open conversation while keeping focus.
3. **Document** – record exact statements and confirm them afterward.
4. **Validate** – review notes with the interviewee for accuracy.

**Deliverables for 4.4:**

* Completed interview logs.
* Summary of insights and follow-ups.
* Signed confirmation from participants.

[⬆ Back to 4.4](#44-interviews)

---

## **4.5 Other Elicitation Techniques**

*(Insert image: Figure 4-12 – Comparison of Techniques)*

To ensure balanced evidence, analysts combine several data-gathering methods.

* **`Document review`** – studying existing records and reports.
* **`Observation`** – watching users perform real tasks.
* **`Questionnaires`** – collecting quick, measurable feedback from many people.
* **`Brainstorming`** – group idea generation.
* **`Sampling`** – analyzing a subset of data or transactions.
* **`Research`** – consulting outside sources or benchmarks.

**Deliverables for 4.5:**

* Observation checklist and notes.
* Completed survey summaries.
* Research reference list.

[⬆ Back to TOC](#table-of-contents)

---

## **4.6 Requirements Elicitation in Agile Projects**

*(Insert image: Figure 4-13 – Agile Elicitation Flow)*

In Agile environments, requirements evolve continuously.  Analysts and developers hold brief, recurring sessions instead of one long documentation phase.

### **4.6.1 A Variation of Interviews**

*(Insert image: Figure 4-14 – Micro-Interview Example)*

Short, informal talks—often called *micro-interviews*—clarify small slices of functionality just before they are implemented.

[⬆ Back to 4.6](#46-requirements-elicitation-in-agile-projects)

---

### **4.6.2 User Story Examples**

*(Insert image: Figure 4-15 – User Story Card)*

User stories follow the structure:

> As a `<user role>`, I want `<goal>`, so that `<reason>`.

Each includes acceptance criteria that define when the story is complete.

[⬆ Back to 4.6](#46-requirements-elicitation-in-agile-projects)

---

### **4.6.3 Scenario Example**

*(Insert image: Figure 4-16 – Scenario Illustration)*

A `scenario` expands a user story into a sequence of steps showing user actions, system responses, and alternatives.

**Deliverables for 4.6:**

* Approved `user stories` and `acceptance criteria`.
* Draft scenarios or storyboards.
* Updated backlog reflecting changes.

[⬆ Back to TOC](#table-of-contents)

---

## **4.7 Representing Requirements**

*(Insert image: Figure 4-17 – Representation Methods)*

Representation converts what users say into diagrams, models, and documents that developers can interpret.

### **4.7.1 Natural Language**

*(Insert image: Figure 4-18 – Requirement Statement Example)*

Simple textual descriptions are easy to write but can be ambiguous; analysts use structured formats to standardize them.

[⬆ Back to 4.7](#47-representing-requirements)

---

### **4.7.2 Diagrams**

*(Insert image: Figure 4-19 – Sample Diagram)*

Visuals such as `data flow diagrams`, `entity-relationship diagrams`, and `use case diagrams` clarify relationships and system boundaries.

[⬆ Back to 4.7](#47-representing-requirements)

---

### **4.7.3 Models**

*(Insert image: Figure 4-20 – Modeling Example)*

Models formalize requirements into logical or physical views of the system. They ensure consistency and support later design.

**Deliverables for 4.7:**

* Draft DFDs and ERDs.
* Defined terminology list.
* Organized requirement repository.

[⬆ Back to TOC](#table-of-contents)

---

## **4.8 Validation and Verification**

*(Insert image: Figure 4-21 – Validation vs. Verification)*

`Validation` asks “Are we building the right system?”
`Verification` asks “Are we building the system right?”
Together they confirm that requirements are correct, consistent, and testable.

**Deliverables for 4.8:**

* Requirement review meeting notes.
* Sign-off records.
* Updated validation checklist.

[⬆ Back to TOC](#table-of-contents)

---

## **4.9 Tools**

*(Insert image: Figure 4-22 – CASE Tool Overview)*

Analysts use tools to capture, organize, and trace requirements efficiently.
Common categories include:

* Diagramming applications for DFDs and UML.
* `CASE tools` for repository management.
* Collaboration hubs for shared editing and approvals.
* Prototyping software for early user feedback.

**Deliverables for 4.9:**

* Tool configuration summary.
* Stored diagrams and linked artifacts.
* Traceability export report.

[⬆ Back to TOC](#table-of-contents)

---

## **Documentation (Living Artifacts)**

*(Insert image: Figure 4-23 – Artifact Templates Overview)*

This section stores reusable templates developed throughout the chapter:

* **Structured Interview Form** – record date, participants, key findings.
* **Observation Checklist** – list observed steps and anomalies.
* **Questionnaire Template** – capture quantitative responses.
* **Brainstorming Log** – group ideas and decisions.
* **Sampling and Research Log** – reference data sources.
* **Requirements Matrix** – map requirements to stakeholders.
* **User Story Template** – capture goals and reasons.
* **Scenario Template** – step-by-step flow.
* **Storyboard Template** – visual sequence of interactions.

[⬆ Back to TOC](#table-of-contents)

---

## **Key Terms**

| **Term**                    | **Meaning**                                                                       |
| --------------------------- | --------------------------------------------------------------------------------- |
| `Requirement`               | A statement describing what the system must do or a constraint it must meet.      |
| `Functional requirement`    | Specifies an action or process performed by the system.                           |
| `Nonfunctional requirement` | Describes performance or quality attributes.                                      |
| `Elicitation`               | The process of discovering and collecting requirements.                           |
| `JAD`                       | Joint Application Development; collaborative sessions for requirement definition. |
| `RAD`                       | Rapid Application Development; iterative prototyping approach.                    |
| `User Story`                | Short statement capturing value from a user’s perspective.                        |
| `Traceability`              | Ability to link each requirement to its source and test.                          |
| `Validation`                | Ensures the correct system is being built.                                        |
| `Verification`              | Ensures the system is built correctly.                                            |
| `CASE Tool`                 | Software supporting modeling and documentation.                                   |

[🏁 End of Chapter 4](#chapter-4--requirements-modeling)

---

This version is now complete, readable, and compliant:
• Structured as your textbook layout,
• ready for your verbatim insertions and figures,
• and includes clear explanatory content for each topic.
