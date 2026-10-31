# Heart_Health_Analysis_Python-EDA_Project
# 1. Project Overview

Pulse of Prevention: Analyzing Heart Health for Better Outcomes is a Python-based data analysis project created for the fictional healthcare company HealthPulse Analytics.

The project explores patient demographics, clinical measurements and medical indicators to understand patterns associated with the presence of heart disease. It uses descriptive statistics, visualisations, correlation analysis and a logistic regression model to examine how patient characteristics relate to the dataset's heart-disease target variable.

The purpose is to communicate data-driven observations that may support further clinical investigation and preventive-health planning. This is an educational analysis, not a clinical diagnostic tool.


# 2. Business requirements
• Summarise age, sex and clinical measurements.

• Explore relationships between features and heart-disease target.

• Compare records where target = 0 and target = 1.

• Identify exploratory patient profiles and build a baseline logistic regression model.

• Communicate insights and areas for further research.

Stakeholders: management, healthcare providers, data analysts, patients, cardiology research institute and healthcare policymakers.

# 3. Tools and technologies
• Python: main analysis language.

• Jupyter Notebook: execute and document the workflow.

• Pandas / NumPy: data inspection, cleaning and numerical operations.

• Matplotlib / Seaborn: charts and statistical visualisations.

# 4. Key findings from the notebook
• Average age: 54.43 years

• Male-coded records:	713 (69.56%)

• Female-coded records:	312 (30.44%)

• Average resting blood pressure:	131.61 mm Hg

• Average cholesterol: 246.00 mg/dl

• Records with fbs = 1:	153

• Records with exang = 1:	33.66%

• Maximum thalach: 202

# 5. Logistic regression results
• Accuracy:	0.810

• ROC-AUC: 0.930

• Recall for target = 1: 0.91

• Precision for target = 1:	0.76

• F1-score for target = 1: 0.83

# 6. Challenges and recommendations
• Duplicates: 723 exact duplicate rows were detected, but the current notebook does not remove them before analysis. Verify and handle duplicates, then rerun the     analysis.

• Coded categories: Treat fields such as cp, restecg, slope and thal as categorical where appropriate.

• Model validation: Use cross-validation, calibration and threshold review; check for duplicate-driven overlap between train and test data.

• Clinical context: Validate interpretations with qualified healthcare professionals.

• Report precision, recall, F1-score, ROC-AUC and confusion matrix—not accuracy alone.

• Present findings as exploratory patterns, not medical advice or a diagnosis.
