Toxic-Comment-Detection
=======================

 

Project Contributors

\----Abhay Kumar Singh (130004782)

\----Mukund Srinath Heragu (128003513)

\----Rizu Jain (430000753)

\----Vindhya Ningegowda (930001925)

 

Toxic Comment Detection is Natural Language Processing based project which tries
to identify the toxicity of a comment based on training multiple types of
Machine and Deep Learning Models.

 

**Directory Structure**

 

Toxic Comment Project

\----Preprocessing

\--------Preprocessing.ipynb -\> *Jupyter notebook with preprocessing logic*

\--------Data -\> *Original Data along with preprocessed pickle files*

\----Binary Classification

\--------TF-IDF

\------------Logistics Regression

\----------------Logistics Regression.ipynb -\> *Jupyter Notebook with Logistics
Regression Algorithms*

\----------------Models -\> *Saved Models to avoid model creation again*

\------------Naive Bayes

\----------------Naive Bayes.ipynb -\> *Jupyter Notebook with Naive Bayes
Algorithms*

\------------SVM

\----------------SVM.ipynb -\> *Jupyter Notebook with SVM Algorithms*

\----------------Models -\> *Saved Models to avoid model creation again*

\--------Word2Vec

\------------Logistics Regression

\----------------Logistics Regression.ipynb -\> *Jupyter Notebook with Logistics
Regression Algorithms*

\----------------Models -\> *Saved Models to avoid model creation again*

\------------Naive Bayes

\----------------Naive Bayes.ipynb -\> *Jupyter Notebook with Naive Bayes
Algorithms*

\------------SVM

\----------------SVM.ipynb -\> *Jupyter Notebook with SVM Algorithms*

\----------------Models -\> *Saved Models to avoid model creation again*

\------------Word2Vec_Data -\> This directory contains the Word2Vec embedding
data

\----Multilabel Classification

\--------FastText

\------------FastText_NN.ipynb -\> Jupyter notebook with FastText embedding and
Neural Network Algorithms

\------------Data -\> *Preprocessed pickle files*

\------------Models -\> *Saved Models to avoid model creation again*

\--------GloVe

\------------LSTM_GloVe.ipynb -\> Jupyter notebook with GloVe embedding and LSTM
Algorithm

\------------Data -\> *Preprocessed pickle files*

\------------Models -\> *Saved Models to avoid model creation again*

 

**How to run the Project?**

Please perform the steps in the same order.

 

1.  Run Preprocessing/Preprocessing.ipynb. Running this file will perform
    preprocessing and save preprocessed file and training testing split files in
    Preprocessing/Data folder.

2.  For TF-IDF Binary Classification, go to Binary Classification/TF-IDF/ folder
    and run any of the algorithm.

3.  For Word2Vec Binary Classification, download file from
    http://nlp.stanford.edu/data/glove.6B.zip , unzip it and move
    glove.6B.50d.txt to Binary Classification/Word2Vec/Word2Vec_Data. Then run
    any of the algorithm from Binary Classification/Word2Vec folder.

4.  For GloVe Multilabel Classification, use the downloaded file from
    http://nlp.stanford.edu/data/glove.6B.zip , move glove.6B.100d.txt file to
    Multilabel Classification/GloVe/Data. Then run LSTM_GloVe.ipynb in
    Multilabel Classification/GloVe folder.

5.  For FastText Multilabel Classification, download file from
    <https://dl.fbaipublicfiles.com/fasttext/vectors-english/crawl-300d-2M.vec.zip>
    , unzip it and move crawl-300d-2M.vec file to Multilabel
    Classification/FastText/Data. Then run FastText_NN.ipynb in Multilabel
    Classification/FastText folder.

 

 

Note -\> Every .ipynb file has it’s PDF version in the same directory to view
the initial model created by us along with the results.
