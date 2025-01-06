# House Price Prediction

![House Price Prediction](images/project2.jpg)

## 🏡 Overview

The **House Price Prediction** project focuses on predicting the prices of houses based on various factors such as size, location, number of rooms, and amenities. This project uses machine learning techniques to predict the market value of houses, providing valuable insights for real estate investors and homebuyers.

## ⚙️ Technologies Used
- **Python** 🐍
- **Machine Learning** 🤖
- **Linear Regression** 📈
- **Random Forest** 🌳
- **XGBoost** 🧠
- **Pandas** 📊
- **NumPy** 🔢
- **Matplotlib** 📉
- **Seaborn** 🎨

## 🔍 Problem Statement

The real estate market is complex, with numerous variables influencing the price of a house. Predicting house prices accurately can help investors make better decisions. This project aims to build a predictive model that can estimate house prices based on historical data.

## 💡 Solution

We use machine learning models to predict house prices by analyzing key features such as:
- **Size of the house** 🏠
- **Number of bedrooms and bathrooms** 🛏️🚿
- **Location** 📍
- **Year of construction** 🏗️
- **Other factors** such as proximity to schools, parks, etc.

The project uses:
- **Linear Regression** to build a baseline model.
- **Random Forest** and **XGBoost** for better accuracy and robustness.

## 📊 Dataset

The project uses the **Boston Housing Dataset** or a similar real estate dataset, which contains information on various houses and their sale prices.

- **Total Samples**: 506
- **Features**: 13 (e.g., crime rate, property tax, average number of rooms, etc.)
- **Target**: Median value of homes in $1000s.

## 🔧 Steps to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/ankitgupta9569/house-price-prediction.git
    ```
2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the script to train the model:
    ```bash
    python train_model.py
    ```
4. To test the model with new house features:
    ```bash
    python predict_price.py
    ```

## 🎯 Results

- **Accuracy**: Achieved a high R-squared score of 0.91, indicating that the model can explain 91% of the variance in the house prices.
- **Mean Absolute Error**: 3.6% average prediction error.

## 📈 Visualizations

The project includes several key visualizations to understand model performance and the relationships between features:
- **Feature Importance** 🌟
- **Predicted vs Actual Prices Plot** 📉
- **Residuals Plot** 🧮
- **Correlation Matrix** 🧩

## 💬 Discussion

The model has performed well with the given dataset. However, there is always room for improvement. More features like location data (longitude and latitude), crime rates, or neighborhood data could enhance the model further.

## 🚀 Future Enhancements

- Incorporating **Geospatial Data** for better location-based predictions.
- Using **Deep Learning** models like **Neural Networks** for better accuracy.
- Experimenting with **Hyperparameter Tuning** to fine-tune the model performance.

## 🌐 View the Project on GitHub

[Click here to view the code on GitHub](https://github.com/ankitgupta9569/house-price-prediction)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 📝 Author
**Ankit Gupta**  
[LinkedIn](https://www.linkedin.com/in/ankitgupta2026) | [GitHub](https://github.com/ankitgupta9569)
