# AI Chatbot

A simple and interactive AI Chatbot built with HTML, CSS, and JavaScript, leveraging the Gemini 2.0 Flash model for generating responses. This chatbot allows users to have conversations, ask questions, and even attach images or other files for context.

## Features

* **Interactive Chat Interface:** A clean and user-friendly interface for seamless conversations.
* **Gemini 2.0 Flash Integration:** Powered by Google's Gemini 2.0 Flash model for intelligent and relevant responses.
* **File Attachment Support:** Users can attach images (`.png`, `.jpg`, etc.) or other files (`.pdf`, `.txt`, `.csv`) to their prompts, providing visual or textual context for the AI.
* **Real-time Typing Effect:** Simulates a natural conversation flow with a typing animation for bot responses.
* **Theme Toggle:** Switch between light and dark themes for a personalized viewing experience.
* **Chat History:** Maintains a history of the conversation within the current session.
* **Clear Chat:** Option to clear the entire chat history.
* **Stop Response:** Ability to stop the AI's response generation midway.
* **Suggested Prompts:** Provides pre-defined suggestions to kickstart conversations.

## Technologies Used

* **HTML5:** For the basic structure of the web application.
* **CSS3:** For styling and layout.
* **JavaScript (ES6+):** For interactive functionality and communication with the AI API.
* **Google Gemini 2.0 Flash API:** The core AI model for generating responses.
* **Material Symbols Rounded:** For various icons used in the interface.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need a Google Cloud Project with the Gemini API enabled and an API Key.

1.  **Enable the Gemini API:**
    * Go to the Google Cloud Console.
    * Create a new project or select an existing one.
    * Navigate to "APIs & Services" > "Enabled APIs & Services."
    * Search for "Gemini API" and enable it.

2.  **Create an API Key:**
    * In the Google Cloud Console, go to "APIs & Services" > "Credentials."
    * Click "Create Credentials" > "API Key."
    * Copy the generated API key.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd ai-chatbot
    ```

2.  **Update your API Key:**
    Open `script.js` and replace `"AIzaSyDLQ0BkKRrZMX7ttz1I8mHrhi_Yfexnkjs"` with your actual Google Gemini API key:

    ```javascript
    const API_KEY = "YOUR_GEMINI_API_KEY_HERE"; // Replace with your actual API key
    ```

3.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser. You can do this by double-clicking the file or by serving it with a local web server (e.g., Live Server VS Code extension).

## Usage

1.  **Type your message:** Enter your query in the input field at the bottom of the chat interface.
2.  **Attach files (optional):** Click the "attach\_file" icon to upload an image or other supported file. A preview will be shown. You can cancel the attachment using the "close" icon.
3.  **Send your message:** Press Enter or click the "arrow\_upward" (send) icon.
4.  **Stop response (optional):** If the bot is still typing, click the "stop\_circle" icon to stop its response.
5.  **Clear chats:** Click the "delete" icon to clear the entire conversation.
6.  **Toggle theme:** Click the "light\_mode" or "dark\_mode" icon to switch themes.

