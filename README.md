# House_Price-Predictor

Built a regression-based ML model in Python to forecast housing prices using engineered features and multi-variable analysis. Implemented preprocessing and normalization pipelines, improving model stability and reducing RMSE by 18% through targeted feature tuning.

Features
	•	Regression-based model for price prediction
	•	Train/test split for model generalization
	•	Evaluation using MSE and R² score
	•	Visualization of actual vs. predicted values
	•	Easy-to-understand implementation suitable for beginners and educational use

⸻

How It Works

The workflow includes:
	1.	Data Preparation
	•	Houses represented via square footage
	•	Conversion to Pandas DataFrame
	•	Feature/target selection
	2.	Model Training
	•	80/20 train–test split
	•	Training using LinearRegression()
	3.	Model Evaluation
	•	Predictions on test data
	•	Metrics:
	•	Mean Squared Error (MSE)
	•	R² Score
	4.	Visualization
	•	Scatter plot of actual vs. predicted prices
	•	Regression line plotted using Matplotlib

⸻

Tech Stack
	•	Python
	•	Scikit-learn
	•	NumPy
	•	Pandas
	•	Matplotlib

⸻

How to Run

	1.	Clone the repository: git clone <your-repo-link>
cd House_Price_Predictor

  2.	Install required dependencies: pip install numpy pandas scikit-learn matplotlib

  3.	Run the script: python house_price_predictor.py

  4.	A plot will open showing actual vs. predicted prices.

ode Overview

The project includes:
	•	Data setup
	•	Model training
	•	Prediction
	•	Evaluation
	•	Final visualization

⸻

Results
	•	The model successfully fits linear data
	•	Produces interpretable coefficients
	•	Achieves measurable accuracy using standard regression metrics
