# Systematic Data Collection, Curation, and Physicochemical Profiling of Chalcone Derivatives for Antimalarial Drug Discovery

## Project Overview

This repository contains all data, code, and  analysis pipeline for the on chalcone derivatives as potential antimalarial compounds against *Plasmodium falciparum*. The work involves systematic literature mining, dataset curation, physicochemical profiling, and statistical analysis of **392 chalcone derivatives** retrieved from 19 peer-reviewed literature sources, yielding a final curated dataset of **251 non-redundant compounds** with experimentally validated antimalarial activity against *Plasmodium falciparum*.

### What this repository provides:
- The complete curated dataset (251 compounds) with SMILES, pIC₅₀ values, activity labels, and computed physicochemical descriptors
- The raw pre-curation dataset (346 compounds, before intermediate removal)
- All Python scripts and Google Colab notebooks to reproduce every figure and table in the paper

# Requirements for: Systematic Data Collection, Curation, and Physicochemical Profiling of Chalcone Derivatives for Antimalarial Drug Discovery

# Install with: pip install -r requirements.txt
# Python version: 3.10

# Note: If rdkit-pypi fails, try: conda install -c conda-forge rdkit=2023.09.4

rdkit-pypi==2023.9.4
pandas==2.1.1
numpy==1.25.2
scipy==1.11.3
scikit-learn==1.3.0
matplotlib==3.7.3
seaborn==0.12.2
jupyter==1.0.0
notebook==7.0.6
ipykernel==6.25.2
openpyxl==3.1.2

