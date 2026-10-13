# ISO-42001-compliance-matrix
# ISO/IEC 42001 Compliance Control Matrix: Customer-Service Chatbot

An assessment of a customer-service chatbot against eight Annex A controls of ISO/IEC 42001 (AI management system standard).

> Completed as part of a Coursera governance and compliance course. The company and system are fictional.

## Problem
A company recently launched a public chatbot. How ready is it for an AI management system audit?

## What I did
- Reviewed the system profile and mapped it to eight controls: validation, data quality, accountability, data provenance, user information, AI disclosure, incident management, and intended use.
- Gave each control a status (Implemented, Partial, or Gap).
- Cited evidence for implemented controls and wrote actionable gap notes for the rest.

## Results

| Status | Controls |
|---|---|
| Implemented | 1 (A.4.2 Accountability) |
| Partial | 4 (A.2.2, A.2.6, A.5.4, A.6.2, A.7.1: see matrix) |
| Gap | 2 (A.4.3, A.5.2) |

## Key lesson
Most controls were only partly in place. The biggest risks were undocumented training data and no AI-specific incident process. Overstating status is a serious audit error, so I rated each control only on the evidence I could show.

## What I would add next
I would add AI-specific monitoring and alert rules to the incident process, based on my SOC experience.

## Files
- [ISO_42001_Compliance_Matrix.pdf](ISO_42001_Compliance_Matrix.pdf)
