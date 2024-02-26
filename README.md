# Retrieval-Augmented-Generation-with-Llama-2
![RAG](https://github.com/rajdas2001/Retrieval-Augmented-Generation-with-Llama-2/blob/main/rag.png)


## Introduction

### Dataset Used:
https://www.kaggle.com/datasets/lusfernandotorres/wikipedia-crypto-articles?resource=download

### Model Used:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML

1. Built on the Llama2 GGML model, this repository contains the code for a text generation model. Llama 2 is a pre-trained model with significant improvements over the Llama 1 models, including being trained on 40% more tokens, having a much longer context length (4k tokens), and using grouped-query attention.
2. One of the most significant advantages of employing GGML for quantization lies in its ability to facilitate efficient model compression while simultaneously upholding high performance standards and reducing memory footprint.
3. RAG has been implemented in this code to reduce hallucination and to help the model answer questions from a custom dataset (knowledge base).

## Dependencies
* python
* pandas
* numpy
* ydata-profiling
* ctransformers
* langchain
* chromadb
* streamlit
* sentence-transformers
* bitsandbytes
* torch
* transformers
