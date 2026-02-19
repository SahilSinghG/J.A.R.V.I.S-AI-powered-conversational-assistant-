# 🤖 J.A.R.V.I.S – AI Chatbot with Persistent Memory (Streamlit + Ollama)

J.A.R.V.I.S is an AI-powered chatbot built using **Streamlit** and **Ollama**, designed to provide interactive conversations with persistent chat history. The system stores conversations in a database, allows users to switch between chats, and automatically generates meaningful conversation titles.

This project demonstrates real-world AI application development including:

* LLM integration
* Persistent chat storage
* Conversation management
* Interactive frontend using Streamlit
* Modular and production-ready architecture

---

# 🚀 Features

## 1. Interactive AI Chat

* Chat with AI models powered by Ollama
* Real-time responses
* Clean and user-friendly interface

## 2. Multiple Model Support

* Dynamically fetch available Ollama models
* Select different models from dropdown

## 3. Persistent Chat History

* Conversations are stored in database
* Automatically saves user and assistant messages
* Reload previous chats anytime

## 4. Automatic Chat Title Generation

* Automatically generates conversation title based on first message

## 5. Conversation Management

* Create new chats
* Switch between existing chats
* View previous chat history

## 6. Modular Architecture

* Clean separation of:

  * UI layer
  * Services layer
  * Database layer

---

# 🏗️ Project Structure

```
project/
│
├── main.py                  # Streamlit frontend application
├── requirements.txt        # Dependencies
├── .env                    # Environment variables
├── env_template.txt       # Environment template
│
├── services/
│   ├── get_models_list.py
│   ├── get_title.py
│   └── chat_utilities.py
│
├── db/
│   └── conversations.py
│
└── README.md
```

---

# ⚙️ Installation

## Step 1: Clone the repository

```
git clone https://github.com/yourusername/jarvis-ai-chatbot.git

cd jarvis-ai-chatbot
```

---

## Step 2: Create virtual environment

Windows:

```
python -m venv venv
venv\Scripts\activate
```

Mac/Linux:

```
python3 -m venv venv
source venv/bin/activate
```

---

## Step 3: Install dependencies

```
pip install -r requirements.txt
```

---

## Step 4: Setup Environment Variables

Create `.env` file using template:

```
cp env_template.txt .env
```

Fill required values.

---

## Step 5: Start Ollama

Make sure Ollama is installed and running.

Example:

```
ollama run llama3
```

---

# ▶️ Run the Project

Use this command:

```
streamlit run main.py
```

---

# 🖥️ How It Works

## Workflow

1. User enters message
2. Message stored in database
3. Selected Ollama model generates response
4. Response displayed to user
5. Response stored in database
6. Conversation available for future access

---

# 🧠 Technologies Used

* Python
* Streamlit
* Ollama (LLM)
* SQLite / Database
* Environment Variables
* Modular Architecture

---

# 📌 Use Cases

* AI Chatbot applications
* LLM integration projects
* Interview demonstration project
* Learning AI application architecture
* Production-ready chatbot foundation

---

# 🎯 Interview Value

This project demonstrates:

* LLM integration
* Persistent storage design
* Modular architecture
* Frontend + backend integration
* Real-world AI system design

# 🔮 Future Improvements

* User authentication
* Cloud deployment (AWS / GCP)
* Vector database integration
* RAG support
* Streaming responses
* Multi-user support

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Sahil Guleria

Associate Software Engineer | AI/ML Enthusiast

---
