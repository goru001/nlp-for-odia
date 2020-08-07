# NLP for Oriya

This repository contains State of the Art Language models
 and Classifier for Oriya, which is spoken in the Indian state of Odisha.
  
The models trained here have been used in [Natural Language Toolkit for Indic Languages
 (iNLTK)](https://github.com/goru001/inltk)


## Dataset

#### Created as part of this project
1. [Oriya Wikipedia Articles](https://www.kaggle.com/disisbig/odia-wikipedia-articles)

2. [Oriya News Dataset](https://www.kaggle.com/disisbig/odia-news-dataset)

#### Open Source Datasets
1. [IndicNLP News Article Classification Dataset - Oriya](https://github.com/ai4bharat-indicnlp/indicnlp_corpus#indicnlp-news-article-classification-dataset)

## Results

#### Language Model Perplexity

| Architecture/Dataset | Oriya Wikipedia Articles |
|:--------:|:----:|
|   ULMFiT  |  26.57  |
|  TransformerXL |  26.81  |


#### Classification Metrics

##### ULMFiT

| Dataset | Accuracy | MCC | Notebook to Reproduce results |
|:--------:|:----:|:----:|:----:|
| IndicNLP News Article Classification Dataset - Oriya |  98.83  |  98.44  | [Link](https://github.com/goru001/nlp-for-odia/blob/master/classification/Oriya_Classification_Model.ipynb) |

#### Visualizations
 
##### Word Embeddings

| Architecture | Visualization |
|:--------:|:----:|
| ULMFiT | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/goru001/nlp-for-odia/master/language-model/embedding_projector_config.json) |
| TransformerXL | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/goru001/nlp-for-odia/master/language-model/embedding_projector_transformer_config.json)  |


## Pretrained Models

#### Language Models 

Download pretrained Language Model from [here](https://drive.google.com/open?id=1aTiXrnSHakkRzZHGjIJ0Euaq9E8k8HPe)

#### Tokenizer

Trained tokenizer using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://drive.google.com/open?id=1ZRE5UWg0qo8USZ-V0XhIH3GFjjCk-mzR)