# 🤖 Python AI Chatbot

A simple AI-powered chatbot built with **Python** and the **Groq API**. This project demonstrates how to create an interactive conversational chatbot that can maintain conversation history and generate AI responses in real time.

## 🚀 Features

- 💬 Interactive command-line chatbot
- 🧠 Maintains conversation history
- ⚡ Real-time AI-generated responses
- 🐍 Built with Python
- 🔑 Groq API key configuration using Google Colab Userdata

## 🛠️ Technologies Used

- Python
- Groq API
- Groq Python SDK
- Google Colab

## 🤖 AI Model

The chatbot uses the `openai/gpt-oss-120b` model through the Groq API.

## ⚙️ How It Works

1. Configure the Groq API key.
2. Install and import the Groq Python SDK.
3. Initialize the Groq client.
4. Get messages from the user through the command-line interface.
5. Store the conversation history.
6. Send the conversation to the AI model.
7. Display the generated response to the user.

## 💻 Example

```text
Your Message : yo
Bot Reply : Hey! What’s up? How can I help you today?

Your Message : im seshan
Bot Reply : Hey Seshan! What’s on your mind today? How can I help you?

Your Message : what is my name
Bot Reply : Your name is Seshan.
```

## 🔑 API Key Setup

This project is designed for Google Colab and retrieves the Groq API key from Colab Userdata.

Make sure your API key is stored securely as:

```text
GROQ_API_KEY
```

Do not hard-code or publish your API key in the GitHub repository.

## 📂 Project Structure

```text
Python-ChatBot/
│
├── Python ChatBot.ipynb
└── README.md
```

## 👨‍💻 Author

**Seshan Rodrigo**

---

⭐ If you find this project useful, consider giving the repository a star!
