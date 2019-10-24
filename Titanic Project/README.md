# Predicting the Survival of Titanic Passengers

 “Titanic: Machine Learning from Disaster” Competition. In this challenge, we are asked to predict whether a passenger on the titanic would have been survived or not.
 The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this contest, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

![titanic](https://user-images.githubusercontent.com/53295619/67478334-73747b00-f679-11e9-8229-684ed323fc05.jpeg)


## using Libraries
This project requires the following Python libraries installed:

NumPy
Pandas
matplotlib
Seaborn
scikit-learn

##Data
The dataset used in this project is included as titanic_data.csv. This dataset is provided by Kaggle.

survival ? Survival (0 = No; 1 = Yes)
pclass ? Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
name ? Name
sex ? Sex
age ? Age
sibsp ? Number of Siblings/Spouses Aboard
parch ? Number of Parents/Children Aboard
ticket ? Ticket Number
fare ? Passenger Fare
cabin ? Cabin
embarked ? Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## DATA CLEANING:
is nothing but how I remove the null values we want to fill missing AGE data instead of just dropping the missing age data rows.one way to do this is filling in the mean age of all the passengers (imputation).however we can be smarter about this and check the average age by the passenger class

## EVALUATION
The historical data has been split into two groups, a 'training set' and a 'test set'. For the training set, we provide the outcome ( 'ground truth' ) for each passenger. You will use this set to build your model to generate predictions for the test set.

## Accuracy
Finally i got '0.8202247191011236' Accuracy


For each passenger in the test set, you must predict whether or not they survived the sinking ( 0 for deceased, 1 for survived ). Your score is the percentage of passengers you correctly predict.
