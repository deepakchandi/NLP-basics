SMS Spam Classification

The purpose of this project was to build a model that can accurately identify which texts are spam. The data data I obtained and bunch of text messages along with spam messages. The first step was to clean the data and remove unnecessary columns and add any extra features that I think were important to make a good model. After cleaning the next step was to to do some preprocessing, which included removing stop words, stemming each word, making all the letters lower case, and then use TFIDF to get numerical values related to the data. 

After that the only thing was to build a basic model and then tune that model to get better results. I used few idfferetn models like SVM, Naive Bayes, and Random Forest. Naive Bayes gave me the best results after just doing a basic grid search. My final model predicted spam messages correctly 98% of the times. Which is almost 12% better than my MVP.


Acknowledgements:

The original dataset was obtained from:
https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection.

The information and the inspiration to use this dataset to build a prediction model was obtained from:
http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/.
