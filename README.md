Bike sharing Dataset
> Outline a brief description of your project.
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.<br>
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.<br>
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- Dataset is about bike sharing company with dependent variable is count and independent varibale is the varibles affecting the independent variable for gaining more profit.
- What is the background of your project?
- Bike sharing dataset
- What is the business probem that your project is trying to solve?
- we are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- What is the dataset that is being used?
- Day.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Final Conclusion:<br>
Driver varibales which are affecting on rented bikes column are:<br>
 -Temp : 0.3937<br>
 -Year : 0.2356<br>
 -Light snow : -0.2748<br>
 -Windspeed : -0.1545<br>
 -Spring : -0.1460<br>
Errors are normally distributed with mean zero.<br>
Here is no multicolinearity.<br>
prediction on test dataset and on train dataset are good and having apporimately same r2_score, so it proves no overfitting and underfitting.<br>
There is linear relationship between Actual and predicted ones.<br>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project --


## Contact
Created by [@SanghamitraMamali] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
