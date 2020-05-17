# Book_Recommender_System

In this repo we build a book recommender system for the Book-Crossing dataset : http://www2.informatik.uni-freiburg.de/~cziegler/BX/ .

We use "item-based collaborative filtering" approach, whose main feature is that we compute the distance of two books based on a metric
of our choice and the ratings that the book has received from all users. Then one can choose a book of their preference and the recommender
system will return a list of books which are close to the book.

The code file is structured as follows :

1) Exploring the dataset : We have 3 big dataframes, one for users, one for books and one for ratings.

2) The book-item matrix : We use it to compute the distances of the books. We deal with its sparsity by considering its CSR representation.

3) 
