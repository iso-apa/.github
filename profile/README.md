## IsoMatrix

---
Learning the polyadenylation grammar of life — and where cancer and autoimmunity breaks the rules.

IsoDecipher is the open-source entry point to IsoMatrix, a dual-licensed ecosystem for single-cell 3' end biology. While IsoDecipher serves as the industry standard for GTF-anchored quantification, our advanced discovery engines for unannotated peak detection and machine learning classification are available under a commercial license for enterprise use.

| Tool | Description | Status |
|------|-------------|--------|
| [IsoDecipher](https://github.com/iso-apa/IsoDecipher) | APA quantification from 3' scRNA-seq BAMs — GTF-anchored, scanpy-ready | ✅ Active |
| [IsoCAPE](https://github.com/iso-apa/IsoCAPE) | Unannotated polyadenylation site detector — PAS-verified CE, Alu-driven CE, and PA sites beyond GTF boundaries | 🔒 Closed-Source |
| [IsoPrime](https://github.com/iso-apa/IsoPrime) | Internal priming probability scorer for IsoCAPE CE sites — genomic context + PAS model | 🔒 Closed-Source|
| [IsoScore](https://github.com/iso-apa/IsoScore) | ML-driven biological significance classifier (peak features, KL Divergence ...) | 🔒 Closed-Source |
| [IsoFormer](https://github.com/iso-apa/IsoFormer) | Foundation model for polyadenylation grammar at single-cell resolution | 🔒 Closed-Source |

---

### Why an isopod?

The logo was found by my daughter on a walk — a real isopod.

The biology fits perfectly:

- **Iso** — isoform, the thing we study
- **The curl** — cancer's self-defense mechanism: immune evasion, drug resistance, isoform switching to survive
- **Segmented body** — multiple isoforms of the same gene, each segment a different version
- **The spiral** — the trajectory from normal differentiation to malignancy

Sometimes the best logos find you.

---
## ⚖️ Licensing & Commercial Use

The IsoMatrix ecosystem operates on a highly focused **Open-Core** model, balancing accessible foundational tools with advanced, proprietary analytics for enterprise discovery.

**1. Open-Source Quantification (AGPLv3)**
Our foundational pipeline for GTF-anchored single-cell APA quantification, **IsoDecipher**, is fully open-source under the AGPLv3 License. It is free to use, modify, and distribute for academic research and non-profit projects, serving as the industry standard for known isoform resolution.

**2. Proprietary Discovery Engine (Commercial Only)**
Our advanced suite for unannotated peak discovery, sequence filtering, and machine learning classification is **strictly proprietary and closed-source**. This includes:
* **IsoCAPE:** Unannotated polyadenylation site detector (CE, Alu-driven, and intergenic events).
* **IsoPrime:** Internal priming sequence artifact filter.
* **IsoScore:** ML-driven biological significance classifier (FWHM, Skewness, KL Divergence).
* **IsoFormer:** Foundation model for single-cell polyadenylation grammar.

**For For-Profit & Enterprise Users:**
Pharmaceutical companies, clinical diagnostic labs, and biotech startups seeking to leverage the full suite of IsoMatrix for novel biomarker discovery, immune evasion target validation, or clinical reporting must obtain a **Commercial License**. 

A commercial license grants access to our proprietary discovery engines, legal permission for SaaS integration, and dedicated bioinformatics consulting. 

Please contact the author for SaaS access, biomarker partnerships, and enterprise licensing.

Built by Rene Yu-Hong Cheng | IsoMatrix Suite
