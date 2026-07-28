# Dokumentasi Data Scraping & Preprocessing KSP

Dokumentasi lengkap mengenai alur pengolahan data mentah scraping, penyesuaian 14 kolom terstandar, serta deduplikasi data pelabelan telah tersedia pada file [README.md utama](../../README.md).

### Ringkasan Direktori Data Scraping:
- **`dataset/`**: Berisi 3 file CSV mentah hasil scraping dari Apify Facebook Comments Scraper (total 588 baris mentah dari 16 URL reels/posts Facebook >5 komentar).
- **`fix_dataset/`**: Berisi hasil penggabungan & deduplikasi bersih (`Data_Komentar_KSP_fix.xlsx` & `.csv`, total 475 baris bersih).
- **`data_labelling/`**: Berisi file Excel pelabelan (`Data_Komentar_KSP_labelling.xlsx`, 473 baris bersih) lengkap dengan 3 sheet (`Panduan Labeling`, `Data Komentar`, `Referensi`).
