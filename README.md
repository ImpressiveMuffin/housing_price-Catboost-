Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the California Housing Dataset. 
Feature distributions are close to, but not exactly the same, as the original. 
Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

Files
train.csv - the training dataset; MedHouseVal is the target
test.csv - the test dataset; your objective is to predict MedHouseVal
sample_submission.csv - a sample submission file in the correct format

Evaluation-
Root Mean Squared Error (RMSE)
Submissions are scored on the root mean squared error. 

Submission File
For each id in the test set, you must predict the value for the target MedHouseVal. The file should contain a header and have the following format:

id,MedHouseVal
37137,2.01
37138,0.92
37139,1.11
etc.
