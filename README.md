Steel Ms Temperature Prediction using Machine Learning

Overview

This project develops a machine learning regression model to predict the Martensite Start Temperature (Ms) of steel alloys based on their chemical composition.

The model learns the relationship between alloying elements and the Ms temperature using Linear Regression.

Dataset

The dataset contains chemical compositions of different steel alloys along with their measured Ms temperature.

Input Features
	•	C (Carbon)
	•	Mn (Manganese)
	•	Si (Silicon)
	•	Cr (Chromium)
	•	Ni (Nickel)
	•	Mo (Molybdenum)
	•	V (Vanadium)
	•	Co (Cobalt)
	•	Al (Aluminium)
	•	W (Tungsten)
	•	Cu (Copper)
	•	Nb (Niobium)
	•	Ti (Titanium)
	•	B (Boron)
	•	N (Nitrogen)

Target Variable
	•	Ms (K) — Martensite Start Temperature


Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	scikit-learn
	•	Google Colaboratory

  Machine Learning Workflow
	1.	Data preprocessing
	•	Load dataset
	•	Remove unnecessary columns
	•	Select features and target variable
	2.	Train–test split
	•	80% training data
	•	20% testing data
	3.	Model training
	•	Linear Regression model trained on alloy composition data
	4.	Model evaluation
	•	Mean Squared Error (MSE)
	•	R² Score

