# Healthcare AI Vendor Quick Screen

**A free resource from NyxTools by NyxTools**

Use this quick screen to evaluate an AI vendor in 15 minutes. It covers the non-negotiable requirements for any AI tool that will touch healthcare data. If a vendor fails the quick screen, there's no need for a full evaluation.

This is not a substitute for a comprehensive vendor evaluation — it's a filter to save you time on vendors that don't meet baseline requirements.

---

## How to Use This Quick Screen

1. Fill in the vendor information
2. Answer the 10 Pass/Fail gate questions
3. If the vendor passes all gates, score the 15 Quick Assessment criteria
4. Use the result to decide: full evaluation, conditional hold, or reject

**Time required:** 15 minutes with vendor documentation in hand.

---

## Vendor Information

| Field | Details |
|-------|---------|
| **Vendor Name** | |
| **Product/Platform** | |
| **Intended Use Case** | |
| **Will It Process PHI?** | Yes / No / Uncertain |
| **Requesting Department** | |
| **Screened By** | |
| **Date** | |

---

## Part 1: Pass/Fail Gates (All Must Pass)

These are non-negotiable. A "Fail" on any item means the vendor cannot be approved for healthcare use until the condition is resolved.

| # | Requirement | Pass | Fail | N/A | Evidence / Notes |
|---|------------|:----:|:----:|:---:|-----------------|
| G1 | **Will execute a BAA** (required if processing PHI) | | | | |
| G2 | **Does NOT use customer data for model training** (or provides contractual opt-out) | | | | |
| G3 | **Encrypts data at rest** (AES-256 or equivalent) | | | | |
| G4 | **Encrypts data in transit** (TLS 1.2+) | | | | |
| G5 | **Holds a current compliance certification** (SOC 2 Type II, HITRUST, or ISO 27001) | | | | |
| G6 | **Data processed and stored in the US** (or approved jurisdiction) | | | | |
| G7 | **Will notify of security incidents within 72 hours** | | | | |
| G8 | **Provides audit logging** of user access and actions | | | | |
| G9 | **Will disclose data handling practices** and provide security documentation upon request | | | | |
| G10 | **Has FDA clearance** (only if the tool is marketed for clinical diagnosis or treatment) | | | | |

### Gate Result

- **All Pass:** Proceed to Part 2.
- **Any Fail:** Stop. Vendor does not meet baseline healthcare requirements. Document the failure and notify the requesting department.
- **"Uncertain" on PHI question:** Treat as Yes until confirmed otherwise. If any data could contain patient information, the PHI requirements apply.

---

## Part 2: Quick Assessment (15 Criteria)

Score each criterion: **Strong** (3), **Adequate** (2), **Weak** (1), **Unknown** (0).

### Security and Compliance

| # | Criterion | 3 | 2 | 1 | 0 | Notes |
|---|----------|:-:|:-:|:-:|:-:|-------|
| Q1 | **Access controls** — RBAC, MFA, least-privilege model | | | | | |
| Q2 | **Penetration testing** — Annual third-party testing with remediation evidence | | | | | |
| Q3 | **Vulnerability management** — Documented program with remediation SLAs | | | | | |

### Data Handling

| # | Criterion | 3 | 2 | 1 | 0 | Notes |
|---|----------|:-:|:-:|:-:|:-:|-------|
| Q4 | **Data retention** — Clear retention periods with customer control and auto-deletion | | | | | |
| Q5 | **Data deletion** — Can delete all customer data on request with certification | | | | | |
| Q6 | **Data isolation** — Customer data logically or physically isolated from other tenants | | | | | |
| Q7 | **Subprocessor transparency** — Discloses all third parties with data access | | | | | |

### AI-Specific

| # | Criterion | 3 | 2 | 1 | 0 | Notes |
|---|----------|:-:|:-:|:-:|:-:|-------|
| Q8 | **Model transparency** — Documents architecture, training data sources, and limitations | | | | | |
| Q9 | **Bias and fairness testing** — Evidence of testing with published results | | | | | |
| Q10 | **Hallucination mitigation** — Documented strategies for reducing false outputs | | | | | |
| Q11 | **Accuracy validation** — Published metrics relevant to healthcare use cases | | | | | |

### Integration and Viability

| # | Criterion | 3 | 2 | 1 | 0 | Notes |
|---|----------|:-:|:-:|:-:|:-:|-------|
| Q12 | **Healthcare experience** — Track record serving healthcare organizations; references available | | | | | |
| Q13 | **EHR/interoperability** — Integration with your EHR; supports FHIR, HL7, or DICOM as applicable | | | | | |
| Q14 | **SSO integration** — Supports SAML, OIDC, or Active Directory | | | | | |
| Q15 | **Uptime SLA** — Published SLA with 99.9%+ commitment | | | | | |

---

## Quick Assessment Scoring

| Score Range | Result | Action |
|-------------|--------|--------|
| **38-45** | **Strong candidate** | Proceed to full vendor evaluation with high confidence |
| **25-37** | **Viable with gaps** | Proceed to full evaluation; flag weak areas for deeper review |
| **15-24** | **Significant concerns** | Request vendor remediation before investing in full evaluation |
| **Below 15** | **Not recommended** | Too many gaps for healthcare use; reject or revisit in 6 months |

**Your Score:** ___ / 45

---

## Quick Screen Result

| Field | Details |
|-------|---------|
| **Gate Result** | All Pass / Fail (specify which) |
| **Quick Assessment Score** | ___ / 45 |
| **Recommendation** | Proceed to Full Evaluation / Hold for Remediation / Reject |
| **Key Strengths** | |
| **Key Concerns** | |
| **Screened By** | |
| **Date** | |

---

## What Comes After the Quick Screen

This quick screen filters out vendors that don't meet baseline requirements. For vendors that pass, a comprehensive evaluation should cover:

- **Weighted scoring across 7 categories** (HIPAA compliance, security, data governance, AI model governance, integration, vendor viability, cost) with 45+ detailed criteria
- **Automatic disqualifiers** that trigger immediate rejection regardless of total score
- **Side-by-side vendor comparison tables** for evaluating multiple options
- **A vendor questionnaire** (25 questions) to send directly to the vendor
- **Formal recommendation documentation** for governance committee review

The **Healthcare AI Governance Kit** from NyxTools includes a complete AI Vendor Evaluation Scorecard with all of the above — plus 7 additional governance templates covering policy, HIPAA prompt safety, incident response, board presentation, training, and implementation.

Learn more: [NyxTools on Gumroad](https://nyxtools.gumroad.com)

---

*Copyright 2026 NyxTools. This quick screen is free to use and distribute with attribution.*
