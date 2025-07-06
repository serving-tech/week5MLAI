# 🧠 AI Development Workflow Project

**Course**: AI in Software Engineering (July 2025)  
**Authors**:  
- Gathigi Moses Muiruri ([gathimoses@gmail.com](mailto:gathimoses@gmail.com))  
- Odongo Isaiah ([odongoreagan19@gmail.com](mailto:odongoreagan19@gmail.com))  
- Keren Hapuch Ninyari ([kerenhapuch68@gmail.com](mailto:kerenhapuch68@gmail.com))  
- Jebichii Joyce ([jebichiijoyce@gmail.com](mailto:jebichiijoyce@gmail.com))  
- Palpable Smart ([palpablee237@gmail.com](mailto:palpablee237@gmail.com))

---

## 📄 Overview

This project presents a comprehensive **AI Development Workflow**, from problem definition to deployment. It includes:

- A **hypothetical case study** on predicting customer churn for a SaaS company.
- A **real-world application** predicting 30-day patient readmission risk in a hospital.
- Insights into **data strategies**, **model development**, **deployment**, and **ethical considerations** in AI.

---

## 📁 Project Structure

The project is organized into four parts:

### Part 1: 🧩 Short Answer Questions
- Focus: Hypothetical SaaS customer churn prediction.
- Topics covered: Problem definition, data collection, preprocessing, model development, evaluation, deployment.

### Part 2: 🏥 Case Study – Hospital Readmission Prediction
- Objective: Predict 30-day readmission risk using EHR data.
- Includes: Data strategies, model selection (Logistic Regression), deployment challenges, and ethical compliance.

### Part 3: ⚖️ Critical Thinking
- Discusses model bias, interpretability vs. accuracy trade-offs, and limitations of computational resources.

### Part 4: 🔄 Reflection & Workflow Diagram
- Challenges encountered and proposed solutions.
- A visual diagram of the AI development workflow stages.

---

## 🔍 Key Features

### 📉 SaaS Customer Churn Prediction
- **Goal**: Reduce monthly churn rate by 25% (e.g., from 4% to 3%).
- **Model**: Gradient Boosting (e.g., XGBoost, LightGBM) for performance and feature insights.
- **Data Sources**: User activity logs, subscription and billing data.
- **Challenges**: Historical bias, concept drift.

### 🏥 Hospital Readmission Risk Prediction
- **Goal**: Improve patient outcomes, reduce costs, and optimize resources.
- **Model**: Logistic Regression for clinical interpretability.
- **Data**: EHR, demographics, discharge info.
- **Ethics**: HIPAA compliance, fair algorithm design.
- **Deployment**: Secure APIs integrated with hospital systems.

---

## ⚙️ Workflow Stages

```mermaid
graph TD;
    A[Problem Definition] --> B[Data Collection];
    B --> C[Data Preprocessing];
    C --> D[Exploratory Data Analysis];
    D --> E[Feature Engineering];
    E --> F[Model Selection];
    F --> G[Model Training];
    G --> H[Model Evaluation];
    H --> I[Hyperparameter Tuning];
    I --> J[Model Validation];
    J --> K[Model Deployment];
    K --> L[Monitoring & Maintenance];
    L --> M[Feedback & Continuous Improvement];
