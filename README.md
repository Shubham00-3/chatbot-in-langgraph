# Chatbot-in-LangGraph

This is a chatbot application built using LangGraph and Streamlit. It demonstrates how to create a conversational AI with persistent memory, allowing for multiple, independent chat threads and conversation history.

## 🚀 Features

  * **Conversational AI:** Engage in interactive conversations with a powerful language model.
  * **Streaming Responses:** Get real-time, streaming responses from the chatbot for a seamless user experience.
  * **Multi-Threaded Conversations:** Manage and switch between multiple, independent conversation threads.
  * **Persistent Memory:** Conversation history is saved to a SQLite database, so you can pick up where you left off.
  * **User-Friendly Interface:** A simple and intuitive user interface built with Streamlit.

## Project Structure

Here's a breakdown of the key files in this project:

  * `streamlit_frontend_Database.py`: The main Streamlit application file that serves as the user interface for the chatbot.
  * `langgraph_database_backend.py`: The backend logic for the chatbot, built with LangGraph. It manages the conversational state and interacts with the language model.
  * `requirements.txt`: A list of the Python packages required to run the project.
  * `.env`: This file (which you need to create) is for storing your API keys.

## 🛠️ Getting Started

Follow these steps to get the chatbot up and running on your local machine.

### Prerequisites

  * Python 3.7+
  * An API key from a supported language model provider (e.g., Groq, OpenAI).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/chatbot-in-langgraph.git
    cd chatbot-in-langgraph
    ```
2.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Configuration

1.  Create a file named `.env` in the root directory of the project.
2.  Add your API key to the `.env` file. For example, if you are using Groq:
    ```
    GROQ_API_KEY="your-groq-api-key"
    ```

### Running the Application

1.  **Start the Streamlit application:**
    ```bash
    streamlit run streamlit_frontend_Database.py
    ```
2.  Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).

## 🖥️ Usage

  * **Chatting:** Type your message in the input box at the bottom of the page and press Enter. The chatbot's response will be displayed in the chat window.
  * **Creating a New Chat:** Click the "New Chat" button in the sidebar to start a new conversation.
  * **Switching Conversations:** Your past conversations are listed in the sidebar. Click on a conversation to view its history and continue the chat.

## 🤝 Contributing

Contributions are welcome\! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

