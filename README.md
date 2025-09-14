# Molecular Property Analyzer
A Jupyter-notebook tool for fetching, analysing and visualising molecular properties from **PubChem**.

## Core Features

* retrieve compound information from PubChem (by **name**, **SMILES**, **CID**, etc.);
* collect key molecular descriptors;
* evaluates **Lipinski's rule** and **Veber's rule**;
* generate: scatter plots and radar charts.

---

## Files

| File | Purpose |
|------|---------|
| `main.ipynb` | User interface: input compounds (manually or from CSV), call PubChem, save results |
| `analise.ipynb` | Utility functions for analysis, rule evaluation and plotting (scatter & radar) |

## Quick Start

**Clone the repository**

   ```bash
   git clone https://github.com/chm-anastasiya/
   ```

**Create and activate conda environment**  
   ```bash
   conda env create -f environment.yml
   conda activate 
   ```
