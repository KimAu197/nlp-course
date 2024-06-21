# <center> Assignment1 </center>

## Task0 - Download datasets
> Download the preprocessed data, enwiki-train.json and enwiki-test.json from the Assignment-01 folder. In the data file, each line contains a Wikipedia page with attributes, title, label, and text. There are 1000 records in the train file and 100 records in test file with ten categories.



## Task1 - Data processing

## Task2 - Build language models

> 1) Based on the training dataset, build unigram, bigram, and trigram language models using Add-one smoothing technique. It is encouraged to implement models by yourself. If you use public code, please cite it.
> 2) Report the perplexity of these 3 trained models on the testing dataset and explain your findings. 
> 3) Use each built model to generate five sentences and explain these generated patterns.


## Task3 - Build NB/LR classifiers

> 1) Build a Naive Bayes classifier (with Laplace smoothing) and test your model on test dataset
> 2) Build a LR classifier. This question seems to be challenging. We did not directly provide features for samples. But just use your own method to build useful features. You may need to split the training dataset into train and validation so that some involved parameters can be tuned. 
> 3) Report Micro-F1 score and Macro-F1 score for these classifiers on testing dataset explain our results.
