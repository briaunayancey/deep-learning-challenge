# deep-learning-challenge

        This analysis is to find the applicant who may have the best success if the nonprofit foundation Alphabet Soup, funds them. 
        
The variables that we are looking at are: 
    
    APPLICATION_TYPE— Alphabet Soup application type
    
    AFFILIATION— Affiliated sector of industry
    
    CLASSIFICATION— Government organization classification
    
    USE_CASE— Use case for funding
    
    ORGANIZATION— Organization type
    
    STATUS— Active status
    
    INCOME_AMT— Income classification
    
    SPECIAL_CONSIDERATIONS— Special considerations for application
    
    ASK_AMT— Funding amount requested
    
    IS_SUCCESSFUL— Was the money used effectively
    

The name and ein of the applicant was removed when processing the data. However the Application type and classification was used for our features in our model, since they represent a group of applicants to choose from. It was very difficult finding the best model to use with our neural networks, but the closest I was able to achieve was an accuracy of 72% within my time window. Increasing the units made the most impact and brought me closer to a better accuracy along with using the "tanh" function. Since I was only able to use two layers, this may have made the accuracy difficult to achieve higher than a 75% accuracy score. 
  
Recommendation: 
 Using more layers may help with improving scores
 
