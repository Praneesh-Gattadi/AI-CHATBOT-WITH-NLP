# AI CHATBOT WITH NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: Gattadi Praneesh

*INTERN ID*: CT04DM1319

*DOMAIN*: Python Programming

*DURATION*: 4 Weeks

*MENTOR*: NEELA SANTOSH

# 🤖 NLP-Based Chatbot using Python and NLTK

## 📄 Overview

This project is a simple rule-based chatbot built using **Python** and **Natural Language Toolkit (NLTK)**. It processes user input using basic NLP techniques and
returns appropriate responses from a predefined FAQ database.
The chatbot identifies greetings, matches user queries to known questions using string similarity (edit distance), and provides fallback replies when it doesn't
understand the input. This project is ideal for learning how NLP can be applied in basic chatbot development without using machine learning.

## ✨ Features

- 🧠 **Natural Language Processing**: Uses NLTK for tokenizing user input and comparing queries.
- 💬 **Predefined Knowledge Base**: Handles common questions related to Python, machine learning, internships, GitHub, etc.
- 🔁 **Continuous Chat Loop**: Engages users in a conversation until they type a termination keyword like `bye`.
- 👋 **Greeting Recognition**: Responds appropriately to greetings like "hi", "hello", etc.
- 🎯 **Edit Distance Matching**: Matches user input to FAQ entries even with slight spelling variations.
- ❓ **Fallback Handling**: If the chatbot can't understand the input, it asks the user to rephrase.

## 🛠 Technologies Used

Python - Programming language                    
NLTK - Tokenization and edit distance calculation

> 🔌 No internet APIs, databases, or third-party frameworks are used. It's lightweight and runs in the terminal.

## 📁 File Structure

chatbot_project/
│
├── chatbot.py # Main Python script with chatbot logic
├── README.md # Project documentation

## ▶️ How to Run

Follow these steps to set up and run the chatbot on your system:

1. 🔧 Prerequisites
Make sure Python 3.x is installed. You can verify it by running:
python --version

3. 📦 Install Required Package
Install the Natural Language Toolkit (NLTK):
pip install nltk

3. 📂 Download NLTK Resources
The first time you run the chatbot, it will download the tokenizer:
nltk.download('punkt')
nltk.download('punkt_tab')
This is handled automatically in the script.

4. 🚀 Run the Chatbot
Run the script from your terminal or command prompt:
python chatbot.py

6. 💬 Interact with the Bot
Start asking questions or greeting the bot. For example:

You: Hello
Chatbot: Hi there!

You: What is Python?
Chatbot: Python is a high-level, interpreted programming language...

6. ❌ Exit the Chat
To end the conversation, type any of the following:
bye
exit
quit

## Note

This chatbot is designed for basic educational and demonstration purposes.
You can enhance it by integrating APIs, machine learning, or a GUI (not included here).
It's kept minimal to focus on understanding NLP basics using NLTK.





