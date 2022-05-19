# Graph Transformer Networks
- This repository is a modification of [original repository](https://github.com/seongjunyun/Graph_Transformer_Networks) for [Graph Transformer Networks(NeurIPS'19)](https://arxiv.org/abs/1911.06455).
- This repository is used for lab freshman and undergraduate students seminar in [MLILAB](https://mli.kaist.ac.kr).

## Download required libraries
```
pip install -r requirements.txt
```

## Download DBLP, ACM, IMDB dataset
- Download data.zip dataset from [this link](https://drive.google.com/file/d/1qOZ3QjqWMIIvWjzrIdRe3EA4iKzPi6S5/view?usp=sharing) and unzip it to the uppermost directory of this repository.

- Make sure that the data are located like below.
```
Graph-Transformer-Network
├── main.py
├── model.py
├── gcn.py
├── utils.py
├── data_preprocessing.ipynb
├── ACM.mat
├── data
    ├── ACM
        ├── edges.pkl
        ├── labels.pkl
        └── node_features.pkl
    ├── DBLP
        ├── edges.pkl
        ├── labels.pkl
        └── node_features.pkl
    └── IMDB
        ├── edges.pkl
        ├── labels.pkl
        └── node_features.pkl    
├── imgs
    └── GTN.png
├── requirements.txt
└── README.md
```

## TODOs

### TODO 1 : Fill in models.py
```
- DBLP
```
$ python main.py --dataset DBLP --num_layers 3
```
- ACM
```
 $ python main.py --dataset ACM --num_layers 2 --adaptive_lr true
```
```

## TODOs