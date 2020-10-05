# Final_Project_Segment-Deliverable
Final Project deliverable 
# Name of the Project - Fraud Detection in Finance Industry 
The challenge is to recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase.

# Reason why I have selected this topic
This is because I work in Finance Industry and typically understand the logic behind the Fraud in the transactions that occur in the Sales business. Furthermore with the pandemic in place and increasing rate of ecomm transactions it is almost mandatory to work towards reducing Fraud. 

# Data Source
I downloaded the data from Kaggle.com. It is downloaded as creditcard.csv.  
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.It contains only numerical input variables.
Features V1, V2, ... V28 are the principal components obtained.
The only features which have not been transformed are Time and Amount. Feature Time contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature Amount is the transaction Amount, this feature can be used for example-dependant cost-senstive learning.
Feature Class is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Objective of the project
The objective is to recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase.

Now that we have added the data we have to add a few dependencies.
import Pandas, seaborn for visualization and numpy for numeric calculations.We will segrerate the fraudulant transactions from the normal ones by using the loc function.Thats how i got no of fraudulant transactions. 

# Visualization: I will be showing the visualization in tableau.
