# UNIV.AI_Hackathon
UNIV.AI Hackathon

Problem Statement


  
An organization wants to predict who possible defaulters are for the consumer loans product. They have data about historic customer behavior based on what they have observed. Hence when they acquire new customers they want to predict who is more risky and who is not.

Evaluation Criteria
Submissions will be evaluated on the basis of roc_auc_score.


![Capture](https://user-images.githubusercontent.com/69980760/119228516-ef25fa80-bb30-11eb-9bd5-207b67d2348b.PNG)

So Here I have used CatBoost Algorithm after trying all other algorithms like XG BOOST , LGBM , RANDOM FOREST , SVM and their ensembled models too
my model was not performing well on the unseen or the test data.
As the Raw data was unbalanced i have used SMOTE oversampling technique to make the data balanced , which affected my model perfromance.
