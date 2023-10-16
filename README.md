# Retriever-Reader Architecture for Review-Based Question-Answering

## Overview
This project focuses on building a Review-Based Question-Answering (QA) system using a Retriever-Reader architecture. I explore key aspects, strategies, and techniques to enhance QA performance.

## Key Aspects Explored
- **SubjQA Dataset**: I work with the SubjQA dataset, designed for understanding subjectivity in customer reviews across various domains.
- **QA System Building Blocks**: I discuss the two-stage process of QA, involving document retrieval and answer extraction.
- **Span Classification**: I delve into the use of pre-trained language models and tokenization for extracting answers from text.

## Construction of QA Pipeline
Learn how to build an effective QA system:

### Efficient Document Retrieval
I employ Elasticsearch for efficient data storage and discuss the sparse retrieval technique using BM25.

### Enhanced Answer Extraction
I utilize the DistilRoBERTa-base model for answer extraction and tackle long contexts with the sliding window technique.

## Assessment and Enhancement of QA Pipeline
In this section, I assess and improve the QA pipeline:

### Retriever Evaluation
I compare Dense Passage Retrieval (DPR) with BM25 using recall measures for retriever performance.

### Reader Enhancement
I evaluate the reader's performance, explore domain adaptation, and discuss the impact on overall QA performance.

### Overall QA Pipeline Evaluation
A comprehensive assessment of the entire QA pipeline and a comparison with baseline models.

## Advancing with Generative QA: RAG
Explore the latest in Generative QA with Retrieval-Augmented Generation (RAG):

### RAG Overview
Understand the concept of Abstractive QA, the challenges it poses, and how RAG enhances traditional QA systems.

### Challenges and Solutions
I discuss the limitations of traditional RAG models and introduce the PromptNode approach to overcome these challenges.

## Conclusions
I summarize my findings and discuss the efficiency and performance of the QA pipeline, including my vision for future enhancements.

## Reference
For more in-depth knowledge on Natural Language Processing and Transformers, you can refer to the book:
- **Title**: [Natural Language Processing with Transformers: Building Language Applications with Hugging Face](https://books.google.ch/books?id=7hhyzgEACAAJ)
- **Authors**: Lewis Tunstall, Leandro von Werra, Thomas Wolf
- **ISBN**: 1098103246
- **Year**: 2022
- **Publisher**: O'Reilly Media, Incorporated
