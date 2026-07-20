# AI Knowledge Base RAG using n8n

This project is my first Retrieval-Augmented Generation (RAG) workflow built with n8n.

The workflow allows an AI agent to retrieve relevant information from a Pinecone vector database using Gemini embeddings before generating responses.

## Features

- AI Agent powered by Google Gemini
- Pinecone Vector Database integration
- Retrieval-Augmented Generation (RAG)
- Semantic document search
- n8n workflow automation
- Modular and easy to extend

## Tech Stack

- n8n
- Google Gemini
- Pinecone
- Vector Embeddings
- Git & GitHub

## Challenges Faced

During development I encountered and solved several real-world issues:

- Vector dimension mismatch (512 vs 3072)
- Pinecone index recreation
- Namespace configuration
- Gemini API quota limits (429 errors)
- Embedding model compatibility
- Git author configuration
- GitHub contributor attribution

Each issue helped me better understand how production AI workflows are built and debugged.

## Project Structure

```
AI-Knowledge-Base-RAG
│
├── knowledge-base-workflow.json
├── workflow-overview.png
├── successful-execution-log.png
├── pinecone-index-config.png
├── chat-demo.png
├── README.md
├── LICENSE
└── .gitignore
```

## Screenshots

### Workflow Overview

See `workflow-overview.png`

### Successful Execution

See `successful-execution-log.png`

### Pinecone Configuration

See `pinecone-index-config.png`

### Chat Demo

See `chat-demo.png`

## Future Improvements

- Voice AI integration
- Live deployment
- WhatsApp integration
- Multi-document knowledge base
- Better prompt engineering
- Production monitoring

## Author

**Ubaid Raheem**

GitHub:
https://github.com/Ubaidraheem