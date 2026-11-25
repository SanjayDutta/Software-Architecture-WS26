# S02 – Institutional Shareholders

## 1. Description

Institutional shareholders are organizations or investment institutions that hold shares and exercise their associated voting rights through authorized representatives. Internal analysis, investment decisions and approval workflows remain outside GOSPL. The platform supports the authorized execution and traceability of externally determined voting decisions.

## 2. Stakeholder Concerns

Concerns are recorded under the stakeholder that first introduces them. The Distinct Concerns table contains original concern definitions, which may also be shared by other stakeholders. Common Concerns lists inherited references without creating duplicate IDs.

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S02-C01 | Representation & Delegation | We want to designate authorized representatives and manage the scope and validity of their voting authority. |
| S02-C02 | Voting Instruction Management | We want our internally determined voting decisions to be accurately executed by our designated representatives. |
| S02-C03 | Accountability & Traceability | We want to trace how our voting rights were exercised, by whom, when and under what authority. |
| S02-C04 | Operational Efficiency | We want to efficiently manage our representatives, voting instructions and voting activities across multiple resolutions. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| S01-C01 | Accessible Participation | Participate before and during the AGM through authorized persons. |
| S01-C02 | Voting Rights (including voting power) | Understand and exercise entitled voting rights and voting power. |
| S01-C03 | Informed Decision-Making | Access reliable, unbiased resolution information and updates. |
| S01-C04 | Voting Flexibility | Cast, revise or delegate votes within permitted conditions. |
| S01-C05 | Voting Transparency | Confirm vote recording and counting and access outcomes. |
| S01-C06 | Privacy & Security | Protect organizational voting information and personal data. |

## 3. Candidate Capabilities and Potential Solutions

All capabilities and solutions are candidates, not finalized requirements or architectural decisions.

Common capabilities from S01 are reused where applicable, including eligibility, weighted voting, resolution information (including the candidate AI assistant), vote management, confirmation and privacy.

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Institutional Identity Management | Organizational profile with associated eligible shareholdings and representatives. | S02-C01, S01-C02 | Additional or extended candidate |
| Representative & Delegation Management | Multiple representatives, scoped authority (potentially per resolution), validity periods, modification and revocation where permitted. | S02-C01, S02-C04, S01-C04 | Additional or extended candidate |
| Voting Instruction Management | Record externally approved voting instructions, assign them to representatives and verify execution against instructions. | S02-C01, S02-C02 | Additional or extended candidate |
| Voting Authority Validation | Detect conflicting authorizations, unauthorized voting and duplicate exercise of voting rights. | S02-C01, S02-C02, S01-C02 | Additional or extended candidate |
| Institutional Voting History | Representative attribution, resolution, vote, exercised voting power, timestamp, applicable authorization and access-controlled exportable records. | S02-C03, S01-C05, S01-C06 | Additional or extended candidate |
| Institutional Voting Dashboard | Overview of resolutions, representatives, instructions and voting status. | S02-C02, S02-C03, S02-C04 | Additional or extended candidate |
| Efficient Voting Operations | Bulk voting, bulk instruction assignment and split voting where permitted. | S02-C02, S02-C04, S01-C02 | Additional or extended candidate |

## 4. Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Advanced Functionality vs. Simplicity (SC04) | S01 – Individual Shareholders | Sophisticated tools for managing organizational voting activities. | Simple and intuitive voting experience. | Keep individual voting workflows simple while supporting institutional needs. |

## 5. Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | Primary stakeholder |
| Importance | High |
| Influence | High (provisional) |
| Justification | Primary users with distinctive organizational voting needs and potentially substantial voting power and influence on product needs; actual project influence is not established. |
| Validation Status | Assumed – pending validation |

## 6. Extra Information

### Scope and Quality Considerations

Operational efficiency is a cross-cutting quality concern; measurable criteria will be derived later. Recording voting instructions does not imply managing internal approval workflows. Institutional-specific extensions overlap with common concerns but capture additional organizational needs.

### Evidence and Validation Status

- Source: Team discussion and initial GOSPL product vision.
- The four distinctive concerns and boundary placing internal decision-making outside GOSPL are agreed working proposals, not validated statements from actual Kesko stakeholders.
- Conflicts, prioritization and solution candidates are preliminary.
- Validate representation, resolution-specific authority, delegation changes, split voting, instruction handling and record access against Kesko documentation and applicable legal rules under Task 3.
- Evaluate candidate features for necessity, feasibility and privacy before committing to implementation.
- Formal functional and non-functional requirements will be derived later.
