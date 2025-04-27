📚 **RAG-Based Chatbot with Gemini + LangChain**

* This project aims to build a Retrieval Augmented Generation (RAG)-based chatbot using the Gemini API and LangChain library.
* Throughout the project, documents are used to retrieve information and deliver a natural conversation experience.

🚀 **Features**
🌟 Google Gemini LLM API integration

📚 Document vectorization and search with ChromaDB

🧠 Smart document querying with LangChain

🖥️ Web interface built with Streamlit

⚡ Fast and real-time chat experience

🛠️ **Installation**
Follow the steps below to run the project:

**Clone the repository:**
git clone https://github.com/elifkeskin/RAG_NEW.git

cd RAG_NEW

**Install the required packages:**
pip install -r requirements.txt

**Set up environment variables:**
Create a .env file and add your API keys:

GEMINI_API_KEY="your_gemini_api_key"

**Run the Streamlit app:**
streamlit run app.py

📄 **Project Structure**


├── app.py               # Streamlit interface

├── .env                 # Set up environment variables

├── GEMINI_RAG.ipynb     # RAG chain setup

├── requirements.txt     # Required Python packages

└── README.md            # This file



📚 **Technologies Used**

* Google Gemini API

* LangChain

* ChromaDB

* Streamlit

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
