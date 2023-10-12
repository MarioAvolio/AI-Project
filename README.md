# Retriever-Reader Architecture for Review-Based Question-Answering

## Overview
This project focuses on building a Review-Based Question-Answering (QA) system using a Retriever-Reader architecture. We explore key aspects, strategies, and techniques to enhance QA performance.

## Key Aspects Explored
- **SubjQA Dataset**: We work with the SubjQA dataset, designed for understanding subjectivity in customer reviews across various domains.
- **QA System Building Blocks**: We discuss the two-stage process of QA, involving document retrieval and answer extraction.
- **Span Classification**: We delve into the use of pre-trained language models and tokenization for extracting answers from text.

## Construction of QA Pipeline
Learn how to build an effective QA system:

### Efficient Document Retrieval
We employ Elasticsearch for efficient data storage and discuss the sparse retrieval technique using BM25.

### Enhanced Answer Extraction
We utilize the DistilRoBERTa-base model for answer extraction and tackle long contexts with the sliding window technique.

## Assessment and Enhancement of QA Pipeline
In this section, we assess and improve the QA pipeline:

### Retriever Evaluation
We compare Dense Passage Retrieval (DPR) with BM25 using recall measures for retriever performance.

### Reader Enhancement
We evaluate the reader's performance, explore domain adaptation, and discuss the impact on overall QA performance.

### Overall QA Pipeline Evaluation
A comprehensive assessment of the entire QA pipeline and a comparison with baseline models.

## Advancing with Generative QA: RAG
Explore the latest in Generative QA with Retrieval-Augmented Generation (RAG):

### RAG Overview
Understand the concept of Abstractive QA, the challenges it poses, and how RAG enhances traditional QA systems.

### Challenges and Solutions
We discuss the limitations of traditional RAG models and introduce the PromptNode approach to overcome these challenges.

## Conclusions
We summarize our findings and discuss the efficiency and performance of the QA pipeline, including our vision for future enhancements.
