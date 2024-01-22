# Overview

An implementation of the parameter free text classification scheme with gzip.

# Structure
## `main.c` Responsibilities
+ handle the test case and the training set, which contains text and labels
+ calculate the NCD and grab the nearest k
+ classify test text file with nearest k

## `parsecsv.c` Responsibilities
+ parse (text, label) tuples from file, given a .csv file pointer

## `knn.c` Responsibilities
+ given labels and text, calculate the NCD and KNN of the test text 