# AI-Assisted Early Detection System for Osteoarthritis (OA) Risk Markers (NER)

AI-Assisted Early Detection System for Osteoarthritis (OA) Risk Markers in North Eastern Region (NER).

## Project Overview

OA Early Detection System is an academic prototype designed to screen and analyze the risk of Osteoarthritis (OA) using patient information, questionnaire responses, and gait parameters.

## Main Features

* **Patient Registration**: Capture patient demographics and clinical baseline.
* **OA Questionnaire**: Interactive questionnaire to record symptomatic pain and joint stiffness.
* **Gait Assessment**: Record and evaluate gait metrics.
* **OA Risk Assessment**: Compute risk scores and risk categories based on multi-parameter analysis.
* **Patient Report & Search**: Query patient history, inspect risk breakdowns, and delete entries.
* **CSV Report Download**: Export patient screening reports directly to CSV.
* **Dashboard & Charts**: Visual data summaries and gait analysis metrics.

## Technologies Used

* Python 3
* Streamlit
* Pandas
* SQLite
* HTML / CSS
* Browser Speech Synthesis

## Gait Parameters

The system analyzes:
* Walking Speed
* Stride Length
* Cadence
* Step Count
* Gait Variability

## Risk Assessment

The prototype considers:
* Age
* BMI
* Pain Level
* Questionnaire Score
* Gait Score

## Getting Started

### Prerequisites

Ensure you have Python 3.10+ installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RajeshwariJ2005/ai-assisted-oa-risk-detection-ner.git
   cd ai-assisted-oa-risk-detection-ner
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Important Note

This is an academic and screening demonstration prototype. The calculated risk score and gait classification are intended for early screening support and educational purposes; they do not constitute a definitive medical diagnosis and should not replace clinical evaluation by a certified healthcare professional.

## Project Structure

```text
├── app.py
├── index.html
├── requirements.txt
├── .gitignore
├── .devcontainer/
│   └── devcontainer.json
├── .vscode/
│   └── settings.json
├── data/
│   ├── README.md
│   ├── app_backup.py
│   ├── requirements.txt
│   └── sample_data.csv
├── model/
│   ├── __init__.py
│   ├── risk_engine.py
│   └── data/
│       └── utils/
│           ├── __init__.py
│           ├── calculations.py
│           └── database.py
└── utils/
    ├── __init__.py
    └── calculations.py
```
