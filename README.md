# IMDb-Retrieval-Project
IMDb Information Retrieval System
This project uses the IMDb reviews dataset to explore Information Retrieval (IR) techniques. It demonstrates indexing, retrieval, and preprocessing workflows and compares the effectiveness of different retrieval models and text preprocessing methods.

Features
Dataset: A subset of IMDb reviews is used to index and query textual data.
Indexing: Efficient document indexing using PyTerrier.
Retrieval Models:
BM25: A probabilistic ranking model.
TF-IDF: A classic term-based ranking approach.
Text Preprocessing:
Porter and Snowball stemming are applied to reduce words to their base forms.
Query Evaluation: A sample query is executed across four configurations to compare retrieval effectiveness.
How It Works
Dataset Loading: IMDb reviews are loaded, and a subset of 2000 documents is prepared for processing.
Index Creation: Documents are indexed using PyTerrier, with separate indexes for stemmed and unstemmed text.
Retrieval Models: BM25 and TF-IDF are applied to rank documents based on the query.
Result Analysis: Rankings are analyzed across combinations of retrieval models and stemming methods.
Technologies Used
Python: For scripting and data handling.
PyTerrier: For indexing and retrieval.
NLTK: For text stemming.
Hugging Face Datasets: This is used to load the IMDb reviews dataset.
