## Hotel Booking Cancellation Analysis and Prediction
Introduction
In this project, we analyze the factors that contribute to hotel booking cancellations and provide recommendations to address this problem. We also build a predictive model that can predict whether a customer will cancel their reservation or not.

Data
The dataset used for this analysis is the Hotel Booking Demand dataset from Kaggle. This dataset contains information on hotel bookings, including demographic information about the customers, the type of room they booked, the duration of their stay, and whether or not they canceled their reservation. The dataset has 119390 rows and 32 columns.

Analysis
We performed data cleaning and exploratory data analysis (EDA) on the dataset to identify the factors that contribute to hotel booking cancellations. We used various visualization techniques to visualize the relationships between different variables and cancellation rates.

We found that the following factors contribute to higher cancellation rates:

Lead time: The longer the time between booking and the arrival date, the higher the cancellation rate.
Market segment: Online Travel Agencies (OTAs) have higher cancellation rates compared to other market segments.
Deposit type: Bookings made without a deposit have higher cancellation rates.
Hotel type: Resort hotels have higher cancellation rates compared to city hotels.
We also found that certain features, such as the number of adults and children in a booking, the room type, and the total cost of the booking, are significant predictors of whether a booking is likely to be canceled or not.

Prediction
To build a predictive model, we split the dataset into training and testing sets and standardized the features using StandardScaler. We also used Principal Component Analysis (PCA) to reduce the dimensionality of the dataset.

We trained a logistic regression model on the training set and tuned its hyperparameters using GridSearchCV to achieve higher accuracy. We then evaluated the model on the testing set and achieved an accuracy of 81.3%.

Conclusion
Our analysis shows that certain factors, such as lead time, market segment, deposit type, and hotel type, contribute to higher cancellation rates. We also built a predictive model that can predict whether a booking is likely to be canceled or not. This model can be used by hotels to take proactive measures to reduce cancellations and improve their revenue generation.

References
Hotel Booking Demand dataset from Kaggle: https://www.kaggle.com/jessemostipak/hotel-booking-demand
