# Multi-class-classification-on-Stack-Overflow-questions using Tensorflow
A naive approach to multiclass text classifier on stack overflow questions with almost **`80%`** accuracy!

This notebook we are going to train a multi-class classifier to predict the **tag** of a programming question on [Stack Overflow](http://stackoverflow.com/) using tensorflow.

## The Dataset
A [dataset](https://storage.googleapis.com/download.tensorflow.org/data/stack_overflow_16k.tar.gz) has been prepared and is ready to be used. It contained the body of several thousand programming questions (for example, "How can I sort a dictionary by value in Python?") posted to Stack Overflow. Each of these is labeled with exactly one tag (either `Python, CSharp, JavaScript`, or `Java`). The task is to take a question as input, and predict the appropriate tag, in this case, Python.

The dataset we will work with is a sample containing several thousand questions extracted from the much larger public Stack Overflow dataset on [BigQuery](https://console.cloud.google.com/marketplace/details/stack-exchange/stack-overflow), which contains more than 17 million posts.
