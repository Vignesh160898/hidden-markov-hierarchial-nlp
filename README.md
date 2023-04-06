# Hidden_markov-hierarchial_clustering-expectation_maximization
This project demonstrates how to use Expectation-Maximization, Hierarchical Clustering, and Hidden Markov Models for various NLP tasks, such as Word Sense Induction, Named Entity Tagging, and Part-of-Speech Tagging

## Table of Contents

1. [Introduction](#introduction)
2. [Expectation-Maximization Clustering for Word-Sense Induction](#em-clustering)
3. [Hierarchical Clustering for Named Entity Tagging](#hierarchical-clustering)
4. [Hidden Markov Model and Viterbi Algorithm for Part-of-Speech Tagging](#hmm-viterbi)
5. [Conclusion](#conclusion)

## Introduction <a name="introduction"></a>

In this project, we implement and explore three different techniques for natural language processing tasks:

1. Expectation-Maximization Clustering for Word-Sense Induction
2. Hierarchical Clustering for Named Entity Tagging
3. Hidden Markov Model and Viterbi Algorithm for Part-of-Speech Tagging

## Expectation-Maximization Clustering for Word-Sense Induction <a name="em-clustering"></a>

We implement the Expectation-Maximization (EM) algorithm to train a word-sense induction system, applied to the word 'say'. The goal is to identify different senses of the word 'say' in the given corpus. The process involves extracting sentences, creating bag-of-words vectors, and running the EM clustering algorithm.

## Hierarchical Clustering for Named Entity Tagging <a name="hierarchical-clustering"></a>

In this section, we download articles from Wikipedia and cluster them into groups using hierarchical clustering. We preprocess the data and vectorize the text data using either CountVectorizer or TfidfVectorizer from the `sklearn` library. A dendrogram is plotted to visualize the hierarchical relationships between articles, and Agglomerative Hierarchical Clustering is used to assign cluster labels to each document or group.

## Hidden Markov Model and Viterbi Algorithm for Part-of-Speech Tagging <a name="hmm-viterbi"></a>

Here, we build Hidden Markov Models (HMMs) and implement the Viterbi Algorithm for Part-of-Speech (POS) tagging. We use the Wall Street Journal dataset for training and testing. The process involves creating dictionaries for emission counts, transition counts, and tag counts, followed by implementing the Viterbi algorithm to predict POS tags for each word in the corpus.

## Conclusion <a name="conclusion"></a>

This project provides a comprehensive understanding of various NLP techniques and their implementation for different tasks such as Word Sense Induction, Named Entity Tagging, and Part-of-Speech Tagging. It demonstrates the use of Expectation-Maximization, Hierarchical Clustering, and Hidden Markov Models in solving NLP problems effectively.
