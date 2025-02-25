Brent Oil Price Analysis
📌 Project Overview
This project analyzes how major political and economic events impact Brent crude oil prices. The study focuses on understanding the fluctuations in oil prices due to geopolitical decisions, conflicts in oil-producing regions, international sanctions, and OPEC policy changes.
The insights generated from this analysis can help investors, policymakers, and energy companies make informed decisions, manage risks, and predict market trends effectively.
🎯 Objectives
The project is divided into three main tasks:
1.	Data Analysis Workflow & Understanding the Model
o	Define the steps for analyzing Brent oil prices.
o	Understand time series models (ARIMA, GARCH) and Bayesian inference.
o	Identify assumptions, limitations, and communication channels for insights.
2.	Exploratory Data Analysis & Time Series Forecasting
o	Perform data preprocessing, visualization, and trend analysis.
o	Implement statistical and machine learning models: 
	ARIMA & GARCH for time series forecasting.
	Bayesian inference (PyMC3) for uncertainty estimation.
	LSTM (Neural Networks) for deep learning-based predictions.
o	Explore the impact of economic indicators and technological factors on oil prices.
3.	Interactive Dashboard Development
o	Build a Flask API (backend) to serve data and model predictions.
o	Develop a React-based frontend to visualize key trends and correlations.
o	Implement interactive features like filters, event markers, and time range selection.
📊 Dataset
•	Source: The dataset contains historical daily Brent crude oil prices.
•	Timeframe: May 20, 1987 – September 30, 2022.
•	Columns: 
o	Date: The date of the recorded oil price.
o	Price: The price of Brent crude oil in USD per barrel.
🔧 Technologies Used
•	Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, PyMC3, Scikit-learn, TensorFlow)
•	Time Series Analysis (ARIMA, GARCH, Bayesian Inference, LSTM)
•	Econometrics & Statistical Models (VAR, Markov-Switching Models)
•	Backend: Flask (for API development)
•	Frontend: React (for interactive visualization)
•	Visualization: Recharts, D3.js, Chart.js
📌 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/Yitayalk/BrentOilPriceAnalysis.git
cd BrentOilPriceAnalysis
2️⃣ Create a Virtual Environment & Install Dependencies
python -m venv bopaven
source env/bin/activate  # On Windows use 'env\Scripts\activate'
pip install -r requirements.txt
3️⃣ Run Exploratory Data Analysis
python notbooks/data_analysis_and_visualization.ipynb
4️⃣ Train Time Series Models
python notbooks/time_series_modeling.ipynbpy
5️⃣ Start Flask API (Backend)
python app.py
6️⃣ Start React App (Frontend)
cd frontend
npm install
npm start
📈 Key Features
•	Historical Trend Analysis: View past oil price movements and patterns.
•	Event Impact Analysis: Identify how major events influenced oil prices.
•	Forecasting: Predict future oil prices using ML and Bayesian inference.
•	Interactive Dashboard: Explore price trends, forecasts, and event-based impacts.

