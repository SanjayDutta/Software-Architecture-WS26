# S07 – Voting Scrutineers

---

## Description

Voting Scrutineers are designated individuals responsible for supervising and verifying shareholder voting activities, vote counting and the accuracy of voting results, within their assigned mandate.

In GOSPL, their primary interest is verifying that voting records accurately reflect voting activities and that results are correctly calculated according to established voting conditions. This is a verification role rather than a general financial auditing or legal compliance role.

## Stakeholder Concerns

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S07-C01 | Voting Integrity & Accuracy | We want to independently verify that voting records accurately and completely reflect the voting activities that occurred and that voting results are correctly calculated according to established voting conditions. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| S01-C05 | Voting Transparency | Ensure voting outcomes accurately reflect applicable votes. |
| S01-C06 | Privacy & Security | Protect sensitive voting and shareholder information during verification. |
| S02-C03 | Accountability & Traceability | Access sufficient evidence to reconstruct and verify voting activities. |
| S02-C04 | Operational Efficiency | Conduct verification activities efficiently. |
| S05-C06 | Voting Result Management | Coordinate verification before authorized result publication, where required. |
| S06-C03 | Procedural Compliance Assessment | Communicate identified discrepancies that may have compliance implications. |

## Candidate Capabilities and Potential Solutions

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Profile Management | View assigned identity, verification responsibilities and access permissions. | S01-C06 | Existing candidate |
| Result Verification Coordination | Access relevant voting records, established conditions, preliminary results and supporting evidence within assigned authority. | S07-C01, S05-C06, S02-C03 | Existing candidate |
| Voting Results Dashboard | Review preliminary and confirmed outcomes and relevant vote totals. | S07-C01, S01-C05 | Existing candidate |
| Voting Result Verification | Reconcile voting records against available evidence and independently check vote totals and calculated outcomes, including applicable voting power and permitted revisions. | S07-C01, S02-C03 | New candidate |
| Verification Findings Management | Document verification findings and discrepancies, communicate them to authorized stakeholders and track their resolution. | S07-C01, S05-C06, S06-C03 | New candidate |

These five capabilities (three existing and two new) are preliminary business capabilities, not committed architectural components. Independent checks may be performed outside GOSPL using authorized evidence; no specific implementation is assumed.

## Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Thorough Verification vs. Timely Publication | S05 – AGM Administrators | Obtain sufficient time and evidence to verify results. | Communicate voting outcomes promptly. | Distinguish preliminary results from authorized outcomes and support verification coordination. |
| Verification Evidence vs. Voting Confidentiality | S01, S02, S03 – Shareholders & Proxy Representatives | Access sufficient evidence to verify voting integrity and accuracy. | Protect personal information and voting choices from unnecessary disclosure. | Provide proportionate, restricted access to verification evidence. |

These conflicts are proposed for validation. The first is reciprocal to the previously identified S05 conflict. Compliance assessment and verification independence are treated as complementary responsibilities rather than an inherent conflict with S06.

## Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | Corporate Governance Stakeholder |
| Importance | High |
| Influence | Medium |
| Justification | Voting Scrutineers contribute to confidence in voting integrity and result accuracy but are not assumed to determine overall voting procedures or platform scope. |
| Validation Status | Assumed – pending validation of the role, mandate and GOSPL interaction. |

## Extra Information

### Separation of responsibilities

| Stakeholder | Responsibility |
|---|---|
| S04 – Board of Directors | Formulate proposals within its authority. |
| S05 – AGM Administrators | Prepare and execute voting activities and coordinate result processing. |
| S06 – Legal Counsel & Compliance Officers | Assess proposal compliance, voting conditions and procedural adherence, including implications of identified deviations. |
| S07 – Voting Scrutineers | Verify voting record integrity and counting accuracy against available evidence. |
| Authorized meeting officials | Formally establish voting outcomes according to applicable procedures. |

### Illustrative verification workflow

1. AGM Administrators conclude voting according to established conditions.
2. GOSPL calculates preliminary voting results and makes authorized evidence available.
3. Voting Scrutineers examine voting records and independently check the calculated outcomes.
4. Scrutineers document findings and communicate discrepancies to relevant authorized stakeholders. Legal & Compliance assesses compliance implications where necessary.
5. Authorized stakeholders address discrepancies under established procedures; verification may be repeated as needed.
6. Authorized meeting officials establish the outcome, and AGM Administrators publish it as permitted.

Verification may also occur during voting or counting. This sequence does not establish a mandatory approval workflow or confer formal result-declaration authority on scrutineers.

### Candidate permissions and scope boundaries

| Within candidate scope | Outside scope or not assumed |
|---|---|
| View assigned verification responsibilities. | Determine legal voting rules or interpret legislation. |
| Access relevant voting conditions, records and supporting evidence, subject to authorization. | Unrestricted access to personal information or individual voting choices. |
| Review preliminary results and independently check calculations. | Modify submitted votes or authoritative ownership records. |
| Record verification findings and communicate discrepancies. | Independently resolve legal disputes or override voting conditions. |
| Access relevant discrepancy-resolution status. | Statutory financial auditing or automatic authority to certify and declare results. |

Verification must be meaningful: reviewing a calculated result alone does not establish its correctness. Reconciliation requires sufficient trustworthy evidence; records generated by the platform alone may not establish that every voting activity was captured correctly. Evidence access should be limited to what is necessary for the assigned verification task.

### Reference-company context and validation

The previous stakeholder discussion identified Kesko AGM minutes as candidate documentary evidence for the appointment of persons supervising vote counting, distinct from persons scrutinising meeting minutes. The following references were identified in that discussion and should be checked against the original documents before being treated as validated evidence:

- [Kesko AGM 2025 – Minutes](https://www.kesko.fi/496889/globalassets/03-sijoittaja/yhtiokokous/2025/kesko-agm-24-march-2025-minutes.pdf)
- [Kesko AGM 2026 – Minutes](https://www.kesko.fi/496c1e/globalassets/03-sijoittaja/yhtiokokous/2026/kesko-2026-agm-minutes.pdf)

The name Voting Scrutineers describes a functional role, not necessarily a permanent job title. Auditors are included only if assigned relevant voting verification responsibilities. The precise mandate, evidence requirements, independence arrangements, access permissions and result confirmation authority remain unvalidated. Mandatory Legal & Compliance clearance is likewise not assumed. GOSPL supports verification rather than independently certifying its own correctness.
