# SarcasmClassifier
This repo is a sarcasm detection classifier built with GloVe embeddings and a BiLSTM model in PyTorch.
It's hitting ~99% Train Accuracy and 86%+ Validation Accuracy — clean, fast, and no overengineering.

## Project structure:
```
├── data/                     # Dataset in JSON format
│   └── File.json
│
├── model/                    # Trained model weights
│   └── SarcasmClassifier.pth
│
├── Notebook/                 # Full pipeline Jupyter notebook
│   └── bilstm.ipynb
│
└── README.md                 # You're here
```
## Results:
Training accuracy : 99.45%
Validation accuracy : 86.67%

You can download the GloVe embeddings from here - [https://nlp.stanford.edu/data/glove.6B.zip]
