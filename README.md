# IMDB_Sentiment_Analysis
sentiment analysis aims to determine the attitude of a speaker, writer, or other subject with respect to some topic or the overall contextual polarity or emotional reaction to a document, interaction, or event. The attitude may be a judgment or evaluation (see appraisal theory), affective state (that is to say, the emotional state of the author or speaker), or the intended emotional communication (that is to say, the emotional effect intended by the author).

Sentiment Analysis can be carried out by text preprocessing using the standard NLP procedures and applying Language Understanding Algorithms to predict user sentiments.

**Problem Statement:**

In this, we have to predict the number of positive and negative reviews based on sentiments by using classification model.

**About the dataset**

* The Data has been collected from the internet movie database(IMDB)
* The dataset consists of 100K Reviews out of which 50K reviews are unsupported i,e they are not labelled as neither positive nor negative
* Remaining 50k reviews has been labelled as positive or negative
* At least 7 out of 10 stars => positive (label=1)
* At most 4 out of 10 stars => negative (label=0)

**Steps Involved:**
>  Creating the movie review corpus by performing necessary text preprocessing steps

* Lowering the text
* Removing URL's
* Removing punctuations,Stopwords, and Extraspaces
* Applying lemmatization
* Using TF-IDF Vectorizer to create Word Embeddings
* model building
