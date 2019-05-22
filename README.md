# Stack-Overflow-NLP
## Classifying Stack Overflow questions through NLP and a neural network

In this project, completed using a dataset retrieved from kaggle through a database, natural language processesing techniques, in conjunction with a neural network, are used to classify questions asked on Stack Overflow. The questions are classified into one of five languages: Java, Javascript, Python, SQL, or R. These questions are labeled by first extracting features from their code blocks. The features extracted from these code blocks include common syntax characters such as brackets, periods, arithmetic operators, etc. The thought process was that, by training the neural network on these features, the network would be able to differentiate questions based on how frequently these characters appeared within the code blocks of each question. Additionally, sklearn's `CountVectorizer` is applied to the contents and title of each question creating a "bag of words". These features are used as the inputs to the deep neural network(DNN). 

The results are displayed within the Jupyter Notebook. These results were limited due to memory constraints on the Kaggle kernel; I was unable to perform K-fold cross validation nor was I able to obtain a larger dataset due to memory constraints. Nevertheless, a precision, recall, and f1-score of approximately 0.80 was achieved. 

In order to improve this project in the future, I would like to engineer a method of extracting syntatic features not limited to characters. This includes spacing, new lines, and style patterns unique to each programming language.



