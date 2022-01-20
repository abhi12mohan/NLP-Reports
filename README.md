# Advanced Natural Language Processing - Reports

A collection of different reports I completed for my MIT 6.864 class (Graduate-level Advanced Natural Language Processing). Each report delves into a set of specific NLP topics, and provides some details regarding implementation of code (prohibited from sharing) and results of different experimental and theoretical tests. Additionally, I have included a research paper that my team wrote summarizing the results of our final research project.

## Overview
### 1. Factorization, Modeling, and Markov Models Report
I explored three different ways of using unlabeled text data to learn pretrained word representations. For each of the three representation learning schemes, I implemented, trained, and evaluated the scheme on a real dataset, then discussed some theoretical properties.

* General Details  
◦&nbsp; Matrix Factorization: Nearest neighbors, word embeddings, classification problems, LSA featurizer models  
◦&nbsp; Language Modeling: Downstream classification problem, Word2Vec-style models, context size  
◦&nbsp; Hidden Markov Models: Baum–Welch algorithm, categorical representations, n-gram models  

### 2. Seq2Seq and Trees Report
I implemented a neural machine translation (NMT) system using an RNN-based sequence-to-sequence (seq2seq) model, and practice constituency based parsing for semantic interpretation.

* General Details  
◦&nbsp; Seq2seq: Deterministic HMMs, EncoderDecoder models, decoding algorithms, model infrastructures  
◦&nbsp; Trees: Context free grammar, word/span embeddings, span labeling  

### 3. Question Answering Report
I explored the use of a transformer-based deep learning model (DistilBERT) for a Question-Answering task. After analyzing some of the basic properties of the pre-trained model, I fine-tuned the model on a public QA dataset (SQuAD) and evaluated it on a span-based answer extraction task.

* General Details  
◦&nbsp; Word embedding representations, QA modeling/decoding strategies, performance improvement  

### 4. Final Project Report
My group investigated different models and datasets on the efficacy of recognizing hate speech by performing dynamic, experimental evaluations for different permutations of categorized hate speech. We showed that while a DistilBERT model, with its pre-trained word representations, retains the highest accuracy overall, a more simple single-stream CNN maintains more resilience to dataset noise.

* General Details  
◦&nbsp; Models used: Single-stream and parallel convolutional neural networks (CNNs), Distilled Bidirectional Encoder Representations from Transformers (DistilBERT)  
◦&nbsp; Tests used: Accuracy, epoch loss, hate level classification, different training/evaluation methods  
