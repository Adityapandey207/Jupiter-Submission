#### Simulate a real world customer behavior data used for predicting the credit score movement [increase, decrease, stable] through classification models.

# Logic
1. Synthetic Data Generation
Developed a dataset of 25,000 rows, each being a customer-month record.
Features are demographics, income, EMIs, credit usage, inquiries, and credit behavior metrics.

2. Target Label Heuristics
Utilized rule-based reasoning to mimic real-world credit score movement:
  Decrease: High DPD, high credit utilization, high hard inquiries frequency.
  Increase: Low EMI-to-Income ratio, high repayment score.
  Stable: All other cases.

3. Model Training & Evaluation
   The model was trained using Random Forest Classifier on preprocessed feature.
   Evaluation was conducted using metrics like accuracy, F1-score and recall.
   Used label encoding for categorical variables.

# Business Takeaways
a. High Risk Segments Traits: High Days Past Due, Utilization > 0.8, Frequent new credit enquiries.
   Interventions: 1) Credit usage alerts, loan restructuring, EMI capping 2) Counseling & monitoring tools for risk users.

b. High opportunity Segments Traits: Strong repayment history, low EMI-to-income ratio, few credit enquiries.
   opportunities: 1) Pre approved credit offers 2) Gamified rewards and loyalty benefits

c. Helps financial institutions in managing risk & retaining good customers.
   Promotes customer financial health by reducing default risk.
