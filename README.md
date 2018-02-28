# MSc.-thesis
Speech utterance classification for triage of 911 emergency calls


The utilisation of speech utterance classification for triage of 911 emergency calls
is described in this research paper. Using speech utterance of caller to analyze and
prioritize 911 emergency calls can reduce call wait time and enable the call taker to
make better and faster decisions. The objective of the research is to examine and
compare the performance of four most widely used text classification algorithms,
Logistic Regression, Support Vector Machine (SVM), AdaBoost and Naive Bayes
for speech utterance classification and prioritization of 911 calls. The research
utilised transcripts of 911 audio calls that were created using IBM, Google and
CMUSphinx Automatic Speech Recogniser (ASR) as training datasets. The classi-
ers were trained on numerical feature vectors of bag-of-words from each training
dataset and tested on manually transcribed first utterance of 911 calls and were
evaluated on classication accuracy and F-score. Furthermore, these classiers were
trained on three dierent features vectors from Bag-of-words, tf-idf weighting and
word2vec model of Google ASR generated dataset to verify if word2vec features vec-
tors improve classier's accuracy. The result showed there was no improvement in
classication accuracy when word2vec features vectors were used. Support Vector
Machines achieved the highest classication accuracy of 73% when feature vectors
of bag-of-words from Google ASR generated dataset were used for training.
