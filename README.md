# Conversational Bot Task

This project demonstrates how to build an interactive conversational AI assistant using Python and the **OpenRouter API**. The task is divided into two main parts: a chatbot that retains conversation history (memory) and a bot equipped with real-time web search capabilities.

---

## 🚀 Features

*   **Contextual Memory:** The bot remembers previous messages in the current session by maintaining a conversation history array.
*   **Interactive Chat Loop:** A continuous chat interface that allows users to talk to the bot until they type `exit` or `quit`.
*   **Web Search Integration:** Utilizes OpenRouter's web plugin to search the internet and provide up-to-date information.
*   **Secure Credentials:** API keys are managed securely using environment variables (`.env`).

---

## 🛠️ Prerequisites & Installation

### 1. Install Required Packages
You will need the `openai` SDK and `python-dotenv` for environment variable management. Install them via terminal:

```bash
pip install openai python-dotenv
