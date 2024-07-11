# Cloud_burst_prediction

This project aims to predict the occurrence of cloud bursts using a Random Forest Classifier. 
It includes data preprocessing, exploratory data analysis (EDA), model training and evaluation, and a graphical user interface (GUI) for user interaction.

1.Clone the repository:
git clone <repository_url>
cd <repository_name>

2.Ensure you have the dataset:
Place your dataset file "cloudpredictionsystemproject.csv" in the project directory.

Project Structure:
cloud-burst-prediction/
├── data/
└── cloudpredictionsystemproject.csv
├── CloudBurstPredictionSystem.py
└── README.md
->data/: Contains the dataset file.
->CloudBurstPredictionSystem.py: Handles data preprocessing, model training, and evaluation.
->README.md: Project documentation.

Features:
•	Data preprocessing: Converts dates, encodes categorical variables, handles missing values, and standardizes numerical features.
•	Exploratory Data Analysis (EDA): Visualizes distributions, correlations, and histograms.
•	Model Training: Uses a Random Forest Classifier with evaluation metrics like accuracy, confusion matrix, ROC curve, and precision-recall curve.
•	GUI: Allows users to input weather data and receive predictions on cloud burst likelihood.
