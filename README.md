# 🕵️‍♀️ Claims Fraud Detection Using Bayesian Networks and XGBoost

## 📌 Project Overview
This project builds a robust fraud detection pipeline for insurance claims using a hybrid approach that combines XGBoost and Bayesian Networks. It processes over 50,000 synthetic insurance claims to identify fraudulent patterns, explain model decisions, and trigger anomaly alerts via a Looker dashboard. The model is deployed on AWS SageMaker with automated retraining capabilities.

## 🎯 Objectives
- Detect fraudulent insurance claims with high accuracy
- Provide interpretable model outputs using SHAP
- Enable real-time anomaly monitoring via Looker
- Automate model retraining and deployment on AWS SageMaker

## 🧠 Methodology
1. **Data Preprocessing**: Clean and encode synthetic claims data.
2. **Modeling**:
   - Train an XGBoost classifier for fraud prediction.
   - Build a Bayesian Network to capture probabilistic dependencies.
3. **Evaluation**:
   - Use ROC-AUC, precision, recall, and F1-score.
   - Achieved 92% AUC on test set.
4. **Explainability**:
   - Integrate SHAP to visualize feature importance and individual predictions.
5. **Deployment**:
   - Use AWS SageMaker for scalable training and inference.
   - Schedule retraining jobs based on new data.
6. **Monitoring**:
   - Push flagged anomalies to Looker dashboard for business review.

## 🧰 Tech Stack
- **Languages**: Python
- **Libraries**: XGBoost, pgmpy, SHAP, Pandas, Scikit-learn
- **Cloud**: AWS SageMaker
- **BI Tools**: Looker
- **Other**: Docker, Git

## 📁 Repository Structure
