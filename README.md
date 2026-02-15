FIN411X_CAPM_Portfolio_and_AI_Literacy_Project

Replication package for the FIN411X CAPM Portfolio Project integrated with an AI Literacy survey study examining AI use, metacognition, and financial education learning outcomes.

Keywords: AI, Python, Finance Education, DBR (Design-Based Research), CDM, ELT, AI Literacy, CAPM

📌 Project Overview

This project combines:

CAPM Portfolio Analysis (Finance)

Construction and evaluation of investment portfolios.

Estimation of CAPM parameters.

Risk-return analysis and portfolio summaries.

AI Literacy & Metacognition Study (Education Research)

Survey-based analysis of AI (ChatGPT) usage.

Investigation of AI literacy in finance education.

Alignment with Design-Based Research (DBR), Cognitive Diagnostic Modeling (CDM), and Experiential Learning Theory (ELT).

This repository provides all materials necessary to reproduce the computational results and survey-based findings.

📂 Repository Structure
FIN411X_CAPM_Portfolio_and_AI_Literacy_Project/
│
├── code/
│   ├── capm_portfolio_project.ipynb
│   └── portfolio_analysis.ipynb
│
├── data/
│   └── chatgpt_survey_raw.csv
│
├── documentation/
│   ├── chatgpt_survey_instrument.pdf
│   └── python_code_notes.docx
│
├── output/
│   └── summary_all_portfolios.csv
│
├── README.md
├── LICENSE
└── CITATION.cff

🔁 Replication Instructions
Step 1 — Clone the Repository
git clone https://github.com/<your-username>/FIN411X_CAPM_Portfolio_and_AI_Literacy_Project.git
cd FIN411X_CAPM_Portfolio_and_AI_Literacy_Project


Or download as a ZIP from GitHub.

Step 2 — Set Up the Python Environment

Recommended:

Python 3.9+

Jupyter Notebook / JupyterLab / VS Code

Install required packages:

pip install numpy pandas matplotlib seaborn scipy statsmodels


If used in notebooks:

pip install yfinance scikit-learn


(Optional Conda setup)

conda create -n fin411x_env python=3.9
conda activate fin411x_env
pip install numpy pandas matplotlib seaborn scipy statsmodels

Step 3 — Run the Analysis

Open code/capm_portfolio_project.ipynb

Run all cells from top to bottom.

Open code/portfolio_analysis.ipynb

Run all cells sequentially.

Generated outputs will appear in the output/ directory.

📊 Data Description
chatgpt_survey_raw.csv

Exported from Google Forms.

Contains anonymized responses related to:

AI usage

AI literacy

Metacognition

Learning outcomes in finance education

summary_all_portfolios.csv

Generated output file summarizing portfolio performance metrics.

⚠️ All survey data included here is anonymized. No personally identifiable information (PII) is included.

📚 Theoretical Framework

This project is situated within:

CAPM (Capital Asset Pricing Model) — financial risk-return modeling.

Design-Based Research (DBR) — iterative educational design and evaluation.

Cognitive Diagnostic Modeling (CDM) — measuring latent learning constructs.

Experiential Learning Theory (ELT) — applied finance learning through computation.

AI Literacy Frameworks — evaluating responsible AI use in education.

📦 Reproducibility & Archiving

This repository is archived via Zenodo.
Each GitHub release is assigned a DOI for citation and long-term preservation.

To cite this project, see CITATION.cff or the Zenodo DOI badge in this repository.

📄 License

Code: MIT License (see LICENSE)

Data: CC BY 4.0 (unless otherwise specified)

👤 Author

Your Name
Affiliation (if applicable)
ORCID (optional)

