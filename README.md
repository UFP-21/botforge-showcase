# BotForge - AI Bot Builder Showcase

BotForge is a showcase project for an AI bot builder that helps create business AI assistants with knowledge base support, retrieval flow and multi-provider LLM integration.

The idea of the project is simple: a user can create an AI assistant, upload business documents, connect a knowledge base, test responses and prepare the bot for use in a website or Telegram workflow.

This repository is published as a showcase. It demonstrates the product concept, system architecture, core workflows and my role in designing the solution. Private implementation details, API keys, real user data, internal workflows and production infrastructure are not published.

## Problem

Many small and medium businesses want to use AI assistants for support, sales, onboarding or internal knowledge access, but building a separate AI solution from scratch for every use case is slow and expensive.

BotForge addresses this by providing a structured workflow for creating configurable AI bots that can answer based on uploaded documents and business-specific knowledge.

## Solution

BotForge is designed as a product-style AI bot builder with the following workflow:

1. Create a new AI assistant.
2. Configure bot behavior and business context.
3. Upload documents for the knowledge base.
4. Process documents for retrieval.
5. Connect one or more LLM providers.
6. Test bot responses.
7. Review logs and analytics.
8. Prepare the bot for Telegram or website integration.

The key focus is not only LLM integration, but the complete backend and product flow around it: knowledge base handling, retrieval logic, bot configuration, testing, logs and analytics.

## My Role

My work on this project focused on:

* product logic design
* backend architecture planning
* AI bot workflow design
* knowledge base and retrieval flow
* multi-provider LLM integration concept
* document upload and processing flow
* response testing scenarios
* logging and analytics workflow
* showcase structure for portfolio presentation

## Key Features

* AI bot creation workflow
* knowledge base support
* document upload and processing
* retrieval-based answer generation
* multi-provider LLM integration
* bot behavior configuration
* response testing interface
* bot management dashboard
* logs and analytics
* preparation for Telegram or website deployment

## Tech Stack

* React
* TypeScript
* Node.js
* Express
* PostgreSQL
* Drizzle ORM
* FAISS
* OpenAI API
* Anthropic Claude API
* Google Gemini API
* DeepSeek API
* GigaChat API
* PDF processing
* Knowledge base / retrieval workflow

## Architecture Overview

The system is designed around several core layers:

1. **Web interface**
   Used for creating bots, managing settings, uploading documents, testing responses and viewing analytics.

2. **Backend API**
   Handles bot configuration, project data, knowledge base operations, LLM provider connections and application logic.

3. **Database layer**
   Stores projects, bots, users, settings, logs and metadata.

4. **Document processing layer**
   Handles uploaded files, extracts text and prepares content for retrieval.

5. **Knowledge base / retrieval layer**
   Selects relevant context from processed documents and passes it to the LLM layer.

6. **LLM provider layer**
   Provides a unified integration point for multiple LLM providers.

7. **Testing, logs and analytics layer**
   Helps test bot behavior, inspect responses and review usage patterns.

## Main User Flow

1. The user creates a new AI bot.
2. The user uploads documents or business materials.
3. The system processes the documents and prepares them for knowledge base search.
4. The bot receives a user question.
5. The retrieval layer selects relevant context.
6. The LLM generates an answer using the selected context and bot settings.
7. The user reviews the response, checks logs and improves the configuration if needed.

## Screenshots

The repository includes visual materials in the `assets` folder.

Suggested screenshot captions:

* Main dashboard
* Create AI bot
* LLM provider connection
* Bot management
* Logs and analytics

## What This Project Demonstrates

This project demonstrates my ability to work with applied AI product architecture, not only isolated API calls.

It shows experience with:

* designing AI assistant workflows
* structuring RAG-style knowledge base logic
* planning backend architecture for AI products
* integrating multiple LLM providers
* building document-based AI flows
* thinking through testing and observability
* presenting private or partially private projects safely as a showcase

## Repository Status

This repository is a showcase repository.

It does not include:

* production API keys
* `.env` files
* real user data
* private prompts
* production databases
* internal business workflows
* sensitive logs
* private infrastructure details

Additional technical details, architecture notes or workflow explanations can be provided separately when relevant.

## Related Skills

Python, FastAPI, RAG, knowledge bases, LLM integration, AI assistants, backend architecture, document processing, retrieval workflows, API integrations, prompt engineering, product logic, logs and analytics.
