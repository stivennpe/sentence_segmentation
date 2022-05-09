#Sentence Segmentation for English

Basic implementation of a sentence segmentor for English.
It predicts when a comma and a dot(period) should be next.
The daset used was the Brown corpus and the treebank corpus both available in NLTK's library.
It is built on a Bi-LSTM as a classification task:

Dataset was tagged as:
 If next token is "." then tag the previous word as "P"
 If next token is "," then tag the previous word as "C"
 All the rest are tagged as "I".
 

See notebook for hyperparameters, better and bigger datasets should be used to achieve better performance.

