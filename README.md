# Heart_Health_Analysis_Python-EDA_Project
This project was called Pulse of Prevention: Heart Health Analysis. The main objective was to analyze patient health data to understand patterns associated with the presence of heart disease and evaluate a machine learning model for predicting the recorded outcome.

I worked with a dataset containing clinical and demographic information, including age, sex, chest-pain category, resting blood pressure, cholesterol, maximum heart rate, exercise-induced angina, and other clinical measurements.

I used Python as the primary programming language, Pandas and NumPy for data processing, Matplotlib and Seaborn for visualization, SciPy for statistical testing, and Scikit-learn for machine learning.

During the project, I performed data-quality checks, descriptive analysis, correlation analysis, group comparisons, and logistic regression.

One of the main challenges was identifying duplicate records. The dataset contained 723 exact duplicate rows, which could affect the accuracy of the analysis and model evaluation. I learned the importance of removing duplicates and validating data before drawing conclusions.

I also found that several clinical variables had measurable associations with the recorded target. However, I learned that correlation does not prove causation and that a predictive model must be evaluated carefully.

My initial logistic regression model achieved approximately 81% accuracy, but after removing duplicate records, I obtained approximately 80% accuracy on a new test split.

To improve the project, I would use cross-validation, improve categorical feature encoding, validate the model on independent data, and develop a Power BI dashboard to communicate the findings.

Overall, this project strengthened my Python, data-cleaning, statistical-analysis, visualization, and machine-learning skills.
