# Capstone Project - Starbucks 


   <img  src= "https://github.com/nourahamads/Capstone-Project-/blob/master/starbucks.jpg "  > 


## Project Overview : 
 The project is about starbucks dataset simulated , there is three datasets : 
   - portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.).
   - profile.json - demographic data for each customer.
   - transcript.json - records for transactions three kinds of transactions offers received, offers viewed, and offers completed.
   ####  the Goals : 
  
    - How many transcript fro each type of transcript ? 
    - How many Femals and male and the averge of them ? 
    - How  the income and the average according the gender ? 
    - The age and try to cluster the age to know  more about costomer ? 
    - Analysis and write the results ? 
    - timeline for the users and  time to be the users  in Starbucks App ? 
    
    
    
 ## Data understanding : 
   the all files as json file and 
    -portfolio.json

        -id (string) - offer id
        - offer_type (string) - type of offer ie BOGO, discount, informational
        - difficulty (int) - minimum required spend to complete an offer
        - reward (int) - reward given for completing an offer
        - duration (int) - UNKNOWN
        -channels (list of strings)

   -profile.json

        - age (int) - age of the customer
        - became_member_on (int) - date when customer created an app account
        - gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
        -id (str) - customer id
        - income (float) - customer's income
        
        
  - transcript.json

        - event (str) - record description (ie transaction, offer received, offer viewed, etc.)
        - person (str) - customer id
        - time (int) - time in hours. The data begins at time t=0
        - value - (dict of strings) - either an offer id or transaction amount depending on the record
        

## Data Preparation
in this data there is nulls values in profile data there is three columns have the values are: age , gender and income . 
I tried to fill the nulls values in gender by "U" letter that mean uknown , and income column I tried fill the nulls by the mean of the income for customer but the age we cann't replace it eith value it will affect the results , so I dropped the nulls values .
and in the portfolio data I seperated chennels wat to market the types of offer .  


## Data Analysis . 
 I  Analysis the data  by python 3 . 
  [ the project ]()
  
  
## Conclusion :
  
 

    
   
   
