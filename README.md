# Lexical-Complexity-Prediction
CMSC 516 : Advanced Natural Language Processing Project

Predicting the lexical complexity of Single words.

SemEval Task 1 - Lexical Complexity Prediction (https://arxiv.org/abs/2106.02340)


## Installation and Requirements

* **Requirements**

  * **Python 3.6** (Tested in this environment) 
  * Cuda



* Download the required dependencies

```sh
    pip install -r requirements.txt
```

* Download GloVE Embeddings

```sh
    wget http://nlp.stanford.edu/data/glove.6B.zip

    unzip glove*.zip
```

## Run the code (Using Google Colab Notebook)

* Our model for lexical complexity prediction can also be run following the instructions in [this](https://colab.research.google.com/drive/1eOBl3uR874tt3IMQKEXPIRNCMdRmcCsy#scrollTo=LoMP9ehkCncl) Colab Notebook

* Go to the Runtime tab above and select Run all. This will run the whole notebook and the results can be seen in the end cells

## Experiments
* We also experimented with the task using BERT transformer model in [this](./https://colab.research.google.com/drive/1t2A-O-XJJ-V2vtPDFZzyU0IyP4Frr4Nt#scrollTo=TxryALeh_G0e&uniqifier=5) Colab Notebook

* Note: This code (Transformer Model) may take a significant amount of time to run (in the order of hours)
