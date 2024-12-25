
**EDA- (By Mitali Patil)**
    1.Upload train,test csv
    2.check null values in train and test.
    3.drop duplicates from train data.
    4.check values counts.
    5.Data Visualization- 
      Barchart,Piechart-
         1.check count of disaster's and nondisaster's tweets on 'target' column.
        -Countplot-
          1.check maximum number 'keywords' of count is disaster and non disaster.
        -Create a binary feature in the train and test dataset for 'location' column.
        -Replace nan value in keyword column: 
              -apply label encoder.
              
**Data Cleaning- (by Pragati Deshamukh)**
    1.Replacing NaN values from 'keyword' 
    2.Data Cleaning - Removed Stopwords , 
    3.Text Lower, 
    4.Removed Punctuation 
    5.Remove url ,  
    6.Applied lemmatization  

**Word To Vector - (by Trupti Chaudhari)**
    1.Word2veg- Sentence tokenization ,
    2.Applied Word2veg Model , 
    3.converted to sentence vector

**Data to train Model - (by Atul Sartape)** 
    1.Stack the feature together ,
    2.vstack and hstack performed,
    3.Perform Train and Test Split    
          
**Created Model and train data - (By Sagar Divekar)**
     1. Logistic Regression - Precision - 0.70 ,Recall - 0.88 , F1 score - 0.78 , Accuracy - 0.72,
     2. Naive bayes -  Precision - 0.62 , Recall - 0.87 , F1 score - 0.72 , Accuracy - 0.62,
     3. Randon Forest - Precision - 0.73 , Recall - 0.87 , F1 score - 0.79 , Accuracy - 0.74

    -Random Forest gives best accuracy so used Randon Forest for Prediction
    -converted into 'submission.csv'

