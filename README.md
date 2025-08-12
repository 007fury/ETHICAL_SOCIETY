# 🌍 Ethical Society Simulation – Thrive Island

A simulation framework for designing an ethically balanced island society where the top 1% of the population maintains a luxury lifestyle while ensuring service roles and essential societal functions are fulfilled by the remaining population.

## 📜 Description
Developed a **Resilience–Contribution Matrix** to evaluate and select the top 1% of candidates based on:
- **Resilience**: health, adaptability, survival skills
- **Contribution**: skills, education, caregiving capacity
- Protected attributes excluded to comply with **GDPR** and the **EU AI Act**

The model ensures fairness, inclusivity, and transparency, supporting societal balance between the elite and the rest.

## 🛠 Methods
- **Data Cleaning & Feature Engineering**
- **Scoring Algorithm** for ethical candidate ranking
- **Visualization** of population distribution & selection outcomes
- Python implementation with Pandas, NumPy, Matplotlib, Seaborn

## 📊 Dataset
- **File**: `STARK Data set for Assignment.xlsx`
- Contains demographic and skill-related attributes used to compute resilience and contribution scores.

## 📂 Structure
```
ethical-society-simulation/
├─ README.md
├─ requirements.txt
├─ notebooks/
│  └─ CT7204_4415500_3.ipynb
├─ data/raw/
│  └─ STARK Data set for Assignment.xlsx
├─ reports/
│  └─ figures/   # 8 auto-exported figures
├─ proofs/
│  └─ CT7204_4415500_1.docx
└─ docs/
```

## ▶️ How to Run
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```
Open the notebook in `notebooks/` and run all cells. Dataset is provided in `data/raw/`.

## 🔍 Verification
- Full notebook: `notebooks/CT7204_4415500_3.ipynb`
- Dataset: `data/raw/STARK Data set for Assignment.xlsx`
- Proof document: `proofs/CT7204_4415500_1.docx`

## 📄 License
MIT
