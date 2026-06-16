# RAG chatbot powered by 🔗 Langchain, OpenAI, Google Generative AI and Hugging Face 🤗

<div align="center">
  <img src="https://github.com/AlaGrine/RAG_chatabot_with_Langchain/blob/main/data/docs/RAG_architecture.png" >
  <figcaption>RAG architecture with Langchain components.</figcaption>
</div>

## Project Overview <a name="overview"></a>

This project is a Retrieval-Augmented Generation (RAG) chatbot developed using LangChain, Hugging Face, and Large Language Models (LLMs). The chatbot allows users to upload documents and ask questions in natural language. Relevant information is retrieved from the uploaded documents and provided to the LLM to generate accurate, context-aware responses.

## Features <a name="Features"></a>

- Document-based Question Answering
- Retrieval-Augmented Generation (RAG)
- Semantic Search using Vector Database
- Support for PDF and Text Documents
- Interactive User Interface with Streamlit
- Context-Aware Responses using LLMs

## Technologies Used <a name="Technologies Used"></a>

- Python
- LangChain
- Hugging Face Transformers
- ChromaDB / FAISS
- Streamlit
- OpenAI API 

## Instructions <a name="instructions"></a>

To run the app locally:

1. Create a virtual environment: `python -m venv langchain_env`
2. Activate the virtual environment : `.\langchainenv\Scripts\activate` on Windows.
3. Run the following command in the directory: `cd RAG_Chatabot_Langchain`
4. Install the required dependencies `pip install -r requirements.txt`
5. Start the app: `streamlit run RAG_app.py`
6. In the sidebar, select the LLM provider (OpenAI, Google Generative AI or HuggingFace), choose an LLM (GPT-3.5, GPT-4, Gemini-pro or Mistral-7B-Instruct-v0.2), adjust its parameters, and insert your API keys.
7. Create or load a Chroma vectorstore.
8. Chat with your documents: ask questions and get 🤖 AI answers.

## Skills Demonstrated <a name="Skills Demonstrated"></a>

- Generative AI
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Prompt Engineering
- Vector Databases
- NLP and Semantic Search
- AI Application Development


## Future Improvements <a name="Future_Improvements"></a>

- Multi-document support
- Chat history memory
- Hybrid search retrieval
- Cloud deployment
- Support for additional LLM providers
