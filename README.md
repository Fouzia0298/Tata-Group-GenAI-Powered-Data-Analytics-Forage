# 🧠 Tata Group - GenAI Powered Data Analytics | Forage Experience

I recently completed the **Tata Group's GenAI-Powered Data Analytics job simulation**, part of the virtual experience program offered by [Forage](https://forage.com/).  This hands-on simulation gave me valuable insight into how AI and data analytics are used in financial services at Tata iQ, focusing on customer delinquency risk modeling, agentic AI systems, and ethical AI practices.

This repository contains:
- Exploratory Data Analysis (EDA)
- Predictive model framework
- AI-driven collections strategy presentation
- Business summary report template
- Supporting documentation and glossary

---

## ✅ What I Did

### 1. **Exploratory Data Analysis (EDA)**
Using GenAI tools, I conducted an exploratory analysis of a dataset containing 500 customer records with features like:
- Credit score, income, loan balance
- Missed payments, employment status
- Credit card type, location
- Monthly payment history

Key findings included:
- Missing values in `Income`, `Credit_Score`, and `Loan_Balance`
- Identification of top 3 risk factors:
  - **Business credit card holders** (21.30% delinquency rate)
  - **Los Angeles residents** (19.63% delinquency rate)
  - **Unemployed individuals** (19.35% delinquency rate)

> I recommended using **MICE imputation** for missing numerical data and explored correlations between variables such as income and delinquency.

📄 [Full EDA Summary Report](Exploratory Data Analysis.docx)

---

### 2. **Predictive Model Framework**
I proposed a **no-code predictive model logic** to assess customer delinquency risk using:

#### ✅ Recommended Model: Gradient Boosting Machine (e.g., XGBoost or LightGBM)
- Chosen for high performance on tabular financial data
- Handles non-linear relationships better than Logistic Regression or Decision Trees
- Evaluated using F1-score, precision, recall, ROC AUC, and fairness checks

#### 📊 Evaluation Strategy
- **Accuracy Metrics**: Accuracy Score, Confusion Matrix
- **Robust Performance Metrics**: Precision, Recall, F1-Score, ROC AUC
- **Fairness Checks**: Disproportionate impact assessment across subgroups, SHAP-based feature importance

📄 [Model Plan & Justification](Task 2.docx)

---

### 3. **AI-Driven Collections Strategy**
I designed a **scalable, responsible AI-powered collections system** leveraging agentic AI and automation, including:

#### 🔁 Learning Loop System Workflow
1. **Input Data** – Customer profile and behavior
2. **Decision Logic** – Risk scoring via predictive model
3. **Action Strategies** – Personalized SMS/email reminders, hardship plans
4. **Feedback Loop** – Continuous improvement based on outcomes

#### 🤖 Role of Agentic AI
| Autonomous Activities | Human Oversight Required |
|-----------------------|--------------------------|
| Real-time risk scoring | Review of high-risk decisions |
| Personalized message generation | Approval of new intervention strategies |
| Feedback loop adjustments | Monitoring fairness metrics |

#### ⚖️ Responsible AI Guardrails
- **Bias Detection & Mitigation** – Regular audits across segments
- **Explainability** – Use of SHAP values for transparency
- **Compliance** – Alignment with ECOA, FCRA, GDPR standards

📊 [Business Summary Report](Updated_Business_Summary_Report_Template.docx)

---

## 🎯 Expected Business Impact

### Quantitative Outcomes:
- Reduce delinquency rates by **10–15% within 6 months**
- Lower collections costs through automation
- Improve recovery rates and portfolio performance

### Qualitative Outcomes:
- More personalized and respectful engagement
- Clearer explanations for decisions affecting customers
- Increased trust through transparency and fair treatment

---

## 🛠 Implementation Roadmap

| Phase | Timeline | Description |
|-------|----------|-------------|
| **Model Validation** | Q2 | Finalize model validation and integrate with CRM |
| **Pilot Launch** | Q3 | Begin testing with business cardholders in Los Angeles |
| **Evaluation & Expansion** | Q4 | Assess results and expand to other high-risk segments |

---

## 📚 Glossary of Key Terms

| Term | Definition |
|------|------------|
| **F1-Score** | Harmonic mean of precision and recall; balances both metrics |
| **SHAP Values** | Tool for explaining machine learning predictions |
| **Agentic AI** | AI that makes autonomous decisions based on goals and context |
| **Bias (in AI)** | Systematic error leading to unfair outcomes for certain groups |
| **ROC AUC** | Measures model's ability to distinguish between classes |
| **MICE Imputation** | Advanced method for handling missing numerical data |

📄 [Tata Data Analytics Glossary](Tata_Data_Analytics_Glossary (1).docx)

---

## 💼 Why This Matters

This simulation provided real-world exposure to how **Generative AI and analytics drive decision-making** in financial services. It helped me understand how to:
- Translate predictive insights into actionable strategies
- Build scalable, ethical AI systems
- Communicate effectively with stakeholders using business reports and presentations

It was a great opportunity to apply theoretical knowledge to practical problems faced by global enterprises like Tata.

---

## 📁 Repository Structure
```
/genai-data-analytics-forage/
│
├── Task 1.docx
├── Task 2.docx
├── Task 3.docx
├── Presentation - AI Innovations in Finance.pdf
└── README.md
```

---

## 🙌 Let's Connect!
If you're interested in this space — AI in finance, predictive modeling, or ethical AI — feel free to reach out!

- **GitHub**: [https://github.com/Fouzia0298]
- **LinkedIn**:[https://www.linkedin.com/in/fouzia-ashfaq/]
