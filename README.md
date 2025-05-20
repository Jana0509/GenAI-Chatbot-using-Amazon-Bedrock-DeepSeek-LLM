# 🤖 GenAI Chatbot using Amazon Bedrock + DeepSeek LLM

This project is a fully functional **Generative AI chatbot application** built using **Amazon Bedrock**, powered by the **DeepSeek LLM**. It combines a serverless backend using LangChain with a dynamic, interactive frontend built in Streamlit.

---

## 🚀 Features

- Context-aware, multi-turn chatbot
- Powered by **DeepSeek**, one of the foundation models available on **Amazon Bedrock**
- Built using **LangChain** for LLM chaining and memory handling
- UI developed with **Streamlit** for a clean, real-time chat interface
- 100% **serverless** and **scalable** architecture

---

## 🧩 Tech Stack

| Layer        | Tool / Service        | Description                                                                 |
|--------------|------------------------|-----------------------------------------------------------------------------|
| LLM          | Amazon Bedrock (DeepSeek) | Serverless access to foundation models (FMs) for generative AI tasks        |
| Memory & Logic | LangChain              | Framework for chaining prompts and managing conversation state              |
| UI           | Streamlit               | Python-based frontend for real-time interaction                             |

---

## 🧠 Core Components Explained

### 1. `ChatBedrockConverse`
- Wrapper class in LangChain that connects to **Amazon Bedrock's DeepSeek LLM**
- Handles API interaction securely using AWS credentials
- Simple and efficient LLM invocation without manual setup

### 2. `ConversationSummaryBufferMemory`
- Smart memory module from LangChain
- Maintains context by summarizing past conversation chunks
- Ensures memory stays compact and relevant while improving response accuracy

### 3. `ConversationChain`
- Combines LLM, prompt template, and memory into one chain
- Takes care of passing context and structuring the prompt
- Perfect for multi-turn, human-like conversations

---

## 🧪 What I Learned

- Using **Amazon Bedrock APIs** securely and effectively within LangChain
- Building memory-aware conversations using `ConversationSummaryBufferMemory`
- Chaining prompts and backend logic using `ConversationChain`
- Deploying a full-stack AI application with a responsive **Streamlit** interface

---

## 💬 Demo

> Coming soon: Live demo + deployment instructions.

---

## 🛠️ Setup Instructions

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/genai-bedrock-chatbot.git
   cd genai-bedrock-chatbot

