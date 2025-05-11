# IS-537 Coffee-Shop Sales QC Pipeline

A fully automated, end-to-end data quality assessment & cleaning workflow for coffee-shop sales, events and weather data covering Weeks 2–15 of IS-537.

## 📁 Repository Contents

- **`process_data.py`**  
  Master Python script that discovers, loads, cleans, profiles, and exports your combined dataset (Weeks 2–15).  
- **`categories.json`**  
  Mapping of detailed sales categories → broad categories.  
- **`requirements.txt`**  
  Pin-file for all Python dependencies.  
- **`.gitignore`**  
  Ignores virtualenvs, caches, outputs, and sensitive files.  
- **`profiling_outputs/`**  
  Auto-generated EDA artifacts (plots & summary CSV) from Week 5.  
- **`imputation_reports/`**  
  Reports on missing-value handling from Week 6.  
- **`combined_data_full.csv`**  
  Final cleaned time series, with flags, holiday marks, error signals, etc.  
- **`env_snapshot.json`**  
  Snapshot of your Python environment for reproducibility (Week 14).  

---

## ⚙️ Installation & Setup (no venv)

1. **Make sure you have Python 3.8+ installed**.  
2. **Install dependencies globally**  
   ```bash
   pip install -r requirements.txt

