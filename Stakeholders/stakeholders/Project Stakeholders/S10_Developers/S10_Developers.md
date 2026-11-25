# S10 – Developers

---

## Description

Developers are individuals responsible for designing, implementing, testing and maintaining GOSPL according to established functional requirements, quality requirements and technical constraints. Their primary interests are technical feasibility, correctness, maintainability and long-term evolution of the platform. They are not necessarily direct users of GOSPL.

## Stakeholder Concerns

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S10-C01 | Requirements Clarity & Feasibility | We want clear, consistent, verifiable and technically feasible requirements that can be implemented within established resource constraints. |
| S10-C02 | Software Quality & Technical Sustainability | We want to develop a reliable, secure, testable and maintainable platform that can be efficiently understood, operated, diagnosed, modified and extended throughout its lifecycle. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| S01-C06 | Privacy & Security | Implement appropriate protection of shareholder information and voting activities. |
| S02-C03 | Accountability & Traceability | Support traceability of relevant system activities and technical events. |
| S06-C02 | Voting Rule Compliance | Correctly implement established voting conditions without independently interpreting legal requirements. |
| S07-C01 | Voting Integrity & Accuracy | Ensure voting functionality correctly records and processes votes and supports verification. |
| S08-C01 | Shareholder Information Exchange | Ensure reliable and secure processing of externally supplied shareholder information. |
| S09-C01 | Product Value & Scope | Implement prioritized functionality aligned with the product vision and available resources. |
| S09-C02 | Product Quality & Sustainability | Ensure technical decisions support product quality and long-term sustainability. |

## Candidate Capabilities and Potential Solutions

These entries represent development, quality and technical considerations rather than dedicated end-user functionality. They are candidates for subsequent requirements and architecture work.

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Requirements Management | Maintain clear, consistent, prioritized and traceable requirements with verifiable acceptance criteria. | S10-C01 | Development consideration |
| Software Maintainability | Support understandable, modifiable and extensible software with appropriate technical documentation. | S10-C02 | Quality consideration |
| Software Testability | Enable efficient verification of functional correctness and quality requirements. | S10-C02, S07-C01 | Quality consideration |
| Technical Monitoring & Diagnostics | Provide sufficient technical information to identify and investigate system failures while protecting sensitive information. | S10-C02, S02-C03, S01-C06 | Technical candidate |
| Failure Handling & Recovery | Support appropriate recovery from technical failures while preserving voting record integrity. | S10-C02, S07-C01 | Technical candidate |
| Secure Development & Maintenance | Support secure implementation, maintenance and vulnerability management. | S10-C02, S01-C06 | Development consideration |

## Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Business Priorities vs. Technical Sustainability | S09 – Product Owners | Ensure sufficient technical quality, maintainability, testability and long-term sustainability. | Deliver valuable functionality within established time, budget and resource constraints. | Balance delivery priorities and costs with technical sustainability without compromising essential voting accuracy, security or compliance requirements. |

This is the reciprocal perspective of the conflict identified under S09, not an additional independent conflict.

## Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | Product & Development Stakeholder |
| Importance | High |
| Influence | High |
| Justification | Developers directly influence the technical realization, quality, feasibility and maintainability of GOSPL. |
| Validation Status | Assumed – pending validation |

## Extra Information

### Relationship with Product Owners

| Aspect | S09 – Product Owners | S10 – Developers |
|---|---|---|
| Primary focus | Product value | Technical realization |
| Requirements | What should be implemented and why? | Can the requirements be understood, implemented and verified? |
| Quality | Does the product meet stakeholder expectations? | How can the required quality be achieved? |
| Sustainability | Is the product economically and operationally viable? | Can the software be maintained and evolved efficiently? |
| Resources | Prioritize available resources | Assess technical effort and feasibility |

### Contribution to Non-Functional Requirements

| Quality Attribute | Relevance to GOSPL |
|---|---|
| Modularity | Limit the impact of changes to individual areas of functionality. |
| Analysability | Efficiently identify defects and assess the impact of changes. |
| Modifiability | Accommodate changes to voting conditions and stakeholder requirements. |
| Testability | Verify voting functionality and quality requirements. |
| Reliability | Support dependable operation during voting periods. |
| Recoverability | Recover from failures without compromising voting records. |
| Security | Protect sensitive information and prevent unauthorized activities. |
| Performance Efficiency | Handle expected voting workloads within acceptable response times. |

These are candidate quality attributes for Task 8, not finalized or measurable non-functional requirements. Operational supportability is included within S10-C02, particularly through analysability, reliability and recoverability. Technical failures during active voting periods may prevent eligible shareholders from exercising their voting rights.

### Separation of Operational and Technical Responsibilities

| AGM Administrators | Developers |
|---|---|
| Manage shareholder voting activities | Maintain the technical platform |
| Investigate operational voting issues | Investigate technical failures |
| Coordinate voting exceptions | Diagnose and resolve software defects |
| Manage authorized voting conditions | Implement support for established voting conditions |
| Coordinate voting result processing | Ensure correct technical implementation of result processing |

Developers should not automatically receive unrestricted access to shareholder information or voting choices, or the ability to modify submitted votes, simply because they maintain the platform. Technical access must be subject to appropriate authorization and confidentiality restrictions.

### Scope Boundaries

| Within Developer Responsibilities | Outside Developer Responsibilities |
|---|---|
| Software design and implementation | Independent interpretation of legislation |
| Software testing and verification | Determination of legal voting entitlements |
| Technical maintenance | Management of authoritative share ownership records |
| Technical failure investigation | Execution of shareholder voting decisions |
| Software evolution | Unauthorized modification of submitted votes |
| Security maintenance | Formal certification of voting results |

### Assumptions and Validation Notes

- Developers are a conceptual stakeholder role within the project, not actual representatives of Kesko.
- Technical maintenance and operational support are grouped within this role rather than introducing a separate Operations or DevOps stakeholder.
- No dedicated application interface for Developers is currently identified.
- Specific operational responsibilities, quality targets, access permissions and technical solutions remain to be established.
- No particular technology, architectural pattern, monitoring tool or deployment infrastructure is prescribed.
- Stakeholder concerns, prioritization and the potential conflict remain modelling assumptions pending validation.
