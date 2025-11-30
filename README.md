Simple AI Chatbot 

This project implements a simple AI-powered chatbot interface using Python and Streamlit. The application allows users to enter a message, sends it to an AI model through an API, and displays the model’s response in a clean, conversational layout.

Features
Intuitive web interface with a page title, text input field, and “Send” button.

Persistent multi-turn chat history managed with Streamlit session state.

Clear labeling of each turn as “You:” (user) and “Bot:” (assistant).

Prompt design that combines the user message with behavior instructions (for example, “Respond briefly and be friendly”).

The user types a message into the input field and clicks the “Send” button.

The message is added to the chat history stored in session state.

Project Structure
chatbot_app.py – Main Streamlit application containing the UI, chat history logic, and API integration.

README.md – Project documentation, including overview, features, and usage instructions.


Setup and Usage
Install dependencies:

bash
pip install streamlit <your-ai-sdk>
Configure your API key as an environment variable:

bash
setx YOUR_API_KEY_NAME "YOUR_SECRET_KEY"
Run the application:

bash
streamlit run chatbot_app.py
After starting the app, open the provided local URL in your browser to interact with the chatbot
