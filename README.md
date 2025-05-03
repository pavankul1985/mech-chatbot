# Hinglish Mech Chatbot

A Flask-based chatbot that processes `.docx` files (e.g., mechanical engineering notes) and answers questions in a funny Hinglish tone, starting with "Comps ka banda Mech bol raha hun". It extracts text from tables, finds YouTube links, suggests Indian products, and offers web search for unanswerable queries.

## Features
- Upload `.docx` files and ask questions about their content.
- Funny Hinglish responses with Indian product examples (e.g., Tata Nexon EV).
- Extracts YouTube links from the document for reference.
- Handles unanswerable queries (e.g., images, equations) by suggesting notes or web search.
- Feedback box after each answer.
- Reads text from tables in `.docx` files.

## Setup Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mech-chatbot.git