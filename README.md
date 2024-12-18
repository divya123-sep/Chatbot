# BERT Chatbot 🤖

Welcome to the BERT Chatbot project! This project uses the BERT (Bidirectional Encoder Representations from Transformers) model to create a simple, interactive chatbot that can answer predefined questions in a conversational style. The chatbot is powered by **Hugging Face's Transformers** library and built with **Streamlit** for a user-friendly interface.

## Features ✨
- **BERT-powered responses**: The chatbot uses the BERT model to understand and generate responses based on user input.
- **Predefined Question & Answer Set**: The bot can respond to a set of predefined questions like "What is your name?" or "Tell me a joke."
- **Cosine Similarity**: The chatbot compares the user input with predefined questions to find the most relevant response.
- **Customizable Responses**: You can easily update or add new questions and responses to the chatbot.

## Demo 🎥
Try out the chatbot live by visiting [Local URL: http://localhost:8501]

## Requirements 📋

To run the project locally, you need the following libraries:

- `streamlit` – for the frontend UI
- `transformers` – for BERT model and tokenizer
- `torch` – for running the BERT model
- `scikit-learn` – for cosine similarity computation

### Install Dependencies

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bert-chatbot.git
   cd bert-chatbot
