# Development of an Explainable Machine Learning Model for Early Heart Disease Risk Prediction in Rural Kenya

**Undergraduate Data Science Research Project**  
**Author:** Arlen Wambugu Ngahu  
**Institution:** United States International University - Africa (USIU-Africa)  
**Semester:** Spring 2026


## Project Overview

Cardiovascular disease (CVD) is the leading cause of death in Kenya and across sub-Saharan Africa. Despite this alarming reality, existing risk prediction tools such as the Framingham Risk Score and QRISK were developed using data from high-income Western populations. These models often fail to accurately predict risk in Kenyan communities due to significant differences in lifestyle, genetics, diet, environmental exposures, and healthcare access — particularly in rural and low-income areas.

This project addresses this critical gap by developing an **explainable machine learning model** specifically designed for **rural and low-income Kenyan populations**. Using the approved individual-level microdata from the **2015 Kenya STEPwise Survey** (a nationally representative dataset of approximately 4,500 adults), the study aims to create a practical, transparent, and fair tool that can help identify individuals at high risk of heart disease **before** they develop serious complications such as heart failure.

### Why This Project Matters
- Only 45.6% of Kenyan adults have ideal cardiovascular health (Oguta et al., 2024).
- Heart failure patients in Kenya are relatively young (mean age 52.3 years) and experience high mortality rates (Varwani et al., 2025).
- Late detection remains a major challenge, especially in rural areas with limited healthcare infrastructure.
- Current global models show bias and reduced performance when applied to African populations.

This research moves beyond simply importing foreign models. It builds a **locally relevant, interpretable, and fair** machine learning solution using real Kenyan data, with a strong focus on rural-urban equity.

### Core Objectives
- Develop a binary classification model to predict heart disease risk using Kenyan data.
- Ensure high interpretability using SHAP (SHapley Additive exPlanations) so community health workers can understand and trust the predictions.
- Evaluate model fairness between rural and urban populations.
- Provide actionable insights and recommendations for integration into low-resource health systems.


## Technologies & Tools

- **Language**: Python 3
- **Models**: Random Forest and XGBoost
- **Interpretability**: SHAP (SHapley Additive exPlanations)
- **Libraries**: pandas, NumPy, scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn
- **Environment**: Google Colab
- **Documentation**: Mendeley (APA 7th)


## Repository Structure
├── notebooks/               # Jupyter notebooks (step-by-step analysis)
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── 03_Model_Training.ipynb
│   └── 04_SHAP_Interpretation.ipynb
├── src/                     # Python scripts
├── data/                    # (Not uploaded - contains approved microdata)
├── results/                 # Model outputs, SHAP plots, metrics
├── figures/                 # Flowcharts and visualizations
├── reports/                 # Final proposal and documentation
├── requirements.txt
└── README.md

## Key Features

- Uses real, nationally representative Kenyan data (2015 STEPwise microdata)
- Focus on rural-urban fairness evaluation
- Full model interpretability with SHAP explanations
- Reproducible and well-documented code
- Practical recommendations for low-resource settings

## Expected Impact

- A transparent model that community health workers can understand and use
- Better early detection of cardiovascular risk in rural Kenya
- Evidence to support data-driven public health policies
- Contribution to health equity in Kenya and similar African contexts
- Open-source contribution to the growing field of locally relevant AI in healthcare

## Citation
Ngahu, A. W. (2026). Development of an Explainable Machine Learning Model for Early Heart Disease Risk Prediction in Rural and Low-Income Kenyan Populations [Undergraduate Research Proposal]. United States International University - Africa.