# campusmind-ai

               +-------------------------+
               | University Documents    |
               | (PDF, TXT)              |
               +------------+------------+
                            |
                            v
                 Document Ingestion
                            |
                            v
                  Text Preprocessing
                            |
                            v
                    Text Chunking
                            |
                            v
             Sentence Embeddings
                            |
                            v
                  FAISS Vector Store
                            |
       +--------------------+-------------------+
       |                                        |
       | User Question                          |
       |                                        |
       +--------------------+-------------------+
                            |
                            v
                  Semantic Retrieval
                            |
                            v
                Retrieved Context
                            |
                            v
               Local LLM (Gemma/Qwen via Ollama)
                            |
                            v
                 Grounded Answer + Sources
                            |
                            v
                    Streamlit Interface
