Book recommendation system  

A system that takes the user's favorite book and recommends book titles that the user might be interested in, based on various similarity factors.  

Dataset: https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata

Recommendation Fucntion:  

The system uses a 2-filtering appraoch, first it filters the dataset based on the category of the book selected by the user, then calculates the cosine similarity of the chosen book with all the other books of the same category, the top 10 similar books are selected and they are sorted based on their weighted rating. The top 5 books with the most weighted rating are recommended to the user

Pre-processing method: Lemmatization  
Vectorizing method: Tf-Idf  
Similarity measure: Cosine similarity

Instructions to run:
1. Simply download the .ipynb file and dataset.
2. After uploading the dataset and running the code, in a new cell, add the following command:

	```recommend("<name of the book>")```

Please ensure that you pass the name of a book that is present in the dataset books.csv
