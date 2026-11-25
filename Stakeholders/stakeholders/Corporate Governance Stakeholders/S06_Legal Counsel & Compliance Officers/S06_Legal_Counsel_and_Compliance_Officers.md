# S06 – Legal Counsel & Compliance Officers

---

## Description

Legal Counsel and Compliance Officers are individuals or teams responsible for advising the company on applicable legal, regulatory and procedural requirements and overseeing adherence to established obligations. Legal Counsel interprets applicable requirements and advises on legal risks, while Compliance Officers monitor adherence to established requirements. They are grouped together because their interests in GOSPL are closely aligned.

In GOSPL, their focus is the compliance of proposals, voting conditions and actual voting activities. GOSPL supports human compliance assessments and applies established voting conditions; it does not independently interpret legislation or guarantee legal validity.

## Stakeholder Concerns

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S06-C01 | Proposal Compliance | We want to assess whether proposed matters and their supporting documentation are consistent with applicable legal, regulatory and corporate governance requirements. |
| S06-C02 | Voting Rule Compliance | We want to ensure that the conditions governing shareholder eligibility, voting rights, representative authorizations and voting activities are consistent with applicable legal and procedural requirements. |
| S06-C03 | Procedural Compliance Assessment | We want to assess whether voting activities have been conducted according to established procedures, using sufficient evidence to identify deviations, document findings and track the resolution of compliance issues. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| S01-C02 | Voting Rights | Ensure eligible shareholders can exercise their entitled voting rights under applicable conditions. |
| S01-C03 | Informed Decision-Making | Ensure relevant information and disclosures are appropriately communicated. |
| S01-C04 | Voting Flexibility | Ensure revisions, delegations and authorization changes occur within permitted conditions. |
| S01-C05 | Voting Transparency | Ensure confirmations and outcomes are communicated according to applicable obligations. |
| S01-C06 | Privacy & Security | Protect personal, corporate and voting information. |
| S02-C03 | Accountability & Traceability | Trace relevant activities, decisions, authorizations and modifications. |
| S02-C04 | Operational Efficiency | Efficiently conduct reviews and access relevant information. |
| S04-C02 | Proposal Integrity | Preserve reviewed and authorized proposal content. |
| S05-C02 | Voting Preparation | Ensure voting activities are prepared according to established conditions. |
| S05-C05 | Operational Exception Management | Coordinate handling of exceptions with potential compliance implications. |
| S05-C06 | Voting Result Management | Assess whether result processing and publication follow applicable procedures. |

## Candidate Capabilities and Potential Solutions

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Profile Management | View professional identity, organizational association and assigned responsibilities. | S01-C06 | Existing candidate |
| Proposal Management | Access submitted proposals and supporting documentation for review. | S06-C01 | Existing candidate |
| Proposal Compliance Review | Record review findings, identify concerns and request authorized amendments. | S06-C01 | New candidate |
| Proposal Lifecycle Management | View proposal status and relevant review activities. | S06-C01, S06-C03 | Existing candidate |
| Proposal Version Management | Compare versions and trace authorized amendments. | S06-C01, S04-C02 | Existing candidate |
| Voting Conditions Management | Record established voting conditions, their sources, applicability and review status. | S06-C02 | New candidate |
| Voting Configuration | Review operational configurations against established conditions. | S06-C02, S05-C02 | Existing candidate |
| Shareholder Eligibility Management | Review relevant eligibility information and discrepancies. | S06-C02, S01-C02 | Existing candidate |
| Representative & Delegation Management | Review relevant authorizations and applicable conditions. | S06-C02, S01-C04 | Existing candidate |
| Voting Authority Validation | Examine authorization conflicts and potentially unauthorized participation. | S06-C02, S06-C03 | Existing candidate |
| Compliance Monitoring Dashboard | View review status, procedural issues and outstanding actions. | S06-C03, S02-C04 | New candidate |
| Compliance Issue Management | Record, classify, communicate and track potential compliance issues and their resolution. | S06-C03 | New candidate |
| Compliance Evidence & Reporting | Access relevant activity records, review findings, voting conditions and supporting evidence. | S06-C03, S02-C03 | New candidate |
| Result Verification Coordination | Access relevant verification findings and assess procedural issues. | S06-C03, S05-C06 | Existing candidate |
| Voting Results Dashboard | Access authorized preliminary and confirmed outcomes for compliance review. | S06-C03, S05-C06 | Existing candidate |

These 15 capabilities (5 new and 10 existing) are candidates, not committed requirements or architectural components. Evidence access and issue management remain supporting capabilities despite the consolidation of concerns.

## Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Proposal Intent vs. Legal Compliance | S04 – Board of Directors | Ensure proposals comply with applicable requirements. | Preserve intended proposal objectives. | Support review feedback and authorized amendments. |
| Operational Efficiency vs. Procedural Compliance | S05 – AGM Administrators | Ensure applicable procedures are followed. | Execute voting efficiently with minimal administrative overhead. | Support necessary reviews and controls without unnecessary complexity. |
| Voting Flexibility vs. Procedural Restrictions | S01, S02, S03 – Shareholders & Proxies | Keep voting activities within permitted conditions. | Exercise, revise and delegate voting rights with sufficient flexibility. | Communicate and apply established restrictions. |
| Compliance Evidence vs. Privacy | S01, S02, S03 – Shareholders & Proxies | Access and retain sufficient evidence for compliance assessment. | Protect personal information and voting choices from unnecessary access and retention. | Support controlled access, data minimization and justified retention. |

The first two conflicts are reciprocal to previously identified S04 and S05 conflicts. The latter two are retained as proposed conflicts pending explicit confirmation. Compliance Assurance vs. Verification Independence is deferred to S07; it may represent separation of responsibilities rather than a conflict.

## Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | Corporate Governance Stakeholder |
| Importance | High |
| Influence | High |
| Justification | Legal Counsel and Compliance Officers influence the applicable constraints, procedural conditions and compliance expectations governing shareholder voting. Their concerns affect the permissible functional scope and non-functional requirements of GOSPL. |
| Validation Status | Assumed – pending validation |

## Extra Information

### 1. Consolidation of concerns

The original Procedural Compliance, Compliance Issue Management and Compliance Demonstrability concerns are consolidated into S06-C03. Evidence access, assessment, documentation of deviations and tracking corrective actions are supporting activities serving the same stakeholder objective. S06-C04 and S06-C05 are no longer active concern IDs.

### 2. Lifecycle participation

| Phase | Candidate responsibility | Concern |
|---|---|---|
| Proposal formulation and review | Assess proposals and supporting documents; communicate findings and requests for amendments. | S06-C01 |
| Voting preparation | Assess applicable voting conditions and review operational configurations. | S06-C02 |
| Eligibility and authorization | Advise on applicable conditions and assess discrepancies. | S06-C02, S06-C03 |
| Voting execution | Assess escalated deviations and advise on appropriate corrective actions. | S06-C03 |
| Counting and verification | Examine evidence and relevant verification findings against established procedures. | S06-C03 |
| Result confirmation and publication | Advise on outstanding compliance concerns and disclosure obligations. | S06-C03 |

Pre-execution clearance and post-execution compliance review are candidate organizational procedures. Mandatory clearance for every proposal or voting procedure, and mandatory sign-off before result declaration, have not been established.

### 3. Voting conditions and proposal review

Legal & Compliance interprets or advises on applicable requirements. Authorized governance stakeholders establish the applicable conditions, AGM Administrators configure voting activities accordingly, and GOSPL applies supported conditions. Illustrative conditions include eligibility, voting power, representation, voting periods, revisions, voting choices, decision thresholds, disclosure and retention. These categories are not verified Kesko requirements and do not imply a rules engine.

An illustrative proposal review workflow is: authorized proposer submits proposal → Legal & Compliance reviews → findings communicated → authorized proposer amends where necessary → review completion recorded → authorized publication by AGM Administrators. Review completion is not automatically legal certification or publication authorization.

### 4. Candidate permissions

| Operation | Proposed access |
|---|---|
| View professional profile and assigned responsibilities | Permitted |
| View proposals, documents and version history | Subject to authorization |
| Record review findings and request amendments | Permitted within assigned responsibilities |
| Independently modify substantive proposal content | Not permitted |
| Record established voting conditions | Subject to assigned authority |
| Review voting configurations | Permitted |
| Independently modify operational configurations | Not assumed |
| Review eligibility and representative authorizations | Subject to justified authorization |
| Monitor procedural compliance and track issues | Permitted within assigned responsibilities |
| Access individual voting choices | Restricted; subject to justified authorization |
| Modify submitted shareholder votes | Not permitted |
| Access verification findings and compliance evidence | Subject to authorization |
| Record compliance assessments | Permitted within assigned responsibilities |
| Independently certify or declare voting results | Not assumed |

### 5. Separation of responsibilities

| Stakeholder | Primary focus |
|---|---|
| S04 – Board of Directors | Proposal substance and intended objectives |
| S05 – AGM Administrators | Operational preparation, execution and exception handling |
| S06 – Legal Counsel & Compliance Officers | Legal and procedural assessment, advice and compliance findings |
| S07 – Auditors & Scrutineers | Examination of voting evidence and verification of records and results |
| Authorized meeting officials | Formal declaration of outcomes according to applicable procedures |

An operational exception may have compliance implications. For example, S05 investigates a shareholder's inability to vote; S06 assesses whether an eligible shareholder was improperly prevented from participating. Findings and authorized corrective actions are recorded. Operational and compliance issue management may share functionality without conflating responsibilities.

A mathematically correct count can still be based on an inappropriate voting condition. Conversely, appropriate conditions can be applied incorrectly. Compliance assessment and voting verification therefore provide complementary perspectives.

### 6. Scope boundaries

| Candidate scope within GOSPL | Outside GOSPL |
|---|---|
| Access proposals and supporting documents | Independent legal interpretation or legal advice by software |
| Record review findings and established voting conditions | Creation of legal or regulatory requirements |
| Review configurations and procedural activities | Independent determination of legal voting rights |
| Track compliance issues and access supporting evidence | General corporate compliance management and dispute adjudication |
| Generate compliance-related reports and record human assessments | Regulatory enforcement, independent legal certification or guarantees of legal validity |

### 7. AI-related considerations

Any candidate AI-assisted resolution explanation should be neutral, grounded in authorized source documents, identify relevant sources and avoid voting recommendations or authoritative legal determinations. Personal information must not be transmitted to OpenRouter. Manual legal approval of every generated explanation is not assumed. These considerations are covered by existing concerns rather than a separate AI concern.

### 8. Validation notes

The stakeholder analysis is preliminary. Direct platform participation by Legal & Compliance, review workflows, permissions, evidence access, monitoring and prioritization have not been validated against actual Kesko procedures or applicable Finnish legislation. The proposed conflict selection is provisional. No mandatory legal approval workflow, independent certification authority or specific implementation architecture is established by this document.
