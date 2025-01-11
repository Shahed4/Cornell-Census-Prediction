# Census Data Salary Prediction
Predicting whether an individual earns more or less than $50,000 annually based on census data using machine learning. This project leverages demographic, financial, and behavioral features to classify income levels, providing valuable insights into socio-economic patterns.

**Features**
- Binary Classification: Predicts income category (<=50K or >50K).
- Feature Engineering: Utilizes key census attributes like age, education, occupation, and more.
- Machine Learning Pipeline: Includes preprocessing, feature scaling, and model training.
- Performance Optimization: Achieves high accuracy through model tuning and evaluation.

**Tech Stack**
- Languages: Python
- Libraries:
- - Data Processing: Pandas, NumPy
- - Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn, Logistic Regression, Random Forrest Classifier, Gradient Boosting, 
- Tools: Jupyter Notebook

**Dataset**
- Source: Cornell CensusData
- Shape: 30,000+ rows and ~15 features.
- Key Features:
- - Age, Workclass, Education, Marital Status, Occupation, Race, Gender, Hours per Week, Native Country.
- - Target Variable: Income (<=50K or >50K).

**How It Works**
1. Data Preprocessing:
- Handle missing values and outliers.
- Convert categorical features using one-hot encoding.
- Normalize numerical features for better model performance.

2. Feature Engineering:
- Analyze feature importance.
- Create interaction terms where beneficial.

3. Model Training:
- Train models such as Logistic Regression, Random Forest, and XGBoost.
- Perform hyperparameter tuning with grid search and cross-validation.

4. Evaluation:
- Evaluate models using metrics like accuracy, precision, recall, and F1 score.
- Plot ROC curves to visualize model performance.
