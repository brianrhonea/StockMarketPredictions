# Stock Market Prediction with Machine Learning

📖 Project Overview

This project was completed as part of the Applied Machine Learning course and focused on predicting stock market trends using machine learning techniques. My team utilized the Yahoo Finance API to pull stock data for Apple (AAPL), augmented the data with technical indicators, and executed the full data science lifecycle of loading, cleaning, feature engineering, and model setup and evaluation. 

While the project primarily focused on Apple due to its relatively stable price patterns, we designed the workflow to accommodate other ticker symbols for broader application. This automated approach enables the testing and prediction of various stocks.

🔍 Key Project Steps

Phase 1: Data Preparation and Quality Checks

  1.	Data Retrieval:
  •	Used the Yahoo Finance API to import Apple stock data.
  •	Experimented with other ticker symbols to ensure scalability.
  2.	Data Cleaning:
	•	Performed quality checks for duplicates and missing values.
	•	Analyzed the distribution of key columns.
	•	Removed unnecessary columns to streamline the dataset.

Phase 2: Model Development and Testing

  1.	Machine Learning Models:
	•	Tested multiple algorithms to identify the best predictor.
	•	Focused on automating the model to generalize across different stocks.
  2.	Challenges:
	•	A major issue arose with the predictive window setup, leading to overly optimistic accuracy results (99%).

🌟 Highlights and Learnings

  •	Gained experience in using Python for API integration and machine learning.
  •	Explored the data science lifecycle from data retrieval to model evaluation.
  •	Learned the importance of correctly defining predictive windows in time series analysis.

🚀 Future Directions

  •	Fix Predictive Window: Correct the setup to ensure realistic predictions.
	•	Enhance Generalization: Modify the model to accurately predict trends for any stock ticker symbol passed into the workflow.
	•	Experiment with More Features: Add advanced technical indicators and external variables (e.g., market sentiment) to improve model accuracy.

🤝 Acknowledgments

This project was a collaborative effort, and I am deeply grateful to my teammates for their contributions and support. As someone still learning Python and machine learning techniques, I welcome all suggestions for improvement. Thank you for reviewing this project and helping me grow as a data scientist!
