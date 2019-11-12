# Toothpaste_sales_price_predictor
Sales price prediction challenge by Colgate- HackRU Fall 2019.

# Key Steps Involved:
Data Preprocessing  - Cleaned the data. Got ingridients count after removing outliers.<br />
<br />
One Hot Encoding- All categorical variables were converted into two bits - 1 or 0. This form was provided to ML algorithms to do a better job in prediction.<br />
<br />
Data Scaling, Training, and Testing - Scaled the dataframe using MinMaxScaler. Calculated the Training and Testing shapes using train_test_split. Instantiated the model with 100 decision trees and trained the model on training data. Used the forest's predict method on the test data and calculated Mean Absolute Error and Accuracy. Finally, generated a list of features which were most consequential towards determining the price of a product.<br />
