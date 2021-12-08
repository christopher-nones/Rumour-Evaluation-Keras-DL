# Rumour-Evaluation-Keras-DL
Google Collab notebook detailing full NLP rumour evaluation framework using Tensorflow Keras

Following an iterative approach 7 models were trained and testing using the same subset of data. 
The best model was selected and achieved a macro F-1 of 0.32 which is comparable to RumourEval submissions with a larger feature set.
Testing this method on independent data created by me yeilded a macro F-1 of 0.58


- The goal was to build a deep learning NLP model that could determine the veracity of a response to a rumourous tweet, similar to Rumour Eval 2017
- Tweet replies can either be in support, denial, querying or simply commenting on the source rumour tweet.
- Regex and pandas used for data cleansing
- NLP Techniques used include tokenization, stop word removal, lemmetization
- A custom word embedding was generated and transferred to GLoVE word embedding
- RNN modeling techniques include LSTM and Bi-Directional LSTM and multi input models
- Final model achieved a macro F-1 of 0.32, in line with other Rumour Eval entries
