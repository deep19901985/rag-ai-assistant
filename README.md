# RAG AI Assistant (LLM + n8n)

## Overview

This project is a Retrieval-Augmented Generation (RAG) based AI assistant designed to improve response accuracy by combining large language models with external data retrieval.

## Key Features

* Uses OpenAI APIs for natural language responses
* Implements RAG to reduce hallucinations
* Integrates with n8n workflows for automation
* Supports multi-channel deployment (WhatsApp, Telegram, Web)

## Motivation

While building this system, I observed that LLM outputs can be inconsistent and sometimes hallucinate when context retrieval is weak. This project explores ways to improve reliability by enhancing retrieval quality and structuring context more effectively.

## Tech Stack

* OpenAI API
* n8n (workflow automation)
* Vector database (Pinecone / similar)
* JavaScript / Python (basic integration)

## Future Work

* Improve retrieval filtering and ranking
* Add evaluation metrics for hallucination detection
* Experiment with structured prompts and validation layers

## Author

Deepthy Chullikkatt Kunjachan
