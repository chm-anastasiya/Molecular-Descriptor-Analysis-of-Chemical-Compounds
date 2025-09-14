# Molecular Property Analyzer
A Jupyter-notebook tool for fetching, analysing and visualising molecular properties from **PubChem**.

---

## Core Features
- Retrieve compound information from PubChem (by name, SMILES, CID, etc.);
- Collect key molecular descriptors;
- Evaluates **Lipinski's rule** and **Veber's rule**;
- Generate: scatter plots and radar charts.

> Descriptors are taken directly from PubChem — no local calculations.
> 
---

## Files

| File | Purpose |
|------|---------|
| `main.ipynb` | User interface: manual or CSV input, PubChem queries, saving results |
| `analise.ipynb` | Helper functions: rule evaluation, scatter plots, radar charts |

---
## Installation

Clone the repository:

```bash
git clone https://github.com/chm-anastasiya/Molecular-Property-Analyser.git
cd Molecular-Property-Analyser
```
Install required packages:

```bash
pip install pubchempy pandas numpy matplotlib
```

## Quick Start
Open and run Jupyter notebook **main.ipynb**
Follow the menu inside the notebook:
* 1 – manual input of compounds
* 2 – load from CSV
* 0 – exit
  
> CSV files should contain one column with identifiers (names, SMILES, CIDs or InChI).

| Folder          | Content                         |
| --------------- | ------------------------------- |
| `results/`      | CSV files                       |                  
| `plots/`        | Scatter plots                   |
| `plots/radars/` | Radar charts                    |
| `images/`       | 2D PNG structures from PubChem  |
