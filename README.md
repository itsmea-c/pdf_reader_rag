# pdf_reader_rag
RAG project - pdf reader
This project is a Retrieval-Augmented Generation (RAG) application that allows users to ask questions about a PDF document and receive relevant answers using a locally running Large Language Model (LLM).

The system extracts text from a PDF, splits it into chunks, converts the chunks into embeddings, and stores them in ChromaDB. When a user asks a question, the system retrieves relevant information and passes it to the LLM to generate an answer.
