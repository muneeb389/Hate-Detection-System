# Hate-Detection-System

ABSTRACTION:
As online content continues to grow, so does the spread of hate speech.
Cyberbullying is increasing day by day and effecting many people life.
Looking at all this we came up with the idea to classify text/tweets into 3 classes.
We got the kaggle dataset for hatespeach containing tweets belonging to 3 classes (Hate, Offensive, Neither) all labeled with the count number of people classified
them as (Hate, Offensive, Neither). We marked each tweet with the class which was selected by maximum people.
We trained several models using that data and compared their scores.
Tweets containing offensive words e.g. (F**k you) etc. were classified in offensive class while simple day to day tweets were classified in neither class.  


INTRODUCTION:
The debate around the regulation of hate speech is still ongoing it is still not clear whether the best response to it is through legal measures,
or other methods Regardless of the means of countering it, the evident harm of hate speech makes its detection crucial. 
Both the volume of content generated online, particularly in social media, and the psychological burden of manual moderation supports the need for the 
automatic detection of offensive and hateful content.
Hate speech is not at all easy to identify, hence the data we used was labeled as hate, offensive, or neither by individuals.
That labels were used as benchmarks to train our model. The models we used were Random Forest, Naive Bayes, Logistic Regression, SVM and KNN

In this project we aimed to build a model through recognizing patterns in the tweets that in turn can identify
the offensive content on the social media and remove it so it doesn’t harm the society. 
Hate content being automatically detected and removed would make the social platform a lot cleaner and useable

Presentation of project is attached here:
[Hate speech detection.pptx](https://github.com/muneeb389/Hate-Detection-System/files/6758684/Hate.speech.detection.pptx)
