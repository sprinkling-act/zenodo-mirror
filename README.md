# Sprinkling Act — Zenodo Mirror

> **Index of all Sprinkling Act academic publications** with DOIs, cross-references to SSRN and HAL, and pointers to OpenTimestamps cryptographic proofs.
>
> This repository is the **navigation hub** to the Sprinkling Act corpus. PDFs themselves are hosted on Zenodo (the authoritative reference) and mirrored to dedicated repositories.

**License**: MIT (for repository structure) · PDFs are CC-BY 4.0 (per Zenodo metadata)

---

## 1. Published corpus

### 1.1 EU AI Act Readiness Report (parent)

- **Title**: EU AI Act Readiness Report — What We Found Screening 50 European AI Companies
- **Date**: April 2026
- **Pages**: 11
- **Zenodo concept DOI**: [10.5281/zenodo.19671328](https://doi.org/10.5281/zenodo.19671328)
- **SSRN ID**: 6652418 (DISTRIBUTED)
- **HAL ID**: hal-05631107
- **Filename**: `eu-ai-act-readiness-report-april-2026.pdf`
- **OpenTimestamps proof**: see [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps)
- **Site landing**: [sprinklingact.com/reports/eu-ai-act-readiness-report](https://sprinklingact.com/reports/eu-ai-act-readiness-report)

**Headline findings**:
- 74% of 50 European AI companies trigger high-risk classification under Annex III
- 96% have no public AI Act position
- 0/14 companies with existing certifications (CE MDR, CE-IVD, ACPR banking) have mapped the AI Act layer

### 1.2 Annex A — The Deployer Multiplier

- **Title**: Annex A — The Deployer Multiplier (deployer cascade Art. 25 + 26 + 27)
- **Date**: May 2026 (v1.1 final)
- **Zenodo concept DOI**: [10.5281/zenodo.20042174](https://doi.org/10.5281/zenodo.20042174)
- **SSRN ID**: 6816018
- **HAL ID**: hal-05631110
- **Filename**: `eu-ai-act-readiness-report-annex-a-v1.1-final-may-2026.pdf`
- **OpenTimestamps proof**: see [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps)
- **Parent**: links to EU AI Act Readiness Report (April 2026) via Zenodo Related Works ("is supplement to")

### 1.3 Discussion Paper — Third Structural Pole

- **Title**: Discussion Paper — Third Structural Pole / Third Attractor
- **Date**: May 2026
- **Zenodo concept DOI**: [10.5281/zenodo.20343243](https://doi.org/10.5281/zenodo.20343243)
- **SSRN ID**: 6815659
- **HAL ID**: _filing in progress_
- **Filename**: `eu-ai-act-third-attractor-may-2026.pdf`
- **OpenTimestamps proof**: see [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps)

---

## 2. Upcoming publications (pipeline)

| Document | Type | Expected | Status |
|---|---|---|---|
| Note of Correction — Readiness Report v1.1 | NoC | May/June 2026 | 🟡 FINAL DRAFT v0.3 ready |
| Sprinkling Act — What We Are Not (A5) | Institutional position | May/June 2026 | 🟡 DRAFT v0.2 ready |
| Note of Correction — Annex A v1.1 | NoC | June 2026 | ⚪ Planned |
| Sprinkling Act Self-Assessment Full Report 2026 (B1) | Application of own methodology to SA | Q3 2026 | ⚪ Planned (40-60h focus) |
| Bloc 1bis institutional PDFs (A6, A7, A8, A9, A10, A11, A12, A13) | Various | Q3-Q4 2026 | ⚪ Planned |
| Cross-Jurisdiction Comparison v1.0 | Zenodo paper | Post-first client | ⚪ Planned |

---

## 3. Repository topology

```
sprinkling-act/
├── timestamps/              # OpenTimestamps .ots proofs for all published PDFs
├── zenodo-mirror/           # this repository — index of academic publications
├── methodology/             # 6-gate framework v1.3 (open-source MIT)
├── institutional-pdfs/      # Bloc 1bis position statements + Notes of Correction
├── acts-for-ai-agents/      # 4 ACTS framework (4 system prompts for AI agents)
└── .github/                 # org profile (verified domain sprinklingact.com)
```

Each repository has a single purpose. Cross-references between them are explicit in their READMEs.

---

## 4. Authoritative versus mirror

- **Zenodo record (DOI)** is the **authoritative reference**. Always cite the DOI, not the GitHub URL.
- **This repository** is a **redundancy mirror** for navigation. PDFs may be added here for convenience, but the canonical source is Zenodo.
- **OpenTimestamps proofs** ([sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps)) are the **cryptographic anchor**. The Bitcoin blockchain timestamp confirms the document existed at the claimed date.
- **SSRN and HAL** are alternative academic indexing channels. Same content, different platform.

---

## 5. Citation

When citing a Sprinkling Act publication, always use the Zenodo DOI:

```
Shucrani, L. B. (2026). EU AI Act Readiness Report — What We Found Screening 50 European AI Companies. 
Sprinkling Act. Zenodo. https://doi.org/10.5281/zenodo.19671328
```

For the suggested citation block of each individual publication, see the corresponding Zenodo record.

---

## 6. License

Repository structure: **MIT License**.

PDF content: **CC-BY 4.0** (Creative Commons Attribution 4.0 International), per Zenodo metadata. You may reproduce, distribute, and adapt these documents, including for commercial purposes, provided you credit Sprinkling Act and link back to the Zenodo DOI.

---

## 7. What this repository is NOT

- Not the authoritative source of PDFs. The Zenodo record is.
- Not the place to file substantive issues about publication content. Use the Sprinkling Act contact channels for that (see [sprinklingact.com/contact](https://sprinklingact.com/contact)).
- Not affiliated with Zenodo, the EU Commission, or any third party. Sprinkling Act is a private independent assessment authority registered in Belgium (BCE BE 1034.962.482), not a notified body within the meaning of Regulation (EU) 2024/1689.

---

*Maintained by Sprinkling Act · Brussels, Belgium · [sprinklingact.com](https://sprinklingact.com)*
*ORCID Lamar B. Shucrani: [0009-0002-5093-8550](https://orcid.org/0009-0002-5093-8550)*
