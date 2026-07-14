# Deep Learning and Large Language Models for Medication Recommendation — Survey Resources

This repository accompanies the survey paper:

**"Trustworthy Medication Recommendation: A Safety-Centered Survey of Knowledge-Grounded and LLM-Assisted Methods"**

It provides methodological artifacts and supporting materials to improve transparency, reproducibility, and reuse of the systematic review process.

---

## 📌 Overview

Medication recommendation (MR) is an emerging research area at the intersection of clinical decision support, recommender systems, graph learning, multimodal electronic health record (EHR) modeling, and large language models (LLMs).

This repository shares the structured review protocol and study corpus used in our survey, which synthesizes **56 recent MR studies (2022–2026)** and proposes a comprehensive taxonomy spanning:

- Input information factors and representations
- Modeling paradigms (DL, graph-based, multimodal, LLM/RAG pipelines)
- Evaluation practices and safety-aware metrics
- Reliability, interpretability, and deployment considerations

---

## 📂 Repository Contents

| File | Description |
| :--- | :--- |
| **PRISMA_Flow.pdf** | PRISMA 2020 flow diagram illustrating the study selection process |
| **PRISMA_Flow.tex** | LaTeX source for the PRISMA flow diagram |
| **Study_List.csv** | Complete list of the 56 studies included in the qualitative synthesis, with year, venue, model family, and dataset(s) |
| **Search_Queries.csv** | Database-specific search strings, execution dates, limits, and record counts (preliminary scoping and formal systematic stages) |
| **Venue_Screening.csv** | Independent venue-specific screening results, including potentially relevant records identified and additional records added (all zero) |
| **Screening_Checklist.txt** | Inclusion and exclusion criteria applied during title/abstract and full-text screening |
| **Data_Extraction_Template.txt** | Structured template used to extract attributes such as modalities, architectures, safety mechanisms, and evaluation metrics |
| **Taxonomy_Summary.pdf** | Visual summary of the proposed MR taxonomy (reproduced from the main paper) |

---

## 🔎 PRISMA Study Selection Summary

The systematic literature search followed a **two-stage strategy** comprising a preliminary scoping search and a formal systematic search, supplemented by independent venue-specific coverage verification.

| Stage | Count |
| :--- | :---: |
| **Formal systematic searches:** Records retrieved from six sources | 132 |
| Duplicate records removed | –39 |
| **Unique records for title/abstract screening** | **93** |
| Records excluded at title/abstract screening | –37 |
| **Records for full-text assessment** | **56** |
| Records excluded at full-text assessment | 0 |
| **Studies included in qualitative synthesis** | **56** |

**Notes:**
- The preliminary scoping search (1,628 records) informed the refinement of the formal search but was **not** included in the PRISMA identification count.
- The formal systematic searches were conducted across: PubMed, IEEE Xplore, ACM Digital Library, Scopus, Web of Science, and arXiv.
- Independent venue screening of selected journals and conference proceedings identified **0 additional records** beyond the 132-record source-based set.
- All searches were executed on **20 May 2026** and limited to publications from **1 January 2022** through the search date.

The complete PRISMA workflow is illustrated in the flow diagram in the paper and reproduced in this repository.

---

## 🧠 Study Corpus (56 Studies)

Representative models reviewed include:

**LLM/RAG-based:**
- LEADER, PharmaLLM, KEDRec-LM, TreatRAG, MedAlign, LAMO, RAG-CPMF, TCM-KLLaMA, FLAME

**Structured neural / Transformer:**
- COGNet, VITA, ACDNet, TAHDNet, CEHMR, SHAPE, TEMPT, HI-DR, ARMR

**Graph and hypergraph:**
- MedGCN, DGCL, KEHGCN, BH3-MedRec, MoleRec, EGNet, BiMoRec, DNMDR, SSPNet, EDRMM, DAI-Net, IMDR

**Causal and debiased:**
- CAMeR, CausalMed, CIDGMed, MR-DTR, GPSRec

**Robustness and rare-case:**
- RAREMed, MetaCare++, StratMed, KRAM, PAUP, EXCERF

**Safety-utility balancing:**
- 4SDrug, SDRBT, AKA-SafeMed

**Knowledge integration:**
- MedRec, DKINet, TAKECare, PROMISE, KindMed, HKRec

The complete list of all 56 studies with metadata (year, venue, model family, datasets) is provided in **Study_List.csv**.

---

## 🎯 Purpose of This Repository

This repository aims to:

- Improve **systematic review reproducibility** in clinical AI research
- Provide a **structured entry point** for new researchers in medication recommendation
- Support **benchmark consolidation and methodological comparison**
- Encourage **transparent reporting and fair evaluation practices**
- Facilitate **reuse of the screening and extraction protocols** in future reviews

---

## 📊 Data Availability

No new datasets were created in this work. All datasets referenced in the survey are publicly available and cited in the original publications. The key datasets referenced include:

- MIMIC-III and MIMIC-IV (ICU EHR benchmarks)
- eICU Collaborative Research Database (multicenter ICU data)
- MIMIC-CXR (multimodal imaging-linked data)

External knowledge resources cited include DrugBank, TWOSIDES, DDInter, RxNorm, ATC, and UMLS.

---

## 📄 Citation

If you use materials from this repository, please cite the survey paper:

```bibtex
@article{hussain2026trustworthy,
  title={Trustworthy Medication Recommendation: A Safety-Centered Survey of Knowledge-Grounded and LLM-Assisted Methods},
  author={Hussain, Sumaira and Ali, Zafar and Ullah, Imran and Ullah, Irfan and Ullah, Inam and Thierry, Nimbeshaho and Kefalas, Pavlos},
  journal={[Journal Name]},
  year={2026},
  note={Under review}
}
