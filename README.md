# NLP
This folder contains all the work that I have done in my intro to NLP class. <br />
The critiques are collection of ideas after reading six research articles.<br />
The jupyter files are project scripts.<br />
[Hotel Review Classification](https://github.com/ShuEmily/NLP/blob/main/LMReviewClassification.ipynb): This project is to use n-gram-based language model and Naïve Bayes 
model to decide whether a hotel review is deceptive or truthful. In the process, I implemented 
add-k smoothing method and handled unknown words. Further based on perplexity score and final 
performance of accuracy, I chose the best parameters of uni-gram/bi-gram/tri-gram and k in 
smoothing.<br />
[NER tagging](https://github.com/ShuEmily/NLP/blob/main/NERTagging.ipynb): Given the famous dataset of CoNLL-2003, the task is to develop NLP models to identify
the named entities automatically. Treating it as sequence-tagging task, for each token in the input 
text, assign one of the following 5 labels: ORG (Organization), PER (Person), LOC (Location), MISC 
(Miscellaneous), and O (Not Named Entity). To achieve this goal, I implemented two sequence 
labeling approaches: Hidden Markov Model (HMM) and Maximum Entropy Markov (MEMM)
model to include more information in the context with the use of a logistic regression classifier. <br />
[Language Translation with Neural Networks](https://github.com/ShuEmily/NLP/blob/main/RNNLSTMSeq2seqStyleTransfer.ipynb): The goal of the project was to build an Encoder Decoder model to translate Modern English into Shakespearean English. Using PyTorch, I 
implemented different models including a basic Recurrent Neural Network (RNN) and modification
into Long short-term memory (LSTM). I also explored the different methods of embedding, 
including using pretrained embedding, self-trained embedding and no embedding, end-to-end 
implementation. Performance of the model like BLEU score is further dependent upon parameters 
such as batch size, hidden size, embedding size.
