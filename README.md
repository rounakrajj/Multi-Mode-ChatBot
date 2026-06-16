# 🤖 Multi-Mode ChatBot

An AI-powered chatbot built using **LangChain**, **Mistral AI**, and **Streamlit**. This chatbot supports multiple personalities, allowing users to interact with different AI behaviors through both a command-line interface and a web-based UI.

## ✨ Features

* 🎭 Multiple AI personalities:

  * 😂 Funny AI
  * 🧐 Serious AI
  * 😔 Sad & Empathetic AI
* 💬 Interactive Streamlit chat interface
* 🖥️ Terminal-based chatbot support
* 🔐 Environment variable support using `.env`
* ⚡ Powered by Mistral AI and LangChain

## 📂 Project Structure

```text
ChatBot/
├── README.md
├── requirements.txt
├── chatmodels/
│   ├── UIchatbot.py      # Streamlit web chatbot
│   ├── chat.py           # Basic Mistral AI test script
│   └── chatbot.py        # Terminal-based chatbot
└── embeddingmodels/      # Future embedding implementations
```

## 🛠️ Technologies Used

* Python
* LangChain
* Mistral AI
* Streamlit
* python-dotenv
* FastAPI

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/rounakrajj/ChatBot.git
cd ChatBot
```

### Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate      # macOS/Linux

# Windows
venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure environment variables

Create a `.env` file:

```env
MISTRAL_API_KEY=your_api_key_here
```

## ▶️ Running the Application

### Streamlit UI

```bash
streamlit run chatmodels/UIchatbot.py
```

### Terminal Chatbot

```bash
python chatmodels/chatbot.py
```

## 🔮 Future Improvements

* Conversation memory support
* Retrieval-Augmented Generation (RAG)
* Vector database integration using FAISS
* Additional AI personalities
* FastAPI deployment endpoint

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

## 📜 License

This project is licensed under the MIT License.
# ChatBot
AI Chatbot built with Streamlit, LangChain, and Mistral AI
