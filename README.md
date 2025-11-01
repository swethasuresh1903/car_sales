🚗 Car Price Prediction using Machine Learning


📘 Overview
    The Car Price Prediction project aims to predict the selling price of a car based on various attributes such as the year of manufacture, fuel type, transmission, ownership, and present price.
    The model helps buyers and sellers estimate a fair price using machine learning regression algorithms.


🧠 Objective
    To build and compare multiple regression models that can accurately predict car prices based on given features.



⚙️ Technologies Used
    Python 3
    Jupyter Notebook / VS Code
    Libraries:
        pandas
        numpy
        scikit-learn
        matplotli
        seaborn
        joblib


🧩 Model Building Steps
    1.Data Preprocessing
        Encoded categorical variables
        Removed unnecessary columns
        Split dataset into training and testing sets

    2.Model Training
        Trained and compared three regression models:
        Linear Regression
        Decision Tree Regressor
        Random Forest Regressor

    3.Evaluation Metrics
        Mean Absolute Error (MAE)
        Root Mean Squared Error (RMSE)
        R² Score


🔮 Predictions
    You can test the model by providing custom input values:

    test_data = pd.DataFrame({
        'Year': [2018],
        'Present_Price': [9.5],
        'Driven_kms': [35000],
        'Fuel_Type': [1],
        'Selling_type': [0],
        'Transmission': [1],
        'Owner': [0]
    })

    predicted_price = model.predict(test_data)
    print(predicted_price)


📈 Visualizations
    Correlation heatmap
    Model performance comparison bar chart
    Actual vs Predicted price scatter plot


👩‍💻 Author
    Swetha Suresh
    📧 swethasuresh1905@gmail.com