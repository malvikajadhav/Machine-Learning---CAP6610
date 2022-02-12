# Homework 1 
## Problem Statement 1:

![image](https://user-images.githubusercontent.com/20522169/153694914-b631e12c-aa93-4624-ab4b-6ab3fb8c8a89.png)
<br>
## Problem Statement 2:
The 20 Newsgroups data set is a collection of approximately 20,000 newsgroup documents,
partitioned (nearly) evenly across 20 different newsgroups. The data set can be downloaded here:
<http://qwone.com/~jason/20Newsgroups/>. For simplicity, we will just focus on the “bag-of-words”
representation of the documents given in the Matlab/Octave section. In this case, the input xi
is a
vector of word histogram of doc i, and the output yi
is the news group that it belongs to.
The data has been divided into a training set and test set. You will build a model from the training
set, and evaluate its performance on the test set. The vocabulary size is more than 60,000, which is
bigger than the number of documents. (Also, you will find that the test data matrix has more rows
than the train data matrix, which means some words in the test data never appear in the training
data.) To simplify computation, you will prune the data first by keeping only the words that have
appeared more than 1,000 times in the training data (which is approximately 300) and keep only those
rows in both the train data matrix and the test data matrix.
![image](https://user-images.githubusercontent.com/20522169/153694946-787dcb73-8a13-45ce-8209-87ec55bf3098.png)
