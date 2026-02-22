System Architecture

Overview
The Restaurant FAQ Bot follows a simple modular architecture:

User Interface (Frontend)
Query Processing Layer
Retrieval Engine (Vector Search)
Language Model (LLM)
Knowledge Base
Response Generator
Architecture Flow

User submits a question.
The query is converted into embeddings.
Relevant documents are retrieved from the knowledge base.
Retrieved context is passed to the language model.
The model generates a contextual response.
The response is displayed to the user.
Technologies Used

Frontend: React / HTML / CSS
Backend: Node.js / Express (if applicable)
AI Model: OpenAI API / Local LLM
Vector Database: FAISS / Chroma / Pinecone
Embeddings: OpenAI Embeddings / HuggingFace
Design Principles

Modular structure
Scalable architecture
Fast response time
Secure API integration
Easy knowledge base updates
