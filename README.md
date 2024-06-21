# C2C-ClickToCareer-Chatbot

<img src="webapp/demo3.png" alt="workflow" width="70%">

The C2C-ClickToCareer is an AI-powered chatbot assistant designed to help users in career-related queries by fetching and processing data from a website. This uses HuggingFace for creating embeddings and Pinecone for managing a vector database. The application is built using Streamlit for an interactive user interface.

## Features
- Efficiently fetches data from website sitemaps using asynchronous loading.
- Splits large documents into manageable chunks for better processing and searchability.
- Implements HuggingFace's SentenceTransformer for high-quality text embeddings.
- Leverages Pinecone to store and retrieve vector representations of documents, ensuring fast and accurate search results.
- Streamlit integration allows for easy interaction and real-time response display.

## Installation

Clone the repository:
```
git clone https://github.com/saleena-18/C2C-ClickToCareer-Chatbot.git
```
## Install dependencies:
```
pip install -r requirements.txt
```
## Run the Streamlit application:
```
streamlit run app.py
```

## Enter API Keys:

Input your HuggingFace API key.
Input your Pinecone API key.

## Load Data

Click the "Load data to Pinecone" button to fetch and store data from the website.

## Interact with the Chatbot:

Enter your query in the input box to receive relevant information from the vector database.
