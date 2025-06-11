# Risk Assessment for Construction Segment

This repository contains the code and report for a risk-assessment project focused on comparing and refining credit-risk profiling for the Construction sector. The analysis is split into three Jupyter notebooks and a PDF report for a non-technical audience.

---

## 📂 Repository Structure

```
.
├── data
│   ├── raw/                ← Original, confidential datasets (not shared)
│   │   ├── file1.csv
│   │   ├── file2.csv
│   │   └── file3.csv
│   └── processed/          ← Cleaned/derived datasets (not shared)
│       ├── df_app.csv
│       ├── df_company.csv
│       ├── df_payments.csv
│       └── df_risk_metrics.csv
├── notebooks
│   ├── 1_data_processing.ipynb
│   ├── 2_risk_profiling.ipynb
│   └── 3_risk_assessment_strategy.ipynb
├── report
│   └── Risk_Assessment_Report.pdf
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 🔑 Data Notes

- **data/raw/**  
  Contains the original source files. *These are confidential; not included in this repo.*

- **data/processed/**  
  Contains cleaned and merged files for analysis. *Also confidential; not included.*

---

## 📓 Notebooks

1. **1_data_processing.ipynb**  
   - Loads raw data  
   - Cleans, merges, and exports processed datasets  

2. **2_risk_profiling.ipynb**  
   - **Segment comparison**: Construction vs Other segments  
   - **Key risk metrics**: Default rates, payment behavior, credit ratings  
   - **Feature exploration**: Correlation with `default_status` and suggestions for new features  

3. **3_risk_assessment_strategy.ipynb**  
   - **Evaluation** of current risk scoring for Construction  
   - **Proposed rule/segmentation**: Data-driven adjustments or segmentation layer  
   - **Justification**: Insights from notebook 2  
   - **Deployment considerations**: How to test and roll out in production  

---

## 📄 PDF Report

- **report/Risk_Assessment_Report.pdf**  
  A non-technical summary for the Risk Management team, including:  
  - Key findings on Construction segment risk profile  
  - Clear visualizations (default rates, distributions, etc.)  
  - Proposed preliminary risk-assessment strategy  
  - Limitations & avenues for further research  

---

## ⚙️ Setup & Dependencies

1. **Clone the repo**  
   ```bash
   git clone <your-repo-url>
   cd <repo-folder>
   ```

2. **Create & activate a virtual environment**  
   ```bash
   python3 -m venv venv
   source venv/bin/activate     # Mac/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebooks**  
   - Launch Jupyter:  
     ```bash
     jupyter notebook
     ```
   - Execute each notebook in order:  
     1. **1_data_processing.ipynb**  
     2. **2_risk_profiling.ipynb**  
     3. **3_risk_assessment_strategy.ipynb**  

---

## 🚫 Confidentiality

> **Note:** The raw and processed data files are not included in this public repository due to privacy and company policy. To reproduce the analysis, please place the original datasets in `data/raw/` and the cleaned outputs in `data/processed/`, matching the filenames described above.

---

## 📝 License & Citation

- *This work was performed as part of [Company Name]’s hiring process and is confidential.*  
- Please do not redistribute without permission.

