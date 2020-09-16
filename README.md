<h1 align="center"> Amazon Food Reivew</h1>

## Introduction:                    
The Amazon Food Review data is an open dataset that found at [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews). This dataset consists of reviews of foods from Amazon. The data includes reviews 568,545 reviews from 256,059 users spans from Oct 1999 to Oct 2012.       

The purpose of this analysis is to make up a prediction model where we will be able to predict whether a recommendation is positive or negative. In this analysis, we will not focus on the Score, but only the positive/negative sentiment of the recommendation.
     
## Goals:         
- Create new variables and convert variable types          
- Generate word cloud to get sense of the review          
- Exploratory data analysis for key variables
- Explore the relationship between key variables       
- Create Bag of Words using three different methods     
- Build logistic regression and random forest regression model and find the one performs the best

## Outline
- <b>1.Data Cleaning and Preprocessing</b>  
 - 1.1 Loading data               
 - 1.2 Create New Variables and Convert Variable Types             
 - 1.3 Build Term-doc incidence matrix            
    - a) stopwords              
    - b) Stemming                  
    - c) punctuaion removal               
 - 1.4 create cloud word             
             
                 
- <b>2. Exploratory Data Analysis</b>      
 - 2.1 Descriptive Statistics                
 - 2.2 Socre analysis                 
 - 2.3 Sentiment analysis          
 - 2.4 Usefulness analysis        
 - 2.5 Reviewers analysis         
 - 2.6 Relationship analysis between variables
   - a)Are positive reveiws more helpful?
   - b)Are frequent reviewers more helpful? 
             
             
- <b>3. Predictive Modeling</b>   
 - 3.1 Test train data split                   
 - 3.2 Convert text to vector                 
     - a) Uni-gram bag of words
     - b) Bi-gram bag of words
     - c) tf-idf
 - 3.3 Logistic Regression
   - a) Using Uni-gram bag of words
   - b) Using bi-gram bag of words
   - c) using tf-idf
 - 3.4 Random Forest Regression              
   - a) Using Uni-gram bag of words
   - b) Using bi-gram bag of words
   - c) using tf-idf                   
                   
                   
- <b>4. Predicition Evaluation</b>       
    - 4.1 Comparison of logistic regression models
        - a) Comparison of Classification report         
        - b) Comparison of AUC values
        - c) Comparison of ROC Curve
    - 4.2 Comparison of random forest regression models
        - a) Comparison of Classification report         
        - b) Comparison of AUC values
        - c) Comparison of ROC Curve
    - 4.3 Comparison between Logistic Regression Model and Random Forest Regression Model   
                 
                 
- <b>5. Conclusion</b>  
