# 🧬 Breast Cancer Drug Candidates ADMET Analysis

[![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue.svg)]()
[![SwissADME](https://img.shields.io/badge/Tool-SwissADME-green.svg)]()
[![Data Format](https://img.shields.io/badge/Data-CSV-orange.svg)]()
[![Status](https://img.shields.io/badge/Status-Research%20Project-success.svg)]()
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)]()

Computational ADMET profiling of breast cancer drug candidate molecules using **SwissADME** and **Python-based data integration**.

---

# 🧪 Project Overview

This repository contains **computational analysis of potential breast cancer drug candidate molecules using ADMET profiling generated from SwissADME**.

The project integrates **multiple SwissADME batch outputs into a consolidated dataset using Python** and provides a **structured workflow for analyzing pharmacokinetic and drug-likeness properties of small molecules**.

The aim of this project is to evaluate:

- Physicochemical properties
- Pharmacokinetics
- Drug-likeness rules
- Medicinal chemistry parameters

for **candidate compounds that may have therapeutic relevance in breast cancer treatment**.

---

# 🎯 Objectives

The main goals of this project include:

- Perform **ADMET profiling** of candidate molecules using SwissADME
- Integrate **multiple SwissADME batch results** into a unified dataset
- Analyze **drug-likeness and pharmacokinetic properties**
- Create a **reproducible Python workflow** for ADMET data processing
- Provide a **clean dataset** for further computational drug discovery analysis

---

# 📂 Repository Structure

```
SwissADME_files_merging.ipynb
swissadme_1.csv
swissadme_2.csv
swissadme_3.csv
Master_ADMET_Results.csv
```

### File Descriptions

**SwissADME_files_merging.ipynb**

Jupyter Notebook used to merge multiple SwissADME result files into a **single master dataset**.

**swissadme_1.csv**

First batch of SwissADME results containing **molecular descriptors and ADMET predictions**.

**swissadme_2.csv**

Second batch of SwissADME results generated from **additional candidate molecules**.

**swissadme_3.csv**

Third batch of SwissADME results generated from **additional candidate molecules**.

**Master_ADMET_Results.csv**

Final merged dataset containing **ADMET properties of all analyzed molecules**.

---

# 📊 Dataset Description

The final dataset contains **ADMET-related descriptors predicted by SwissADME for each molecule**.

The dataset includes parameters related to:

- Physicochemical properties
- Pharmacokinetics
- Drug-likeness
- Medicinal chemistry

### Key properties included in the dataset

- Molecule name
- Canonical SMILES representation
- Molecular formula
- Molecular weight
- Number of heavy atoms
- Number of aromatic atoms
- Fraction of sp³ carbons
- Number of rotatable bonds
- Hydrogen bond donors
- Hydrogen bond acceptors
- Topological polar surface area
- Lipophilicity predictions (LogP values)
- Water solubility predictions
- Pharmacokinetic properties
- Drug-likeness rule evaluations
- Medicinal chemistry alerts

A total of **96 small molecules** were successfully profiled and included in the final dataset.

---

# ⚙️ Workflow

### Step 1

Molecular structures were submitted to the **SwissADME web server** to calculate:

- ADMET descriptors
- Drug-likeness parameters

### Step 2

SwissADME generated **separate CSV files** for each batch of molecules.

### Step 3

**Python** was used to combine the datasets into a **single master file**.

### Step 4

The final dataset was exported as a **consolidated CSV file for downstream analysis**.

---

# 🐍 Python Script Logic

The merging workflow was implemented in **Python using the pandas library**.

The script performs the following steps:

```
1. Load SwissADME CSV files
2. Combine datasets using pandas
3. Concatenate into one dataframe
4. Export the merged dataset
```

This ensures that **all molecules and their corresponding ADMET descriptors are organized in a single structured table**.

---

# 🧰 Tools and Technologies

- 🐍 Python
- 📊 Pandas
- 📓 Jupyter Notebook
- 🌐 SwissADME Web Server
- 📁 CSV Data Processing

---

# 🔬 Applications

This dataset and workflow can be used for:

- ADMET filtering of drug candidates
- Drug-likeness evaluation using **Lipinski and other rules**
- Computational drug discovery pipelines
- Machine learning model development for **pharmacokinetics prediction**
- Bioinformatics and cheminformatics research
- Early-stage drug discovery analysis

---

# 🚀 How to Use This Repository

Clone the repository:

```bash
git clone https://github.com/yourusername/breast-cancer-drug-candidates-admet-analysis.git
```

Open the **Jupyter Notebook**:

```
SwissADME_files_merging.ipynb
```

Run the notebook to merge SwissADME output files.

The notebook will generate the final dataset:

```
Master_ADMET_Results.csv
```

Researchers can then use this dataset for **further computational analysis or visualization**.

---

# 🔮 Future Improvements

Future development of this project may include:

- Statistical analysis of ADMET descriptors
- Drug-likeness filtering pipelines
- Visualization of pharmacokinetic properties
- Integration with molecular docking results
- Machine learning models for predicting biological activity

---

# 📜 License

This project is released under the **MIT License**.

Researchers are free to **use, modify, and distribute the code and data for academic and research purposes**.

---

# 👨‍🔬 Author

**Nagendra**

Clinical Data Science and Bioinformatics Researcher
