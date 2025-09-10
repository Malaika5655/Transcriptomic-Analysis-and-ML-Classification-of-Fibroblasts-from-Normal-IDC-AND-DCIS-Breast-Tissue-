### Breast Cancer Progression Analysis: From DCIS to IDC🧬

## 📌 Project Overview

* Focus on *breast cancer progression* from Ductal Carcinoma In Situ (DCIS) to Invasive Ductal Carcinoma (IDC).
* Highlights the *understudied role of cancer-associated fibroblasts (CAFs)* in tumor aggressiveness.
* Utilizes *RNA-Seq dataset (GSE228582)* to analyze fibroblast-specific transcriptomic profiles.
* Integrates *bioinformatics pipelines* and *machine learning models* for fibroblast subtype classification.

## 🛠️ Methodology
 *Data Acquisition & Preprocessing*

  * RNA-Seq data (NCBI GEO: GSE228582)
  * Python-based preprocessing & normalization

* *Differential Gene Expression (DGE) Analysis*

  * Performed using *PyDESeq2*
  * Identified *49 significant DEGs* across normal, DCIS, and IDC samples
  * Visualization with *volcano plots*

 *Functional Enrichment Analysis*

  * Tools: *DAVID, **Enrichr*
  * Pathways enriched in:

    * DNA replication
    * Cell cycle control
    * ECM remodeling
    * Immune evasion

 *Machine Learning Models*

  * Algorithms applied: *Random Forest, **Neural Networks*
  * Goal: Classification of fibroblast subtypes
  * Achieved *high accuracy* in classification

---

## 📊 Results & Insights

* *49 DEGs* highlight fibroblast-specific signatures in cancer progression.
* Functional pathways link fibroblast activity to *tumor invasion and immune modulation*.
* ML models show promise for *precision oncology applications*.

---

## ⚠️ Limitations

* Small dataset size.
* Lack of *experimental validation*.
* CAF heterogeneity not fully captured due to *bulk RNA-Seq limitations*.

---

## 🚀 Future Directions

* Integration of *single-cell RNA-Seq* for higher resolution fibroblast profiling.
* Incorporation of *proteomics & epigenomics* for multi-omics insights.
* Functional assays to validate *computational predictions*.
* Development of *fibroblast-based diagnostic biomarkers* for early detection.

---

## 📂 Repository Structure (Suggested)


├── data/                # Processed RNA-Seq datasets
├── preprocessing/       # Python scripts for normalization & QC
├── DEGs_analysis/       # PyDESeq2 workflows + volcano plots
├── enrichment/          # Functional analysis results (DAVID, Enrichr)
├── ML_models/           # Random Forest & Neural Network scripts
├── results/             # DEGs, pathway enrichment, ML metrics
└── docs/                # Project report, references, and documentation


---

## 🏷️ Keywords

breast cancer ductal carcinoma in situ (DCIS) invasive ductal carcinoma (IDC)
fibroblasts cancer-associated fibroblasts (CAFs) RNA-Seq PyDESeq2
machine learning bioinformatics precision oncology
