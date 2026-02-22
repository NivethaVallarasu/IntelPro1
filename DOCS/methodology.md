Methodology

Data Collection
A structured FAQ dataset was created containing restaurant-related questions and answers including menu details, policies, timings, and reservation information.

Data Preprocessing
Text cleaning
Lowercasing
Removal of unnecessary characters
Formatting into structured JSON format
Embedding Generation
Questions and documents converted into vector embeddings.
Stored in a vector database for semantic search.
Retrieval Process
User query converted into embedding.
Similar documents retrieved using cosine similarity.
Response Generation
Retrieved context passed to LLM.
LLM generates natural and relevant answer.
6. Testing & Evaluation
Tested with common restaurant-related queries.
Evaluated based on response accuracy and relevance.
