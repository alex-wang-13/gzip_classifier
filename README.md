# Overview

An implementation of the parameter free text classification scheme with gzip.

# Structure
## `main.c` responsibilities
+ handle the test case and the training set, which is a list of (text, labels)
+ calculate the NCD and grab the nearest k
+ classify test text file

## `parsecsv.c` responsibilities
+ parse (text, label) tuples from file names, given a .csv file pointer

## 