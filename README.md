# English-Persian-Machine-Translation

> This repository is made for the NLP course project -  2023.

* Translating English text to Persian using [Fairseq-py](https://github.com/facebookresearch/fairseq).

---

## Models
- en-fa-MT_model1
  - LSTM Decoder-encoder architecture includes one encoder layer and one decoder layer with with attention mechanism
  - [sentencepiece](https://github.com/google/sentencepiece) model is used for byte-pair-encoding (BPE) data
  - train model using [Fairseq-py](https://github.com/facebookresearch/fairseq)

- en-fa-MT_model2
  - LSTM Decoder-encoder architecture includes one encoder layer and one decoder layer with with attention mechanism
  - [BERT-multilingual-base-model](https://huggingface.co/bert-base-multilingual-cased) Tokenizer is used for tokenize data
  - train model using [Fairseq-py](https://github.com/facebookresearch/fairseq) & Using the weights of the embedding layer of [BERT-multilingual-base-model](https://huggingface.co/bert-base-multilingual-cased) as the initial value of the Model weights
## Data

AFEC dataset includes aligned Persian and English sentences and human-translated sentences. For more information about the AFEC dataset, you can read its [article](https://aclanthology.org/2012.amta-caas14.3/)