

## DATA Science 101 Final Exam

#### Directions

Copy the Test into a word document.  Upload to Oaks a the word document with the answers printed underneigth the questsion.  Every student must answer the questions in their own words (and typing).  

#### Programing (write code that would to the following tasks)

+ 1 Using python pandas package, write code to read in a csv called 'my.csv', print out number of rows and columns, save to a variable called 'df'


+ 2 Using python pandas,  suppose df data frame has a 'value' column and a 'id' column, write code to create a new data frame
where every row is a unique id, and only has one column, the sum of 'value'


+ 3 Using Scikit Learning, suppose df has categorical column called 'categories' create a one hot encoder array based on that column


+ 4 Using Scitkit Learning, create an sklearn pipeline that transforms dataframe df 'categories' column using one hot encoding, and 'values' using median imputation and combines them into one array.



##### CRISP DM on Projects

Describe how your team use each step of the CRIPS DM Process for you final project.  ( A new sentences per step)



+ 5 Business understanding




+ 6 Data understanding




+ 7 Data preparation




+ 8 Modeling




+ 9 Evaluation




+ 10 Deployment





+ 11 In the modeling phase of your project, how was the data split and why?



#### Modeling Techniques 

+ 12 What is the difference between 10 fold cross validation and a random holdout when splitting data? Why would you use one vs the other?




+ 13 How to decision tree use entropy to decide where to split variables?




Define the following parts of a decision tree: 

+ 14 root:


+ 15 node: 


+ 16 leaf: 

#### Understanding Classication Models
A model is training the following results.
The following are error metrics of predictive models of a SEVERLY imbalanced data set:

    * model1: training-set: accuracy 99.9%, auc 0.5, test-set: accuracy 99.9%, auc 0.5
    * model2: training-set: accuracy 60% auc .6, test-set: accuracy 99.9%, auc 0.5
    * model3: training_set: accuracy 95% auc .92, test_set: accuracy 75.9%, auc 0.63
    * model4: training_set: accuracy 92% auc .85, test_set: accuracy 91%, auc 0.83


+ 17 Which model is under fit?

+ 18  Which model is over fit?

+ 19 Which model learned a trivial, non intersting, solution?
 
+ 20 Which is the best model?
 
+ 21 Why is a good idea to test AuC and accuracy when assesing classification models

#### Regression Models
A model is training the following results, answer the questions bellow. 

    * model1: 500 leaves, training-set: mse 1.1, r2_score .86 , test-set: mse 3.3 r2_score .75
    * model2: 250 leaves, training-set: mse 3.4, r2_score .8 , test-set: mse 3.3, r2_score .81
    * model3: 100 leaves, training-set: mse 4.0, r2_score .75 , test-set: mse 4.0 r2_score .75

  
+ 22 Why would you choose mean squared (MSE) as a regression metric vs MAE (mean average error)?


+ 23 A model has been trained on a training set with 10,000 training set rows and 2,500 test set rows


+ 24 Given the  performance metrics Which is the best decision tree model, and why?


+ 25 Why is it a good idea to test MSE and R2_score when assessing a regression model 



#### CLustering

+ 26 When building cluster models, what are desirable features that a good model might demonstrate?  


+ 27 Can a cluster model be over fit, if so how could you tell?


#### Data Mining Process

28 You work at a cell phone service provider that has a large problem customer retention (customers are switch to a rival cell provided in alarming rates). You have access to payment and account history of all your customer, as well as website visits and search histories.  Create a project proposal using CRIP DM as a frame work to use Data Science create a proposal of a project that will address the customer retention.





