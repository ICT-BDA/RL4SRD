# Adapting Markov Decision Process for Search Result Diversification

## Training data
Files in the *data* fold

* query_permutation: documents information related to each query

* query_representation: embeddings of queries 

* document_representation: embeddings of documents 

* query_doc: subtopics covered by each document

## Command Line
python RL4SRD.py query_permutation.json query_representation.dat document_representation.dat query_doc.json folder

## Training results
The results are saved in *folder*

## Reference
[1] Long Xia, Jun Xu, Yanyan Lan, Jiafeng Guo, Wei Zeng, and Xueqi Cheng. Adapting Markov Decisioin process for Search Result Diversification. In Proc. SIGIR 2017. 
