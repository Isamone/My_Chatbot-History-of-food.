Food History Chatbot
A simple NLP-powered chatbot that answers questions about the history of food by analyzing content from a text file using NLTK and Streamlit.

🚀 Features
Interactive chatbot interface with Streamlit

Natural language processing using NLTK

Preprocessing steps: tokenization, stopword removal, lemmatization

Finds the most relevant answer using Jaccard similarity

Answers sourced from a local file: History of food.txt

📦 Technologies Used
Python

NLTK – for natural language processing

Streamlit – for building the web app

📁 File Structure
app.py – main application code

History of food.txt – source text used by the chatbot

⚙️ How It Works
Loads and preprocesses the food history text.

Accepts user queries via text input.

Computes similarity between the query and preprocessed sentences.

Returns the most relevant sentence as the chatbot's answer.
