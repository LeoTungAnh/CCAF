# AI in Healthcare (incl. Surgical Planning): Research Report

**Generated:** 2026-10-19

> **Coverage notice:** Surgical planning was explicitly requested but is **not substantively covered**. The restricted-access source timed out, so only a one-line excerpt is available. Only 2 of 6 sources were analyzed in full.

---

## Executive Summary
Peer-reviewed evidence shows AI-assisted radiology improves accuracy (94.2% vs 87.5%) and cuts reading time by 50%. A JAMA review found racial performance disparities in 9 of 15 commercial clinical decision support (CDS) systems. No conclusions on surgical planning are possible.

## Key Findings

### Radiology accuracy — *document-verified, peer-reviewed*
- RCT across 15 hospitals and 12,847 patients (chest X-rays).
- AI-assisted accuracy was 94.2% (95% CI 93.1–95.3), radiologists alone 87.5% (95% CI 86.0–89.0), and AI alone 91.8%.
- Reading time fell from 4.2 to 2.1 minutes. The largest gains were in early pneumonia and subtle fractures.
- Limitations: only one commercial system was tested (RadAssist v3.2), and the training data's demographics were never independently audited.
- Source: Chen, Torres, Patel — "AI Diagnostic Systems Show 94% Accuracy in Radiology," *Journal of Medical AI*, 2024-09-15. https://journal-medical-ai.example.com/diagnostics-2024

### Bias in clinical decision support — *document-verified, peer-reviewed*
- 9 of 15 (60%) commercial CDS systems showed significant racial performance disparities.
- A dermatology AI was 31% less accurate for darker skin tones. It is unclear whether this is a relative or absolute figure.
- 4 systems had a gap of more than 10% between their best- and worst-served groups.
- Only 3 of 15 vendors reported demographic breakdowns.
- Hospitals using biased systems were 2.3x more likely to have unequal outcomes. This is an association, not proof of causation.
- Recommendations: mandatory demographic performance reporting, independent equity audits before deployment, minimum performance thresholds for every group, and monitoring after deployment.
- Source: Rodriguez, Washington, Sharma — "Ethical Concerns About AI Bias in Clinical Decision Support," *JAMA*, 2025-02-14. https://jama.example.com/ai-bias-clinical-2025

### Drug discovery — *excerpt-only, peer-reviewed*
- ML screening cut drug candidate identification time from 4.5 to 2.7 years (40%).
- Source: "Machine Learning Accelerates Drug Discovery by 40%," *Nature Biotechnology*, 2025-01-22. https://nature-biotech.example.com/drug-discovery-ml-2025

### Remote monitoring and economics — *excerpt-only, trade press, not peer-reviewed*
- A study of 2,400 patients at 8 hospitals reported 23% fewer 30-day readmissions and an estimated $4.2M saved per hospital per year.
- Source: "Remote Patient Monitoring with AI Reduces Hospital Readmissions," *Healthcare IT News*, 2025-03-08. https://healthcare-it.example.com/rpm-ai-2025

### Mental health screening — *excerpt-only, peer-reviewed*
- NLP screening of intake forms detected depression with 89% sensitivity and could cut screening time by an estimated 60%.
- Source: "AI-Powered Mental Health Screening Tools Show Promise," *Lancet Digital Health*, 2024-11-30. https://lancet-digital.example.com/mental-health-ai-2024

### Surgical planning — *excerpt-only, unverified*
- The excerpt describes a meta-analysis of 47 studies covering orthopedic, cardiac and neurological procedures. No findings, figures, methods or limitations are available.
- Source: "Comprehensive Review of AI in Surgical Planning," *International Journal of Surgical AI* (Restricted Access), 2025-03-01. https://restricted-journal.example.com/ai-surgical-planning-2025

## Contested or Uncertain Findings
- **Radiology sample size:** The search excerpt said "12,000 chest X-rays," but the full text reports 12,847 patients at 15 hospitals. This report uses the full-text figures.
- **Generalizability:** The JAMA bias findings cast doubt on generalizing the radiology accuracy results, because that study's training data was never audited. The two studies cover different domains, so they are not directly comparable.

## Limitations
- Only 2 of 6 sources were analyzed in full.
- The JAMA authors state no limitations. The analyst noted a small, US-only sample with unstated methods.
- The $4.2M savings figure comes from an unverified trade publication.

## Coverage Gaps
- **Surgical planning:** Excerpt only, and no other source was analyzed. Coverage is insufficient.
- **Drug discovery, economics and mental health:** Excerpt only, so coverage is partial.
- **Regulation:** No sources were found.
- **Implementation costs:** No data was found.
- **Counterarguments:** Only the bias source offers a critical view.

## Errors
| Field | Value |
|---|---|
| failure_type | timeout |
| attempted_url | https://restricted-journal.example.com/ai-surgical-planning-2025 |
| title | Comprehensive Review of AI in Surgical Planning |
| publication / date | International Journal of Surgical AI (Restricted Access), 2025-03-01 |
| partial_results | One-sentence excerpt only |
| alternatives | Retry the fetch (access restrictions may still block it), or find open-access surgical-planning sources |

## Sources
1. Journal of Medical AI, 2024-09-15 — https://journal-medical-ai.example.com/diagnostics-2024
2. International Journal of Surgical AI, 2025-03-01 — https://restricted-journal.example.com/ai-surgical-planning-2025 *(fetch failed)*
3. Nature Biotechnology, 2025-01-22 — https://nature-biotech.example.com/drug-discovery-ml-2025
4. JAMA, 2025-02-14 — https://jama.example.com/ai-bias-clinical-2025
5. Healthcare IT News, 2025-03-08 — https://healthcare-it.example.com/rpm-ai-2025
6. Lancet Digital Health, 2024-11-30 — https://lancet-digital.example.com/mental-health-ai-2024
