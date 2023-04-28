# Spam-Detection
NLP spam detection project using LSTM
Dataset from paper:
Almeida, T.A., GÃ³mez Hidalgo, J.M., Yamakami, A. Contributions to the Study of SMS Spam Filtering: New Collection and Results. Proceedings of the 2011 ACM Symposium on Document Engineering (DOCENG'11), Mountain View, CA, USA, 2011.


Preprocessed data and removed all punctuation and stopwords. Vectorized all message texts and created embeddings. Created sequential model with embedding layer, LSTM, fully connected layer, and sigmoid layer to convert to probabilities. Trained on 2/3, tested on 1/3 for a 97.99% accuracy on the test set, as well as a precision of 0.996 and a recall of 0.981.
