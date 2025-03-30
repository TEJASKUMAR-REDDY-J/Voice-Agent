# Voice Agent: Conversational AI for PDFs  

This AI-powered voice agent allows users to interact with PDF documents through speech, eliminating the need for typing. Built as a final project for the Agentic Systems 101 course.

## Features  

- **Voice Interaction**  
  - Speak instead of typing to query PDFs.  
  - Uses **Assembly AI** for speech-to-text (STT) and text-to-speech (TTS).  

- **AI-Powered Responses**  
  - Employs **GROQ LLM** to generate contextual answers based on PDF content.  

- **Efficient Document Processing**  
  - Extracts text and processes PDFs for meaningful responses.  
  - Uses **Sentence Transformers** for embedding creation.  

- **Vector Search for Fast Retrieval**  
  - Stores document embeddings in **ChromaDB** for efficient querying.  

## Technologies Used  

- **Assembly AI** (STT & TTS)  
- **GROQ LLM**  
- **ChromaDB** (Vector Database)  
- **Sentence Transformers** (Embedding Generation)  
- **Python & Jupyter Notebook** for development  

## Installation & Usage  

1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/voice_agent.git
   cd voice_agent
