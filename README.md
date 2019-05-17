# Optional Project for Machine Learning Course
This project is about `churn prediction`. Netid of group numbers are hd1047,yl5934,yl6019.
### Training Dataset from Kaggle 
1.	The Kaggle Dataset contains tweets from a political debate in America.<br> 
2.	Tweets were scraped from Twitter of Nov.2016 and were manually classified into positive, negative, and neutral categories.<br> 

### Project Goal
In this project, we use and compare various different methods for sentiment analysis on tweets (a 3-class classification problem).<br> 

### Challenges
1.	Text language can be very challenging to classify due to the ambiguity and subjectivity in the data.<br> 
2.	The task may become more challenging than usual, since users use a lot of figurative language, abbreviations etc. <br> 
3.	There is also not much classified debate sentiment data available, so training models with a substantial amount of data can be difficult. This may affect the models performance in generalizing well to unseen data.<br> 
4.	The next step of this project will be to explore "dealing with class imbalance", which is a very common problem in real world datasets.<br> 

### General Idea
In this project, we use and compare various different methods for sentiment analysis on tweets (a 3-class classification problem).<br>  
1. Data preprocessing:<p> 
>>1) Cleaning<br>
        • Remove URLs<br>
        • Remove usernames (mentions)<br>
        • Remove tweets with Not Available text<br>
        • Remove special characters<br>
        • Remove numbers<br>
        • Remove "RT"s<br>
        •Change it into lower case<br>
>>2) add some other features which may influence the sentiments.<br>
    
>>3) Build word list for Bag-of-Words<br>
    
2. Feature Extraction<br>
>>>>Text processing<br>
        • Tokenize<br>
        • Stemming<br>
        • Lemmatising<br>
3. Estimation: <br>
      >>• Naive Bayes<br>
        • Random Forest<br>
        • XGboost<br>



