# automatidata
### Predicting Taxi Gratuities in New York City
Automatidata Project - Google Advanced Data Analytics Certificate
## Overview
The goal of this project was to construct a multiple linear regression and random forest model for the NYC Taxi and Limousine Commission to predict whether or not a cutsomer is going to be a generous tipper. The final random forest model performed with 86% accuracy and 72% precision in perdicting the features that were most important in separating low tippers and high tippers. According to the model, the factors that had the most influence in determining generous (>20%) and non-generous (<20%) tippers were duration, distance, and cost of the trip.
## Business Understanding
According to salary.com, the average salary for a taxi driver in New York City is approximately $45,000 per year. The average salary of all employees in New York City, New York, is approximately $84,500 (salary.com). The salary of a taxi driver is significantly lower than most New Yorkers, and higer tips can help supplement their income.
## Data Understanding
The NYC Taxi and Limousine Commission data came from NYC.gov. In this dataset, there are approximately 408,000 unique trips and 18 features. Features in this dataset include information on trip duration adn destination, the vendor, toll information, and payment type. Features were engineered to represent rides that were taken during rush hour, and redundant columns were dropped or reformated for use in the model. 
## Modeling and Evaluation
The random forest model was used to determine feature importance in if the customer would tip generously. The following plot shows htat the three most important features in separating a generous tipper from a non-generous tipper are trip duration, trip distance, and the cost of the ride. The final model had an accuracy score of 86% and a precision score of 72%.

<img width="562" alt="Screenshot 2023-10-07 at 6 51 12 PM" src="https://github.com/allisonlmueller/automatidata/assets/147258601/165d972c-815a-4537-b41d-8ba839fe1689">

# Conclusion
The model would help taxi drivers determine if the customer will tip them generously or not, but it would be beneficial to do further analysis to determine how much each variable influences that tip amount. Adding information on customers past tipping behaviors could help the model better predict if a customer will be a generous tipper 
