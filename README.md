# Capstone-Project

This project is part of the IBM Data Science Professional Certificate Capstone on Coursera. The goal was to predict whether the Falcon 9 first stage booster will successfully land, which has significant cost implications for SpaceX and potential competitors in the space launch market.

### Data Collection
- Scraped SpaceX launch data using public APIs and `BeautifulSoup`.
- Combined with publicly available datasets to enrich the data.

### Data Wrangling
- Cleaned and structured the dataset using `Pandas` for analysis.

### Exploratory Data Analysis (EDA)
- Performed EDA using `Matplotlib` and `Seaborn`.
- Identified key features affecting landing outcomes.

### Feature Engineering
- Created relevant features like:
  - Payload Mass
  - Orbit Type
  - Launch Site
  - Boosters used
  - Flight number

### Machine Learning Models:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### Model Evaluation
- Evaluated models using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

### Hyperparameter Tuning
- Optimized model performance using `GridSearchCV`.

### Tech Stack
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, BeautifulSoup  
- **Tools**: Jupyter Notebook, APIs
