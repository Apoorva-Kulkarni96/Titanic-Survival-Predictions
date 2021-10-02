# Titanic-Survival-Predictions
The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic
sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone
onboard, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people
were more likely to survive than others.
In this challenge, we ask you to build a predictive model that answers the question: “what sorts of
people were more likely to survive?” using passenger data (ie name, age, gender,
socio-economic class, etc).
This project predicts whether a person survived in Titanic tragedy using passenger data (ie name, age, gender,
socio-economic class, etc). In this project , Logistic Regression Model is used.

### Steps involved :

1 Import Libraries

2 EDA
  Approximately 20% of Age data is missing and 77% of cabin data is missing.
  Most of the people died in the Titanic Tragedy , only around 300 people survived.
  There were more males than females aboard the ship, roughly double the amount. More males died in Titanic Tragedy than females
  The majority of the people traveling, had tickets to the 3rd class.
  
 3 Data Cleaning
   We have to fill the missing data in Age Feature.
  
 4 Data preparation

 5 Converting Categorical Features

 6 Implement Model

 7 Evaluation
   Our model predicts 76% of the time, a passengers survival correctly (precision). The recall tells us that it predicted the survival of 68% of the people who actually survived.The first row is about the not-survived-predictions: 129 passengers were correctly classified as not survived (called true negatives) and 24 where wrongly classified as not survived (false positives). The second row is about the survived-predictions: 37 passengers where wrongly classified as survived (false negatives) and 78 where correctly classified as survived (true positives).
