# <center> Assignment - Explore HMM POS Taggers using Brown corpus </center>

## Task 1 Load and explore your data

## Task 2 Method 1: Build a baseline method, namely, the most frequent tagger 
If you can recall, we introduced a strong baseline method (See Dan's book in 
 https://web.stanford.edu/~jurafsky/slp3/ed3book_jan72023.pdf Page 164.),
     where we label each word by using the most frequent-used tag associated with it.


Notice: since there are unkown words in test samples. 

Following ways could handle this (choose one or create your own): 

(1). mark all words that appear only once in the data with a "UNK-x" tag

(2). tag every out-of-vocabulary word with the majority tag among all training samples.

(3). find more methods in https://github.com/Adamouization/POS-Tagging-and-Unknown-Words


## Task 3 Method 2: Build an HMM tagger 
Notice: You may also need to handle unknown words just like Task 2.

1) You should use nltk.tag.HiddenMarkovModelTagger to build an HMM tagger.

It has parameters: symbols, states, transitions, outputs, priors, transform (ignore it).
Specify these parameters properly. For example, you can use MLE to estimate transitions, outputs and priors.
That is, MLE to estimate matrix A (transition matrix), and matrix B (output probabilites) (See. Page 8.4.3)

1) Compared with your baseline method, discuss that why your HMM tagger is better/worse than baseline method.


##  Task 4 Method 3: Fine-tuning on BERT-base model for POS-tagging