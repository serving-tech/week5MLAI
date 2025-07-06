AI Development Workflow Project
Overview
This project, developed as part of the "AI in Software Engineering" course (July 2025), outlines the AI Development Workflow from problem definition to deployment. It includes a hypothetical case study on predicting customer churn for a Software as a Service (SaaS) company and a real-world application for predicting patient readmission risk in a hospital setting. The document provides detailed insights into data strategies, model development, ethical considerations, and deployment challenges.
Authors

Gathigi Moses Muiruri (gathimoses@gmail.com)
Odongo Isaiah (odongoreagan19@gmail.com)
Keren Hapuch Ninyari (kerenhapuch68@gmail.com)
Jebichii Joyce (jebichiijoyce@gmail.com)
Palpable Smart (palpablee237@gmail.com)

Project Structure
The project is divided into four main parts:

Part 1: Short Answer Questions

Focuses on a hypothetical SaaS customer churn prediction problem.
Covers problem definition, data collection and preprocessing, model development, evaluation, and deployment.


Part 2: Case Study Application

Applies the AI development workflow to predict 30-day patient readmission risk in a hospital.
Discusses data strategies, ethical concerns (e.g., HIPAA compliance, algorithmic bias), model selection (Logistic Regression for interpretability), and deployment strategies.


Part 3: Critical Thinking

Explores ethical considerations and bias mitigation strategies.
Discusses the trade-off between model interpretability and accuracy in healthcare.
Analyzes the impact of limited computational resources on model choice.


Part 4: Reflection & Workflow Diagram

Reflects on challenges in the workflow, such as communication breakdowns and tool integration issues.
Proposes improvements like automation, clearer role definitions, and feedback loops.
Includes a detailed AI development workflow diagram with stages from problem definition to continuous improvement.



Key Features

SaaS Churn Prediction:

Objective: Identify at-risk customers to reduce churn rate by 25% (e.g., from 4% to 3% monthly).
Model: Gradient Boosting Machine (e.g., XGBoost, LightGBM) for high performance and feature importance analysis.
Data Sources: User activity (e.g., login frequency, feature usage) and subscription/billing data.
Challenges: Handling historical bias and concept drift.


Hospital Readmission Risk Prediction:

Objective: Improve patient outcomes, reduce healthcare costs, and optimize clinical resource allocation.
Model: Logistic Regression for interpretability in clinical settings.
Data Sources: Electronic Health Records (EHR), demographic data, and discharge information.
Ethical Considerations: HIPAA compliance, algorithmic fairness to avoid perpetuating health inequities.
Deployment: Secure, HIPAA-compliant API integrated into EHR systems.



Workflow Stages

Problem Definition: Define objectives, stakeholders, and KPIs.
Data Collection: Gather relevant data from appropriate sources.
Data Preprocessing: Clean, normalize, and transform data.
Exploratory Data Analysis (EDA): Identify patterns and anomalies.
Feature Engineering: Create predictive features (e.g., usage frequency, comorbidity index).
Model Selection: Choose suitable algorithms based on use case.
Model Training: Train the model on prepared data.
Model Evaluation: Assess performance using metrics like precision and recall.
Hyperparameter Tuning: Optimize model settings.
Model Validation: Ensure generalization with test sets.
Model Deployment: Integrate into production environments.
Monitoring & Maintenance: Track performance and address concept drift.
Feedback & Continuous Improvement: Iteratively refine the model.

Ethical Considerations

Bias Mitigation: Avoid proxies for protected attributes (e.g., zip codes) and use fairness-aware algorithms like adversarial debiasing.
Healthcare Ethics: Ensure patient privacy (HIPAA compliance) and address health disparities to prevent inequitable resource allocation.

Installation and Usage
This is a theoretical project and does not include executable code. To explore the concepts:

Review the provided PDF document (AI 4 SE..pdf) for detailed explanations.
Use the workflow stages as a guide for developing AI solutions in similar domains.
For practical implementation, refer to the model choices (e.g., XGBoost for churn, Logistic Regression for healthcare) and adapt to your data and infrastructure.

Requirements

Data Sources: Access to relevant datasets (e.g., user activity logs, EHR data).
Tools: Python (for model development), scikit-learn/XGBoost for machine learning, and HIPAA-compliant infrastructure for healthcare applications.
Ethical Compliance: Ensure adherence to regulations like HIPAA for healthcare data.

Future Improvements

Automation: Implement tools to automate repetitive tasks in the workflow.
Role Clarity: Define clear responsibilities to enhance accountability.
Feedback Loops: Schedule regular reviews to monitor progress and model performance.
Training: Provide team members with comprehensive onboarding and documentation.
