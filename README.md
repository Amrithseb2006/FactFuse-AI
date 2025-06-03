## FactFuse: AI-Powered News Research Tool


“Fuse facts. Find truth.”

FactFuse is an intelligent assistant that helps you research and reason over multiple news articles. By combining web scraping, text processing, vector embeddings, and OpenAI’s language model, FactFuse lets you input URLs, ask natural language questions, and get clear, cited answers — all in one place.


## 🚀 Features


        🔗 Accepts up to 3 news article URLs
        
        📝 Extracts and processes article text using UnstructuredURLLoader
        
        🧩 Splits content into chunks with RecursiveCharacterTextSplitter
        
        📐 Generates vector embeddings using OpenAI
        
        📦 Stores and retrieves information using FAISS
        
        🤖 Uses RetrievalQAWithSourcesChain for question answering with sources
        
        💾 Persists vector index across sessions



## 🛠️ How to Set Up

        🚀 Clone the repository and navigate into the project directory.
        
        🔐 Create a .env file in the root folder and add your OpenAI API key:
            OPENAI_API_KEY=your_openai_api_key_here
        
        📥 Install the dependencies:
            pip install -r requirements.txt
        
        ▶️ Run the application:
            streamlit run app.py
        
        🌐 Open the Streamlit URL shown in your terminal to access the app.




##📂 Project Structure

            FactFuse/
        ├── app.py                  # Main Streamlit application
        
        ├── .env                    # Environment variables (API key)
        
        ├── requirements.txt        # Python dependencies
        
        ├── faiss_store_openai/     # Local FAISS vector storage
        
        └── README.md               # Project documentation




##💡 How It Works


        🔍 You enter up to 3 news article URLs
        
        📰 FactFuse loads and extracts the textual content from the pages
        
        ✂️ The content is split into manageable chunks for embedding
        
        🤖 OpenAI embeddings are generated and stored in a FAISS vector index
        
        🔎 When you ask a question, relevant text chunks are retrieved semantically
        
        💬 OpenAI's language model answers the question using the retrieved chunks
        
        📢 The answer and the source URLs are displayed on the screen



##🔍 Example Use Cases


        📝 “Summarize the economic impact discussed in these articles.”
        
        🏛️ “Which article mentions government regulation on AI?”
        
        🌍 “What’s the shared stance on the climate policy?”


##🔮 Future Improvements


        ✅ Accept more than 3 URLs
        
        ✅ Handle broken URLs or unsupported pages gracefully
        
        ✅ Support PDFs, YouTube transcripts, or local file uploads
        
        ✅ Add summarization and article comparison features
        
        ✅ Add user authentication and history tracking
        
        ✅ Enable switching between OpenAI and open-source LLMs


##📜 License

        This project is licensed under the MIT License.


##🙌 Acknowledgements


        🧩 LangChain
        
        📦 FAISS
        
        ⚡ Streamlit
        
        🤖 OpenAI


## 👤 Author

Built with ❤️ by A Amrith Sebastin  
Amrithseb2006 | amrithsebastin20@gmail.com
