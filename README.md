
# ChatWithYourData_Bot

## Introduction
This repository contains code for ChatWithYourData_Bot, an AI-powered conversational agent that interacts with data through a question-and-answer mechanism.
Users can upload a pdf file and then ask any question based on the file uploaded to get answers and a deeper understanding of the document.
It utilizes pre-trained models, language models, document embeddings, and vector search to retrieve relevant information from provided documents.

## Installation

### Libraries
Ensure you have the necessary Python libraries installed. Use the following commands:

```bash
pip install hnswlib --no-cache-dir
pip install openai
pip install python-dotenv
pip install langchain
pip install pypdf
pip install tiktoken
pip install chromadb
pip install --upgrade pydantic
```

## Setup and Usage
## Configuration
Set up the OpenAI API key by assigning the value to the environment variable OPENAI_API_KEY.

Load the necessary Python libraries and dependencies.

## Execution

Load Documents:
Load PDF documents using PyPDFLoader and split them into text chunks.

Vectorize Text:
Utilize document embeddings and create a vector database using Chroma and OpenAIEmbeddings.

Query and Retrieve Information: Retrieve information by asking questions. Examples are provided for various types of queries using the established vector database.
Chatting:

Engage in a conversation with the AI-powered model, querying information based on the loaded documents.
Dashboard Interface (Optional):

Run the provided code to set up a dashboard for an interactive interface. Follow the provided instructions within the code for loading documents and interacting with the bot.

## Deployment

To view how this application works. Click the link below

```bash
  npm run deploy
```


## Feedback

If you have any feedback, please reach out to us.



## Authors


- [@Shinells](https://www.github.com/octokatherine)


- [@hilaryookrah](https://www.github.com/octokatherine)

