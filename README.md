# Fake News Detection

This model will accurately classify a piece of news as REAL or FAKE.

Using sklearn, we build a TfidfVectorizer on our dataset. Then, we initialize a PassiveAggressive Classifier and fit the model. In the end, the accuracy score and the confusion matrix tell us how well our model fares.

<img
src=“https://github.com/SaifAlmaliki/Fake-news-detection/blob/master/Fake_real-1_gebpwg.png”
raw=true
alt=“Subject Pronouns”
style=“margin-right: 10px;”
/>

What is a TfidfVectorizer? 
TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

What is a PassiveAggressiveClassifier? 
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.

Source: https://data-flair.training/blogs/advanced-python-project-detecting-fake-news/
