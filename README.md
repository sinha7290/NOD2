# NOD2: Code Companion for "Distinct Colitis-Associated Macrophages Drive NOD2-Dependent Bacterial Sensing and Gut Homeostasis"

## Overview

This repository provides the computational framework and analysis scripts used in the study:  
**“Distinct Colitis-Associated Macrophages Drive NOD2-Dependent Bacterial Sensing and Gut Homeostasis”**  
by Katkar et al. (2024).

---

## Repository Contents

- `NOD2(1).ipynb` – Primary analysis notebook for evaluating ColAM signatures, composite score calculations, and plotting.
- `bone(1).py` – Module for Boolean Network Explorer (BoNE) composite score calculations.
- `icolam.txt` – gene list for iCoLAM signature.
- `nicolam.txt` – gene list for niCoLAM signature.
---

## Setup Instructions

### Prerequisites

- Python ≥ 3.8  
- Jupyter Notebook

### Required Python Packages

Install dependencies using pip:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn
