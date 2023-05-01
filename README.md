# Bit-Rebels
Natural Language Processing Spring 2023 Term Project **Asking Clarifying Question Based on requirement**


## Members:
+ Ananya Parikh                       
+ Neha Chowdhary
+ Kumar Pranjal Tripathi
+ Rashi Goyal


## Objective
Implementing Classification and Information Retrieval models better than base-case


## Problem Statement
Training a deep learning model to find out whether a clarifying question needs to be asked in a dialogue system, and which clarifying questions are needed to be asked. The main aim of the conversational systems is to return an appropriate answer in response to the user requests. However, some user requests might be ambiguous. In Information Retrieval (IR) settings such a situation is handled mainly through the diversification of search result page. It is however much more challenging in dialogue settings.

The ClariQ dataset aims to study the following situation for dialogue settings:

* a user is asking an ambiguous question (where ambiguous question is a question to which one can return > 1 possible answers);
* the system must identify that the question is ambiguous, and, instead of trying to answer it directly, ask a good clarifying question.

## Models used
We used the following models for Classsification task:
* BERT-base-uncased
* DistilBERT
* RoBERTa
* XLNet

We used the following models for Information Retrieval task:
* BM25okapi
* BERT-Ranker, BERT-reranker and Bm25
* ERNIE
* ELECTRA

## Contribution to Project

* **Retrieval Models**: Ananya Parikh (all)
* **Classification Models**: Neha Chowdhary (BERT-base-uncased, DistilBERT, RoBERTa, LSTM and GLOVE) and Rashi Goyal (XLNet)
* **Report**: Kumar Pranjal Tripathi and Neha Chowdhary

## To run

Our models are all uploaded as Notebooks.
