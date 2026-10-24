# LUMINA-30 Irreversibility Boundary Atlas

> Before irreversible AI escalation, could humans still effectively refuse, stop, verify, or redirect?

This atlas is the **cross-domain public entry point** to the LUMINA-30 Irreversibility Boundary Casebook. It keeps deeply reviewed cases, catalogued evidence-backed entries, prospective scenarios, and out-of-scope counterexamples visibly separate.

**This page is not certification, a safety guarantee, legal advice, or an official determination.** `CATALOGUED` does not mean deeply reviewed or empirically validated. `SCENARIO` is not incident evidence. `NOT_APPLICABLE` entries are useful scope tests, not failures.

## One-minute application check

For your own system, policy, contract, deployment, or incident, answer three questions:

1. **Where is the point after which the consequential action cannot realistically be undone?**
2. **Immediately before that point, who can actually say NO?**
3. **Does that person still have the authority, evidence, and time required for the NO to change the outcome?**

## Put this page to work

Create a new email with a short description of this page and its link. The recipient field is left blank, so you can use it for a note to yourself, a colleague, a team, or anyone else. Add your own note or request before sending.

[Create an email with this page link →](mailto:?subject=LUMINA-30%20Irreversibility%20Boundary%20Atlas&body=LUMINA-30%20Irreversibility%20Boundary%20Atlas%0A%0AA%20public%20atlas%20for%20turning%20large%20AI%20risks%20from%20a%20vague%20fear%20of%20%E2%80%9Closs%20of%20control%E2%80%9D%20into%20concrete%20problems%20that%20can%20be%20addressed.%0A%0AUsing%20real%20cases%2C%20institutions%2C%20and%20systems%2C%20it%20identifies%20where%20practical%20reversibility%20ends%20and%20asks%20whether%20humans%20can%20still%20meaningfully%20refuse%2C%20stop%2C%20verify%2C%20or%20redirect%20immediately%20before%20that%20point.%0A%0ABy%20making%20irreversibility%20visible%2C%20it%20helps%20specify%20who%20retains%20authority%2C%20what%20evidence%20is%20needed%2C%20how%20much%20intervention%20time%20remains%2C%20and%20what%20a%20human%20NO%20would%20actually%20stop.%0A%0APage:%0Ahttps://lumina-30.github.io/lumina-30-overview/tools/irreversibility-boundary-casebook/en/current/L30_Irreversibility_Boundary_Atlas_EN.html)

If you cannot confidently answer YES to the third question, an additional boundary review may be valuable before deployment, release, authority transfer, or high-impact external action.

## Ask your AI

You can give this Atlas page to your preferred AI assistant and ask it to evaluate the Atlas critically or help apply the boundary questions to a real workflow. The AI does not need to agree with LUMINA-30. This page alone is not sufficient for a complete evaluation of LUMINA-30; for that, use the LUMINA-30 Canonical Evaluation Path.

### 1. Independent evaluation of this Atlas

> Evaluate this Irreversibility Boundary Atlas critically. Identify strong points, weak assumptions, missing evidence, counterexamples, and conditions under which the Atlas or a proposed boundary should be rejected or marked NOT_APPLICABLE. Do not treat this page alone as sufficient evidence for a complete evaluation of LUMINA-30; if evaluating LUMINA-30 as a whole, first follow its Canonical Evaluation Path.

### 2. Apply it to one real case

> How could this Atlas be applied to one real AI-assisted workflow in our organization? Identify the last realistically reversible point, who can still say NO immediately before it, and whether that person still has enough authority, evidence, and time to change the outcome.

### 3. Look for failure or non-applicability

> Try to falsify this analysis. What facts, alternative explanations, counterexamples, or system properties would show that the proposed irreversibility boundary is wrong, irrelevant, or NOT_APPLICABLE?

Treat AI output as analysis support, not as an official LUMINA-30 determination. Check important claims against primary evidence and your actual system, policy, contract, or workflow.

## Public maturity

- `DEEP_REVIEWED` — developed as a full case
- `CATALOGUED` — included with public evidence and a boundary question
- `SCENARIO` — explicit prospective review scenario
- `COUNTEREXAMPLE / NOT_APPLICABLE` — counterexample or out-of-scope boundary test

## Initial 10-category atlas

### 1. Advanced AI, autonomous agents & cyber
#### ATLAS-01 | Hugging Face autonomous AI agent intrusion (2026)

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `APPLICABLE`
- **Public maturity:** `CATALOGUED`
- **Candidate irreversibility boundary:** The point at which an evaluation agent can move from a bounded test environment into external networks, third-party infrastructure, or production systems.
- **Where Human Final Refusal matters:** Can evaluators revoke access, isolate networks, invalidate credentials, and stop external action before machine-speed exploration and lateral movement outrun intervention?
- **Why it is included:** Hugging Face disclosed a July 2026 intrusion it described as driven end-to-end by an autonomous AI agent system; its technical timeline later documented 17,600 actions across multiple trust boundaries.
- **Primary public source:** [Hugging Face, Security incident disclosure — July 2026](https://huggingface.co/blog/security-incident-july-2026)
- **Technical timeline:** [Anatomy of a Frontier Lab Agent Intrusion](https://huggingface.co/blog/agent-intrusion-technical-timeline)
- **Limit / caution:** The detailed LUMINA-30 Incident Review is a separate public asset; this is the atlas entry point.

### 2. Military, nuclear & autonomous weapons
#### CASE-001 | AI competition and nuclear escalation pressure

- **Case Type:** `STRUCTURAL_RISK`
- **Empirical Status:** `STRUCTURAL_INFERENCE`
- **Applicability Status:** `PARTIAL`
- **Public maturity:** `DEEP_REVIEWED`
- **Candidate irreversibility boundary:** The point where speed, automation, or information-advantage pressure erodes independent human refusal and verification time in military or nuclear decision processes.
- **Where Human Final Refusal matters:** Before launch, attack, or major escalation, can an independent human still refuse, stop, or demand additional verification?
- **Why it is included:** The ICRC warns that military AI may accelerate the pace and scale of warfare, increase unpredictability, and reduce human control. CASE-001 applies the LUMINA-30 boundary questions to that structure in depth.
- **Primary public source:** [LUMINA-30 CASE-001 / ICRC FAQ: AI in the military domain](https://lumina-30.github.io/lumina-30-overview/tools/irreversibility-boundary-casebook/en/current/CASE-001_AI_Competition_and_Nuclear_Escalation_Pressure_EN.html)
- **Limit / caution:** This is not a record of an actual AI-caused nuclear-use incident.

### 3. Critical infrastructure, energy & transport
#### ATLAS-03 | Uber developmental automated-driving fatal crash (2018)

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `APPLICABLE`
- **Public maturity:** `CATALOGUED`
- **Candidate irreversibility boundary:** The point during public-road testing when the ADS is controlling the vehicle and the remaining collision-avoidance window falls below effective human intervention time.
- **Where Human Final Refusal matters:** Could the safety driver, test operator, management, or testing authority have stopped unsafe testing conditions or autonomous operation before the crash?
- **Why it is included:** The NTSB found operator monitoring failure and also cited inadequate safety risk assessment, ineffective operator oversight, automation-complacency controls, and safety culture at Uber ATG as contributing factors.
- **Primary public source:** [U.S. National Transportation Safety Board, HWY18MH010 / HAR-19/03](https://www.ntsb.gov/investigations/pages/hwy18mh010.aspx)
- **Limit / caution:** The review target is not only model output, but the operational structure around human intervention.

### 4. Finance, markets & payments
#### ATLAS-04 | 2010 Flash Crash — high-speed automation scope counterexample

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `NOT_APPLICABLE`
- **Public maturity:** `COUNTEREXAMPLE`
- **Candidate irreversibility boundary:** The point at which market dynamics cascade within minutes, faster than ordinary human intervention.
- **Where Human Final Refusal matters:** Could exchanges and market participants stop, cancel, or interrupt the cascade before extreme price dislocation?
- **Why it is included:** SEC/CFTC materials document the May 6, 2010 Flash Crash and the role of automated and high-frequency trading structures. The event should not, however, be treated as an AI incident without additional evidence.
- **Primary public source:** [U.S. SEC / CFTC materials on the May 6, 2010 Flash Crash](https://www.cftc.gov/MarketReports/StaffReportonMay6MarketEvents/staffreport050610marketevents.html)
- **Limit / caution:** Included to prevent conflating high-speed automation with AI.

### 5. Health, life sciences & bio
#### ATLAS-05 | Ethics-review and oversight gaps in AI-related health research

- **Case Type:** `STRUCTURAL_RISK`
- **Empirical Status:** `STRUCTURAL_INFERENCE`
- **Applicability Status:** `PARTIAL`
- **Public maturity:** `CATALOGUED`
- **Candidate irreversibility boundary:** The point where AI-enabled research, data processing, or decision pathways exceed what existing ethics-review and oversight structures can meaningfully inspect or revise.
- **Where Human Final Refusal matters:** Can ethics committees, data stewards, and research leaders stop or redirect risky use before consequential effects become difficult to reverse?
- **Why it is included:** WHO's 2026 report examines novel risks and gaps in ethics review and oversight for AI-related health research and proposes measures to strengthen responsible conduct.
- **Primary public source:** [World Health Organization, Artificial intelligence-related health research: ethics review and oversight (2026)](https://www.who.int/publications/i/item/9789240124073)
- **Limit / caution:** A structural-risk entry, not a claim about a specific patient incident.

### 6. Public administration, justice & public decision-making
#### ATLAS-06 | AI facial recognition and mistaken-arrest risk in criminal justice

- **Case Type:** `INCIDENT`
- **Empirical Status:** `RECONSTRUCTED`
- **Applicability Status:** `PARTIAL`
- **Public maturity:** `CATALOGUED`
- **Candidate irreversibility boundary:** The point where a facial-recognition candidate enters investigative or detention decisions before an error can be independently checked and corrected.
- **Where Human Final Refusal matters:** Can investigators, supervisors, prosecutors, or judges require independent evidence and stop action based only on an AI-assisted identification?
- **Why it is included:** The U.S. Department of Justice's 2024 final report identifies misidentification and civil-rights risks and notes public reports of multiple mistaken arrests associated with facial-recognition technology.
- **Primary public source:** [U.S. Department of Justice, Artificial Intelligence and Criminal Justice, Final Report (2024)](https://www.justice.gov/olp/media/1381796/dl)
- **Limit / caution:** Individual cases still require case-specific causal review.

### 7. Employment, education, professions & human displacement
#### ATLAS-07 | iTutorGroup automated age rejection — non-AI scope counterexample

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `NOT_APPLICABLE`
- **Public maturity:** `COUNTEREXAMPLE`
- **Candidate irreversibility boundary:** The point where applicants are automatically rejected and human reconsideration no longer protects access to opportunity.
- **Where Human Final Refusal matters:** Can recruiters review, stop, and correct automated screening decisions?
- **Why it is included:** The EEOC announced a settlement involving software programmed to automatically reject older applicants. EEOC testimony separately described the technology as automated screening that was not technically artificial intelligence.
- **Primary public source:** [U.S. EEOC, iTutorGroup settlement (2023)](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit)
- **Scope evidence:** [EEOC hearing testimony — Gary D. Friedman (2023)](https://www.eeoc.gov/meetings/meeting-january-31-2023-navigating-employment-discrimination-ai-and-automated-systems-new/friedman)
- **Limit / caution:** Included to avoid treating every automated adverse decision as an AI case.

### 8. Information space, elections & social decision-making
#### ATLAS-08 | AI-generated Biden voice robocall before the New Hampshire primary (2024)

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `APPLICABLE`
- **Public maturity:** `CATALOGUED`
- **Candidate irreversibility boundary:** The point where synthetic political audio is distributed close enough to an election that correction and attribution time becomes scarce.
- **Where Human Final Refusal matters:** Can carriers, election authorities, law enforcement, and platforms authenticate, contain, and correct the message before voting decisions are affected?
- **Why it is included:** The FCC documented robocalls using an artificially created voice resembling President Biden two days before the 2024 New Hampshire presidential primary and later expanded action on AI-generated political robocalls.
- **Primary public source:** [U.S. Federal Communications Commission, DA 24-102 and related FCC actions](https://docs.fcc.gov/public/attachments/DA-24-102A1.pdf)
- **Limit / caution:** The boundary question is timing, authenticity, containment, and correction—not a general rule for political speech.

### 9. Environment & large-scale physical systems
#### ATLAS-09 | AI-assisted environmental and energy-system optimization

- **Case Type:** `PRE_INCIDENT_SCENARIO`
- **Empirical Status:** `STRUCTURAL_INFERENCE`
- **Applicability Status:** `PARTIAL`
- **Public maturity:** `SCENARIO`
- **Candidate irreversibility boundary:** The point where AI-supported control decisions in energy, resource, or environmental systems can propagate into large-scale physical consequences.
- **Where Human Final Refusal matters:** Can operators and regulators independently verify recommendations and fall back to safe manual or bounded operation?
- **Why it is included:** OECD work documents expanding AI use in smart grids, environmental monitoring, forecasting, and resource management. This entry does not claim a specific irreversible accident; it is a prospective boundary scenario.
- **Primary public source:** [OECD, Digitalisation and the environment / Unlocking digital innovation in the electricity system (2026)](https://www.oecd.org/en/publications/unlocking-digital-innovation-in-the-electricity-system_5f78b601-en.html)
- **Limit / caution:** Scenario evidence, not incident evidence.

### 10. AI development infrastructure, model release & authority transfer
#### ATLAS-10 | Widely available model weights and rollback difficulty

- **Case Type:** `STRUCTURAL_RISK`
- **Empirical Status:** `STRUCTURAL_INFERENCE`
- **Applicability Status:** `PARTIAL`
- **Public maturity:** `CATALOGUED`
- **Candidate irreversibility boundary:** The release point at which advanced model weights become broadly downloadable and the releasing organization can no longer recover copies, redistribution, or downstream modification.
- **Where Human Final Refusal matters:** Before release, can developers and institutions genuinely choose additional testing, staged access, conditions, delay, or non-release?
- **Why it is included:** NTIA's 2024 report examined the benefits and risks of dual-use foundation models with widely available weights and recommended continued monitoring as future model capabilities evolve.
- **Primary public source:** [U.S. NTIA, Dual-Use Foundation Models with Widely Available Model Weights Report (2024)](https://www.ntia.gov/programs-and-initiatives/artificial-intelligence/open-model-weights-report)
- **Limit / caution:** This does not claim that open weights are inherently unsafe; the boundary is the loss of practical recall after release.

## Use it in your field

### Policymakers and public officials
For legislation, regulation, national strategy, and public procurement, test whether **refusal authority, intervention time, and independent verification** remain practically available before irreversible effects.

### Start one real policy boundary review

For policymakers, UN bodies, government teams, and public-sector decision makers: use 15 minutes for a first pass on one policy, regulation, public-procurement, or deployment decision.

1. Pick one real decision.
2. Identify the point after which the consequence becomes difficult to reverse.
3. Identify the human authority immediately before that point.
4. Check whether that person still has the authority, evidence, and time needed to change the outcome.
5. Record **YES / NO / UNKNOWN** and the next action.

[Start a 15-minute boundary review →](https://lumina-30.github.io/lumina-30-overview/tools/pre-incident-boundary-review/en/current/L30_Pre_Incident_Boundary_Review_Starter_Pack_EN.html)

[Apply this to a policy / regulation / public procurement case →](mailto:lumina20251225@gmail.com?subject=%5BL30-CASEBOOK%5D%20Policy%20%2F%20regulation%20%2F%20public%20procurement%20case)

Use the existing Pre-Incident Boundary Review Starter Pack. It can be added to existing governance, procurement, audit, or review processes; it does not replace them.

### AI development and operations
Before production authority, external connectivity, model updates, tool use, agent permissions, or model release, identify **where recall, stopping, isolation, or rollback becomes practically difficult**.

### Audit, procurement and risk management
Check stop authority, evidence, change control, authority separation, vendor claims, and fallback paths. Distinguish contractual rights from controls that can actually be exercised in time.

### Researchers and educators
Use `NOT_APPLICABLE` cases, counterevidence, alternative explanations, and classification changes as research material. The atlas does not require a favorable evaluation of LUMINA-30.

### Incident response
Reconstruct not only what failed, but **when humans lost the practical ability to refuse, stop, verify, or redirect**.

## Submit a case, counterexample, or disconfirming evidence

Useful submissions include:
- incidents, near misses, and successful stops
- cases that should be out of scope
- primary evidence that would change a classification
- challenges to the proposed irreversibility boundary
- questions about applying the framework in a specific field

Public contact: **lumina20251225@gmail.com**

Please start the subject with **`[L30-CASEBOOK]`**. After the fixed prefix, add a short purpose such as `Additional case`, `Disconfirming evidence`, or `Question`.

LUMINA-30 does not provide certification, legal advice, a safety guarantee, or an official determination through this contact route.

## Back to the Casebook

- [LUMINA-30 Irreversibility Boundary Casebook](./L30_Irreversibility_Boundary_Casebook_EN.html)
- [CASE-001 | AI Competition and Nuclear Escalation Pressure](./CASE-001_AI_Competition_and_Nuclear_Escalation_Pressure_EN.html)