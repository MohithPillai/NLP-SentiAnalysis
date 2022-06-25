# NLP-SentiAnalysis
Sentiment Analysis on Tweets

                                                                      ABSTRACT-

This project addresses the problem of sentiment analysis in twitter; that is classifying tweets according to the sentiment expressed in them: positive, negative or neutral. Twitter is an online micro-blogging and social-networking platform which allows users to write short status updates of maximum length 140 characters. It is a rapidly expanding service with over 200 million registered users - out of which 100 million are active users and half of them log on twitter on a daily basis - generating nearly 250 million tweets per day [20]. Due to this large amount of usage we hope to achieve a reflection of public sentiment by analysing the sentiments expressed in the tweets. Analysing the public sentiment is important for many applications such as firms.

                                                                   
                                                                   Data Acquisition-
                                                                   
 The Data in the form of raw tweets was acquired form Kaggle. There are two datasets training and test datasets. It comes in the form of Dataframe with the following Labels-
     -Tweet_id:
         Contains the id number of the user.
     -Entity:
         Contains the subject of the Tweet.
     -Sentiment:
         Contains the label- Neutral,Irrelevant,Positive,Negative
     -Tweet_content:
         Contains the original content of the tweets.
         
         
                                                                 Human Labelling-
                                                                 
We labelled the tweets in four classes according to sentiments expressed/observed in the tweets: positive, negative, neutral/irrelevant. We gave the following guidelines to our labellers to help them in the labelling process:
       • Positive: If the entire tweet has a positive/happy/excited/joyful attitude or if something is mentioned with positive connotations. Also if more than one
                   sentiment is expressed in the tweet but the positive sentiment is more dominant.
       • Negative: If the entire tweet has a negative/sad/displeased attitude or if something is mentioned with negative connotations. Also if more than one sentiment
                   is expressed in the tweet but the negative sentiment is more dominant.
       • Neutral/Irrelevant: If the creator of tweet expresses no personal sentiment/opinion in the tweet and merely transmits information. Advertisements of different
                   products would be labelled under this category.
