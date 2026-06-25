# NexusChat AI

A conversational AI assistant built using **LangGraph**, **LangChain**, **OpenAI**, and **Streamlit**. The chatbot supports persistent conversations, intelligent tool calling, and real-time response streaming.

---

## Features

- 💬 Multi-thread conversations
- 🧠 Persistent chat memory using SQLite
- 🔧 Intelligent tool calling
- 🌐 Web search using DuckDuckGo
- 📈 Live stock price lookup using Alpha Vantage API
- 🧮 Built-in calculator tool
- ⚡ Real-time streaming responses
- 🎨 Interactive Streamlit interface

---

## Tech Stack

- Python
- LangGraph
- LangChain
- OpenAI
- Streamlit
- SQLite
- DuckDuckGo Search
- Alpha Vantage API

---

## Project Structure

```text
GraphAssist-AI/
│── backend.py
│── frontend.py
│── requirements.txt
│── README.md
│── .gitignore
│── .env.example
└── assets/
```

---

## How It Works

1. The user enters a query through the Streamlit interface.
2. LangGraph manages the conversation flow and state.
3. The LLM decides whether a tool is required.
4. If needed, the appropriate tool (Calculator, Web Search, or Stock Price) is executed.
5. The tool output is sent back to the LLM to generate the final response.
6. The conversation is automatically saved using SQLite, allowing users to resume previous chats.

---

## Future Improvements

- 🌦️ Weather tool integration
- 📰 News API integration
- 📄 PDF Chat (RAG)
- 🎙️ Voice input/output
- 🐳 Docker support
- 🚀 FastAPI backend
- 🔐 User authentication

---

## Author

**Jay Unadkat**

If you found this project useful, feel free to ⭐ the repository!
