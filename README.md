# Solving-Donors-Choose-Data-Set-Using-Decisioin-Trees
Decission Trees Classification on Donor Choose Data Set
Imported preprocessed data.The data contains numerical features,categorical features and text data as well
Text data has been vectorised using Tf-Idf and TfIdf weighted W2V.Two sets of data has been taken.(num.feat+cat.feat+Tfidf_Textdata,num.feat+cat.feat+TfidfW2V_Textdata)
Hyperparameters such as max_depth and min_samples_split have been tuned using brutemethod(on dev_data) and GridSearch(on trained data)
Best hyperparameters have been used to model the both sets of data
Since the data given is highly imbalanced, have taken AUC score as the metric for the classificatioin
Have modelled data, this time only on important features obtained from DTs, using LogisticRegression
