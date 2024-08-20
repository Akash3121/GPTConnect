# GPTConnect

Install Open AI

pip3 install openAI

---
This project is a simple AI chatbot that leverages OpenAI's GPT-3.5 Turbo model to engage in conversations. It uses the OpenAI API to send user prompts and receive responses from the model.

# Features
Real-time interaction with GPT-3.5 Turbo.
Continuously chat until the user decides to exit.
Exits the chat when the user types specific keywords like "bye," "break," "exit," or "quit."
# Prerequisites
Python 3.x installed on your machine.
An OpenAI API key.
# Installation
1. Clone the repository:

```
git clone https://github.com/your-username/gpt3-chatbot.git

cd gpt3-chatbot
```

2. Install dependencies:

Install the OpenAI Python package using pip:

```
pip install openai
```
3. Set up your OpenAI API key:

Replace "SECRET_KEY" in the openai.api_key assignment with your actual OpenAI API key.

```
openai.api_key = "YOUR_OPENAI_API_KEY"
```

# Usage
1. Run the chatbot:

Simply run the script in your terminal:

```
python chat.py
```

2. Interact with the chatbot:

Type your message and press Enter. The chatbot will respond based on the GPT-3.5 Turbo model. To exit, type any of the following: bye, break, exit, or quit.

# Example

```
You: Hello, how are you?
Chatbot: I'm just a bunch of code, but I'm here to help! How can I assist you today?

You: Tell me a joke.
Chatbot: Why don't programmers like nature? It has too many bugs.

You: quit
```