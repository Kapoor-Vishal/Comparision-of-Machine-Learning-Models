# Comparision-of-Machine-Learning-Models

Group Presentation Video - https://drive.google.com/file/d/1RVGIsbqc0ySXUD3HS7_wfEc1LVJF1d3T/view?usp=sharing

Self Presentation Video - https://drive.google.com/file/d/1SU-3_Ieo9JFsmBxlKm_Ggp02P-ZFM3WW/view?usp=sharing

# 🔍 Bank Marketing Campaign – Model Comparison and Optimization

## 🧠 Project Overview

This project focuses on predicting the success of a marketing campaign for a Portuguese bank using machine learning. The objective is to identify whether a customer will subscribe to a term deposit based on their profile and interaction history.

We evaluated multiple classification models, tuned them for optimal performance, and compared their results using both code and dashboard visualizations.

🎯 **Goal:**

Build a robust model comparison framework that not only evaluates models before and after hyperparameter tuning but also provides actionable visual insights for stakeholders via a Power BI dashboard.

---

## ⚙️ Key Features & Technologies

### 📌 Key Functionalities

- 🔍 Comparative evaluation of **7 classification models**
- 🛠️ Automated **hyperparameter tuning** (GridSearchCV)
- 📈 **Performance metrics tracked**: Accuracy, Precision, Recall, F1 Score, ROC AUC, R² Score
- 🔁 Pre- and post-tuning comparisons
- 📊 Dashboard-ready visuals: bar charts, ROC curves, radar plots, heatmaps
- 📤 Exportable CSV results for integration with Power BI
- 🧼 Clean, modular code with markdowns and separation of concerns

### 🧰 Technologies Used

- **Python**: Core programming language
- **scikit-learn**, **XGBoost**: Model training & tuning
- **pandas**, **NumPy**: Data manipulation
- **matplotlib**, **seaborn**: Data visualization
- **Power BI**: Dashboard creation
- **Jupyter Notebook**: Interactive development

---

## 🚀 Setup Instructions

### ✅ Prerequisites

Ensure the following are installed:

- Python 3.8+
- Jupyter Notebook or JupyterLab
- The following Python libraries:
    
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost
    ```
    

### 🛠️ Running the Project

1. Clone the repository or download the notebook:
    
    ```bash
    git clone https://github.com/your-username/bank-marketing-model-comparator.git
    cd bank-marketing-model-comparator
    ```
    
2. Launch the notebook:
    
    ```bash
    jupyter notebook bank_marketing_model_comparator_cleaned.ipynb
    ```
    
3. Follow the notebook:
    - Preprocessing → Baseline Evaluation → Hyperparameter Tuning → Post-Tuning Evaluation → Visualization
4. To export visuals for Power BI:
    - Run the image export cells (already included)
    - Use the exported `.png` or `.jpg` images in your Power BI dashboard
5. For Power BI data:
    - Use the final exported CSV file: `final_model_comparison.csv`

---

## 📊 What We Achieved

✅ Built a robust, extensible pipeline to:

- Train & evaluate multiple models consistently
- Objectively compare models using interpretable metrics
- Tune hyperparameters and quantify performance improvements
- Generate ready-to-import visuals for Power BI

### 🧪 Results Summary:

- **Best model before tuning**: Gradient Boosting (Highest Accuracy & ROC AUC)
- **Most improved model after tuning**: XGBoost (Significant gain in F1 & Recall)
- **Insights visualized**: ROC curves, radar plots, precision-recall bars, heatmaps

---

## 🏆 Why This Project Stands Out

- 🔍 Full transparency: All metrics before and after tuning
- 📊 Dashboard-first approach: Visuals for non-technical audiences
- 💡 Insight-driven: We go beyond accuracy to emphasize business relevance (recall/precision)
- 🧪 Reproducibility: All code is modular, reusable, and commented
- 📂 Power BI-ready assets: CSV + visual exports included

---

## 📬 Contact

For questions or feedback, reach out at vishalkapoor9803@gmail.com
