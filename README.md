## Intrusion Detection System (IDS) using Machine Learning
##########################################################################################

ARTICLE-->[IDS.pdf](https://github.com/user-attachments/files/24402348/IDS.pdf)

ARTICLE TRANSLATION-->[IDSt.pdf](https://github.com/user-attachments/files/24402360/IDSt.pdf)

PROJECT REPORT-->[project report.pdf](https://github.com/user-attachments/files/24402365/project.report.pdf)

DATASETS-->https://www.unb.ca/cic/datasets/index.html
## 🚀 Run Project on Google Colab

To ensure easy execution without local setup, this project can be run directly on **Google Colab**.

### Steps to Run:

1. Open the Google Colab notebook.
2. Run all cells **in order** from top to bottom.
3. The Streamlit application (`app.py`) will be launched automatically.
4. A public URL (generated via `trycloudflare.com`) will be displayed in the output.
5. Open the generated URL in your browser to access the application.

> ⚠️ Note:  
> The generated link is temporary and remains active only while the Colab runtime is running.

---

## ▶️ Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/sabaamk1404/IDS_WITH_ML/blob/main/Run_IDS_Project.ipynb)

##########################################################################################

This repository contains the implementation of a Machine Learning–based Intrusion Detection System (IDS) developed as an academic project.

The project is inspired by the research paper:

Intrusion Detection System for Cyberattacks in the Internet of Vehicles Environment

The complete project pipeline has been fully implemented, including data preprocessing, feature selection, class balancing, model training, evaluation, and deployment through a web-based interface.

📌 Project Status (Important)

✅ The project is fully completed.
All stages described in the reference paper have been implemented and tested on multiple benchmark datasets.

However, to keep this GitHub repository lightweight and easy to run, only one trained model is included here for demonstration and evaluation purposes.

The full version of the project, including all trained models and artifacts, is available separately.

📊 Supported Datasets (Fully Implemented)

The complete project was implemented and evaluated on the following datasets:

CIC-IDS-2017

CSE-CIC-IDS-2018

CIC-DDoS-2019

All datasets were processed using the same pipeline:

Data cleaning and normalization

Feature selection

Class imbalance handling (SMOTE / SMOTE-ENN)

Model training and evaluation

🧠 Machine Learning Models (Fully Implemented)

The following models were fully trained and evaluated during the project:

Random Forest

XGBoost

LightGBM

CatBoost

Performance was evaluated using:

Accuracy

Precision (weighted)

Recall (weighted)

F1-score (weighted)

Evaluation summaries are stored as JSON reports.

⚖️ Lightweight GitHub Version (This Repository)

To simplify execution and avoid GitHub file size limitations:

✅ Only one lightweight trained model is included in this repository

❌ Large models and full datasets are intentionally excluded

Included Model

LightGBM model trained on IDS dataset
(Used for demonstration, testing, and evaluation)

This allows instructors to:

Clone the repository

Run the application immediately

Upload sample data

Observe real prediction results

☁️ Full Project Version (Google Drive)

The complete version of the project, including:

All trained models (2017, 2018, 2019)

Large model files

Additional artifacts

is available via Google Drive:

👉 Full project (models and artifacts):
[Google Drive Link – Full Version]

https://drive.google.com/file/d/1p-2PYAGZ9HkvYaKP3IuQt5ZqnfDtfNks/view?usp=sharing

🗂 Repository Structure
IDS_WITH_ML/
│
├── app.py                  # Streamlit web application
├── src/                     # Data processing & training scripts
├── sample_inputs/           # Sample CSV files for testing
├── data/
│   └── fs/                  # Selected feature lists
├── outputs/
│   └── reports/             # Evaluation summaries (JSON)
├── requirements.txt
├── README.md
└── .gitignore

🚀 Running the Project
Local Execution
pip install -r requirements.txt
streamlit run app.py


Then open the provided local URL in your browser.

Google Colab Execution

The project can also be executed on Google Colab:

Clone this repository

Install dependencies

Run the Streamlit application

(Optional) Download full models from Google Drive if needed

🧪 Testing the System

Lightweight sample input files are provided in the sample_inputs/ directory.
These files allow quick testing without downloading full datasets.

🎓 Academic Note

The entire project pipeline has been fully implemented and validated.

This repository provides a simplified deployment version for ease of testing and evaluation.

The full experimental setup and all trained models are preserved separately and can be accessed if required.

This design follows standard Machine Learning and software engineering best practices, including:

Separation of code and large artifacts

Reproducibility

Clear documentation

📄 Reference

Original research paper: IDS.pdf

Translated version: IDSt.pdf

📬 Contact


For questions regarding the full implementation or execution details, please refer to the documentation or the complete project files linked above.




