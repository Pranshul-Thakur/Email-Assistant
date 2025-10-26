# Email Assistant

A LangGraph-based email assistant. It uses AI to detect spam, categorize legitimate messages, and draft polite preliminary responses for review, streamlining email management through an intelligent state-driven workflow.

## Features

- **Spam Detection**: Automatically identifies and filters spam emails
- **Email Classification**: Categorizes legitimate emails (inquiry, complaint, thank you, etc.)
- **Draft Responses**: Generates professional preliminary responses for review
- **Workflow Automation**: Uses LangGraph's state machine to orchestrate the email handling process

## How It Works

The system processes emails through a multi-node workflow:
1. Reads incoming email
2. Classifies as spam or legitimate using AI
3. Routes spam to spam folder or drafts a response for legitimate emails
4. Notifies the user with a prepared draft response

## Tech Stack

- **LangGraph**: Workflow orchestration
- **LangChain**: LLM integration
- **OpenAI**: Language model for classification and response generation
