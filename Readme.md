# University Natural Language Processing exercises

The following repository includes exercises from my **Natural Language Processing(NLP)** coursework. The course consisted of fundamentals of **NLP** and **Information Retrieval(for textual contents)** as one of the NLP applications. Four exercises have been gathered in this repository which is described in the following:

### Exercise-1: Analytical Dictionary 
The purpose of this exercise is to form a dictionary from a pair of English and Farsi subtitles. For tokenizing English sentences, we used the simple regex to remove extra characters from text and split them by space. Though, for tokenizing Farsi sentences, we used the hazm library because of the complexion of the Farsi language. In the end, by comparing the frequency of words used together as a pair in different sentences and using enough data, we can achieve the English-to Farsi-dictionary which is not so far from the actual dictionary.

### Exercise-2: Max Length Tokenizer algorithm
The Max length tokenizer algorithm is when there are missing spaces or merged words in the document. In the implementation of this exercise, I used multi-threading to speed up the processing of the documents proposed by the instructor.

### Exercise-3: Information Retrieval on Hamshari news
This exercise is a search problem on the Hamshari news corpus. We used Information Retrieval Boolean Model to implement this exercise. 


### Exercise-4: Naive Bayes Classifier
In this exercise, we are supposed to implement the Naive Bayes Classifier to classify the Hamshari news corpus into 23 categories. our implementation of this classifier using 80% of data for the training phase was able to gain ~ 75% accuracy in classifying the news.

**Note**: Datasets used for these exercises is not available on this repository because of its size. **(~ 10 GB)**