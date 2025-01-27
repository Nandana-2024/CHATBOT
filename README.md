# CHATBOT using RAG framework

RAG App is an open-source chatbot application that leverages Retrieval-Augmented Generation (RAG) to combine a powerful retrieval system with generative AI. This app is entirely open source, relying on frameworks like LangChain, Haystack, and other open libraries to provide a robust and scalable solution.

**Features**

_Open-Source Components:_ Uses open-source frameworks like LangChain and Haystack, eliminating the need for proprietary APIs.

_Retrieval-Augmented Generation:_ Efficiently retrieves and integrates relevant data for highly accurate responses.

_Customizable Knowledge Base:_ Easily extend and manage your own domain-specific documents and data.

_Dynamic Context Understanding:_ Responds to user queries with real-time contextual relevance.

_Lightweight Frontend:_ Simple and user-friendly interface built with HTML and CSS.

**Technologies Used**

_Backend:_ Python (FastAPI or Flask)

_Retrieval Frameworks:_ LangChain, Haystack

_Vector Databases:_ FAISS, Weaviate, or Milvus

_Frontend:_ HTML, CSS

_Document Parsing:_ PyPDF2, BeautifulSoup for text extraction and processing

**How It Works**

_Document Indexing:_ Use Haystack or LangChain to preprocess and index your knowledge base.

_Retrieve:_ Query the indexed knowledge base for the most relevant documents.

_Generate:_ Use an open-source language model (e.g., Hugging Face Transformers) to generate accurate and natural responses.

_Respond:_ Display responses in a clean and lightweight frontend.
