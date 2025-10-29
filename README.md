# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Overview
This project aims to detect fraudulent credit card transactions using **Machine Learning**.  
The system analyzes transaction patterns and identifies anomalies to distinguish between **legitimate** and **fraudulent** transactions.  
It uses a **Random Forest Classifier** to achieve high precision and recall, helping financial institutions reduce risk and flag suspicious activities early.

---

## 🎯 Objective
To develop a reliable and efficient fraud detection model that:
- Accurately identifies fraudulent transactions.
- Handles imbalanced datasets effectively.
- Minimizes false positives (valid transactions marked as fraud).
- Maximizes recall (detects as many frauds as possible).

---

## ⚙️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
- **Tools:** Jupyter Notebook / Google Colab  

---

## 🧩 Dataset
The dataset consists of **284,807 transactions** and **31 features**, including:
- `Time` — The seconds elapsed since the first transaction.  
- `V1–V28` — Features generated through PCA (to protect sensitive data).  
- `Amount` — The monetary value of the transaction.  
- `Class` — Target variable (`0` = Normal, `1` = Fraud).  

The dataset is highly **imbalanced**, with fraudulent transactions making up only **0.02%** of the total.

📂 **Source:** [Kaggle – Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## 🧠 Project Workflow
1. **Importing Libraries** – Load Python packages for data manipulation, visualization, and modeling.  
2. **Loading the Dataset** – Read and explore data to understand its structure and attributes.  
3. **Data Exploration** – Analyze class distribution and transaction patterns.  
4. **Feature Analysis** – Study correlations and visualize relationships using heatmaps.  
5. **Data Preparation** – Split data into training and testing sets.  
6. **Model Building** – Train a Random Forest Classifier to detect fraud.  
7. **Model Evaluation** – Assess performance using accuracy, precision, recall, F1-score, and MCC.  
8. **Visualization** – Plot confusion matrix and other charts for better interpretation.  

---

## 📊 Key Insights
- Fraud cases represent **less than 0.02%** of total transactions.  
- Fraudulent transactions often have **higher average amounts**.  
- The model achieves high **accuracy** and **precision**, ensuring minimal false alerts.  
- **Recall** can be improved further through data resampling techniques.

---

## 📈 Evaluation Metrics
| Metric | Description | Result |
|---------|-------------|--------|
| **Accuracy** | Percentage of correct predictions | 99.96% |
| **Precision** | Correctly predicted frauds among predicted frauds | 98.73% |
| **Recall** | Correctly detected frauds among all actual frauds | 79.59% |
| **F1-Score** | Balance between precision and recall | 88.14% |
| **MCC** | Balanced score for imbalanced datasets | 0.8863 |

---

## 🚀 Future Improvements
- Apply **SMOTE** or **ADASYN** to handle class imbalance.  
- Experiment with other models like **XGBoost**, **LightGBM**, or **Logistic Regression**.  
- Perform **hyperparameter tuning** for better recall and precision balance.  
- Deploy the model using **Flask**, **FastAPI**, or cloud services like **AWS SageMaker** for real-time fraud detection.

---

## 🧾 Visualizations
- **Correlation Heatmap** – Understand relationships between features.  
- **Class Distribution Chart** – Visualize imbalance in the dataset.  
- **Confusion Matrix** – Measure model performance in detecting fraud.  

---

## 💻 How to Run
1. Clone this repository to your local system.  
2. Install required dependencies from `requirements.txt`.  
3. Download the dataset from Kaggle and place it in the project directory.  
4. Run the notebook or script to train and test the model.  
5. Analyze the performance metrics and visualizations.  

---

## 🧑‍💻 Author
**Gurajala Sai Kiran**  
🎓 B.Tech in Computer Science (AI & ML) | B V Raju Institute of Technology  
🔗 [LinkedIn](#) | [GitHub](#)

---

## 🪪 License
This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with appropriate credit.

---

## ⭐ Acknowledgements
- **Dataset:** [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
- **Reference:** [GeeksforGeeks – Credit Card Fraud Detection Project](https://www.geeksforgeeks.org)
