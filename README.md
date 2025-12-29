Cohere RAG Chatbot (Multilingual/1024 Dim)

This project is a Multilingual Retrieval-Augmented Generation (RAG) Chatbot built with Cohere for embedding and Gemini for generation, designed to provide intelligent responses in various languages, including Persian.

-Features:

Multilingual Support: Utilizes Cohere's multilingual embedding models for a more robust, language-agnostic experience.

RAG Architecture: Combines embedding, retrieval, and reranking with Gemini's language model to generate contextual responses based on relevant documentation.

Dynamic Knowledge Base: The chatbot retrieves context from a Supabase database and ranks the most relevant chunks using Cohere's reranking model.

-Technologies Used:

Cohere: Used for generating embeddings and reranking documents to improve the accuracy of responses. This makes the chatbot capable of working with vast, multilingual data sources.

Embedding Model: embed-multilingual-v3.0 (1024 dimensions)

Rerank Model: rerank-multilingual-v3.0

Gemini (Google): For generation of natural, context-aware responses.

Supabase: Used as a database to store and retrieve site pages' embeddings.

Streamlit: Front-end interface for the chatbot, allowing interaction with the user.
