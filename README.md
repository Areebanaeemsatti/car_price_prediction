🚘 Car Price Prediction & Recommendation System
A machine learning project for predicting luxury car prices and recommending the best option based on multiple features — built using real-world data from PakWheels.

👨‍💻 About the Project
As a car enthusiast, I developed this system to estimate used luxury car prices using a variety of regression models. The app not only predicts prices but also recommends the best car using an A* Search-inspired approach. It’s user-friendly, powered by Gradio, and provides both performance insights and recommendations.

📊 Models Used
Linear Regression

Ridge Regression

CatBoost Regressor ✅

LightGBM Regressor ✅

✅ = Newly implemented and compared with existing models.

🔍 Features
Real car dataset from PakWheels

Preprocessing (categorical encoding, feature scaling)

Model training, testing, and RMSE comparison

best Car recommendation using A* Search logic

Interactive Gradio interface

📈 Dataset
Collected from PakWheels 

Contains features like:

Company, Model, Year

Mileage, Fuel type, Transmission, etc.

💡 A* Search-Based Recommendation
We use a score-based system where feature values are preprocessed and summed. The car with the lowest combined score is selected as the optimal recommendation — combining cost-effectiveness and desirability.

🛠 Tech Stack

Python--colab google
Pandas, NumPy
CatBoost, LightGBM, scikit-learn
Gradio (for UI)
Matplotlib / Seaborn (for visuals)


🤝 Contribution
Feel free to fork the repo, create an issue, or suggest enhancements!

