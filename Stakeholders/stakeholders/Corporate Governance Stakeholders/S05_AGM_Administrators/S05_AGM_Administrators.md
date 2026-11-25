# S05 – AGM Administrators

---

## Description

AGM Administrators are individuals or teams responsible for the operational preparation, coordination and execution of Annual General Meetings (AGMs) and their associated shareholder voting activities.

In GOSPL, they prepare authorized proposals for voting, manage established voting conditions, coordinate shareholder participation, monitor voting activities and communicate authorized voting outcomes. Unlike the Board of Directors, which is concerned with the substance of its proposals, AGM Administrators focus on the correct and efficient execution of the voting process.

## Stakeholder Concerns

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S05-C01 | AGM Management | We want to efficiently prepare, organize and manage shareholder voting activities associated with an AGM. |
| S05-C02 | Voting Preparation | We want to prepare authorized proposals, supporting documentation and applicable voting conditions for shareholder participation. |
| S05-C03 | Eligibility & Authorization Management | We want to ensure that shareholder participation and representative authorizations are established according to authoritative information and applicable conditions. |
| S05-C04 | Voting Process Control | We want to monitor and control the progression of voting activities according to established procedures and deadlines. |
| S05-C05 | Operational Exception Management | We want to identify and appropriately address operational issues, inconsistencies and exceptional situations that arise throughout the voting process. |
| S05-C06 | Voting Result Management | We want to coordinate vote counting, result verification and the publication of authorized voting outcomes. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| S01-C01 | Accessible Participation | Ensure shareholders can participate through accessible and usable processes. |
| S01-C02 | Voting Rights | Ensure eligible shareholders can exercise their entitled voting rights. |
| S01-C03 | Informed Decision-Making | Make authorized proposals, supporting documentation and relevant updates available. |
| S01-C04 | Voting Flexibility | Accommodate permitted vote revisions, delegations and authorization changes. |
| S01-C05 | Voting Transparency | Provide appropriate vote confirmations and communicate voting outcomes. |
| S01-C06 | Privacy & Security | Protect shareholder, corporate and voting information. |
| S02-C03 | Accountability & Traceability | Maintain traceability of administrative activities, voting operations and relevant changes. |
| S02-C04 | Operational Efficiency | Efficiently coordinate multiple proposals, shareholders, representatives and voting activities. |
| S04-C01 | Proposal Management | Receive and prepare submitted proposals for shareholder voting. |
| S04-C02 | Proposal Integrity | Preserve authorized content and intended meaning during operational preparation. |

## Candidate Capabilities and Potential Solutions

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Profile Management | View administrative identity, organizational association and assigned permissions. | S01-C06 | Existing candidate |
| AGM Management | Create and manage AGM records, meeting schedules, agendas and associated voting activities. | S05-C01 | New candidate |
| Proposal Management | Receive, organize and prepare authorized proposals and supporting documents. | S05-C02, S04-C01 | Existing candidate |
| Proposal Lifecycle Management | Coordinate proposal progression through preparation, review, publication, voting and result processing. | S05-C02, S05-C04 | Existing candidate |
| Proposal Version Management | Track authorized amendments and maintain proposal modification history. | S04-C02, S02-C03 | Existing candidate |
| Voting Configuration | Configure voting periods, available voting choices and externally established voting conditions. | S05-C02 | New candidate |
| Shareholder Eligibility Management | Access and manage relevant eligibility information obtained from authoritative sources. | S05-C03, S01-C02 | New candidate |
| Representative & Delegation Management | Review relevant representative appointments and authorization records. | S05-C03, S01-C04 | Existing candidate |
| Voting Authority Validation | Identify unauthorized participation and conflicting exercise of voting rights. | S05-C03, S05-C05 | Existing candidate |
| Voting Process Management | Open, monitor and close voting activities according to applicable conditions. | S05-C04 | New candidate |
| AGM Administration Dashboard | Provide a consolidated overview of AGM preparation, voting progress, operational issues and result status. | S05-C01, S05-C04, S02-C04 | New candidate |
| Information Publication & Notifications | Publish authorized proposals, documents, voting schedules and relevant updates. | S05-C02, S01-C03 | New candidate |
| Operational Exception Management | Identify, document, investigate and escalate operational issues to appropriate stakeholders. | S05-C05 | New candidate |
| Vote Counting & Result Processing | Calculate preliminary voting outcomes according to established voting conditions. | S05-C06 | New candidate |
| Result Verification Coordination | Make relevant voting records and preliminary results available to authorized verification stakeholders. | S05-C06, S02-C03 | New candidate |
| Voting Results Dashboard | Access preliminary and confirmed voting outcomes according to assigned permissions. | S05-C06, S01-C05 | Existing candidate |
| Result Publication | Publish formally established voting outcomes and relevant documentation. | S05-C06, S01-C05 | New candidate |

These 17 candidates (10 new and 7 existing) are not committed requirements or separate software modules.

## Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Operational Visibility vs. Voting Confidentiality | S01, S02, S03 – Shareholders & Proxies | Access sufficient information to monitor voting activities and resolve operational issues. | Protect personal information and voting choices from unnecessary disclosure. | Separate operational monitoring information from restricted voting information. |
| Timely Publication vs. Thorough Verification | S07 – Auditors & Scrutineers | Communicate voting outcomes promptly. | Ensure voting records and results are sufficiently verified. | Distinguish preliminary results from formally established outcomes. |
| Operational Efficiency vs. Procedural Compliance | S06 – Legal Counsel & Compliance Officers | Conduct voting activities without unnecessary delays or administrative overhead. | Ensure that applicable procedural and legal conditions are satisfied. | Support necessary reviews and controls without unnecessary operational complexity. |
| Operational Flexibility vs. Proposal Integrity | S04 – Board of Directors | Flexibility to prepare, format and update proposals for voting. | Preserve the authorized content and intended meaning of proposals. | Distinguish administrative modifications from substantive amendments. |

## Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | Corporate Governance Stakeholder |
| Importance | High |
| Influence | High |
| Justification | AGM Administrators coordinate and execute shareholder voting activities. Their operational needs significantly influence the functional scope, usability and process management capabilities of GOSPL. |
| Validation Status | Assumed – pending validation |

## Extra Information

### Role throughout the shareholder voting lifecycle

| Stage | Candidate responsibilities |
|---|---|
| Before the AGM | Create AGM records; receive authorized proposals; organize agendas; prepare established voting conditions; coordinate eligibility information; publish proposals and documents; manage advance voting where applicable. |
| During the AGM | Coordinate the agenda; open and close voting periods; monitor participation; publish authorized updates; handle exceptions; coordinate with governance stakeholders. |
| After voting | Coordinate preliminary counting; provide records for verification; coordinate discrepancy resolution; record formally established outcomes; publish authorized results; maintain relevant records. |

### AGM Administration Dashboard

A candidate dashboard could show proposal publication status, eligibility record availability, open and closed voting activities, operational issues and result processing status. It should focus on operational information rather than individual voting choices or interim results, access to which requires separate justification.

### Candidate profile and permissions

An AGM Administrator is a business role, not an unrestricted technical system administrator.

| Information or Operation | Proposed Access |
|---|---|
| Administrative profile | View |
| Assigned AGM records | View and manage |
| Create AGM records and manage agendas | Permitted |
| Receive submitted proposals | Permitted |
| Independently change substantive proposal content | Not permitted |
| Publish authorized proposals | Permitted |
| Configure established voting conditions | Permitted |
| Independently establish legal voting rules | Not permitted |
| Access shareholder eligibility records | Subject to authorization |
| Independently change authoritative share ownership | Not permitted |
| Review representative authorizations | Subject to authorization |
| Open or close voting | Subject to established procedures |
| Monitor voting participation | Permitted |
| View individual voting choices | Restricted; subject to justified authorization |
| Modify submitted shareholder votes | Not permitted |
| Initiate preliminary vote counting | Permitted |
| Access preliminary voting results | Subject to authorization |
| Independently certify voting results | Not assumed |
| Publish authorized voting results | Permitted |

### Separation of responsibilities

| Responsibility | Responsible Stakeholder | AGM Administrator's Role |
|---|---|---|
| Formulate proposals | S04 or other entitled parties | Receive and prepare proposals |
| Interpret legal requirements | S06 | Apply established conditions |
| Establish authoritative ownership information | S08, S09, as applicable | Use relevant authoritative information |
| Grant voting authorization | S01, S02 | Administer and review authorization records |
| Exercise voting rights | S01, S02, S03 | Facilitate participation |
| Independently verify voting records | S07, where applicable | Provide evidence and coordinate verification |
| Formally declare voting outcomes | Authorized meeting officials | Record and publish authorized outcomes |

### Scope boundaries

| Candidate Scope Within GOSPL | Outside GOSPL |
|---|---|
| AGM and voting activity management | Physical venue and catering arrangements |
| Proposal and agenda preparation | Corporate strategy formulation |
| Voting condition configuration | Independent legal interpretation |
| Eligibility information management | Maintenance of authoritative share ownership registers |
| Voting process monitoring | Shareholders' internal voting decisions |
| Operational exception tracking | Independent adjudication of legal disputes |
| Preliminary vote counting | Independent external audit execution |
| Verification coordination | Independent certification of legal validity |
| Authorized result publication | Implementation of adopted resolutions |

### Operational exception management

| Example Situation | Potential Administrative Response |
|---|---|
| Inconsistent shareholder eligibility information | Request clarification from the relevant authoritative source. |
| Conflicting representative voting authority | Identify the conflict and initiate an authorization review. |
| Proxy authorization revoked during voting | Apply the established procedure for authorization changes. |
| Substantive proposal amendment required | Request an authorized amendment from the responsible party. |
| Shareholder technical difficulties | Provide appropriate assistance within permitted procedures. |
| Inconsistent voting records and preliminary results | Escalate the discrepancy for investigation and verification. |
| Technical disruption affecting voting | Coordinate the applicable contingency procedure. |

Administrators should be able to identify, coordinate and escalate exceptions without unrestricted authority to override voting rights, voting records or legal conditions.

### Assumptions and validation

The proposed permissions, direct involvement in eligibility management, exception handling, preliminary counting and result publication remain candidate responsibilities. The precise authority of AGM Administrators, verification stakeholders and meeting officials, including any required review or approval sequence, must be validated against applicable Finnish legislation and Kesko's AGM procedures. Individual vote recording confirmation is distinct from formal result confirmation. No integration mechanism or software architecture is assumed.
