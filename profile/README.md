# IsoMatrix

---
> *Learning the polyadenylation grammar of life — and where cancer and autoimmunity breaks the rules.*

**IsoDecipher** is the foundational open-source entry point to the broader **IsoMatrix Suite** — a comprehensive ecosystem for single-cell 3' end biology. While IsoDecipher sets the standard for GTF-anchored quantification, the complete ecosystem extends into unannotated peak discovery, sequence filtering, and machine learning-driven target classification.

| Tool | Description | Status | License |
|------|-------------|--------|---------|
| [IsoDecipher](https://github.com/iso-apa/IsoDecipher) | APA quantification from 3' scRNA-seq BAMs — GTF-anchored, scanpy-ready | ✅ Active | AGPLv3 |
| [IsoCAPE](https://github.com/iso-apa/IsoCAPE) | Unannotated polyadenylation site detector — PAS-verified CE, Alu-driven CE, and PA sites beyond GTF boundaries | 🔒 Closed-Source | Commercial |
| [IsoPrime](https://github.com/iso-apa/IsoPrime) | Internal priming probability scorer for IsoCAPE CE sites — genomic context + PAS model | 🔒 Closed-Source | Commercial |
| [IsoScore](https://github.com/iso-apa/IsoScore) | ML-driven biological significance classifier (peak features, KL Divergence ...) | 🔒 Closed-Source | Commercial |
| [IsoFormer](https://github.com/iso-apa/IsoFormer) | Foundation model for polyadenylation grammar at single-cell resolution | 🔒 Closed-Source | Commercial |

---

### 🧬 Why an isopod?

The logo was found by my daughter on a walk — a real isopod.

The biology fits perfectly:

- **Iso** — isoform, the thing we study
- **The curl** — cancer's self-defense mechanism: immune evasion, drug resistance, isoform switching to survive
- **Segmented body** — multiple isoforms of the same gene, each segment a different version
- **The spiral** — the trajectory from normal differentiation to malignancy

Sometimes the best logos find you.

---

### ⚖️ Licensing & Commercial Use

The IsoMatrix ecosystem operates on an **Open-Core** model — balancing an accessible, reproducible foundation with advanced proprietary analytics for enterprise discovery.

#### 1. Open-Source Quantification (AGPLv3)

**IsoDecipher** is fully open-source under the [GNU AGPLv3 License](https://github.com/iso-apa/IsoDecipher/blob/main/LICENSE).

Under AGPLv3, you are free to use, modify, and distribute IsoDecipher for any purpose — including academic research and non-profit projects — provided that any modifications or derivative works are also released under AGPLv3.

**A commercial license is required if you:**
- Integrate IsoDecipher into a proprietary or closed-source pipeline without open-sourcing your modifications
- Use IsoDecipher as part of a SaaS, cloud, or hosted service offering
- Use IsoDecipher within a for-profit organization for commercial R&D, biomarker discovery, or clinical reporting purposes
- Seek access to proprietary IsoMatrix components (see below)

#### 2. Proprietary Discovery Engine (Commercial Only)

Our advanced suite for unannotated peak discovery, sequence filtering, machine learning classification, and foundation model inference is **strictly proprietary and closed-source**. This includes:

- **IsoCAPE** — Unannotated polyadenylation site detector (CE, Alu-driven, and intergenic events)
- **IsoPrime** — Internal priming sequence artifact filter
- **IsoScore** — ML-driven biological significance classifier (FWHM, Skewness, KL Divergence)
- **IsoFormer** — Foundation model for single-cell polyadenylation grammar
- **Disease-specific panel tracks** — Pre-built, validated cancer and disease-specific cleavage site panels (myeloma, prostate cancer, breast cancer, and others), updated continuously via the IsoCAPE discovery pipeline

#### 3. Enterprise & Commercial Licensing

Pharmaceutical companies, clinical diagnostic labs, and biotech organizations seeking to use the full IsoMatrix Suite for novel biomarker discovery, immune evasion target validation, or clinical reporting must obtain a **Commercial License**.

A commercial license provides:
- Legal permission for proprietary and commercial use of IsoDecipher
- Access to IsoCAPE, IsoPrime, IsoScore, and IsoFormer
- Access to pre-built and continuously-updated disease-specific panel tracks
- On-premise Docker deployment (HIPAA-compliant, no data egress required)
- Dedicated bioinformatics consulting and technical support
- Priority access to new panel updates and model releases

**Contact:** [rene271828@gmail.com](mailto:rene271828@gmail.com)

---

*Built by Rene Yu-Hong Cheng | IsoMatrix Suite*
