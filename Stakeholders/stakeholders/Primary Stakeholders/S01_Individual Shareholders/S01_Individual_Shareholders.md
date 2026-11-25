# S01 – Individual Shareholders

## 1. Description

Individual shareholders are natural persons who own shares in a company and may exercise voting rights associated with their eligible shareholdings. They are primary users of GOSPL before and during the AGM, subject to applicable voting rules.

## 2. Stakeholder Concerns

Concerns are recorded under the stakeholder that first introduces them. The Distinct Concerns table contains original concern definitions, which may also be shared by other stakeholders. Common Concerns lists inherited references without creating duplicate IDs.

### Distinct Concerns

| ID | Concern | Stakeholder Expectation |
|---|---|---|
| S01-C01 | Accessible Participation | I want to easily participate in shareholder voting before and during the AGM. |
| S01-C02 | Voting Rights | I want to understand and exercise my entitled voting rights and voting power, including knowing which resolutions I may vote on. |
| S01-C03 | Informed Decision-Making | I want accessible, reliable and unbiased information about resolutions, supporting documents and relevant updates. |
| S01-C04 | Voting Flexibility | I want to cast, revise or delegate my votes within permitted conditions. |
| S01-C05 | Voting Transparency | I want confirmation that my votes are correctly recorded and counted, and access to voting outcomes. |
| S01-C06 | Privacy & Security | I want my personal information and voting choices to be appropriately protected. |

### Common Concerns (Cross-References)

| Reference | Concern | Relevance |
|---|---|---|
| — | — | No inherited concerns; S01 introduces the six common shareholder concerns. |

## 3. Candidate Capabilities and Potential Solutions

All capabilities and solutions are candidates, not finalized requirements or architectural decisions.

| Candidate Capability | Potential Solution | Concerns Addressed | Status |
|---|---|---|---|
| Shareholder Participation & Eligibility | Accessible voting interface; eligibility checks against authoritative records; display of eligible resolutions and voting power. | S01-C01, S01-C02 | Originating candidate |
| Resolution Information & AI-Assisted Understanding | Resolution and supporting document viewer; notifications of relevant updates; document-grounded conversational assistant, potentially using RAG and an LLM via OpenRouter. | S01-C03 | Originating candidate |
| Voting & Proxy Management | Vote submission and revision workflows; delegation and revocation workflows where permitted; enforcement of applicable voting periods and authority. | S01-C04 | Originating candidate |
| Vote Confirmation & Results | Vote acknowledgements; authorized verification of vote recording and counting; publication of authorized voting outcomes. | S01-C05 | Originating candidate |
| Data Protection & Access Control | Appropriate identity and access controls, data minimization and encryption; privacy-aware handling of voting records and AI queries. | S01-C06 (cross-cutting) | Originating candidate |

## 4. Potential Stakeholder Conflicts

| Conflict | Conflicting Stakeholders | Stakeholder Expectation | Other Stakeholder Expectation | Implication for GOSPL |
|---|---|---|---|---|
| Voting Flexibility vs. Timely Finalization | S05 – AGM Administrators | Flexible voting and revisions. | Timely finalization of results. | Apply permitted voting periods and finalization rules. |
| Ease of Participation vs. Procedural Restrictions | S06 – Legal Counsel & Compliance Officers | Easy participation. | Compliance with legal and procedural restrictions. | Support accessible participation within established rules. |
| Voting Confidentiality vs. Auditability | S07 – Auditors & Scrutineers | Confidential voting choices. | Sufficient auditability. | Restrict access to voting records according to authorized audit needs. |
| Information Access vs. Confidentiality | S04 – Board of Directors | Extensive resolution information. | Protection of sensitive corporate information. | Provide authorized information only. |
| Advanced Functionality vs. Simplicity (SC04) | S02 – Institutional Shareholders | Simple and intuitive voting experience. | Sophisticated tools for organizational voting activities. | Keep individual voting workflows simple while supporting institutional needs. |

## 5. Stakeholder Prioritization

| Attribute | Assessment |
|---|---|
| Category | Primary stakeholder |
| Importance | High |
| Influence | Low individually; potentially high collectively |
| Justification | Individual shareholders are primary users. They may have limited influence over project decisions individually, although collective influence may be greater. |
| Validation Status | Assumed – pending validation |

## 6. Extra Information

### AI-Assisted Informed Decision-Making

Individual shareholders may have limited time or expertise to interpret extensive resolution documentation and may only be interested in specific aspects. A conversational assistant could answer natural-language questions using authorized resolution documents, cite its sources and indicate when information is insufficient. It should not recommend how to vote, provide definitive legal advice or determine the legal validity of resolutions.

RAG and OpenRouter are candidate technologies. The team has stated that it has \$20 in OpenRouter credit; feasibility remains to be evaluated. Personal data must not be sent to OpenRouter under the course instructions. The actual documentation available for Kesko resolutions and the applicable voting and revision procedures must be investigated under Task 3.

### Evidence and Validation Status

-   Source: Team discussion and initial GOSPL product vision.
-   The six concerns and before/during AGM scope are agreed working proposals, not validated statements from actual Kesko shareholders.
-   Conflicts, prioritization and solution candidates are preliminary assessments.
-   Validate against Kesko AGM documentation, applicable legal and governance sources, and stakeholder consultation where feasible.
-   Formal functional and non-functional requirements will be derived later from the goals, use cases, business rules and quality concerns.
