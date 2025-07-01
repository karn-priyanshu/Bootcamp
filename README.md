# Bootcamp

# 🧪 Data Science Capstone Projects

This repository contains end-to-end **Capstone Projects** covering various domains in **Data Analysis, Machine Learning Modeling, and Visualization**, as part of a comprehensive learning journey in Data Science.

Each project follows the standard capstone structure:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building & Evaluation
- Hyperparameter Tuning
- Power BI Dashboard (optional)
- Reporting

---

## 📁 Projects Included

### 1. **E-Commerce Delivery Prediction**
- **Dataset**: `E_Commerce.csv`
- **Goal**: Predict whether a product will be delivered on time (`Reached.on.Time_Y.N`)
- **Models Used**: Logistic Regression, Decision Tree, Random Forest
- **Techniques**: One-Hot Encoding, Feature Scaling, GridSearchCV for Tuning
- **Evaluation Metrics**: Accuracy, F1-Score, Confusion Matrix

> Perfect for understanding classification problems with categorical features.

---

### 2. **Customer Classification (Car Insurance Claims)**
- **Dataset**: `sample type claim.csv`
- **Goal**: Classify the type of car insurance claim based on claim amount and paid amount.
- **Models Used**: Logistic Regression, Decision Tree, Random Forest
- **Techniques**: Text-based CSV parsing, Label Encoding, Multi-class Classification
- **Evaluation Metrics**: Accuracy, Classification Report, Confusion Matrix

> Ideal for beginners working with semi-structured datasets and text-based files.

---

### 3. **Mobile Price Range Prediction**
- **Dataset**: `data_mobile_price_range.csv`
- **Goal**: Predict mobile phone price range (`0`, `1`, `2`, `3`) based on specs like RAM, battery power, screen size, etc.
- **Models Used**: Logistic Regression, Decision Tree, Random Forest
- **Techniques**: Feature Scaling, Hyperparameter Tuning (GridSearchCV)
- **Evaluation Metrics**: Accuracy, Confusion Matrix, Classification Report

> A great example of multi-class classification using numerical features only.

---

### 4. **Customer Segmentation & Classification**
- **Dataset**: `Customers.csv`
- **Goal**: Analyze customer demographics and build models for classification or segmentation.
- **Techniques**: DOB to Age Conversion, One-Hot Encoding, Missing Value Handling
- **Models Used**: Logistic Regression, Decision Tree, Random Forest
- **Visualizations**: Histograms, Boxplots, Correlation Heatmap

> Excellent for practicing feature engineering from raw demographic data.

---

## 🧾 What You’ll Find in Each Project Folder

| Folder/Item | Description |
|-------------|-------------|
| `*.ipynb` | Jupyter Notebook with full analysis and model building |
| `*.csv` | Cleaned and processed dataset used for modeling |
| `README.md` | (Optional) Individual project description |

---

## 🔧 Tools & Technologies Used

- **Python Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Modeling**: Logistic Regression, Decision Trees, Random Forest
- **Hyperparameter Tuning**: GridSearchCV
- **Visualization**: Matplotlib, Seaborn, Power BI (optional)

---

## 📌 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/Bootcamp.git
```

2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook:
```bash
jupyter notebook <project_notebook>.ipynb
```

---


## ✅ Contributing

If you'd like to contribute improvements or add more projects, feel free to fork this repository and submit a pull request.

---

## 📬 Feedback

Have suggestions or want a specific project expanded? Feel free to open an issue or reach out!

---

## 🚀 Future Plans

- Add model deployment examples (Flask / Streamlit)
- Include time-series forecasting for relevant datasets
- Create a single dashboard to compare all models

