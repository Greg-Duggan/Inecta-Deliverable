# Inecta-Deliverable
📦 AI-Powered Predictive Procurement Engine
Developer: Gregory Duggan | Domain: ERP & Supply Chain Analytics

🎯 The Business Problem
Traditional ERP systems (like SAP, Oracle, or Microsoft Dynamics) are often reactive. They tell you what was sold yesterday, but they don't always predict what you will need tomorrow. This leads to:
Stockouts: Lost revenue because items aren't on the shelf.
Overstock: Wasted capital tied up in slow-moving inventory.

🚀 The AI Solution
I developed a predictive tool that transforms raw ERP transaction logs into a Forward-Looking Procurement Plan. By combining historical data with Machine Learning, the system identifies stock-out risks before they happen.

Key Features:
Sales Velocity Calculation: Automatically calculates the "Daily Movement" of numerous different SKUs across many store locations.
Predictive Modeling: Utilizes a Random Forest Regressor to identify seasonal trends and sales patterns.
Automated Reorder Triggers: A logic engine that flags an item for reorder the moment Current Stock < 14-Day Predicted Demand.

🛠️ Technical Stack
Language: Python
Libraries: Pandas (Data Engineering), Scikit-Learn (Machine Learning), Matplotlib (Visualization).
Data Handling: Excel/CSV Ingestion (ERP-style exports).

📊 Project Results
Accuracy: Achieved a high correlation between predicted and actual sales (see "AI Model Accuracy" chart below).
Actionable Output: The system generates a timestamped Procurement Alert Report (.xlsx) ready for use by purchasing departments.

🖼️ Visual Proof

AI Accuracy Plot: ![Model Accuracy]<img width="761" height="600" alt="image" src="https://github.com/user-attachments/assets/bd78902b-0cca-4dd5-b72c-0235c016b7a2" />
)
)

The Procurement Report: ![Final Report](<img width="798" height="238" alt="image" src="https://github.com/user-attachments/assets/c4868947-1158-4ee5-9f24-ca402d3bdc6a" />
)
