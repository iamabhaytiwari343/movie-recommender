# movie-recommender

A content based movie recommender that recommend movies based on tags

What is bag-of-Words algorithm ?

Bag of words is a Natural Language Processing technique of text modelling.
Bag of words is a Natural Language Processing technique of text modelling. In technical terms, we can say that it is a method of feature extraction with text data. This approach is a simple and flexible way of extracting features from documents.
A bag of words is a representation of text that describes the occurrence of words within a document. We just keep track of word counts and disregard the grammatical details and the word order. It is called a “bag” of words because any information about the order or structure of words in the document is discarded. 

Why it is used here ?

we are using this method to convert the tags for a movie into vectors whoose similiarity-score can be used for movie recommendation.

ast.literal_eval() is a function provided by the ast (Abstract Syntax Trees) module in Python. This function is used to safely evaluate a string containing a Python literal or container display, like a dictionary, list, tuple, set, or basic data types like strings, numbers, booleans, and None. It's commonly used to convert a string representation of a literal into the corresponding Python object.The main advantage of ast.literal_eval() over other evaluation methods like eval() is that it is safer. It only evaluates literals and not arbitrary code, which helps prevent code injection and security vulnerabilities.

