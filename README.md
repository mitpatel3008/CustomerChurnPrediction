🧠 Project Overview

This project aims to predict customer churn in a telecom company using a Deep Neural Network (DNN) model. By analyzing customer demographics and service usage data, the model helps identify users likely to leave the service, supporting retention strategies and revenue protection.

⸻

📂 Dataset

The dataset includes 7,032 telecom customer records with features such as demographics, tenure, service plans, and billing information.
Each record is labeled as:
	•	1 → Churned (customer left the service)
	•	0 → Retained (customer stayed active)

Dataset Source: Telco Customer Churn Dataset (Kaggle)

⸻

⚙️ Project Workflow
	1.	Data Preprocessing
	•	Handled missing values and encoded categorical variables via One-Hot Encoding.
	•	Scaled numerical features using MinMaxScaler for faster gradient convergence.
	2.	Model Development
	•	Built a Sequential DNN with 3 hidden layers (150 neurons each) using ReLU activation.
	•	Applied Dropout (28%) and EarlyStopping callbacks to reduce overfitting.
	3.	Training and Evaluation
	•	Split data using an 80-20 ratio with train_test_split.
	•	Achieved 78% accuracy, 78% precision for non-churn, and 69% precision for churn predictions.

⸻

🧰 Technologies Used
	•	Programming Language: Python
	•	Libraries: Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn
	•	Key Modules: MinMaxScaler, train_test_split, Sequential, Dropout, EarlyStopping

⸻

📊 Results
	•	Achieved 78% overall accuracy with balanced precision and recall across classes.
	•	The model demonstrated consistent performance on unseen data and helped highlight key churn indicators.

⸻

🚀 Future Improvements
	•	Implement hyperparameter tuning using GridSearchCV or Keras Tuner.
	•	Experiment with XGBoost or ensemble models for higher accuracy.
	•	Deploy the model with a Flask dashboard for interactive prediction.
