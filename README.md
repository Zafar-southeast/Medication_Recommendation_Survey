# Deep Learning and Large Language Models for Medication Recommendation — Survey Resources

This repository accompanies the survey paper:

**“Deep Learning and Large Language Models for Medication Recommendation: A Survey, Taxonomy, and Roadmap.”**

It provides methodological artifacts and supporting materials to improve transparency, reproducibility, and reuse of the systematic review process.

---

## 📌 Overview

Medication recommendation (MR) is an emerging research area at the intersection of clinical decision support, recommender systems, graph learning, multimodal electronic health record (EHR) modeling, and large language models (LLMs).

This repository shares the structured review protocol and study corpus used in our survey, which synthesizes **40 recent MR studies (2022–2025)** and proposes a comprehensive taxonomy spanning:

* Input information factors and representations
* Modeling paradigms (DL, graph-based, multimodal, LLM/RAG pipelines)
* Evaluation practices and safety-aware metrics
* Reliability, interpretability, and deployment considerations

---

## 📂 Repository Contents

* **PRISMA_Section.pdf / .tex / .txt**
  Detailed PRISMA-based study selection methodology.

* **Model_List.txt**
  Unique medication recommendation models included in the survey.

* **Search_Queries.txt**
  Representative database search strings used during study identification.

* **Screening_Checklist.txt**
  Inclusion and exclusion criteria applied during title/abstract and full-text screening.

* **Data_Extraction_Template.txt**
  Structured template used to extract attributes such as modalities, architectures, safety mechanisms, and evaluation metrics.

---

## 🔎 PRISMA Study Selection Summary

* Records identified: **95**
* After duplicate removal: **83**
* Excluded during screening: **43**
* Final studies included in synthesis: **40**

The complete workflow is illustrated in the PRISMA flow diagram in the paper.

---

## 🧠 Study Corpus (Example Models)

Representative models reviewed include:

SafeDrug, GAMENet, Trans-GAHNet, DGCL, CEHMR, StratMed, VITA, CIDGMed, ACDNet, LEADER, PharmaLLM, TAKECare, and others.

---

## 🎯 Purpose of This Repository

This repository aims to:

* Improve **systematic review reproducibility** in clinical AI research
* Provide a **structured entry point** for new researchers in medication recommendation
* Support **benchmark consolidation and methodological comparison**
* Encourage **transparent reporting and fair evaluation practices**

---

## 📊 Data Availability

No new datasets were created in this work. All datasets referenced in the survey are publicly available and cited in the original publications.

---

## 📄 Citation

If you use materials from this repository, please cite the survey paper (BibTeX will be added after publication).

---

## 🤝 Contributions

Suggestions, corrections, or extensions are welcome via issues or pull requests.



