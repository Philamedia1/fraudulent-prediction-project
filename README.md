# fraudulent-prediction-project
Build an ML-based fraud detection system for NovaPay to improve fraud accuracy and reduce false positives, ensuring better customer experience, trust, and lower operational/financial fraud impact adaptable as tactics evolve.

## Business Challenge
NovaPay Business Challenges Due to the existing system of using fixed and manual rules for fraud detection and operation, NovaPay is experiencing various forms of challenges, such as:

Missing Real Fraud: Fraudsters continuously evolve their tactics, employing methods such as identity theft, account takeovers, and transaction laundering that the existing static rules are unable to detect. Because these rules never update automatically, the system consistently fails to catch emerging fraud patterns, resulting in direct financial losses through chargebacks and refunds.

Blocking Legitimate Customers (False Positives): The rigid nature of static rules causes the system to flag too many legitimate transactions as suspicious. This blocks genuine customers from completing their payments, frustrating their experience, eroding their trust in the platform, and ultimately driving them toward competitor services.

Regulatory and Compliance Exposure: Lacking the capability to maintain an adequate and explainable fraud control system puts NovaPay at risk of falling short of AML and KYC regulatory requirements. This results in penalties, increased regulatory scrutiny, and reputational damage from the authorities.

These challenges in turn lead to a lack of competitive capability, loss of customer trust, financial losses from penalties and refunds, all of which collectively threaten NovaPay's long-term growth and profitability.

## Identify the target variable for the prediction
The target variable is: Fraud_Label Type: Binary Classification Variable Values: 0 = Legitimate Transaction 1 = Fraudulent Transaction

This variable is derived from: Confirmed fraud investigations Verified chargebacks Customer disputes