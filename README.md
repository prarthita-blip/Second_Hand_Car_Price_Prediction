# Second_Hand_Car_Price_Prediction

Project: Second Hand Car Price Prediction
Install
The project requires python and following python libraries installed:
1.	numpy
2.	pandas
3.	matplotlib
4.	seaborn
5.	scikit-learn

The project has been executed using a jupyter notebook.

Data
The dataset used in this project is the “Vehicles Dataset” available at Kaggle.
The data has the following columns:
1.	Car_Name
2.	Year
3.	Selling_Price
4.	Present_Price
5.	Kms_Driven
6.	Fuel_Type
7.	Seller_Type
8.	Transmission
9.	Owner
The column names are self-explanatory.

Code
The code uses a Linear Regression model to predict the Selling Price using data from the other columns. The code is intended to analyse the relation between the columns, it tries to get an idea of how various factors are affecting the selling price of the second hand car.

Result
The model can predict the selling price of the car with a decent accuracy. The R2 score was nearly 90% for both train and test data. The dataset was very small(only 300 rows) so there is genuine scope of improvement with a larger dataset.
