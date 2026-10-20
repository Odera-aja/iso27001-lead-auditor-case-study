# ISO/IEC 27001:2022 Lead Auditor Case Study (Stage 2 Certification Audit Simulation)

## About this project

This repository documents my own work completing the practical capstone of the GRC Mastery ISO 27001 Lead Auditor training: a simulated Stage 2 (initial certification) audit against ISO/IEC 27001:2022, acting as Lead Auditor for a fictional, anonymised organisation (a fictional cloud-storage provider).

This is training material, not a real client engagement. The fictional case materials, templates and evidence pack are the proprietary property of GRC Mastery and are not reproduced here, this write-up intentionally avoids restating the exact case details, scenario text or deliverable structure. What follows is my own account of the audit methodology I applied and the conclusions I reached, generalised enough to protect the course material while still reflecting the real work.

## What the exercise covered

The audit followed the ISO 19011 audit lifecycle across five phases:

**1. Plan the audit.** I was given a deliberately flawed draft audit plan and had to identify its weaknesses against ISO 19011 clause 6.3.2.2, among them incorrect audit criteria, no defined sampling method, an underused team member, no confidentiality arrangements, and an inappropriate approach to handling disagreement with the auditee. I then produced a corrected final audit plan: proper scope and criteria, a realistic schedule, a risk-based sampling method, clear team roles, and an escalation path.

**2. Lead the audit team.** I briefed the audit team, ran the opening meeting, and worked through two live scenarios: a threat to auditor objectivity (a team member with a prior working relationship to the auditee, reassigned immediately rather than just "monitored") and a situation where expected evidence simply wasn't available on request. Both scenarios tested the same underlying principle, that impartiality and evidentiary rigour are non-negotiable, not something to work around.

**3. Conduct the audit.** I built an audit checklist and a documented sampling plan for three sampled Annex A controls, conducted interviews, cross-checked every claim against documentary evidence rather than accepting it at face value, and recorded findings in ISO 19011 Annex A.18 format (conformities, nonconformities, opportunities for improvement). One early draft concern was deliberately withdrawn after the sampled evidence showed full conformity, a practical example of not treating a first suspicion as a finding until the evidence actually supports it.

**4. Report and close.** I prepared the final audit report, ran the closing meeting, and set up corrective-action tracking, without prescribing the auditee's corrective action itself, that decision belongs to the auditee, not the auditor. Classifying severity (minor vs. major nonconformity) came down to a consistent test: is this an isolated, evidenced gap with a compensating control in place, or a sign of a systemic breakdown?

**5. Professional behaviour and reflection.** I worked through five ethics scenarios (pressure to change a finding, a confidentiality breach, a conflict of interest, inappropriate conduct, a gift offer) and completed a self-evaluation against seven Lead Auditor competence areas, plus a written reflection on where I'd want to develop further as an auditor.

## Sampled scope

Three Annex A controls were sampled in depth, alongside ISO/IEC 27001:2022 Clauses 4 to 10:

- **A.8.3** Information access restriction
- **A.8.13** Information backup
- **A.7.14** Secure disposal or re-use of equipment

## Summary of my conclusions

| Ref | Area | Classification |
|---|---|---|
| C1 | A.8.3 Information access restriction | Conformity |
| C2 | A.8.13 Information backup | Conformity |
| N1 | A.7.14 Secure disposal or re-use of equipment | Minor Nonconformity |
| OFI1 | Supplier-security review scheduling | Opportunity for Improvement |
| OFI2 | Training-evidence dating | Opportunity for Improvement |

**Certification recommendation:** Recommend subject to corrective action.

**The reasoning behind N1:** the organisation's own risk documentation already flagged secure disposal as not fully implemented, and the sampled evidence confirmed it, a disposal procedure existed only in draft, with no approved version and no disposal/erasure records, although retired equipment was at least being held securely in the meantime. That combination, a real, evidenced gap with a compensating control and no sign of a systemic breakdown, is what separates a minor nonconformity from a major one under the certification-body criteria used in this exercise.

## Why this project

I completed this as part of my own professional development in GRC and cybersecurity governance, alongside the GRC Mastery ISO 27001 Lead Auditor coursework. It's a fictional exercise, not a claim of professional auditing experience. I'm documenting it here because the methodology, risk-based planning, evidence-based sampling, finding classification, and the ethical boundaries of the Lead Auditor role, is directly transferable to real GRC and IT Service Continuity work.

## Related work

- [ICT Resilience Framework: DORA & ISO/IEC 22301](https://github.com/Odera-aja/DORA-ISO27001-CryptoCustodian-ISMS)
- [NIST CSF Cybersecurity Assessment & 3-Year Roadmap](https://github.com/Odera-aja/nist-csf-cybersecurity-assessment)
