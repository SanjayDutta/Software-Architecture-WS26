# S09 – Product Owners

---

## Description

Product Owners are individuals responsible for defining the product vision, managing product scope, prioritizing requirements and ensuring that the product delivers value to its intended stakeholders.

In the context of GOSPL, Product Owners are concerned with delivering a usable, reliable and trustworthy shareholder voting platform that addresses stakeholder needs within established business, regulatory and resource constraints.

## Stakeholder Concerns

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S09-C01 | Product Value & Scope | We want GOSPL to deliver meaningful stakeholder value by addressing prioritized stakeholder needs within established business and resource constraints. |
| S09-C02 | Product Quality & Sustainability | We want GOSPL to meet stakeholder quality expectations while remaining economically and operationally sustainable. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| S01-C01 | Accessible Participation | Ensure the product is accessible to its intended users. |
| S01-C05 | Voting Transparency | Establish stakeholder trust through transparent voting confirmations and outcomes. |
| S01-C06 | Privacy & Security | Protect stakeholder information and maintain product trustworthiness. |
| S02-C04 | Operational Efficiency | Ensure the product improves the efficiency of shareholder voting activities. |
| S06-C02 | Voting Rule Compliance | Ensure the product supports established voting conditions. |
| S07-C01 | Voting Integrity & Accuracy | Support accurate voting records and trustworthy voting outcomes. |

## Candidate Capabilities and Potential Solutions

Product Owners are not necessarily direct users of GOSPL. No dedicated application capabilities have been identified for this stakeholder. The following are requirements and development implications rather than proposed GOSPL features or architectural components.

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Product Vision Alignment (development activity) | Align requirements with stakeholder goals and the product vision. | S09-C01 | Proposed; not an application capability |
| Requirements Prioritization & Scope Management (development activity) | Prioritize requirements according to stakeholder value, necessity and available resources. | S09-C01 | Proposed; not an application capability |
| Quality Requirements & Acceptance Criteria (development activity) | Establish measurable quality requirements and acceptance criteria and verify them against stakeholder expectations. | S09-C02 | Proposed; not an application capability |
| Product Sustainability (quality and resource considerations) | Consider maintainability, adaptability and reasonable development and operational costs. | S09-C02 | Proposed; not an application capability |

## Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Business Priorities vs. Technical Sustainability | S10 – Developers | Deliver valuable product functionality within established time, budget and resource constraints. | Ensure sufficient technical quality, maintainability, testability and long-term sustainability. | Balance business priorities, delivery timelines and costs with software quality and technical sustainability without compromising essential voting accuracy, security or compliance requirements. |

This potential conflict may arise in decisions concerning feature prioritization, delivery timelines, technical debt, testing effort and operational costs. It does not imply that Product Owners and Developers have inherently opposing objectives.

## Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | Product & Development Stakeholder |
| Importance | High |
| Influence | High |
| Justification | Product Owners influence the product vision, scope, requirements prioritization and acceptance criteria. |
| Validation Status | Assumed – pending validation |

## Extra Information

### Alignment with the Product Vision

Product Owners should ensure that requirements remain aligned with the three fundamental objectives of GOSPL:

- **Ease:** Accessible and efficient shareholder participation.
- **Accuracy:** Correct recording, processing and verification of votes.
- **Validity:** Authorized exercise of voting entitlements within established conditions, without claiming independent legal certification.

AI-assisted resolution explanations should be considered for their potential contribution to informed shareholder participation, rather than for the sake of introducing a particular technology. Any implementation must respect applicable project constraints, including the prohibition on sending personal information to OpenRouter.

### Relationship with Developers

| Product Owners | Developers |
|---|---|
| Define what should be built and why it is valuable. | Assess how requirements can be technically realized. |
| Prioritize stakeholder needs and product scope. | Assess technical feasibility, effort and risks. |
| Establish expected quality outcomes and acceptance criteria collaboratively. | Design, implement and verify solutions against those outcomes. |
| Assess whether the product meets stakeholder needs. | Assess whether the product is correctly implemented and maintainable. |

### Scope Boundaries

Product ownership activities influence GOSPL requirements but are not themselves shareholder voting functionality. A Product Owner dashboard, backlog management module or dedicated Product Owner profile is not assumed. Product Owners are not granted authority to determine legal voting rights, modify shareholder votes or formally certify voting results by virtue of their product role.

### Validation Notes

- Product Owners and Developers are conceptual roles in the course project; they are not actual representatives of Kesko. The project team may fulfil both roles.
- Stakeholder prioritization and specific product ownership responsibilities remain assumptions pending validation.
- No particular architecture, technology, budget, quality threshold or commercial operating model is established by this analysis.
- Course instructors are not retained as a separate active stakeholder group; applicable assignment constraints and instructor expectations should be documented under Task 3 – Other Requirements Sources.
