# Amazon Food Review
This project aims to build a prediction model where we will be able to predict whether a recommendation is positive or negative. In this analysis, we will not focus on the Score, but only the positive/negative sentiment of the recommendation.            

We created new variables and converted variables into the desired data types, built a term-doc incidence matrix, created the cloud word, and conduct exploratory data analysis. Methods used in building term-doc incidence matrix are:          
- stopwords removal           
- stemming           
- punctuation removal           
- Lowercase the capital letters           
           
Three methods were used in converting text into vector：           
- Uni-gram bag of words           
- Bi-gram bag of words           
- TF-IDF           

Two models were used in this project:           
- Logistic Regression           
- Random Forest Regression           

## Outline
<b>1.Data Cleaning and Preprocessing</b>  
1.1 Loading data               
1.2 Create New Variables and Convert Variable Types             
1.3 Build Term-doc incidence matrix            
a) stopwords              
b) Stemming                  
c) punctuaion removal               
1.4 create cloud word             
             
              
<b>2. Exploratory Data Analysis</b>      
2.1 Descriptive Statistics                
2.2 Socre analysis                 
2.3 Sentiment analysis          
2.4 Usefulness analysis        
2.5 Reviewers analysis         
2.6 Relationship analysis between variables                   
a)Are positive reveiws more helpful?           
b)Are frequent reviewers more helpful?          
             
             
<b>3. Predictive Modeling</b>   
3.1 Test train data split                    
3.2 Convert text to vector                 
a) Uni-gram bag of words                
b) Bi-gram bag of words           
c) tf-idf                
3.3 Logistic Regression             
a) Using Uni-gram bag of words         
b) Using bi-gram bag of words          
c) using tf-idf        
3.4 Random Forest Regression               
a) Using Uni-gram bag of words          
b) Using bi-gram bag of words         
c) using tf-idf                     
                  
                   
<b>4. Predicition Evaluation</b>       
4.1 Comparison of logistic regression models            
a) Comparison of Classification report         
b) Comparison of AUC values                 
c) Comparison of ROC Curve                      
4.2 Comparison of random forest regression models              
a) Comparison of Classification report         
b) Comparison of AUC values             
c) Comparison of ROC Curve                 
4.3 Comparison between Logistic Regression Model and Random Forest Regression Model       
               
                 
<b>5. Conclusion</b>   
                 
                          
-----                                  
-----update 9/16/2020--------                  
*Note: For a complete analysis, please check the kernal named Amazon Food Review Project.           
The other three kernals were truncated from the complete project and used for my school work project purposes.             
