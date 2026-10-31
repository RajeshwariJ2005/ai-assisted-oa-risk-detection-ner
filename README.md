# AI-Assisted Early Detection System for Osteoarthritis (OA) Risk Markers (NER)

[![Live Web Application](https://img.shields.io/badge/Live%20Website-GitHub%20Pages-0ea5e9?style=for-the-badge&logo=github)](https://rajeshwarij2005.github.io/ai-assisted-oa-risk-detection-ner/)
[![Streamlit App](https://img.shields.io/badge/Streamlit%20Cloud-Ready%20to%20Deploy-FF4B4B?style=for-the-badge&logo=streamlit)](https://share.streamlit.io/deploy?repository=RajeshwariJ2005/ai-assisted-oa-risk-detection-ner&branch=main&mainModule=app.py)
[![Python Version](https://img.shields.io/badge/Python-3.10%20%7C%203.11-3776AB?style=for-the-badge&logo=python)](https://github.com/RajeshwariJ2005/ai-assisted-oa-risk-detection-ner)

> **Live Public URL**: [https://rajeshwarij2005.github.io/ai-assisted-oa-risk-detection-ner/](https://rajeshwarij2005.github.io/ai-assisted-oa-risk-detection-ner/)

---

## 🌐 Live Website & Online Access

Anyone can access and use this AI system online directly in any browser:
* **Interactive Live Web App**: [https://rajeshwarij2005.github.io/ai-assisted-oa-risk-detection-ner/](https://rajeshwarij2005.github.io/ai-assisted-oa-risk-detection-ner/)
* **Streamlit Community Cloud 1-Click Deploy**: [Launch on Streamlit Cloud](https://share.streamlit.io/deploy?repository=RajeshwariJ2005/ai-assisted-oa-risk-detection-ner&branch=main&mainModule=app.py)

---

## 🩺 Project Overview

The **AI-Assisted Early Detection System for Osteoarthritis (OA) Risk Markers** is designed for the North Eastern Region (NER) to screen, analyze, and detect early biomarkers of knee osteoarthritis. The system combines demographic vitals, clinical symptom questionnaires, biomechanical gait metrics, and radiographic Kellgren-Lawrence (KL) grading to stratify patient risk before irreversible joint degeneration occurs.

---

## ✨ Key System Features

1. **Clinical Screening & Risk Engine**:
   - Multi-marker patient registration (Age, Gender, Height, Weight, automated BMI calculation).
   - Standardized 5-question clinical OA symptom questionnaire with pain scale (VAS 0–10).
   - Biomechanical Gait Analysis computing walking speed, stride length, cadence, step count, and gait variability coefficient.
   - Real-time AI risk stratification engine (Low Risk, Moderate Risk, High Risk) with marker weight breakdown and clinical advisory.

2. **Knee Radiographic AI Vision Screener**:
   - Radiograph upload support (AP knee view) with sample test presets.
   - Deep-learning inspired evaluation of Joint Space Width (JSW), marginal osteophytes, and subchondral sclerosis.
   - Standardized Kellgren-Lawrence (KL Grade 0 to Grade 4) grading with confidence scores.

3. **Multi-lingual Voice Guidance (Web Speech Synthesis)**:
   - Voice assistant guiding users through the screening workflow in **English**, **Tamil (தமிழ்)**, and **Hindi (हिन्दी)**.

4. **NER Population Analytics Dashboard**:
   - Visual charts powered by Chart.js showing risk distribution and state-level screening volumes across Assam, Meghalaya, Sikkim, Manipur, Mizoram, Nagaland, Tripura, and Arunachal Pradesh.

5. **Patient Database & CSV Report Generator**:
   - Searchable, filterable patient records with instant CSV clinical report export.

---

## 🏃 Quick Start / Local Development

### 1. Run the Web Application
Open [`index.html`](file:///C:/Users/Admin/.gemini/antigravity/scratch/ai-assisted-oa-risk-detection-ner/index.html) directly in any modern browser, or run a local HTTP server:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

### 2. Run the Streamlit Application
```bash
# Clone the repository
git clone https://github.com/RajeshwariJ2005/ai-assisted-oa-risk-detection-ner.git
cd ai-assisted-oa-risk-detection-ner

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

---

## 📂 Repository Structure

```text
├── index.html                  # Live Single-Page Web Application (GitHub Pages)
├── app.py                      # Multi-page Streamlit Application
├── requirements.txt            # Python dependencies (streamlit, pandas)
├── .gitignore                  # Git ignore rules
├── .devcontainer/              # VS Code Dev Container configuration
│   └── devcontainer.json
├── .vscode/                    # VS Code editor settings
│   └── settings.json
├── data/
│   ├── README.md               # Project documentation
│   ├── app_backup.py           # Backup archive
│   ├── requirements.txt        # Supplementary requirements
│   └── sample_data.csv         # Sample patient data
├── model/
│   ├── __init__.py
│   ├── risk_engine.py          # AI Risk calculation engine
│   └── data/
│       └── utils/
│           ├── __init__.py
│           ├── calculations.py
│           └── database.py     # SQLite persistence
└── utils/
    ├── __init__.py
    └── calculations.py         # Biomechanical gait analysis algorithms
```

---

## ⚠️ Important Note

This system is an academic research and early screening prototype for educational and preventive support. Calculated risk scores and gait classifications do not replace clinical diagnosis by a certified orthopedic specialist or radiologist.
