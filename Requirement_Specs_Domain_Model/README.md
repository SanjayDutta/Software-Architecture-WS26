# Universität Stuttgart – SQA
## SA Project Sheet 2
**DL for requirements specification deliverable:** 11.12.2026 EOD  
**Course:** Software Architecture Lab (WS 2026/27)

---

### Task 1: Plan Your AI Use
Unlike in earlier terms, there is no simulated customer in this project. The project is your own idea, so your team owns the requirements and decides what the system should do. For requirements engineering, you can use your AI tools directly through your team's OpenRouter access (e.g. with OpenCode), following the rules in Sheet 1, Task 1.

Before you start, go back to the review by Schmid et al.[^1] (Sheet 1, Task 3). Use it to decide for each of the following tasks whether it makes sense to use AI and, if so, which model to use.

> **Note:** Do not send personal data to OpenRouter, for example from conversations with stakeholders. See Sheet 1, Task 1.

---

### Task 2: Identify and Analyze Stakeholders
Identify all relevant stakeholders of the system. Prioritize the stakeholders according to their importance and influence on the project. For each stakeholder, identify their main concerns and potential conflicts with the concerns of other stakeholders.

* **Deliverable:** A stakeholder table containing descriptions and concerns, and a stakeholder matrix illustrating their importance and influence.

---

### Task 3: Identify Other Requirements Sources
Identify other potential sources of requirements beyond the stakeholders, such as existing systems, regulations, standards, and domain documentation.

* **Deliverable:** A table listing the identified requirements sources, their descriptions, and their relevance to the system.

---

### Task 4: Develop the Domain Model
Develop a conceptual domain model of the system under study. Identify the relevant domain concepts, their attributes, relationships, and constraints. Use consistent terminology throughout the requirements specification.

* **Deliverable:** A UML conceptual class diagram and a short glossary defining the main domain concepts.
* **Derive from:** Domain knowledge, stakeholder concerns, existing systems, and other requirements sources.
* **Revise when:** New use cases introduce domain concepts, requirements reveal business rules, or inconsistencies are discovered.

---

### Task 5: Derive the Goal Model
Identify the goals of your system, starting from the problem and expected benefits described in your PIBA. Develop a goal model using the graphical notation presented in the lecture. You may use PiStar[^2] or another suitable modeling tool.

* **Deliverable:** A goal model with appropriate AND/OR refinements and, where applicable, quality goals and contribution relationships.
* **Derive from:** The PIBA, stakeholder concerns, domain knowledge, and other requirements sources.
* **Revise when:** Requirements introduce functionality without clear justification, conflicting goals emerge, or stakeholder priorities change.

---

### Task 6: Develop the Use Case Model
Construct a UML use case diagram illustrating how actors interact with the system to achieve their goals. Identify the main use cases and provide detailed textual specifications for three of them. Include the main success scenario and relevant alternative or exception flows.

* **Deliverable:** A UML use case diagram and textual specifications of three main use cases, including preconditions, postconditions, main flows, and alternative flows.
* **Derive from:** Stakeholder goals, domain knowledge, and the agreed system boundary.
* **Revise when:** Functional requirements reveal missing interactions, alternative scenarios, or inconsistent preconditions.

---

### Task 7: Derive Functional Requirements
Derive functional requirements from the identified goals, use cases, and relevant business rules. Specify the requirements according to IEEE Std. 830-1998 or the Volere Template. Ensure that each requirement is clear, unambiguous, and verifiable.

* **Deliverable:** A numbered list of functional requirements, each with a unique identifier and references to relevant goals or use cases.
* **Derive from:** Use case scenarios, alternative flows, business rules, and operational goals.
* **Revise when:** Use cases or domain rules change, requirements cannot be verified, or inconsistencies are discovered.

---

### Task 8: Derive Non-Functional Requirements
Examine the quality model described in ISO/IEC 25010. As a team, identify and justify the quality characteristics most relevant to your project. Specify the corresponding non-functional requirements according to IEEE Std. 830-1998 or the Volere Template. Where possible, formulate measurable acceptance criteria.

* **Deliverable:** A numbered list of non-functional requirements, each with a unique identifier, measurable criterion, operating context, and verification approach.
* **Derive from:** Quality goals, stakeholder concerns, applicable constraints, and important use case scenarios.
* **Revise when:** Functional scope, workload assumptions, stakeholder priorities, or feasibility constraints change.

---

### Task 9: Verify and Validate the Requirements
Review the requirements and models for completeness, consistency, correctness, and verifiability. AI-generated content may contain errors or hallucinations and must be verified against reliable sources. Where possible, consult real representatives of the identified stakeholders to validate whether the goals, scenarios, and requirements reflect their actual needs. Explicitly distinguish validated information from assumptions.

* **Deliverable:** A verification and validation report documenting the performed checks, consulted sources, identified issues, validation results, and remaining assumptions.
* **Revise when:** Validation reveals incorrect assumptions, missing requirements, conflicting expectations, or inconsistencies between artifacts.

---

### Task 10: Iterate and Synchronize the Artifacts
Requirements Engineering is an iterative process. Revisit and refine the artifacts as your understanding of the problem and system evolves. Ensure consistency between the stakeholder concerns, domain model, goal model, use cases, and functional and non-functional requirements. Maintain traceability between related artifacts. Your team should be able to explain and justify every requirement, regardless of whether AI was used to formulate it.

* **Deliverable:** A traceability table linking goals, use cases, and functional and non-functional requirements, together with a short summary of important revisions and resolved inconsistencies.
* **Revise when:** Any artifact changes in a way that affects related goals, concepts, scenarios, or requirements.

---

### Task 11: Organize and Submit the Deliverables
Organize all deliverables in a clearly structured project folder. Use meaningful filenames, consistent identifiers, and a common terminology across all artifacts. The requirements specification must follow IEEE Std. 830-1998 or the Volere Template and include the relevant models and requirements developed in the previous tasks.

Use the following folder structure:

#### Deliverable Folder Structure
```text
requirements/
├── README.md
├── requirements-specification.pdf
├── stakeholders/
│   ├── stakeholder-table.md
│   └── stakeholder-matrix.pdf
├── sources/
│   └── requirements-sources.md
├── models/
│   ├── domain-model.md
│   ├── goal-model.md
│   └── use-case-diagram.md
├── use-cases/
│   ├── use-case-specification-1.md
│   └── use-case-specification-2.md
├── requirements/
│   ├── functional.md
│   └── non-functional.md
├── validation/
│   └── verification-validation-report.md
├── traceability/
│   └── traceability-matrix.md
└── ai-usage/
    └── ai-usage-statement.md
```

#### Folder Contents
* **`README.md`:** Brief project overview, folder descriptions, and instructions for navigating the deliverables.
* **`requirements-specification.pdf`:** Consolidated requirements specification containing the relevant results of the previous tasks.
* **`stakeholders/`:** Stakeholder descriptions, concerns, prioritization, and stakeholder matrix.
* **`sources/`:** Identified requirements sources and their relevance.
* **`models/`:** Domain model, goal model, and use case diagram.
* **`use-cases/`:** Detailed textual use case specifications.
* **`requirements/`:** Functional and non-functional requirements with unique identifiers.
* **`validation/`:** Verification and validation activities, findings, and remaining assumptions.
* **`traceability/`:** Relationships between goals, use cases, and requirements.
* **`ai-usage/`:** AI usage statement identifying the tools and models used, their purposes, and how their outputs were verified (see Sheet 1, Task 1).

#### Final Deliverable & Submission
* **Deliverable:** A complete project folder following the specified structure, including the consolidated requirements specification as a PDF. Individual artifacts must be consistent with the consolidated specification. Where applicable, include the editable source files of diagrams and models alongside their exported PDF versions.
* **Submission:** Submit the project folder as a ZIP archive in ILIAS by **11.12.2026, end of day**.

---

[^1]: https://arxiv.org/abs/2505.16697
[^2]: https://www.cin.ufpe.br/~jhcp/pistar/