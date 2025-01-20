# Explainable AI-based Diagnosis of Coronary Heart Disease using Machine Learning 🩺💻

This project leverages machine learning techniques to predict and diagnose Coronary Heart Disease (CHD) based on patient data. The key focus of this project is **explainability**, allowing healthcare professionals to understand the reasoning behind the model’s predictions. By utilizing powerful ML algorithms like **CatBoost** and **LightGBM**, the system is capable of handling categorical variables effectively, making it highly applicable in real-world healthcare datasets.

## 📋 Overview

Coronary Heart Disease (CHD) is one of the leading causes of death worldwide, and early diagnosis plays a crucial role in saving lives. In this project, we use **Explainable AI (XAI)** to build a machine learning model that can diagnose CHD based on several clinical factors, including age, blood pressure, cholesterol levels, and more. The goal is to not only predict CHD but also explain the reasoning behind the predictions in an interpretable manner.

### Key Features:
- **XAI Techniques** for transparency in predictions 🧠
- Machine learning models built with **CatBoost** and **LightGBM** 🚀
- Handles **categorical data** and provides high accuracy 🎯
- Suitable for real-world medical datasets 🏥

## ⚙️ Technologies Used

- **Python** 🐍
- **CatBoost**: A powerful gradient boosting algorithm for handling categorical data.
- **LightGBM**: A fast, efficient gradient boosting framework.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For model building and evaluation.
- **SHAP**: For model explainability.
- **Matplotlib** & **Seaborn**: For visualization.
- **Jupyter Notebook**: For easy experimentation.


## ⚡ Usage

Once the dependencies are installed, you can start by running the Jupyter Notebook to train and test the model:

```bash
jupyter notebook
```

Open the notebook and follow the instructions for:
1. Loading the dataset
2. Data preprocessing (handling missing values, encoding categorical features)
3. Model training (CatBoost and LightGBM)
4. Model evaluation
5. Generating explanations using SHAP

## 🧠 Explainability

One of the primary features of this project is to provide **explainable AI**. By using **SHAP** (Shapley Additive Explanations), we generate visualizations to help interpret the model's decisions, such as:
- Which features are most important in making predictions?
- How do different feature values influence the prediction?


## 🔐 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💬 Acknowledgments

- Thanks to the creators of **CatBoost** and **LightGBM** for their exceptional gradient boosting libraries.
- Thanks to **SHAP** for providing powerful explainability tools.
- This project would not be possible without the research and data from the **Framingham Heart Study** and **Cleveland Heart Disease dataset**.

## 🚀 Future Work

- Incorporating other explainability techniques like **LIME**.
- Improving model performance with more advanced hyperparameter tuning.
- Exploring neural network-based approaches for heart disease prediction.

---
