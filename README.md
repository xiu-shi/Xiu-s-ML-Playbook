
# 🧠 Xiu(Janet)'s ML Playbook

Welcome to my open-source Machine Learning playbook — a curated portfolio of projects that blend data-driven insights with real-world business applications.

This repository reflects my transition from SaaS QA leadership to data-powered consulting, focusing on human-centered AI, scalable ML workflows, and storytelling through code.

---

## 📌 Project Focus

- Supervised Learning (Logistic Regression, SVM, Random Forest)
- Data Cleaning & Feature Engineering
- Exploratory Data Analysis (EDA)
- Model Evaluation (F1, ROC-AUC, Precision/Recall)
- Real-world datasets with business context

---

## 🧭 Project Structure

| Folder | Description |
|--------|-------------|
| `accident_severity_prediction/` | ML model to predict road accident severity in the UK using PCA and classification models |
| `eda_notebooks/` | Visual exploratory analysis and insights generation |
| `model_eval/` | Scripts and experiments with performance metrics |

> *This repo will evolve as I build new ML notebooks and blog content.*

> Data source:
https://www.kaggle.com/datasets/tsiaras/uk-road-safety-accidents-and-vehicles 
Accident_Information.csv: every line in the file represents a unique traffic accident (identified by the Accident_Index column), featuring various properties related to the accident as columns. Date range: 2005-2017
Due to the volume of the Accident_Information.csv and local computing power. Dataset has been intentionally filtered to include data of in Year 2010 only (~115k rows, 34 features).

Acknowledgements
Thanks to data.gov.uk for making this information publicly available. Also thanks to Dave Fisher-Hickey for previously publishing, what I consider to be, the first solid and structured version of this dataset on Kaggle.

UK Road Accident Severity Prediction: Machine Learning Analysis and Classification

Executive Summary
Road traffic accidents represent a significant public health concern globally, with substantial economic and social costs. In the UK, understanding and predicting the severity of road accidents is essential for developing effective safety measures and policies. This report analyzes the 2010 UK road accident dataset to identify patterns and develop predictive models for accident severity.
The analysis employs machine learning techniques to classify accidents into binary categories: "slight" severity versus "serious/fatal" severity. This classification framework enables the application of established machine learning approaches to road safety, where preventing progression from slight to serious/fatal outcomes is the primary goal.
Due to computational constraints, this project utilized random sampling to reduce data size for model experimentation and validation. Multiple sample sizes were tested, ranging from 5,000 to 30,000 rows. This approach enabled faster iteration while maintaining representation of the class distributions and preserving the integrity of the dataset.


---

## 📇 About Me

I'm Xiu (Janet) — the Creative Technologist, the Data Storyteller, the Data-powered Strategist.  
My mission is to bridge cloud, AI, and human impact through education and experimentation.

📍 [LinkedIn](https://linkedin.com/in/janetxiushi)  
📝 [Medium](https://medium.com/@janetxiushi)


---

## 🔧 How to Use

1. Clone the repo:  
   `git clone https://github.com/xiu-shi/Xiu-s-ML-Playbook.git`
2. Navigate to a project folder
3. Launch in Jupyter, Colab, or your preferred IDE

---

## 🛡 License

MIT — feel free to learn, fork, or contribute.
