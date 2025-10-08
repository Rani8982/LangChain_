# LangChain
Langchain based project with HuggingFace
# LangChain PDF & Excel Reader using Hugging Face

An intelligent document reader that processes **PDF** and **Excel** files to extract, understand, and answer questions from your data using **LangChain**, **Hugging Face**,**Vectorstore** and **ChromaDB**.  
This project turns your unstructured documents into **searchable, AI-understandable knowledge** — enabling instant insights from business reports, financial data, and text-heavy documents.

## Features

- Read and analyze **PDF** and **Excel** files effortlessly  
- Automatically **split and structure large texts** into semantic chunks  
- Generate **Hugging Face sentence embeddings** for contextual understanding  
- Store and query document embeddings using **ChromaDB**  
- Works **locally** — local machine required  

**Pipeline Flow:**
1. Upload → PDF/Excel Loader  
2. Chunk Text → Recursive Text Splitter  
3. Embed → Hugging Face Sentence Embeddings  
4. Store → Chroma Vector DB  
5. Query → Retrieval + LLM Response
