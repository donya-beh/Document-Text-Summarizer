## Document-Text-Summarizer

# Project Overview

This project implements a serverless document summarization pipeline using AWS services and generative AI. The system automatically processes uploaded documents, generates concise summaries using Amazon Bedrock, and stores the results for retrieval through a web interface.

The pipeline is designed as an event-driven architecture, meaning the entire workflow is automatically triggered when a new document is uploaded. This eliminates the need for manual processing and allows documents to be summarized quickly and efficiently.

The system leverages several AWS services including Amazon S3, AWS Lambda, Amazon Bedrock, Amazon DynamoDB, and API Gateway to create a scalable and fully serverless architecture.

# Use Case

As a consultant assisting attorneys representing children in lawsuits against youth-serving organizations, large volumes of historical documents must be analyzed to identify patterns of negligence and institutional failures. These documents can include:

- Journals

- Books

- News articles

- Scholarly reports

- Historical publications dating back decades

Reviewing these documents often requires creating executive summaries of long texts, which can be time-consuming and repetitive. This pipeline automates that process by:

- Accepting uploaded documents

- Using generative AI to summarize key takeaways

- Storing summaries in a structured database

- Making summaries easily accessible through a web interface

The result is a system that can significantly reduce the time required to analyze large collections of documents while still highlighting the most important insights.
