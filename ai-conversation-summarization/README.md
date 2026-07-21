# Add Conversation Summarization to Your AI Chatbot

A Streamlit chatbot that automatically summarizes long conversations 
every 3 user messages using OpenAI's gpt-4o-mini, reducing token usage 
and cost while preserving context. Built as part of an eCornell assignment.

## Features
- Streaming chat responses (gpt-4o)
- Automatic conversation summarization (gpt-4o-mini)
- Real-time token usage tracking
- Sidebar showing running conversation summary

## Run locally
1. `pip install -r requirements.txt`
2. Set your OpenAI API key as an environment variable: `OPENAI_API_KEY`
3. `streamlit run app.py`
