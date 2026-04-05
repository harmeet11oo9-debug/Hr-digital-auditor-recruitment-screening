# 🤖 The Digital Auditor: AI-Driven Recruitment Screening

[](https://www.python.org/)
[](https://scikit-learn.org/)
[](https://en.wikipedia.org/wiki/People_analytics)

## 💼 Case Scenario: Scaling Talent Acquisition

In high-volume recruitment, HR teams are often overwhelmed by thousands of applications. Manual screening is not only slow but also prone to "Decision Fatigue," where the 100th resume is reviewed with less consistency than the 1st.

**The Problem:** A growing organization needs to automate the initial 80% of resume screening to ensure that recruiters only spend their time interviewing high-potential candidates.

**The Solution:** This project implements a **Decision Tree Classifier** that acts as a **Digital Auditor**. It evaluates candidates based on objective metrics—Skills, Experience, and Education—to provide an instant, unbiased "Shortlist" recommendation.

-----

## 🚀 Key Business Features

  * ⚖️ **Bias Mitigation**: By focusing on hard skills and tenure, the model ignores subjective "gut feelings," ensuring every candidate is judged on the same criteria.
  * 📈 **Efficiency at Scale**: Capable of processing thousands of candidate profiles in seconds, reducing the "Time-to-Hire" metric significantly.
  * 🧠 **Explainable AI (XAI)**: Unlike "black-box" models, this Auditor provides clear reasoning for every rejection or approval, essential for HR compliance and candidate feedback.

-----

## 📊 Analytics & Visual Insights

### **1. Strategic Hiring Drivers**

This visualization identifies which candidate attributes are actually driving the hiring decision. In this model, **Technical Skill Scores** and **Years of Experience** carry the most weight, proving that the AI is aligned with professional merit.

### **2. Model Audit: Accuracy vs. Actual Hiring**

The following **Decision Matrix** validates the reliability of the Auditor. By comparing AI predictions against historical top-performer data, we ensure the system identifies "A-Player" talent with high precision while minimizing the risk of "False Rejections."

-----

## 🛠️ Technical Implementation

  * **Dataset**: 32,000+ candidate records (Experience, Age, Education, Skill Ratings).
  * **Algorithm**: **Decision Tree Classifier** (chosen for its "Flowchart-like" transparency for HR stakeholders).
  * **Logic Engine**: Implemented custom hiring thresholds to mirror organizational standards.

-----

## 📁 Repository Structure

```text
├── recruitment_data.csv        # Secure Candidate Data (32K+ Records)
├── HR_Recruitment_AI.ipynb     # End-to-End Screening Pipeline
├── Eligibility_Factors.png     # Visual: Feature Importance Analysis
├── Confusion_Matrix.png        # Visual: Model Reliability Audit
└── README.md                   # Project Documentation
```

-----

## 🎯 Strategic Objective

  * **Reduce Operational Cost**: Automate repetitive manual screening tasks.
  * **Standardize Quality**: Ensure a consistent "Hiring Bar" across all departments.
  * **Ethical Governance**: Build a transparent, auditable bridge between Data Science and Human Resources.

## 🌍 Domain

**People Analytics | Talent Acquisition | Ethical AI**

-----

### **How to Use This Project**

1.  **Inference**: Use the `predict()` function in the notebook to screen new batch uploads.
2.  **Audit**: Run the **Bias Check** cell to ensure the model remains fair across different age demographics.
3.  **Deploy**: The model is ready to be integrated into an existing **ATS (Applicant Tracking System)**.
