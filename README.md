# NLP for Telugu

This repository contains State of the Art Language models
 and Classifier for Telugu language(spoken in Indian sub-continent)

The models trained here have been used in [Natural Language Toolkit for Indic Languages
 (iNLTK)](https://github.com/goru001/inltk)

## Dataset

#### Created as part of this project
1. [Telugu Wikipedia Dataset](https://www.kaggle.com/shubhamjain27/telugu-wikipedia-articles)

2. [Telugu News Dataset](https://www.kaggle.com/shubhamjain27/telugu-news-articles)

## Results

#### Language Model Perplexity

| Architecture/Dataset | Telugu Wikipedia Articles |
|:--------:|:----:|
|   ULMFiT  |  27.47  |
|  TransformerXL |  29.44  |

#### Classification Metrics

##### ULMFiT

| Dataset | Accuracy | Kappa Score |
|:--------:|:----:|:----:|
| Telugu News Articles |  95.4  |  93.8  |

#### Visualizations
 
##### Embedding Space

| Architecture | Visualization |
|:--------:|:----:|
| ULMFiT | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/Shubhamjain27/nlp-for-telugu/master/language-model/embedding_projector_config.json) |
| TransformerXL | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/Shubhamjain27/nlp-for-telugu/master/language-model/embedding_projector_transformer_config.json)  |



## Pretrained Language Model

Download pretrained Language Model from [here](https://drive.google.com/file/d/14y13-QqgZ9fkxDi5IyLVMswWaT4JgYpJ/view?usp=sharing)


## Classifier

Download classifier from [here](https://drive.google.com/file/d/1-5YYYFdbGKVK4CvGYqYxbq2JubmkiDfH/view?usp=sharing)


## Tokenizer

Trained tokenizer using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://drive.google.com/open?id=19ew2B2IPy_t7hRFnNDFvIvysAUtv2SNt)
