# bhagavad-gita-rag-search

A **Retrieval-Augmented Generation (RAG)**-based search application for the **Bhagavad Gita** that retrieves and generates contextually relevant answers using verse embeddings. Built with **Sentence Transformers** for embedding generation and a vector database (**FAISS/Pinecone**) for efficient verse retrieval. Open-source and easy to use.

## Project Overview
This project answers user queries by providing contextually relevant verses from the **Bhagavad Gita**. Using advanced **Natural Language Processing (NLP)** techniques, it extracts meaningful insights from the sacred text, making it easier to access the wisdom of the Bhagavad Gita.

## Key Features
- **Verse Retrieval**: Efficiently retrieve relevant verses based on user input.
- **Generative Responses**: Generate context-aware answers by combining verse retrieval with a generative model.
- **Embedding-Based Search**: Uses **Sentence Transformers** to create embeddings and stores them in a vector database for fast retrieval.
- **Open-Source**: Freely available for anyone interested in exploring the Bhagavad Gita or building similar RAG-based search applications.

## Technologies Used
- **Python**
- **Sentence Transformers** for generating embeddings
- **FAISS / Pinecone / Elasticsearch** for vector database storage
- **Hugging Face Transformers** for generative models
- **Flask / FastAPI** for the web interface (optional)



## Installation and Usage

### 1. Clone the repository
Clone the repository to your local machine using the following command:
```bash
git clone https://github.com/<your-username>/bhagavad-gita-rag-search.git
```

### 2. Install the dependencies
Navigate into the project directory and install the required dependencies using **pip**:
```bash
cd bhagavad-gita-rag-search
pip install -r requirements.txt
```

### 3. Preprocess the Bhagavad Gita verses
Follow the scripts provided in the repository to preprocess the Bhagavad Gita verses and generate embeddings. You may need to run a preprocessing script to convert the verses into a suitable format for the vector database.

### 4. Set up a vector database
Choose one of the following vector database options and set it up for efficient verse retrieval:
- **FAISS**: [FAISS installation guide](https://github.com/facebookresearch/faiss)
- **Pinecone**: [Pinecone setup guide](https://www.pinecone.io/docs/)
- **Elasticsearch**: [Elasticsearch documentation](https://www.elastic.co/guide/en/elasticsearch/reference/index.html)

### 5. Run the application
Once everything is set up, you can run the application to start querying the Bhagavad Gita and receive contextually relevant answers:
```bash
python app.py
```

This will start the web application where you can input your queries and get answers based on the Bhagavad Gita.
```

This Markdown provides a clear, step-by-step guide for installation and usage, using proper code blocks for commands. It also links to external resources for setting up the vector database options.

Let me know if you'd like further adjustments!
