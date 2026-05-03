📌 Overview

This project simulates a fraud detection scenario in transactional data, with the goal of identifying risk patterns and evaluating detection strategies.

The dataset was synthetically generated to replicate common fraud behaviors, allowing for controlled experimentation and analysis.

🎯 Objectives
Analyze transactional data to detect fraud patterns
Quantify fraud impact
Build features to improve detection
Train a simple classification model
Evaluate business impact through decision thresholds

🧱 Dataset
50,000 transactions
1,000 users
2% fraud rate
30-day simulated period
Simulated fraud types:
High transaction amounts
Country mismatch
New accounts with high spending

🔍 Analysis
Exploratory analysis shows that fraudulent transactions tend to:
Have higher amounts
Be associated with newer accounts
Occur in inconsistent locations

🧠 Feature Engineering

Key features:
Transaction amount vs user average (ratio_monto)
New account flag
Country mismatch

🤖 Modeling
A Logistic Regression model was trained using engineered features.

Results:
High precision and recall
No false positives in this simulated scenario

⚠️ Note: Results are optimistic due to synthetic data.

⚖️ Business Perspective

A scoring system was implemented to:

Assign fraud probability
Define decision thresholds
Balance fraud detection vs user experience

🚧 Limitations
Synthetic dataset
Low noise
Clearly defined fraud patterns

🔮 Future Work
Add noisy and ambiguous cases
Include payment method features
Test more advanced models
Run A/B testing on thresholds

📄 Documentation

Full report available

🛠️ Tech Stack
Python
Pandas
NumPy
Scikit-learn

👤 Author
Juan Manuel Pizzorno
