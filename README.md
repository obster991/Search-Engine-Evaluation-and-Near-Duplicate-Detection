# Search Engine Evaluation and Near Duplicate Detection

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

University project at the course of Data Mining Technology for Business and Society concerning the building of a search engine using the Pyterrier library and the Near Duplicates Detection task.

## Project Tasks

The project is divided in two main parts:

1. Search Engine Evaluation:
   - use the Pyterrier library in order to build a search engine for the 'irds:nfcorpus/dev dataset' and improve the search-engines performance, comparing different pipeline combination of preprocessing and weighting model, togheter with choosing in a proper way different evaluation metrics of the information retrieval task (like Normalized Discounted Cumulative Gain or Mean Recirpocal Rank) in order to understand the quality of the engine.
   - given several scenarios, like a company needing a search engine for the dataset of scientific paper, being able to build the proper search engine with a single specific configuration of preprocessing, weighting model and evaluation metrics, justifying the choice. 

2. Near Duplicate Detection:
   - in this part of the homework, we have to find, in an approximated way, all near-duplicate documents inside a collection of documents, following the rules below.
   
    >- We will consider Near-duplicates all those pair of documents that have a Jaccard similarity greater than or equal to 0.95 <br>
    >- Each set of shingles, that represents an original document, must be sketched in a Min-Hashing sketch with a length of at most 210 <br>
    >- The probability to have as a near-duplicate candidate a pair of documents with Jaccard=0.95 must be > 0.97 <br>
    >- The generation process of near-duplicate pairs you implement must generate the smallest amount of both False-Negatives and False-Positives <br>
    >- The running time of all the LSH process must be less than 10 minutes, and motivate the choice of the hyperparameters like the row and band for the LSH.

## Project group members
- [Giulio D'Erasmo](https://github.com/giulio-derasmo)
- [Andrea Potì](https://github.com/obster991)


