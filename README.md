<b>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Predicting Genre from Song Lyrics </b><br>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;with Naive Bayes and Logistic Regression

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; - Rohan Bapat, Jack Prominski


Our goal in this project was to further delve into applications of naive Bayes for text classification. Our research question was simple: given a song’s lyrics, can we accurately predict its genre? Essentially, are there particular words in song lyrics that can be used to reliably differentiate between genres? If so, what are those words? 

Our process involved a data cleaning pipeline, feature extraction using term frequency and TFIDF, modeling with naive Bayes, and interpreting our results. We also built two multinomial logistic regression models - one using TFIDF and the other trained on word embeddings. We then compared the performance of the logistic regression models with that of naive Bayes. 
