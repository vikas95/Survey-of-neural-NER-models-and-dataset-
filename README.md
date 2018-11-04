# Survey of neural NER models and datasets
This repository is written as a blog for the conference paper "A Survey on Recent Advances in Named Entity Recognition from Deep Learning models" (http://www.aclweb.org/anthology/C18-1182)  published at COLING 2018 (Santa Fe, NM).

If you find these resources useful, please cite our above Neural NER survey paper - 



## NER datasets

CoNLL 2002, 2003 - Newswire NER dataset in Spanish, Dutch, English, German languages - 
[CoNLL 2002 dataset](https://www.clips.uantwerpen.be/conll2002/ner/) ,
[CoNLL 2003 dataset](https://www.clips.uantwerpen.be/conll2003/ner/)

NER dataset on 7 slavic languages (Croatian, Czech, Polish, Russian, Slovak, Slovene, Ukrainian) - [shared task](http://bsnlp.cs.helsinki.fi/shared_task.html)

Clinical NER dataset - 2010 I2B2 NER task - [shared task](https://www.i2b2.org/NLP/Relations/)

Drug NER shared task - [shared task 1](https://www.cs.york.ac.uk/semeval-2013/task9/index.html), [shared task 2]

Chemical and Drug NER - [collection of similar datasets](http://www.biocreative.org)

Microbiology NER - [shared tasks](http://2016.bionlp-st.org/tasks/bb2) 

## Neural Netowrk based Named Entity Recognition (NER) models 

### Word+Char level NN NER model

CNN(characters) + Word embeddings

Convolution Neural Networks (CNN) over characters of word and combines the output with word embedding giving the whole representation of the word. Then a Bi-LSTM layer is used over sentence where each word is defined by this word representation and finally softmax or CRF uses the output of this Bi-LSTM to generate labels.


Paper - End-to-end sequence labeling via bi-directional lstm-cnns-crf - [CODE](https://github.com/LopezGG/NN_NER_tensorFlow)

For more related papers on similar architectures, [read this paper](http://www.aclweb.org/anthology/P16-1101)

## Recent State of the Art models for Named Entity Recognition (NER) and contextual embeddings for NER



## NER evaluation metrics




