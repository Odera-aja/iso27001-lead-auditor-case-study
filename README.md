# ISO/IEC 27001:2022 Lead Auditor Case Study: SafeStore Pty Ltd (Stage 2 Certification Audit Simulation)

## About this project

This repository documents my own work completing the practical capstone of the **GRC Mastery ISO 27001 Lead Auditor training**: a simulated Stage 2 (initial certification) audit against ISO/IEC 27001:2022, acting as Lead Auditor for a fictional organisation, "SafeStore Pty Ltd" (a fictional cloud-storage provider).

This is training material, not a real client engagement. The fictional case materials, templates and evidence pack belong to GRC Mastery and are not reproduced here. What follows is my own write-up of the audit methodology I applied and the conclusions I reached, based on that case.

## What the exercise covered

The audit followed the ISO 19011 audit lifecycle across five phases:

1. **Plan the audit**: reviewed a deliberately flawed draft audit plan, identified its weaknesses against ISO 19011 clause 6.3.2.2 (incorrect audit criteria, no defined sampling method, an idle team member, no confidentiality arrangements, an inappropriate approach to disagreements), and produced a corrected final audit plan.
2. **Lead the audit team**: briefed the team, ran the opening meeting, and worked through two live scenarios, a threat to auditor objectivity (a team member who previously worked for the auditee) and unavailable evidence.
3. **Conduct the audit**: built an audit checklist and sampling plan for three sampled Annex A controls, interviewed stakeholders, verified evidence, and recorded findings in ISO 19011 Annex A.18 format (conformities, nonconformities, opportunities for improvement).
4. **Report and close**: prepared the final audit report, ran the closing meeting, and set up corrective-action follow-up, without prescribing the auditee's corrective action, which is the auditee's own responsibility, not the auditor's.
5. **Professional behaviour and reflection**: worked through five ethics scenarios (pressure to change a finding, a confidentiality breach, a conflict of interest, inappropriate conduct, a gift offer) and completed a self-evaluation against seven Lead Auditor competence areas.

## Sampled scope

Three Annex A controls were sampled in depth, alongside ISO/IEC 27001:2022 Clauses 4 to 10:

- **A.8.3**: Information access restriction
- **A.8.13**: Information backup
- **A.7.14**: Secure disposal or re-use of equipment

## Summary of my conclusions

| Ref | Area | Classification |
|---|---|---|
| C1 | A.8.3 Information access restriction | Conformity |
| C2 | A.8.13 Information backup | Conformity |
| N1 | A.7.14 Secure disposal or re-use of equipment | Minor Nonconformity |
| OFI1 | Supplier-security review scheduling | Opportunity for Improvement |
| OFI2 | Training-evidence dating | Opportunity for Improvement |

**Certification recommendation: Recommend subject to corrective action.**

The reasoning behind N1: SafeStore's own Statement of Applicability and risk register already flagged A.7.14 (secure disposal) as "not fully implemented," and the evidence confirmed it. A secure-disposal procedure existed only in draft, with no approved procedure and no disposal/erasure records, although retired equipment was at least being held securely in the meantime. That combination, a real, evidenced gap, but with a compensating control and no sign of a systemic breakdown, is what separates a *minor* nonconformity from a *major* one under the certification-body criteria used in this exercise.

One early draft concern (an access-control account flagged for review) was **withdrawn** after the sampled evidence showed it fully conformed to policy, a deliberate example of not treating a first suspicion as a finding until the evidence actually supports it.

## Why this project

I completed this as part of my own professional development in GRC and cybersecurity governance, alongside the GRC Mastery ISO 27001 Lead Auditor coursework. It's a fictional exercise, not a claim of professional auditing experience. I'm documenting it here because the methodology (risk-based planning, evidence-based sampling, finding classification, and the ethical boundaries of the Lead Auditor role) is directly transferable to real GRC and IT Service Continuity work.

## Related work

- [ICT Resilience Framework: DORA & ISO/IEC 22301](https://github.com/Odera-aja/ICT-Resilience-DORA-BCM-CaseStudy)
- [NIST CSF Cybersecurity Assessment & 3-Year Roadmap](https://github.com/Odera-aja/nist-csf-cybersecurity-assessment)
