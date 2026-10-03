# Trustworthy Medication Recommendation: A Safety-Centered Survey of Knowledge-Grounded and LLM-Assisted Methods

This repository accompanies our survey and provides supporting materials, study registers, and LaTeX sources.

## Overview

The updated survey synthesizes **60 eligible medication recommendation studies published in 2022–2026**, covering structured neural models, graph learning, multimodal approaches, offline reinforcement learning, and LLM/RAG methods.

The taxonomy examines patient information, model architectures, knowledge integration, evaluation, safety, and deployment considerations. Categories overlap.

## Study Selection

The original database-search cutoff was **20 May 2026**. A targeted revision update was completed on **3 October 2026**.

| Stage | Count |
| :--- | ---: |
| Records identified in the original formal search | 132 |
| Duplicates removed | 39 |
| Records screened | 93 |
| Original roster entries | 56 |
| Diagnosis-only MetaCare++ excluded during revision | 1 |
| Eligible original studies retained | 55 |
| Full-text studies added during revision | 5 |
| **Updated included studies** | **60** |

The five additions are **RPNet, MetaDrug, HypeMed, GenRxR**, and **safety-aware offline RL for nephrotoxic medication management**. The targeted update does not represent an exhaustive database-search rerun.

Foundational pre-2022 studies and contextual citations are excluded from the 60-study count.

## Repository Contents

| File | Description |
| :--- | :--- |
| `updated_study_register.csv` | Updated register of all 60 included studies |
| `appraisal_subset_47.csv` | Available ordinal appraisal for 47 included studies |
| `revision_evidence_extraction.csv` | Evidence extraction for the five additions |
| `supplementary_revision_addendum.tex` | Updated supplementary documentation |
| `manuscript.tex` | Manuscript with important revisions highlighted |
| `manuscript-clean.tex` | Clean manuscript compilation entry point |
| `cas-refs.bib` | External bibliography |

The project includes required figures and Elsevier style files. Original search and screening documentation should be read alongside the revised register. Standalone PRISMA and taxonomy files should match the updated manuscript.

## Evidence Coverage

Appraisal ratings are available for **47 of 60 studies**. Full-corpus counts for individual safety endpoints require further extraction. Benchmark DDI rates and prescription agreement should be distinguished from demonstrated clinical safety.

## Data Availability

No new primary clinical dataset was created or analyzed. Reviewed studies use public and private datasets, including MIMIC-III, MIMIC-IV, eICU, and MIMIC-CXR. Access and licensing conditions are determined by the original providers. Patient-level data are not distributed here.

## Citation

```bibtex
@misc{hussain2026trustworthy,
  title={Trustworthy Medication Recommendation: A Safety-Centered Survey of Knowledge-Grounded and LLM-Assisted Methods},
  author={Hussain, Sumaira and Ali, Zafar and Ullah, Imran and Ullah, Irfan and Ullah, Inam and Thierry, Nimbeshaho and Kefalas, Pavlos},
  year={2026},
  note={Manuscript under review; revised 3 October 2026}
}
```
