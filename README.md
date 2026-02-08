# 🧬 Identification of Tumor Suppressor Genes in Breast Cancer  
### Pathway Analysis & Protein Structure Modeling

![Field](https://img.shields.io/badge/Field-Bioinformatics-blueviolet)
![Focus](https://img.shields.io/badge/Focus-Breast%20Cancer-red)
![Tools](https://img.shields.io/badge/Tools-KEGG%20%7C%20STRING%20%7C%20AlphaFold-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

Breast cancer progression is strongly influenced by the **loss or dysfunction of tumor suppressor genes (TSGs)** and dysregulation of associated molecular pathways.  
This project integrates **pathway enrichment, gene expression profiling, survival analysis, and protein structure modeling** to study key tumor suppressor genes involved in breast cancer.

The analysis focuses on **BRCA1, BRCA2, TP53, PTEN, and PI3K**, bridging **omics-level insights** with **structural bioinformatics** to provide biologically meaningful interpretations.

---

## 🎯 Objectives

- Identify **breast cancer–associated tumor suppressor pathways**
- Analyze **gene expression and survival relevance**
- Study **protein–protein interactions and biological processes**
- Generate and validate **3D protein structures** for tumor progression–related proteins

---

## 🧠 Biological Questions Addressed

- Which tumor suppressor genes are most enriched in breast cancer pathways?
- How do these genes behave across different cancer stages?
- Are their expression patterns linked to patient survival?
- Which biological processes dominate tumor suppressor dysfunction?
- Can reliable protein structures be modeled for downstream studies?

---

## 🔬 Methodology Pipeline

### 1️⃣ Gene & Pathway Analysis
- Tumor suppressor gene selection based on literature
- Pathway mapping using **KEGG Breast Cancer Pathway (hsa05224)**

### 2️⃣ Functional Enrichment & Network Analysis
- **Gene Ontology (GO) enrichment** (Biological Process)
- **Protein–Protein Interaction (PPI)** networks using STRING
- Identification of DNA damage response and cell-cycle regulation modules

### 3️⃣ Expression & Survival Analysis
- Differential expression using **TCGA & GTEx datasets**
- Boxplots and violin plots across breast cancer stages
- Kaplan–Meier survival analysis for prognostic relevance

### 4️⃣ Structural Bioinformatics
- Protein sequence retrieval from UniProt
- Homology modeling via SWISS-MODEL
- Structure prediction and ranking using AlphaFold
- Structural validation:
  - GMQE
  - QMEANDisCo
  - Ramachandran plot
  - Clash and disorder analysis

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/8bf11792-887b-401e-8254-ad4397376096" />


---

## 🧪 Tools & Databases Used (With Links)

### 🔹 Biological Databases
- **NCBI** – https://www.ncbi.nlm.nih.gov  
- **UniProt** – https://www.uniprot.org  
- **KEGG** – https://www.kegg.jp  
- **STRING** – https://string-db.org  
- **GEPIA** – http://gepia.cancer-pku.cn  
- **PDB** – https://www.rcsb.org  
- **Pfam** – https://pfam.xfam.org  
- **Ensembl** – https://www.ensembl.org  
- **ExPASy** – https://www.expasy.org  

### 🔹 Bioinformatics & Structural Tools
- **BLAST** – https://blast.ncbi.nlm.nih.gov  
- **SWISS-MODEL** – https://swissmodel.expasy.org  
- **AlphaFold** – https://alphafold.ebi.ac.uk  
- **PyMOL** – https://pymol.org  

---

## 📊 Key Results & Insights

### ✅ Pathway & Functional Enrichment
- Strong enrichment in:
  - DNA damage response
  - Double-strand break repair
  - Cell-cycle checkpoint regulation
  - Intrinsic apoptotic signaling
- Confirmation of **PI3K involvement** in breast cancer pathways

### ✅ Expression & Survival
- Stage-dependent expression patterns for BRCA1, BRCA2, TP53, PTEN
- Survival analysis highlights **clinical relevance** of tumor suppressor dysregulation

### ✅ Protein Structure Modeling
- Best PI3K-C2α model selected based on:
  - Highest GMQE score (0.52)
  - QMEANDisCo score: 0.68 ± 0.05
  - Zero steric clashes
- AlphaFold Model 0 ranked highest (score: 0.81)
- Structures suitable for docking and molecular dynamics studies

---

## 📁 Recommended Repository Structure

```bash
├── data/           # Gene lists, expression datasets
├── results/        # Plots, enrichment outputs
├── structures/     # AlphaFold & SWISS-MODEL files
├── figures/        # Publication-quality images
├── references/     # Research papers
└── README.md

## 🚀 Future Improvements

- Molecular docking of PI3K inhibitors
- Molecular dynamics simulations
- Integration of somatic mutation data
- Pipeline automation using Python/R
- Multi-omics expansion (CNV, methylation)

## 👤 Author
T. P. Rajarajan
Bioinformatics | Cancer Biology
📅 December 2024

## ⚠️ Disclaimer

This is an academic research project, not a production-grade software package.
The emphasis is on biological interpretation, data integration, and structural validation rather than automation.

# ⭐ If this repository helped you understand breast cancer bioinformatics workflows, feel free to star it.
