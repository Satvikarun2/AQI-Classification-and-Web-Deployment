📌 Project Overview
This project focuses on classifying air quality based on AQI data into categories such as Good, Moderate, and Hazardous. It includes data preprocessing, model building using machine learning techniques, and deployment through a Streamlit web application for real-time predictions.

🎯 Objectives
Clean and preprocess AQI dataset (handle outliers, missing values, and scaling)

Train multiple classification models and evaluate performance

Classify AQI into labeled categories based on input features

Build and deploy an interactive web app for end-user predictions

🛠️ Technologies & Tools
Language: Python

Libraries:

pandas, numpy – data processing

scikit-learn – ML models (Logistic Regression, Random Forest, SVM, Gradient Boosting)

matplotlib, seaborn – visualization

Streamlit – web deployment

Environment: Jupyter Notebook, Streamlit App

📂 Dataset Description
The dataset contains monthly AQI readings with features such as:

AQI (Air Quality Index value)

Additional attributes: location, time, pollution levels (as applicable)

Target: Categorized AQI labels (Good, Moderate, Poor, etc.)

📊 Key Features
Outlier detection using IQR method

Imputation of missing values

Feature scaling for model compatibility

Training and comparison of multiple classification models

Performance evaluation using confusion matrix and classification report

Web app with interactive input and instant prediction

🚀 How to Run
🔧 Notebook (Model Training)
Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Launch:

bash
Copy
Edit
jupyter notebook AQI\ Classification\ and\ Web\ Deployment.ipynb
🌐 Streamlit Web App
Install Streamlit:

bash
Copy
Edit
pip install streamlit
Run the app:

bash
Copy
Edit
streamlit run app.py
Note: Ensure app.py uses the final trained model and scaler saved from the notebook.

📈 Output Highlights
Cleaned AQI data ready for modeling

Classification accuracy across multiple models

Confusion matrix and performance metrics

A user-friendly web interface for AQI category prediction

🔮 Future Improvements
Extend classification labels using WHO standards

Include weather data (temperature, humidity) as features

Add a map-based interface for city-wise AQI prediction

Deploy app on cloud (e.g., Heroku, AWS)

✍️ Author
Satvik Arun
Postgraduate in Data Science | Machine Learning Engineer

