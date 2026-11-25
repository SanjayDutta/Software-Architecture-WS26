# S03 – Proxy Representatives

## 1. Description

Proxy representatives are persons appointed by individual or institutional shareholders to exercise voting rights on their behalf within the scope of a valid authorization. They directly interact with GOSPL and need not personally own shares. Proxy representation is a role, not an exclusive identity; a person may also be a shareholder.

## 2. Stakeholder Concerns

Concerns are recorded under the stakeholder that first introduces them. The Distinct Concerns table contains original concern definitions, which may also be shared by other stakeholders. Common Concerns lists inherited references without creating duplicate IDs.

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S03-C01 | Authorization Awareness | I want to know whom I represent, which voting rights have been delegated to me and the scope and validity of my authorizations. |
| S03-C02 | Delegated Voting | I want to correctly exercise voting rights on behalf of each shareholder according to the applicable authorizations and voting instructions. |
| S03-C03 | Authorization Updates | I want to be informed of changes to my voting authorizations and instructions, including their revocation. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| S01-C01 | Accessible Participation | Easily participate in shareholder voting. |
| S01-C03 | Informed Decision-Making | Access resolution information and supporting documentation. |
| S01-C04 | Voting Flexibility | Cast or revise votes within permitted authorizations. |
| S01-C05 | Voting Transparency | Receive confirmation of submitted votes and access voting outcomes. |
| S01-C06 | Privacy & Security | Protect personal information and entrusted voting information. |
| S02-C03 | Accountability & Traceability | Review voting activities performed on behalf of shareholders. |
| S02-C04 | Operational Efficiency | Efficiently manage multiple authorizations and voting activities. |

## 3. Candidate Capabilities and Potential Solutions

All capabilities and solutions are candidates, not finalized requirements or architectural decisions.

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Profile Management | View necessary personal details and associated roles. | S01-C06 | Shared candidate |
| Representative & Delegation Management | View received authorizations, represented shareholders, delegated voting power, assigned resolutions, validity and status. | S03-C01 | Existing candidate |
| Voting Authority Validation | Check recorded authority before accepting a delegated vote; prevent representatives from expanding their own authority. | S03-C01, S03-C02 | Existing candidate |
| Voting Instruction Management | View applicable shareholder instructions and distinguish them from the scope of authorization. | S03-C02 | Existing candidate |
| Multi-Shareholder Representation | Switch between represented shareholders while keeping their authorizations, instructions and votes separate. | S03-C02, S02-C04 | New candidate |
| Authorization Notifications | Communicate changes to authority, revocations and updated voting instructions. | S03-C03 | New candidate |
| Voting History | View submitted votes for each represented shareholder, including representative attribution and applicable authorization. | S02-C03, S01-C05 | Existing candidate |

## 4. Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Representative Autonomy vs. Shareholder Control | S01 – Individual Shareholders; S02 – Institutional Shareholders | Sufficient flexibility to exercise delegated voting rights and respond to developments during an AGM. | Control over how delegated voting rights are exercised and adherence to applicable voting instructions. | Distinguish authorization scope, binding instructions and permitted representative discretion. |

## 5. Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | Primary stakeholder |
| Importance | High |
| Influence | Medium |
| Justification | Directly participates in voting and enables delegated participation, but voting authority originates from other shareholders. |
| Validation Status | Assumed – pending validation |

## 6. Extra Information

### Authorization and Scope

Common participation, resolution information, voting flexibility and privacy capabilities identified for S01 and S02 also apply, subject to the proxy's authority. A proxy may exercise delegated voting rights and revise votes where permitted, but may not independently change assigned resolutions, increase delegated voting power or modify received instructions. These are candidate rules, not finalized requirements or architecture decisions.

S01-C02 (Voting Rights) is not repeated because S03-C01 captures the delegated-rights perspective. Common concerns retain their original identifiers; their applicability is interpreted in the proxy role.

### Conflict Example

For example, new information during an AGM may prompt a representative to reconsider a voting choice while the shareholder expects adherence to an existing instruction. This is a potential tension, not an established conflict; discretion depends on the authorization and applicable rules.

### Validation Notes

The concerns, conflict and prioritization are working assumptions, not findings validated with actual Kesko stakeholders. Candidate capabilities remain open for evaluation. Proxy appointment procedures, resolution-specific delegation, multiple representation, vote revision, representative discretion and required personal attributes must be validated against applicable rules and the Kesko reference case. GOSPL should validate recorded authority against established rules rather than independently determine legal validity or resolve representation disputes.
