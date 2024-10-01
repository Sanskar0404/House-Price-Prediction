# **House Price Prediction**

This project focuses on predicting house prices in Delhi city based on various attributes such as area, number of bedrooms, and location details. The model is built using the **Simple Linear Regression** algorithm in Python to estimate house prices based on historical data.


## **Overview**
The aim of this project is to predict house prices based on attributes such as location, size, and other factors in Delhi. By using **Simple Linear Regression**, the project seeks to establish a relationship between house price and one or more independent variables like area, number of bedrooms, and more.

## **Dataset**
The dataset contains the following features:

- **price**: The price of the house (target variable).
- **Address**: The address of the house.
- **area**: The area of the house (in square feet).
- **latitude**: The latitude of the house location.
- **longitude**: The longitude of the house location.
- **Bedrooms**: The number of bedrooms in the house.
- **Bathrooms**: The number of bathrooms in the house.
- **Balcony**: The number of balconies in the house.
- **Status**: The status of the house (ready to move/under construction).
- **neworold**: Whether the house is new or old.
- **parking**: Availability of parking space (yes/no).
- **Furnished_status**: Whether the house is furnished, semi-furnished, or unfurnished.
- **Lift**: Availability of lift (yes/no).
- **Landmarks**: Nearby landmarks to the house.
- **type_of_building**: The type of building (apartment, villa, etc.).
- **desc**: A description of the house.
- **Price_sqft**: The price per square foot.

## **Tools and Libraries**
This project was implemented using Python, with the following libraries:
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For implementing the Simple Linear Regression model.
- **Matplotlib/Seaborn**: For data visualization.

## **Methodology**
1. **Data Preprocessing**:
   - Handle missing values.
   - Convert categorical variables like **Furnished_status**, **Status**, and **neworold** into numerical values.
   - Perform feature scaling for numerical features like **area**, **Price_sqft**, etc.

2. **Model Selection**:
   - **Simple Linear Regression** was selected to predict house prices based on one or more independent variables such as **area** and **Price_sqft**.

3. **Model Evaluation**:
   - The model was evaluated using metrics like **Mean Squared Error (MSE)** and **R-squared (R²)** to assess prediction accuracy.

## **Modeling**
The **Simple Linear Regression** algorithm was applied to the dataset. The model attempts to find the best-fitting line that predicts the house price based on the input features like **area**, **Bedrooms**, and **Price_sqft**. The model was trained on a portion of the data and tested on the remaining to validate its performance.

## **Conclusion and Solution**
The **Simple Linear Regression** model performed reasonably well in predicting house prices in Delhi. The analysis revealed that features like **area**, **Bedrooms**, and **Price_sqft** are key determinants of house prices in the city.

The model can help homeowners, buyers, and real estate professionals in making informed decisions based on historical data. Future enhancements could include more advanced models such as multiple linear regression or incorporating more features like amenities and neighborhood quality to improve prediction accuracy.

