# Reaction Network Database for Fast Pyrolysis of Vanillyl Alcohol
## Integrated with Electronic Structure Descriptors

**Authors:** Shi Jingyuan，Li Chenchen，Cheng Xiaoxue，Ling Qifan，Mu Mao，Wang Shuang*，Jiang Ding* 
**Affiliation:** School of Energy and Power Engineering, Jiangsu University  


---

### 📂 Overview
This repository contains the raw computational data associated with the research paper: **"Reaction Network Database for Fast Pyrolysis of Vanillyl Alcohol Integrated with Electronic Structure Descriptors"**.

The dataset systematically maps the fast pyrolysis pathways of vanillyl alcohol (a lignin model compound) at **823.15 K** using Density Functional Theory (DFT). It integrates thermodynamic energy barriers with atomic-level electronic fingerprints to support machine learning modeling and catalyst design.

### 📄 Data Specifications
* **Total Size:** ~233 MB
* **File Formats:** * `.log` / `.chk`: Gaussian 16 output and checkpoint files (Geometries & Energies)
    * `.wfn`: Wavefunction files (Electronic properties)
    * `.txt` / `.xlsx`: Extracted descriptors and summary tables

### 🔧 Computational Details
* **Software:** Gaussian 16
* **Level of Theory:** B3LYP/6-311G(d,p)
* **Temperature:** 823.15 K
* **Wavefunction Analysis:** Multiwfn 3.8

### 🚀 Usage
This dataset can be used for:
1.  Benchmarking catalytic vs. non-catalytic pyrolysis mechanisms.
2.  Training Machine Learning Force Fields (MLFF) or Graph Neural Networks (GNN).
3.  Analyzing regioselectivity via electronic descriptors.

### 🔗 Citation
If you use this data, please cite our paper:


---
*Disclaimer: This dataset is provided for research purposes. Please refer to the specific license file for usage rights.*
