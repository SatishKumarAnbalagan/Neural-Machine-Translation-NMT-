# Neural-Machine-Translation-NMT-
Implementation of neural machine translation (NMT) using Recurrent Neural Network (RNN) choosing either Long Short-Term Memory (LSTM) or Gated Recurrent Units (GRU). Trained &amp; tested using Stanford University’s NLP pre processed WMT ’15, WMT'14, IWSLT'15 datasets. The English-Vietnamese English-Czech and English-German datasets can be found at: https://nlp.stanford.edu/projects/nmt/ under Preprocessed Data. Choose any one of the three datasets (English-Czech, English-German, and English-Vietnamese), based on your interests and the data size.

“NMT.py” file runs with the following commands:
python NMT.py train
python NMT.py test
python NMT.py translate

# Train
"python NMT.py train" to train the network displaying the training loss in each iteration of training function. The model is saved in a folder named “model” after finishing the training process.

# Testing
"python NMT.py test" which will (1) load the testing data and translate the sentences; and (2) calculate the BLEU score (referring to https://www.nltk.org/_modules/nltk/translate/bleu_score.html) with the smoothing method1.

# Translate
“python NMT.py translate” which will accept the command. Given a sentence, the model will be able to translate it into the corresponding language.
