# 🧬 NORMAN Database with CCS, RT and MS2

## 📋 Overview
A comprehensive database combining:
- 🔬 NORMAN compounds ([NORMAN-SusDat](https://www.norman-network.com/nds/susdat/))
- 📊 CCS values (experimental and predicted)
- ⏱️ Retention times (experimental and predicted)
- 📈 MS2 spectra from MassBank

## 📚 Notebooks

1. `1_NORMAN_and_CCSbase.ipynb`: 
   - 🔄 Combines NORMAN database with CCS values
   - 🧪 Standardizes SMILES structures
   - 📊 Merges experimental and predicted CCS values

2. `2_add_RT.ipynb`:
   - ⏱️ Adds predicted retention times
   - 🤖 Uses QSRR model
   - 🔍 Data cleaning and validation

3. `3_add_MS2.ipynb`:
   - 📈 Integrates MS2 spectra from MassBank
   - 🔍 Filters for ESI-QTOF data
   - 🧪 Matches spectra with compounds

4. `4_database_info.ipynb`:
   - 📊 Statistical analysis
   - 📉 Data visualization
   - 📋 Coverage assessment

## ⚙️ Requirements

- 🐍 Python 3.8+
- 📦 Required packages:
  - pandas
  - rdkit
  - [QSRR_predictor](https://github.com/narvall018/QSRR-Retention-Time-Prediction)
  - matplotlib
  - seaborn

## 🚀 Installation & Usage

1. Clone this repository:
```bash
git clone https://github.com/narvall018/NORMAN_CCS_RT_MS2_database.git