# S08 – Share Registry & Custody Providers

---

## Description

Share Registry & Custody Providers are external organizations responsible for maintaining or administering shareholding information and facilitating the exchange of relevant shareholder information.

In the context of GOSPL, their relevance is primarily associated with providing reliable information concerning shareholder eligibility, voting power and, where applicable, representation. Examples include Euroclear Finland, as a central securities depository and share registry operator, and custodian or nominee banks. These organizations have distinct responsibilities but are grouped together because of their shared relevance to GOSPL.

## Stakeholder Concerns

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S08-C01 | Shareholder Information Exchange | We want relevant shareholder eligibility, voting entitlement and representation information to be accurately, securely and promptly communicated and correctly utilized throughout the shareholder voting process. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| S01-C06 | Privacy & Security | Protect shareholder information during exchange and processing. |
| S02-C03 | Accountability & Traceability | Ensure exchanged information and relevant changes are traceable. |
| S02-C04 | Operational Efficiency | Minimize unnecessary administrative effort associated with information exchange. |

## Candidate Capabilities and Potential Solutions

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Shareholder Information Exchange | Receive relevant shareholder information through authorized exchange procedures. | S08-C01 | New candidate |
| Shareholder Eligibility Management | Utilize authoritative information when establishing shareholder eligibility and voting entitlements. | S08-C01, S05-C03 | Existing candidate |
| Operational Exception Management | Identify and escalate missing, inconsistent or outdated shareholder information. | S08-C01, S05-C05 | Existing candidate |

## Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Information Confidentiality vs. Operational Accessibility | S05 – AGM Administrators | Ensure shareholder information is exchanged and accessed only for authorized purposes. | Obtain sufficient information to prepare and execute voting efficiently. | Support controlled access and data minimization. |

## Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | External Stakeholder |
| Importance | High |
| Influence | Medium |
| Justification | Reliable shareholder information is fundamental to establishing eligibility and voting entitlements. However, these providers do not necessarily influence GOSPL's internal functionality or voting procedures. |
| Validation Status | Assumed – pending validation |

## Extra Information

### 1. Relevant information

Potential information includes shareholder identification, eligibility information, shareholding or voting entitlement information, representation information where applicable, and relevant corrections or updates. Only information necessary for authorized voting activities should be exchanged. Entitlements must be established or appropriately validated before a vote is accepted, including advance votes. Updates during voting are subject to applicable procedures and record-date conditions.

### 2. Separation of responsibilities

| Stakeholder or System | Proposed Responsibility |
|---|---|
| S08 – Share Registry & Custody Providers | Provide authoritative or appropriately sourced shareholder information within their respective responsibilities. |
| S06 – Legal Counsel & Compliance Officers | Assess applicable eligibility, voting rights and representation conditions. |
| S05 – AGM Administrators | Coordinate and prepare voting entitlements using authorized information and established conditions. |
| GOSPL | Support the accurate and authorized exercise of established voting entitlements. |

### 3. Scope boundaries

| Candidate Scope Within GOSPL | Outside GOSPL |
|---|---|
| Receive and use relevant shareholder information through authorized procedures | Maintain authoritative share ownership registers |
| Support eligibility and voting entitlement management | Administer securities custody or settlement |
| Identify and escalate information discrepancies | Independently determine legal ownership or voting rights |
| Protect and trace exchanged information | Correct authoritative external records independently |

S08 is not necessarily a direct GOSPL user. A dedicated profile, dashboard or user interface is not assumed. No direct API integration or particular exchange mechanism is committed to; information may be made available through authorized organizational procedures.

### 4. Validation notes

The grouping of registry operators and custody providers, their proposed concern, prioritization, information exchange responsibilities and the division of responsibilities between S05 and S06 are modelling assumptions pending validation. Actual data availability, exchange procedures, permissions and applicable conditions must be established before deriving detailed requirements.

Regulatory authorities are excluded from the active stakeholder register under the agreed scope decision. Applicable legislation, regulations and regulatory guidance remain relevant under Task 3 – Other Requirements Sources. Registry and custody documentation may also provide requirements sources.
