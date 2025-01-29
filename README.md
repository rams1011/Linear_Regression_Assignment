# Linear Regression Assignment
> This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- What is the dataset that is being used?


## Conclusions
- The R-squared value of the train set is 82.38% and test is 81.13% which indicates model explains the variance quite accurately on the test set.
- The mean squared value of both train and test data set is is almost 0 which indicates model explains the variance quite accurately on the test set.
- Rental count depends year,holiday,temperature,spring,spring,winter,July,September,Cloudy,Light-RainOrSnow
- cnt = (0.2326 x yr)-(0.1003 x holiday)+(0.5029 x temp)-(0.0766 x spring)+(0.0367 x spring)+(0.0829 x winter)-(0.0523 x July)+(0.0812 x September)-(0.0785 x Cloudy)-(0.2989 x Light-RainOrSnow)


## Technologies Used
- Python 	 - version 3.12.7
- Numpy  	 - version 1.26.4
- Pandas 	 - version 2.2.2
- Matplotlib - version 3.9.2
- Seaborn  	 - version 0.13.2
- sklearn    - version 1.5.1
- statsmodel - version 0.14.2


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad live session and video turorials
- Plots created in this project based on [Seaborn Documentation](https://seaborn.pydata.org/api.html).


## Contact
Created by [@rams1011](https://github.com/rams1011/) - feel free to contact me!
