# RL4SRD

## Train
### 训练数据  
data文件夹中，query_permutation是每个query的相关文档信息，query_representation是每个query的向量表示，document_representation是每个文档的向量表示，query_doc是每个文档所包含的subtopic

### 运行命令
python RL4SRD.py query_permutation.json query_representation.dat document_representation.dat query_doc.json folder

### 训练结果
实验结果存储在folder中