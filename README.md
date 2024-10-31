# Decision-Trees-Diabetes-dataset

Here I consider the Pima Indians Diabetes Database data set([https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)). This data set is created for prediction of whether a patient has diabetes or not. The data set contains several parameters which are considered important during the determination of diabetes. The sample size is 768 and all patients here are females at least 21 years old of Pima Indian heritage. I take Outcome as the binary response variable and consider all predictors as quantitative variables. Additionally I take all the data as training data. 

For all the models I use leave-one-out cross-validation (LOOCV) to compute the estimated miss classification error rate.
