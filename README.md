# Wine Quality Prediction using Machine Learning

This project aims to predict the quality of red wine using various physicochemical features. The dataset was sourced from the Wine quality dataset from Kaggle and the problem is treated as a **regression task**.

## Project Structure

This notebook is divided into four key milestones, each reflecting a standard machine learning pipeline:

---

## Milestone 1: Data Preprocessing & Exploratory Data Analysis (EDA)

**Objective:** Prepare the dataset and understand the relationships between features.

- Handled missing values and removed duplicates
- Scaled numerical features using `StandardScaler`
- Conducted EDA using:
  - Histograms (feature distributions)
  - Boxplots (outlier detection)
  - Correlation heatmaps (feature relationships)
- Generated summary statistics and initial insights

---

## Milestone 2: Model Selection & Training

**Objective:** Build and train machine learning models to predict wine quality.

- Selected two regression models:
  - Linear Regression
  - Random Forest Regressor
- Split data into training and test sets (80/20)
- Trained and saved model predictions

---

## Milestone 3: Model Evaluation

**Objective:** Evaluate model performance using appropriate regression metrics.

- Used the following metrics:
  - Mean Squared Error (MSE)
  - R-squared (R²)
- Performed 5-fold cross-validation for Random Forest
- Visualized performance using bar charts
- Compared both models and selected the best performer

---

## Milestone 4: Interpretation & Final Report

**Objective:** Interpret model results and extract actionable insights.

- Analyzed feature importance (e.g., alcohol and volatile acidity are strong predictors)
- Summarized key findings and model recommendations
- Suggested future improvements: hyperparameter tuning, feature engineering

---

## Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Machine Learning models (Linear Regression, Random Forest)

---

## Results

- **Best model:** Random Forest Regressor
- **Top features:** Alcohol, Sulphates, Volatile Acidity
- **Conclusion:** Model performs well and can guide wine quality assessment.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/wine-quality-prediction.git
## COLLABORATORS
Maria Wangari Kanene.
Vincent Kimutai Ronoh
Joy Melvine Okinyi
Nasrudin Abdulahhi
