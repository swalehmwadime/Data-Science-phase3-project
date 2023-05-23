####   Flight Delay Prediction

This project aims to predict flight delays using machine learning algorithms. It involves analyzing a dataset containing information about flights, such as departure time, flight duration, airline, and airports.

#### Dataset
The dataset used for this project is stored in a CSV file named 'airlines_delay.csv'. It consists of the following columns:

Flight: Flight number (index column)
Time: Departure time
Length: Flight duration
Airline: Airline code
AirportFrom: Departure airport code
AirportTo: Arrival airport code
DayOfWeek: Day of the week (1-7)
Class: Target variable (0 for on-time flights, 1 for delayed flights)

#### Data Cleaning and Preparation
The project begins with data cleaning and preparation steps, which include:

Importing the dataset using pandas library.
Setting the Flight column as the index.
Checking the data types and statistical information of the columns.
Handling missing values (no missing data found).
Performing exploratory data analysis (EDA) to gain insights into the data.


#### Exploratory Data Analysis
EDA is conducted to visualize and understand the relationships between different features and the target variable. Some of the visualizations performed in this project include:

Bar plot of the total number of flights per airline.
Count plot of delayed flights vs. on-time flights for each airline.
Bar plot of average flight length for each airline.
Bar plot of departure time for each airline.
Count plot of delayed flights per day of the week.
Pie charts showing the percentage of delayed flights for each day of the week.


#### Model Creation and Prediction
The project involves creating machine learning models to predict flight delays. The following steps are performed:

Standardizing the numerical features (Time and Length) using MinMaxScaler.
Encoding the categorical features using one-hot encoding.
Moving the target variable (Class) to the end of the DataFrame.
Splitting the dataset into training and testing sets.
Implementing logistic regression as the chosen model.
Training the model on the training data and making predictions on the testing data.
Evaluating the model's performance using accuracy score.


### Conclusion
This project demonstrates the process of predicting flight delays using machine learning techniques. By analyzing various features and applying logistic regression, it aims to provide insights into the factors influencing flight delays. The results and insights gained from this project can be used to improve airline operations and optimize flight scheduling.