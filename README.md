
## Abstract

The data sets released here has been used in our a study on longitudinal information seeking and social networking behaviors across academic communities. Social media like Twitter have been widely used in physical gatherings, such as conferences and sports events, as a "backchannel" to facilitate the conversations among participants. It has remained largely unexplored though, how event participants seek information in those situations. There are three key results: 
(1) Our study takes the first initiative to characterize the information seeking and responding networks in a concrete context---academic conferences---as one example of physical gatherings. By studying over 190 thousand tweets posted by 66 academic communities over five years, we unveil the landscape of information-seeking activities and the associated social and temporal contexts during the conferences.
(2) We leverage crowdsourcing and machine learning techniques to identify distinct types of information-seeking tweets in academic communities. We show that the information needs can be differentiated by their posted time and content, as well as how they were responded to. Interestingly, users' tendencies of posting certain types of information needs can be inferred by prior tweeting activities and network positions. 
(3) Moreover, our results suggest it is also possible to predict the potential respondents to different types of information needs. 

Our study was based on two data sets: (1) a long-term collection of tweets posted by 66 academic communities over five years, and (2) a subset of information-seeking tweets with human annotated labels (the types of questions). We are making the data sets available for academic researchers and public use, to enable the disovery of new insights and development of better techniques to facilitate information seeking.
## Data

The conference tweets are collected through keywords search using Topsy API in 2014. The keywords vary for each conference and each year, but typically include two parts in the text and follow the format of "Conference Acronym"+"Year". For example, the International World Wide Web Conference in the year of 2013 would have the hashtag as "www2013". 

Duration: 2008 to 2013
Total number of tweets:  334,507

We further identify the information seeking tweets by checking whether the tweet contains the question mark (?) in its text. From here, we design the information seeking question categorization and develop the code book to help human subjects identify the question type. The human annotation are obtained from Amazon Mechanical Turk. Based on the human annotations, we train machine classifiers to identify the question types for the rest of information seeking tweets.

Duration: 2008 to 2013

Total number of labeled information seeking tweets: 1,899
Total number of unlabeled information seeking tweets: 9,967

## Publication

If you make use of this data set, please cite:

Wen, X., & Lin, Y. R. (2015, November). Information Seeking and Responding Networks in Physical Gatherings: A Case Study of Academic Conferences in Twitter. In Proceedings of the 2015 ACM on Conference on Online Social Networks (pp. 197-208). ACM.



