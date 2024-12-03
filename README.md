Customer Service App with LangChain and Streamlit
This project is a customer service application built with Streamlit and LangChain. It integrates various tools to handle real-time queries, manage business info, interact with a database, and provide presentation slides. It also allows customer service agents to chat with users and maintain context throughout the conversation.

Features
Chat with AI Assistant: The assistant interacts with customers, collecting information like name and email, and uses LangChain to process real-time queries.
Database Interaction: The app allows uploading and editing a SQLite database. The database can be reset, and tables are displayed for easy editing.
Business Information: The app displays and allows the modification of business-related information stored in a text file.
Presentation: The app can display images for presentations, with navigation buttons to go through them.
Email Interaction: The app integrates an email tool to send messages to users.
Technologies Used
LangChain: A framework to integrate with LLMs (Large Language Models) to automate interactions.
Streamlit: For building the user interface and displaying information.
SQLite: Used for storing and managing clinic-related data.
OpenAI: For running the AI models (via the ChatGPT API).
SerpAPI: For integrating search functionality.
PIL (Python Imaging Library): For displaying images in the presentation section.
Dotenv: For managing environment variables securely.
