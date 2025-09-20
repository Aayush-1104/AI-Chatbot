# 🤖 AI Chatbot using Groq + LangChain + Streamlit

This project is an **AI-powered conversational assistant** built with **Groq API**, **LangChain**, and **Streamlit**.  
It allows users to interact with different AI models, maintain conversational memory, and choose between multiple personas (Default, Expert, Creative).  

---

## 🚀 Features
- **Multi-Model Support** – Choose between Groq models like `mixtral-8x7b-32768` and `llama3-8b-8192`.
- **Conversational Memory** – Configurable memory window to keep track of chat history.
- **Persona Modes** – Switch between Default, Expert, and Creative assistants.
- **Interactive UI** – Built with Streamlit for a clean and responsive interface.
- **Customizable Chat Settings** – Control memory length, clear history, and monitor chat statistics.

---

## 🛠️ Tech Stack
- [Streamlit](https://streamlit.io/) – Web app framework  
- [Groq](https://groq.com/) – High-speed AI inference engine  
- [LangChain](https://www.langchain.com/) – Conversational AI pipeline  
- [Python-dotenv](https://pypi.org/project/python-dotenv/) – Environment variable management  

---

## 📂 Project Structure
AI-Chatbot/
│── app.py # Basic chatbot implementation
│── main.py # Enhanced chatbot with personas, memory, stats
│── req.txt # Required dependencies
│── .env # Store your GROQ_API_KEY here
│── LICENSE # License file (Apache-2.0)


---

## ⚙️ Installation & Setup

### 1. Clone the repository
git clone https://github.com/Aayush-1104/AI-Chatbot.git
cd AI-Chatbot

### 2. Create and activate virtual environment (optional but recommended)
# Mac/Linux
python -m venv venv
source venv/bin/activate
# Windows
python -m venv venv
venv\Scripts\activate

