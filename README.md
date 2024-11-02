# Introduction



# What is Text Retrieval?
Text Retrievel (TR) (also called as Document Retrievel): A branch of information Retrievel (IR) where the system matching of some stated user search against a set of Text
![title](Images/swappy-20241102-075007.png)

# Basis Text Retrievel Pipline
  Query: A text descibers user's information need.

  Corpus: A set of document (texts)

  Relevance: satisfaction of user's information need.
  
  Information need: the topic about which the user desires to know more.

  Index: a data structure for storing document.

# Project Statement
I used [MSMARCO Dataset](https://huggingface.co/sentence-transformers/msmarco-distilbert-base-v2) to create a simple text retrivel program using Vector Space Model.

## Vector Space Model
Vector space model or term vector model is an algebraic model for representing text document as vectors such that the distance between vectors represents the relevance between document.

1. Brings raw text to vector space
2. Indexing
3. Calculate similarity between vectors4.
4. Ranking

