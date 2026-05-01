# NLP_Resumes2Roles
Natural Language Processing project that creates a list of job roles that will match with a given resume.
4 Vectorization methods are implemented:
* TF-IDF
* Word2Vec
* GloVe
* Sentence BERT

Authors:
* Ethan Eckmann
* Neha Indolikar
* Eddie Lin
* Chi-Heng (Henry) Wei

Class:
* I320D: Text Mining & Natural Language Processing Essentials
* Dr. Abhijit Mishra

Demo:
This code creates a UI that allows you to enter in the text of a resume and get the best matching job roles. There are customizable for the number of results and chosen vectorization method.

Analysis:
This code was used for testing and developing the project. It contains a BERTScore section for evaluating Recall, Precision, and F1-score for all 4 vectorization methods.

Notes on running .ipynb files: 
The first time you run either the demonstration or the main analysis .ipynb file, it will take a very long time. This is because all the vectors/embeddings need to be created on the first run. Unfortunately, since GitHub has a max file size of 100MB these supporting files could not be included.
The SentenceBERT embeddings take an extremely long time to generate if not using a GPU. 
