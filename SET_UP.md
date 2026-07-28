# Analisis Sentimen Kartu Sumbawa Pintar (KSP) ✨

## Setup Environment - Anaconda
# (Nama environment bebas)
conda create --name <nama_env> python=3.11
conda activate <nama_env>
pip install -r requirements.txt

## Setup Environment - Shell/Terminal
# (Nama venv bebas)
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt

## Opsi Instalasi Terpisah
# Instalasi manual via pip:
pip install pandas numpy openpyxl scikit-learn joblib matplotlib seaborn wordcloud jupyter

## Daftar Dataset

### 1. Raw Dataset (`data/dataset/`)
- `dataset_facebook-comments-scraper_2026-07-27_05-16-43-920.csv`
- `dataset_facebook-comments-scraper_2026-07-27_07-45-29-790.csv`
- `dataset_facebook-comments-scraper_2026-07-27_11-34-39-617.csv`

### 2. Preprocessed Dataset (`data/proceed_dataset/`)
- `Data_Komentar_KSP_fix.csv`
- `Data_Komentar_KSP_fix.xlsx`

### 3. Data Labelling (`data/data_labelling/`)
- `Data_Komentar_KSP_labelling.xlsx`
- `data_labelled.xlsx`

## Run Preprocessing Script
python notebook/clean_preprocessing.py

## Run Jupyter Notebook
jupyter notebook
