# Book-Recommendation-System
A book recommendation system using cosine similarity and tf-idf vectorization that has the following steps:<br>

<li>Text Preprocessing: Clean and preprocess the summary data, including removing stop words, stemming, and converting to a numerical representation.<br>

<li>Tf-idf Vectorization: Use Tf-idf (term frequency-inverse document frequency) to convert the summary information into numerical vectors, representing the importance of each word in the summary.<br>

<li>Cosine Similarity Calculation: Use the cosine similarity metric to compare the similarity between the numerical vectors of the input book and all other books in the dataset.<br>

<li>Recommendation Generation: Based on the calculated cosine similarity scores, the system  recommends the top 10 books that are most similar in genre and summary information to the input book.<br>

The dataset is from https://www.kaggle.com/datasets/ymaricar/cmu-book-summary-dataset
