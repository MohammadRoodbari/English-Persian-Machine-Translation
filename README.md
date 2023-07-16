# English-Persian-Machine-Translation

> This repository is made for the NLP course project -  2023.

* Translating English text to Persian using [Fairseq-py](https://github.com/facebookresearch/fairseq).

---

## Models
- en-fa-MT_model1
  - LSTM Decoder-encoder architecture includes one encoder layer and one decoder layer with with attention mechanism
  - [sentencepiece] model is used for byte-pair-encoding (BPE) data(https://github.com/google/sentencepiece)
  - train model using [Fairseq-py](https://github.com/facebookresearch/fairseq)
- en-fa-MT_model2
  -

## Data

AFEC dataset includes aligned Persian and English sentences and human-translated sentences. For more information about the AFEC dataset, you can read its [article](https://aclanthology.org/2012.amta-caas14.3/)

HengamCorpus data along with strong labeled data is uploaded in [HuggingFace](https://huggingface.co/datasets/kargaranamir/HengamCorpus). Click on hyperlinks to download.
- HengamCorpus
  - [HengamCorpus train data](https://huggingface.co/datasets/kargaranamir/HengamCorpus/resolve/main/train.txt)
  - [HengamCorpus test data](https://huggingface.co/datasets/kargaranamir/HengamCorpus/resolve/main/test.txt)
  - [HengamCorpus validation data](https://huggingface.co/datasets/kargaranamir/HengamCorpus/resolve/main/val.txt)
- [Strong labeled data](https://huggingface.co/datasets/kargaranamir/HengamCorpus/raw/main/strong.txt)