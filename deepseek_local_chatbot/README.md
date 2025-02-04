# DeepSeek Local Chatbot 🤖

A locally-run AI chatbot powered by DeepSeek models through Ollama, Langchain and Streamlit

[Chatbot Interface](screenshot.png)

## Chatbot Features ✨
- 🔒 100% local execution - no internet required with help of models from Ollama
- 🎛️ Model size selection (1.5B or 7B parameters)
- 💬 Real-time chat with streaming responses
- 📚 Conversation history persistence
- ⚡ LangChain integration for efficient processing

## Prerequisites 📋
- Python 3.8+
- [Ollama](https://ollama.ai/) installed locally
- Deepseek models pulled from Ollama
- 8GB+ RAM (16GB recommended for 7B model)

## Installation ⚙️

### 1. Set Up Ollama
```bash
# Start Ollama service (keep running in separate terminal)
ollama serve
