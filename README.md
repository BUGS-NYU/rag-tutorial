# rag-tutorial
Basic RAG model tutorial

## Setup Instructions
Ensure python3 installed

Run the following code in terminal to install necessary packages

```
pip install sentence-transformers transformers faiss-cpu numpy sentencepiece protobuf
```

## Setup Errors (debug info)
Following package may fail during installation (tested with python 3.13)
```
pip install sentencepiece
```
If this command gives an error message, refer to the following options.
- Filenotfound error: do pip install wheel & install cmake from website
- Otherwise, try running a different python version