# EV-Choise-Optimizer :battery:


## Optimizing electric vehicle choices in Taiwan through data analysis. 
This project aims to develop a simple system to compare EVs available in Taiwan. The system will focus on the most critical features that customers care about, such as driving range, price, body style, number of seats, and powertrain, to provide clear and helpful recommendations. 

There are typically three types of recommendation strategies used to suggest electric vehicles (EVs) to users based on their preferences and input. 

### Strict Recommendation System ### :round_pushpin: :recycle:
This system recommends EVs that match the user's input exactly. 
It uses specific user preferences like: 
* budget (maximum price) 
* preferred brand
* body style (e.g., sedan, SUV, etc.)
* minimum required range (km)
* maximum acceleration time
* number of seats 
* preferred powertrain (AWD, RWD, FWD, or no preference) 

### Fallback Recommendation System ### :round_pushpin:
When no cars are found that match all of the user's exact preferences, the fallback system uses a relaxed version of the filtering criteria. 
It primarily considers: 
* budget
* minimum range
* number of seats

### Machine Learning (ML) Recommendation System :round_pushpin:
This system uses a machine learning model (an artificial neural network) to predict which cars might suit the user based on their input. The model is trained using historical data on car features (price, range, seats) and user preferences.

### Data Collection ### :open_file_folder:
The dataset was collected manually from each  manufacturer's website, compared with reviews, and checked whether it is verification-based on WLTP (Worldwide Harmonised Light vehicles Test Procedure); additionally, it was compared with the list of cars on 8891.tw. Data was collected in ***2024***. 


