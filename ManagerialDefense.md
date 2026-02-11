# MANAGERIAL DEFENSE: LegalGuardian AI

**TO:** Board of Directors, Bank CenterCredit  
**FROM:** Head of Cloud Transformation  
**DATE:** February 12, 2026  
**SUBJECT:** Go/No-Go Recommendation — AI Contract Review Agent

---

## 1. FINANCIAL ANALYSIS (ROI)

**Baseline (Current State):**
- Senior Legal Counsel monthly salary: **750,000 KZT**
- Working hours per month: 160
- Hourly cost: **4,688 KZT**
- Time to review one IT procurement contract: **4 hours**
- Contracts reviewed per week (per lawyer): **6**
- Weekly legal cost per lawyer: **112,512 KZT** (4h × 4,688 × 6)

**With LegalGuardian AI:**
- Time to review one contract: **30 minutes (0.5 hour)**
- Weekly legal cost per lawyer: **14,064 KZT** (0.5h × 4,688 × 6)

**Weekly savings per lawyer:** **98,448 KZT**
**Annual savings per lawyer (48 weeks):** **4,725,504 KZT**

**AI Operational Costs:**
- Tokens per contract (40 pages): 80,000
- Cost per 1M tokens (Claude/GPT-4): $3 ≈ 1,500 KZT
- Cost per contract: 120 KZT
- Annual contracts per lawyer: 288
- Annual AI cost per lawyer: **34,560 KZT**

**Net Annual Savings per Lawyer:**
**4,725,504 KZT − 34,560 KZT = 4,690,944 KZT**

**Scale:**
- Legal team (IT procurement): 10 lawyers → **46.9M KZT/year**
- Full Legal & Compliance: 20 lawyers → **93.8M KZT/year**

**Payback Period:** < 1 month
**Year 1 ROI:** **> 2,000%**

---

## 2. GOVERNANCE & COMPLIANCE (Kazakhstan AI Ethics Test)

### 2.1 Data Residency & Banking Secrecy

**Risk:**
IT procurement contracts contain:
- Personal data of counterparties (IIN, beneficiary information)
- Banking secrecy (Article 50, Law "On Banks")
- Commercial terms and pricing

**Legal Requirements:**
- **Article 25-1, Law "On Informatization":** Personal data must be stored on servers physically located in Kazakhstan.
- **Article 51, Law "On Banks":** Transfer of banking secrecy to third parties requires client consent. Foreign cloud providers are not automatically compliant.

**Mitigation:**
- On-premise deployment only
- No public cloud APIs (OpenAI, Anthropic, AWS, Google Cloud)
- Licensed Kazakhstan-based data centers (Transtelecom, Kazakhtelecom, IDC)

**Verdict:** **Compliant with conditions**

---

### 2.2 Liability & Legal Responsibility

**Risk:**
- AI hallucination: false positive (wastes time) or false negative (bank signs bad contract)
- Under Kazakhstan Civil Code, **Article 946**: liability for harm caused by a source of increased danger
- No current jurisprudence classifying AI as "source of increased danger," but ambiguity favors the bank to assume liability

**Mitigation:**
- **Human-in-the-loop:** AI recommends, lawyer decides. No automated decision-making.
- **Full audit trail:** Every AI interaction logged with:
  - User ID
  - Timestamp
  - Document hash
  - Clause extracted
  - User override/edit history
- **Explainable AI:** Every flag includes citation to specific law (e.g., "Article 51, Law On Banks") or internal BCC policy

**Verdict:** **Compliant**

---

### 2.3 Language Accessibility

**Requirement:**
Law "On Languages" — banking documentation and official workflows must support Kazakh and Russian.

**Mitigation:**
- Interface: English, Russian, Kazakh (user-selectable)
- Explanations: Russian (primary), Kazakh (secondary)
- Clause extraction: Russian, English

**Verdict:** **Compliant**

---

### 2.4 Regulatory Alignment (ARDFM)

**Requirement:**
Agency for Regulation and Development of the Financial Market (ARDFM) expects banks to maintain adequate controls over outsourced IT services.

**Mitigation:**
- LegalGuardian does not replace legal review — it augments it
- Audit trail satisfies ARDFM requirements for "verifiability of decision-making"
- Quarterly validation audits will be submitted to Internal Audit and Risk Committee

**Verdict:** **Compliant**

---

## 3. STRATEGIC ALIGNMENT

| BCC Strategic Priority | How LegalGuardian Delivers |
|------------------------|----------------------------|
| Digital Transformation | First enterprise AI tool deployed on-premise, proving BCC can innovate safely |
| Risk Management | Reduces probability of missing non-compliant clauses in vendor contracts |
| Cost Efficiency | 4.69M KZT annual savings per lawyer, payback <1 month |
| BCC-HUB Integration | Pilot can be co-developed with BCC-HUB, transforming them from "vendor" to "product team" |

---

## 4. RECOMMENDATION

**GO / NO-GO: GO**

**Approve a 6-month pilot with the following parameters:**

| Parameter | Value |
|----------|-------|
| **Users** | 5 Senior Legal Counsels, IT Procurement team |
| **Budget** | 15,000,000 KZT (development + on-premise infrastructure) |
| **Timeline** | March – August 2026 |
| **Success Criteria** | • 70% reduction in contract review time<br>• 95% user satisfaction (≥4/5)<br>• Zero data residency violations<br>• 100% audit trail capture |

**Post-Pilot:**
If success criteria met, full rollout to 20+ Legal users in Q4 2026.

---

**Respectfully submitted,**

Yedil Niyazbekov

Head of Cloud Transformation

Bank CenterCredit

**Date:** February 12, 2026
