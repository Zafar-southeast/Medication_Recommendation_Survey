# Trustworthy Medication Recommendation: A Safety-Centered Survey of Knowledge-Grounded and LLM-Assisted Methods

This repository accompanies our survey and provides supporting materials, study registers, quality assessments, safety-evaluation records, and LaTeX sources.

## Overview

The survey synthesizes **60 eligible medication recommendation studies (2022–2026)**, covering structured neural models, graph learning, multimodal approaches, offline reinforcement learning, and LLM/RAG-assisted methods.

The taxonomy examines patient information, model architectures, knowledge integration, safety, evaluation, and deployment. Categories are non-mutually exclusive.

## Study Selection

The original database-search cutoff was **20 May 2026**, followed by a targeted revision update completed on **3 October 2026**.

| Stage | Count |
| :--- | ---: |
| Records identified | 132 |
| Duplicates removed | 39 |
| Records screened | 93 |
| Title/abstract exclusions | 37 |
| Original study roster | 56 |
| Diagnosis-only MetaCare++ excluded | 1 |
| Eligible original studies retained | 55 |
| Full-text studies added during revision | 5 |
| **Total included studies** | **60** |

The five additions are **RPNet, MetaDrug, HypeMed, GenRxR**, and **safety-aware offline RL for nephrotoxic medication management**.

The targeted update was not an exhaustive database-search rerun. Pre-2022 foundational studies and contextual references are excluded from the 60-study count.

## Repository Contents

| File | Description |
| :--- | :--- |
| `updated_study_register.csv` | Register of 60 eligible studies |
| `appraisal_60.csv` | Descriptive quality appraisal of all 60 studies |
| `revision_evidence_extraction.csv` | Evidence extraction for revision additions |
| `supplementary_revision_addendum.tex` | Revised supplementary documentation and evidence audit |
| `manuscript.tex` | Revised manuscript with highlighted changes |
| `manuscript-clean.tex` | Clean manuscript |
| `cas-refs.bib` | Bibliography |

The repository also includes relevant figures, Elsevier style files, and original screening documentation.

## Quality Assessment and Safety Evidence

All **60 studies** are covered by the seven-criterion descriptive appraisal, comprising 47 original-roster ratings and 13 newly assigned ratings pending final author cross-check.

The endpoint-level evidence audit confirmed:

| Evaluation dimension | Studies |
| :--- | ---: |
| Predictive performance | 58 |
| Drug–drug interaction (DDI) evaluation | 33 |
| External institutional validation | 30 |
| Robustness/subgroup testing | 14 |
| Contraindication violations | 1 |
| Probability calibration | 1 |
| Grounding/hallucination evaluation | 1 |

Endpoint verification remains incomplete; these figures represent confirmed evaluations rather than definitive absence of evaluation in other studies.

Benchmark DDI rates and prescription agreement should not be interpreted as demonstrated clinical safety.

## Data Availability

No new primary clinical dataset was generated or analyzed. Reviewed studies use public and private clinical datasets, including MIMIC-III, MIMIC-IV, and eICU. Access is governed by the original data providers. No patient-level data are distributed.

## Citation

```bibtex
@misc{hussain2026trustworthy,
  title={Trustworthy Medication Recommendation: A Safety-Centered Survey of Knowledge-Grounded and LLM-Assisted Methods},
  author={Hussain, Sumaira and Ali, Zafar and Ullah, Imran and Ullah, Irfan and Ullah, Inam and Thierry, Nimbeshaho and Kefalas, Pavlos},
  year={2026},
  note={Manuscript under review; revised 3 October 2026}
}
```
