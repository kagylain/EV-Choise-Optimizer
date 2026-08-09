# EV-Choise-Optimizer


## Optimizing electric vehicle choices in Taiwan through data analysis. 
This project aims to develop a simple system to compare EVs available in Taiwan. The system will focus on the most critical features that customers care about, such as driving range, price, body style, number of seats, and powertrain, to provide clear and helpful recommendations. 

There are typically three types of recommendation strategies used to suggest electric vehicles (EVs) to users based on their preferences and input. Here's a breakdown of each recommendation type in the context of the system:

### Strict Recommendation System ###

This system recommends EVs that match the user's input exactly. It uses specific user preferences like: budget (maximum price), preferred brand, body style (e.g., sedan, SUV, etc.), minimum required range (km), maximum acceleration time, number of seats, preferred powertrain (AWD, RWD, FWD, or no preference). 
If there are any cars that exactly match all the user's input preferences, they are recommended. This approach filters cars strictly based on the exact conditions set by the user.

### Fallback Recommendation System ###
When no cars are found that match all of the user's exact preferences, the fallback system uses a relaxed version of the filtering criteria. It primarily considers: budget, minimum range, number of seats.
This system will recommend cars that fit the more relaxed criteria but may not meet every exact preference. For example, it may suggest cars that fit within the user's budget and seat requirements, even if they do not exactly meet the preferred body style or brand.

### Machine Learning (ML) Recommendation System
This system uses a machine learning model (an artificial neural network) to predict which cars might suit the user based on their input. The model is trained using historical data on car features (price, range, seats, etc.) and user preferences.


