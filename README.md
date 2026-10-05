# Kanmalai-tech-internship-report
AI Admission Predictor – Internship Project

📌 Project Overview

AI Admission Predictor is a Machine Learning-based web application developed during my internship to predict the expected number of student admissions for a college.

The application takes 7 important factors as input and uses a trained Random Forest Regression model to generate an estimated admission count. The prediction is visualized using interactive charts, helping colleges make better decisions regarding seat planning, staff requirements, and infrastructure.

«Note: The model was trained and evaluated using a generated practice dataset. The predictions are intended for learning and decision-support purposes and are not guaranteed real-world admission forecasts.»

🎯 Objectives

- Predict expected college admissions using Machine Learning.
- Analyze multiple factors that can influence admissions.
- Compare different regression algorithms.
- Provide an easy-to-use web interface for predictions.
- Visualize predictions using charts.
- Demonstrate the deployment of an ML model as a web application.

📊 Input Features

The model uses the following 7 factors:

1. Applications Received
2. Seats Available
3. Placement Percentage
4. Advertisement Budget
5. Courses Available
6. Annual Fees
7. Last Year's Admissions

🤖 Machine Learning Model

Two regression models were compared:

Model| MAE| R² Score
Linear Regression| 88.33| 0.619
Random Forest Regression| 56.97| 0.820

Based on the practice dataset, Random Forest Regression performed better because it achieved a lower MAE and higher R² score.

Why Random Forest?

Random Forest combines multiple decision trees and can capture complex relationships between different input factors better than a simple linear model.

⚙️ How the Application Works

User enters 7 factors
        ↓
Web Form
        ↓
Flask Backend / API
        ↓
Input Validation
        ↓
Trained Random Forest Model
        ↓
Admission Prediction
        ↓
Seat Capacity Check
        ↓
Charts & Prediction Display

The prediction is capped at the available seat capacity because a college cannot admit more students than its sanctioned seats.

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- HTML
- CSS
- JavaScript
- Chart.js
- Git
- GitHub
- Render

📈 Evaluation Metrics

MAE – Mean Absolute Error

MAE measures the average difference between the predicted and actual admission values.

Lower MAE = Better performance

R² Score

R² indicates how much of the variation in the target variable is explained by the model.

Closer to 1 = Better performance

🌐 Web Application

The Flask backend connects the trained Machine Learning model with the web interface. Users can enter the required information and receive the predicted admission count along with visual representations of seat utilization.

🚀 Deployment

The project can be deployed using Render, with the source code maintained in GitHub.

GitHub Repository
       ↓
     Render
       ↓
Public Web Application

⚠️ Limitations

- The model uses a generated practice dataset.
- Real-world accuracy has not been established.
- Only 7 input factors are currently considered.
- The application does not currently use a production database.
- Admission predictions can change based on real-world factors that are not included in the dataset.

🔮 Future Enhancements

Future versions could include:

- Training with real multi-year college admission data.
- Adding more admission-related features.
- Course-wise admission prediction.
- Historical admission trend analysis.
- Database integration.
- User authentication and login.
- Displaying model evaluation metrics within the application.
- Improved prediction and validation using real-world data.

👨‍💻 Internship Learning Outcomes

Through this project, I gained practical exposure to:

- Machine Learning model development
- Regression algorithms
- Dataset creation and preprocessing
- Model evaluation using MAE and R²
- Python programming
- Flask backend development
- API-based communication
- Data visualization
- Git and GitHub
- Web application deployment

📜 Disclaimer

This project was developed as part of an internship for educational and practical learning purposes. The dataset used for training is a generated practice dataset, and the predictions should not be considered guaranteed real-world admission forecasts.

---

⭐ Project

AI Admission Predictor

A Machine Learning-powered approach to college admission planning and decision support.
