# Conversation Management & Classification using Groq API

This notebook implements:
- Task 1: Conversation history manager with truncation and periodic summarization.
- Task 2: JSON Schema extraction (function-calling with Groq/OpenAI-compatible client) and offline regex fallback.

## How to run (Colab)
1. Open the notebook in Google Colab.
2. Run the "Install dependencies" cell.
3. Run the "Secure prompt" cell and paste your GROQ API key (hidden). If you don't have a key, leave empty — offline fallbacks will run.
4. Run "Model discovery" cell to see available models. Set `MODEL = "<model-id>"` if auto-selection doesn't work.
5. Run all cells (Runtime → Run all).

**Security:** Do NOT commit API keys. If you exposed a key publicly, revoke it and create a new one.

## Files
- `Conversation_Management_Groq_complete.ipynb` — main notebook
- `.gitignore` — recommended ignores
