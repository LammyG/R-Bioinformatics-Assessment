# R-Bioinformatics-Assessment
MSc Bioinformatics: R programming and differential gene expression analysis pipeline for Acute Myeloid Leukemia (AML) microarray datasets.
# MSc Bioinformatics: R for Bioinformatics Assessment

## 📌 Project Overview
This repository contains the final data analysis report for the **R for Bioinformatics Assignment** submitted by **Olamide Okunola**. 

The project demonstrates core competencies in programming, statistical computing, object-oriented design, and advanced high-throughput biological data workflows using microarray datasets.

---
https://github.com/LammyG/R-Bioinformatics-Assessment/blob/main/R_report_OlamideOkunola_S3559438.html
## 📊 How to View the Interactive Report
Because GitHub does not natively render `.html` files (it displays them as raw code text), you can view the fully formatted report—complete with publication-grade charts, clean tables, and code formatting—by using the live preview link below:

👉 **[CLICK HERE TO VIEW THE FULL INTERACTIVE REPORT](https://htmlpreview.github.io/?https://github.com/LammyG/R-Bioinformatics-Assessment/blob/main/R_report_OlamideOkunola_S3559438.html)**

*(Alternatively, you can download the `R_report_OlamideOkunola_S3559438.html` file from this repository and open it locally in any web browser like Chrome, Safari, or Edge.)*

---

## 📁 Core Tasks Addressed in the Report

* **Task 1: Principles of R in Bioinformatics**
  * Critical evaluation of R's advantages and memory/threading constraints within the Bioconductor ecosystem, alongside a breakdown of standard biological data structures and atomic types.
* **Task 2: Protein Hydrophobicity Analysis Pipeline**
  * Implementation of custom, matrix-free indexing functions to compute length, sequence properties, and hydrophobicity percentages using the Lehninger scale.
* **Task 3: S4 Object-Oriented Class Design**
  * Formal S4 class representation for a `Gene` object tracking expression data, complete with customized polymorphism methods for output normalization.
* **Task 4: Mathematical Modeling of Algae Population Growth**
  * An iterative recurrence sequence loop calculating cellular expansion across generations with degradation and conditional filtering logic.
* **Task 5: High-Throughput Microarray & Differential Gene Expression Analysis**
  * Complete downstream pipeline processing a log2-transformed AML (Acute Myeloid Leukemia) dataset (22,283 genes across 64 cohorts). 
  * Features demographic profiling, quality-control boxplots, custom multi-sample Row-T-test algorithms contrasted with empirical Bayes linear modeling (`limma`), and statistical intersection mapping via a Venn diagram.

---

## 🛠️ Software Environment & R Packages Used
The code was compiled using **R version 4.3.3** under a **macOS** environment. The pipeline relies on the following packages (visible and detailed within the report):
* `ggplot2` (Exploratory demographics plots and density layouts)
* `limma` (Bioconductor package for Microarray differential linear models)
* `VennDiagram` & `grid` (Cohort overlap visualizations)
