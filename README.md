# Document-Text-Summarizer

# Project Overview

This project implements a serverless document summarization pipeline using AWS services and generative AI. The system automatically processes uploaded documents, generates concise 5 bullet pointsummaries using Amazon Bedrock, and stores the results for retrieval through a web interface.

The pipeline is designed as an event-driven architecture, meaning the entire workflow is automatically triggered when a new document is uploaded. This eliminates the need for manual processing and allows documents to be summarized quickly and efficiently.

The system leverages several AWS services including Amazon S3, AWS Lambda, Amazon Bedrock, Amazon DynamoDB, and API Gateway to create a scalable and fully serverless architecture.

