# Stack-Overflow-NLP
## Classifying stack overflow questions through NLP and a neural network

In this project, completed using a dataset retrieved from kaggle through a database, natural language processesing techniques, in conjunction with a neural network, are used to classify questions asked on Stack Overflow. The questions are classified into one of five languages: Java, Javascript, Python, SQL, or R. These questions are labeled by extracting features from their code blocks as well as using count vectorization on their contents. These are then fed as inputs into a neural network. 

The results are displayed within the Jupyter Notebook. These results were limited due to memory constraints on the Kaggle kernel; I was unable to perform K-fold cross validation nor was I able to obtain a larger dataset due to memory constraints. Nevertheless, a precision, recall, and f1-score of approximately 0.8 was achieved. 

In order to improve this project in the future, I would like to engineer a method of extracting syntatic features not limited to characters. This includes spacing, new lines, and style patterns within the code blocks. 
