#Project Structure
fraud-detection-risk-decision-system/
│
├── notebooks/
│ └── fraud_detection_databricks.ipynb
│
├── data/
│ └── sample_data.csv
│
├── images/
│ ├── dashboard.png
│ └── output.png
│
├── requirements.txt
├── README.md
#  Fraud Detection & Risk Decisioning System

##  Overview
This project demonstrates an end-to-end fraud detection system using machine learning, behavioral feature engineering, and business-driven decision logic.

---

##  Key Features

- Feature engineering (velocity, device trust, location mismatch)
- Rule-based Anomaly Detection with API calling for AI generated insights
- ML-based fraud prediction
- Risk scoring (0–100)
- Risk categorization (Low / Medium / High)
- Decision engine (Allow / OTP / Block)
- Explainability layer based on transaction behavior(API-based)

---

## Architecture

Data → Feature Engineering → ML Model → Risk Score → Decision → Explanation → Dashboard

---

##  Sample Output

| Amount | Risk Score | Risk Level | Action | Explanation |
|--------|-----------|------------|--------|-------------|
| 100000 | 92 | High | Block | High velocity + new device + foreign |

---

## Tech Stack

- Databricks (PySpark)
- Python
- Machine Learning
- Power BI (Dashboard)
- OpenAI (for explanation layer)

---

## Note on API Usage

OpenAI API key is not included for security reasons.

---

## Business Impact

- Improved fraud detection using behavioral features
- Reduced false positives through risk-based decisioning
- Enabled explainable AI for analyst support

---

##  Author

[Nisha Roy]
