
## Multi-label Movie Genre Classification of big dataset using Random Forest in Spark 
The project demonstrates using Apache Spark on big dataset and using Natural processing techniques for text classifcation by predicting multi genres for a list of movies based on the plot summaries. A sequence of 0's and 1's of length 20 correspondimg to 20 genres is predicted for each movie. The sequence is mapped according to the format in mapping.csv file where 1 means that a particular genre is predicted for that movie and the opposite for 0.

### Data Description
o Training data (train.csv): Movie summaries of nearly 31,000
movies with their genres. This was used to train the predictive
analysis model.
o Testing data (test.csv): Plot summaries of nearly 31,000 movies
with their genres. This was used to test the predictive analysis
model.
o Sample data (sample.csv): Sample submission file which shows
the format in which the predictions (0s or 1s) are to be done.
o Mapping data (mapping.csv): Mapping of genre to string index.
If it’s a Drama movie then there’s a 1 at the first position and if
not, 0 elsewhere.

## List of Techniques Used
RegexTokenizer
StopWordsRemover
Count Vectorizer
TF-IDF
Word2Vec
Random Forest(for classification model)
String Indexing

<b> Macro F-1 score of 1 was obtained after using Random Forest and Word2Vec. </b>
