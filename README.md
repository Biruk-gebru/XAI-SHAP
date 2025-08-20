# XAI-SHAP
## 📈 Project Overview
This project explores the use of **SHAP (SHapley Additive exPlanations)** to interpret and compare the predictions of two different machine learning models: **Logistic Regression** and **Random Forest**. The goal is to understand how each model makes its decisions and which features are most important.

## 📊 Data
The analysis uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**. This dataset contains features computed from digitized images of breast mass, which are used to classify tumors as either benign or malignant.

## 🔬 SHAP Analysis
SHAP plots were used to provide explanations for the model predictions. The following visualizations are included in the project:

* **Beeswarm Plots**: Used to show overall feature importance and the distribution of feature effects on the model's output.
* **Waterfall Plots**: Used to explain individual model predictions.
* **Force Plots**: Also used to explain individual predictions in a different visual format.

Detailed descriptions and interpretations of each plot type can be found within the project notebooks.

## ✨ Summary of Results
The analysis highlights key differences in how the two models operate:
* The **Logistic Regression** model relies heavily on a few key features for its predictions, making it highly interpretable but potentially less robust.
* The **Random Forest** model distributes feature importance more broadly, capturing complex, non-linear relationships and leading to more nuanced predictions.

***

### 💻 Note on Force Plots
Since the JS package of the force plot isn't supported by GitHub's markdown, a static image of the plot is provided below for reference.
<img width="1803" height="262" alt="Screenshot from 2025-08-20 10-24-17" src="https://github.com/user-attachments/assets/4fb344aa-5a5c-4f6c-9098-78394382f12d" />
