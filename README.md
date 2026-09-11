# Sprinkling Act Zenodo Mirror

Index of Sprinkling Act academic publications: DOIs, cross-references to SSRN, and pointers to OpenTimestamps proofs. PDFs are hosted on Zenodo (the authoritative reference); this repository is a navigation index.

License: MIT (repository structure) · PDFs CC-BY 4.0 (per Zenodo metadata)

## 1. Published corpus

### 1.1 EU AI Act Readiness Report (parent)

- **Title**: EU AI Act Readiness Report — What We Found Screening 50 European AI Companies
- **Date**: April 2026
- **Pages**: 11
- **Zenodo concept DOI**: [10.5281/zenodo.19671328](https://doi.org/10.5281/zenodo.19671328) (resolves to the latest version)
- **Versions**: v1 [10.5281/zenodo.19671329](https://doi.org/10.5281/zenodo.19671329) · v2 [10.5281/zenodo.19820525](https://doi.org/10.5281/zenodo.19820525) deposited 27 April 2026
- **SSRN ID**: 6652418 (DISTRIBUTED)
- **Filename**: `eu-ai-act-readiness-report-april-2026.pdf`
- **OpenTimestamps proof**: see [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps)
- **Site landing**: [sprinklingact.com/reports/eu-ai-act-readiness-april-2026](https://sprinklingact.com/reports/eu-ai-act-readiness-april-2026)

**Headline findings**:
- 74% of 50 European AI companies trigger high-risk classification under Annex III
- 96% have no public AI Act position
- 0/14 companies with existing certifications (CE MDR, CE-IVD, ACPR banking) have mapped the AI Act layer

### 1.2 Annex A — The Deployer Multiplier

- **Title**: Annex A — The Deployer Multiplier (deployer cascade Art. 25 + 26 + 27)
- **Date**: May 2026 (v1.1 final)
- **Zenodo concept DOI**: [10.5281/zenodo.20042174](https://doi.org/10.5281/zenodo.20042174)
- **SSRN ID**: 6816018
- **Filename**: `eu-ai-act-readiness-report-annex-a-v1.1-final-may-2026.pdf`
- **OpenTimestamps proof**: see [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps)
- **Parent**: links to EU AI Act Readiness Report (April 2026) via Zenodo Related Works ("is supplement to")

### 1.3 Discussion Paper — Third Structural Pole

- **Title**: Discussion Paper — Third Structural Pole / Third Attractor
- **Date**: May 2026
- **Zenodo concept DOI**: [10.5281/zenodo.20343243](https://doi.org/10.5281/zenodo.20343243)
- **SSRN ID**: 6815659
- **Filename**: `eu-ai-act-third-attractor-may-2026.pdf`
- **OpenTimestamps proof**: see [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps)

## 2. Consolidated edition

**The Deployer Multiplier: Classification, Cascade, and the Third Structural Pole of the EU AI Act**
Eliva Press, 12 June 2026 · 82 pages · EN · ISBN 978-99993-4-609-2
[Publisher](https://www.elivapress.com/en/book/book-4559819695/) · [Amazon](https://www.amazon.com/dp/999934609X)

A print consolidation of the three papers above. It adds no new research. The open-access Zenodo versions remain the reference and the thing to cite: they are free, CC BY 4.0, versioned, and carry the colour figures that the print edition renders in greyscale.

## 3. What these papers say, and as of when

All three papers, and the April 2026 method card held in [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps), were written under the earlier positioning. They use its vocabulary: pre-conformity, position assessment, classification, readiness. That vocabulary was retired in August 2026, when the work moved from placing an AI system under the AI Act to measuring the distance between what an organisation declares about one workflow and what its own material establishes. The reasons are set out in [`methodology/TRANSITION.md`](https://github.com/sprinkling-act/methodology/blob/main/TRANSITION.md).

**None of these documents is being edited to match.** A timestamped deposit guarantees one thing, which is that this text existed on that date. Editing it to fit a later position destroys that guarantee and puts nothing in its place. The DOIs resolve, the OpenTimestamps proofs verify against the Bitcoin chain, and the papers say what was held in April and May 2026. Cite them as of their date.

What survives the change unaltered: the screening figures, the deployer cascade of Articles 25, 26 and 27, and the gate framework itself, which was moved downstream of the analysis rather than retired.

## 4. What is not published

Nothing has been deposited since May 2026. Earlier revisions of this file carried a table of upcoming publications with expected dates. Those dates passed without deposits, so the table has been removed rather than rolled forward. A publication appears here when it has a DOI, not before.

## 5. Repository topology

```
sprinkling-act/
├── timestamps/      # OpenTimestamps .ots proofs for published PDFs
├── zenodo-mirror/   # this repository, index of academic publications
├── methodology/     # Human in the Map v1.6 + the AI Act gate framework v1.3 + TRANSITION.md (MIT)
└── .github/         # org profile (verified domain sprinklingact.com)
```

Each repository has a single purpose. Cross-references between them are explicit in their READMEs.

## 6. Authoritative versus mirror

- **Zenodo record (DOI)** is the **authoritative reference**. Always cite the DOI, not the GitHub URL.
- **This repository** is a **redundancy mirror** for navigation. PDFs may be added here for convenience, but the canonical source is Zenodo.
- **OpenTimestamps proofs** ([sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps)) are the **cryptographic anchor**. The Bitcoin blockchain timestamp confirms the document existed at the claimed date.
- **SSRN** is an alternative academic indexing channel. Same content, different platform.
- **HAL** is not used. Two HAL identifiers were listed here until 11 September 2026; neither resolves, and the HAL API returns no record for them nor for the author. No HAL deposit exists. The line is removed rather than corrected, because a filing that never happened has nothing to correct.

## 7. Citation

When citing a Sprinkling Act publication, always use the Zenodo DOI:

```
Shucrani, L. B. (2026). EU AI Act Readiness Report — What We Found Screening 50 European AI Companies. 
Sprinkling Act. Zenodo. https://doi.org/10.5281/zenodo.19671328
```

For the suggested citation block of each individual publication, see the corresponding Zenodo record.

## 8. License

Repository structure: **MIT License**.

PDF content: **CC-BY 4.0** (Creative Commons Attribution 4.0 International), per Zenodo metadata. You may reproduce, distribute, and adapt these documents, including for commercial purposes, provided you credit Sprinkling Act and link back to the Zenodo DOI.

## 9. What this repository is NOT

- Not the authoritative source of PDFs. The Zenodo record is.
- Not the place to file substantive issues about publication content. Use the Sprinkling Act contact channels for that (see [sprinklingact.com/contact](https://sprinklingact.com/contact)).
- Not affiliated with Zenodo, the EU Commission, or any third party. Sprinkling Act is an independent analysis firm registered in Belgium (BCE BE 1034.962.482), not a notified body within the meaning of Regulation (EU) 2024/1689.

*Maintained by Sprinkling Act · Brussels, Belgium · [sprinklingact.com](https://sprinklingact.com)*
*ORCID Lamar B. Shucrani: [0009-0002-5093-8550](https://orcid.org/0009-0002-5093-8550)*
