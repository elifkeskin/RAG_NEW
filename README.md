📚 **RAG-Based Chatbot with Gemini + LangChain**

This project demonstrates how to build a Retrieval Augmented Generation (RAG) chatbot using the Google Gemini API and the LangChain framework. The chatbot leverages document retrieval to provide accurate, context-aware, and natural conversational experiences.

   <img width="477" alt="Basic_RAG Application with Gemini" src="https://github.com/user-attachments/assets/1bfebe83-1da1-437a-a5db-32b67e03aefd" />


🚀 **Features**
- **Google Gemini LLM API Integration:** Harnesses the power of Gemini for advanced language understanding and generation.
- **Document Vectorization & Search with ChromaDB:** Efficiently indexes and retrieves relevant documents using vector embeddings.
- **Intelligent Document Querying via LangChain:** Utilizes LangChain’s RAG pipeline for smart, context-driven responses.
- **Interactive Web Interface with Streamlit:** User-friendly, real-time chat experience in your browser.
- **Fast & Scalable:** Designed for responsive, real-time interactions.

🛠️ **Installation**
Follow these steps to set up and run the project:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/elifkeskin/RAG_NEW.git
    cd RAG_NEW
    ```

2. **Install Required Packages**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up Environment Variables**
    - Create a `.env` file in the project root directory.
    - Add your Gemini API key:
      ```
      GEMINI_API_KEY="your_gemini_api_key"
      ```

4. **Run the Streamlit App**
    ```bash
    streamlit run app.py
    ```

📄 **Project Structure**


├── app.py # Streamlit web interface
├── .env # Environment variables (API keys, etc.)
├── GEMINI_RAG.ipynb # Jupyter notebook for RAG chain setup and experimentation
├── requirements.txt # Python dependencies
└── README.md # Project documentation



📚 **Technologies Used**

- **Google Gemini API** – Large Language Model for text generation
- **LangChain** – Framework for building RAG pipelines and LLM applications
- **ChromaDB** – Local vector database for document storage and retrieval
- **Streamlit** – Rapid web app development for interactive chat

🎯 **Purpose**

* This project aims to demonstrate the practical use of the RAG architecture for querying documents more efficiently and providing more accurate responses to user queries.

🛠️ **Common Errors and Solutions**

**Error	Solution**
* **RuntimeError:**  chromadb cannot start	Ensure all required system dependencies are installed. Try reinstalling with pip install chromadb.
* **ModuleNotFoundError:** langchain_chroma not found	Install the module using pip install langchain-chroma.
* **API key error:** 	Make sure you have correctly set your API key in the .env file.
* **Streamlit not running:**	Verify Streamlit is installed (pip install streamlit) and check for port conflicts.

❓ **FAQ - Frequently Asked Questions**

**Is Gemini API free?**
* Google Gemini API has a free usage quota; charges may apply after exceeding the limit. Check Google Cloud Pricing for details.

**Where is the data stored?**
* Documents are stored locally using ChromaDB in a folder (typically under db/).

**Can I use other models?**
* Yes! You can easily adapt the project to work with other models supported by LangChain (e.g., OpenAI, HuggingFace).

✨ Happy Coding! ✨
