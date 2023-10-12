# Leveraging Retriever-Reader Architecture for Enhanced Review-Based Question-Answering

**Author**: Mario Avolio

## Table of Contents
1. [Key Aspects Explored](#key-aspects-explored)
2. [Constructing a Question-Answering Pipeline Using the Retriever-Reader Architecture](#constructing-a-question-answering-pipeline-using-the-retriever-reader-architecture)
3. [Assessment and Enhancement of the QA Pipeline](#assessment-and-enhancement-of-the-qa-pipeline)
4. [Advancing with Generative QA: Retrieval-Augmented Generation (RAG)](#advancing-with-generative-qa-retrieval-augmented-generation-rag)

## Key Aspects Explored

### SubjQA Dataset, Span Classification, and Sliding Window Technique
- SubjQA is an English Question-Answering dataset centered around customer reviews in six domains: TripAdvisor, Restaurants, Movies, Books, Electronics, and Grocery.
- SubjQA focuses on understanding subjectivity in reviews, unlike previous QA datasets.

### Strategies for Extracting Answers from Text for Effective Question-Answering (QA) Systems
- Different types of Question Answering (QA) systems.
- The two-stage process of QA: retrieving relevant documents and extracting answers.
- Key tasks in building a QA system and challenges in handling long passages.

### Span Classification: Utilizing Pre-Trained Models
- The importance of leveraging pre-trained language models for QA.
- The focus on primary models: `roberta-base-squad2-distilled`, `xlm-roberta-large-squad2`, and `tinyroberta-squad2`.
- Tokenization and the process of extracting answers from text.

## Constructing a Question-Answering Pipeline Using the Retriever-Reader Architecture

### Efficient Document Retrieval and Answer Extraction
- Overview of the Retriever-Reader Architecture.
- The roles of Retriever and Reader.
- Using the Haystack library for QA system development.

### Document Store Selection: Leveraging Elasticsearch for Efficient Data Storage
- Introduction to the Elasticsearch Document Store.
- ElasticsearchDocumentStore features and functionality.

### Sparse Retrieval: Utilizing BM25 for Effective Document Retrieval
- Utilizing the BM25 algorithm for document retrieval.
- BM25's sparse vector approach for efficient searches.

### Reader Component: Enhancing Answer Extraction with DistilRoBERTa-base
- Details about the Reader component.
- Using the DistilRoBERTa-base model trained on SQuAD 2.0 for answer extraction.
- The sliding window technique for handling long contexts.

## Assessment and Enhancement of the QA Pipeline

### Retriever Evaluation: Comparative Analysis of DPR and BM25 with Recall Measure
- Evaluation of the Retriever component using the Recall metric.
- Comparison of Dense Passage Retrieval (DPR) and BM25.

### Reader Enhancement: Comparing Fine-Tune and Domain Adaptation Models with EM and F1-Score
- Assessment of Reader performance.
- Domain adaptation for enhancing performance.

### Overall QA Pipeline Evaluation: Measuring Performance Impact of Retriever on Reader
- Comprehensive evaluation of the entire QA pipeline.
- Comparison of the QA pipeline with baseline models.

## Advancing with Generative QA: Retrieval-Augmented Generation (RAG)

### RAG Overview: Introducing Retrieval-Augmented Generation as an Abstractive QA Approach
- Introduction to Abstractive or Generative QA.
- Retrieval-Augmented Generation (RAG) as a modern advancement in QA.

### Challenges of RAG: Limitations and Considerations
- Challenges in traditional RAG models.
- Use of PromptNode for overcoming limitations.
- The potential of using advanced models for further improvements.

### Solution: The PromptNode Approach with T5 and BM25
- Explanation of the PromptNode approach.
- Overcoming token size limitations.
- Concluding remarks.

## Conclusions
- Summary of key findings and outcomes.

> "Computer science is no more about computers than astronomy is about telescopes." - Edsger Dijkstra
