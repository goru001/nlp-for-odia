# NLP for Odia

This repository contains State of the Art Tokenizer, Language model
 and Classifier for Odia, which is spoken spoken in the Indian state of Odisha.

## Dataset

* Download [Odia Wikipedia Articles Dataset](https://drive.google.com/open?id=1urhDry1d6geLSKUl9SZdxw2BB61vyb_D) (17,781 articles) which I scraped, cleaned and
used to train the language model

* Download [Odia News classification Dataset](https://drive.google.com/open?id=1dHPdD5E-cK48nUH6AjsEQe5fOKkexodj) which I scraped and used to train 
the classifier

## Results

#### Language Model

`on 30% validation set`

* Perplexity of language model: ~27

#### Classifier

* Accuracy of classification model: ~95%
* Kappa score of classification model: ~92

## Pretrained Language Model

Download pretrained Language Model from [here](https://drive.google.com/open?id=1aTiXrnSHakkRzZHGjIJ0Euaq9E8k8HPe)


## Classifier

Download classifier from [here](https://drive.google.com/open?id=1VShx6epZmQI_8BnXvF6Gqb4vHiNpb1qm)


## Tokenizer

Trained tokenizer using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://drive.google.com/open?id=1ZRE5UWg0qo8USZ-V0XhIH3GFjjCk-mzR)