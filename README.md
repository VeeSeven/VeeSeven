# Hey, I'm Vaibhav Hingorani | Full-Stack & AI Systems

I focus on building deterministic systems in a non-deterministic world. I lean toward backend complexity and simple, effective frontend delivery.

---

## 🗂️ Core Projects

### 🛠️ MindSpace: Your Infinite Digital Workspace
  
*Enables complex notes hierarchies (folders in folders / notes in notes) with an intuitive tagging system that auto‑assigns consistent colors for visual organization.*

**Tech Stack**  
React + Vite | Django REST Framework | PostgreSQL | JWT Authentication | Docker

**Engineering Highlights**  
- Fully containerized with Docker Compose for one‑command local development.  
- Implements recursive note relationships and efficient tag filtering via Django ORM.  
- Rich text editor (TipTap) with auto‑save, word count, and formatting toolbar.  
- JWT authentication with token rotation and blacklisting for enhanced security.  
- Responsive UI built with Chakra UI and state management using React hooks.

https://github.com/VeeSeven/MindSpace

### 🤖 RapidSummarize: RAG-Augmented PDF Intelligence System

*A fully local RAG system that lets you upload PDFs and ask questions – no cloud, no data leaks, just answers.*

**Tech Stack**  
React + Vite | FastAPI | Ollama (Llama 3.2 + nomic‑embed‑text) | ChromaDB | Tesseract OCR | Docker

**Engineering Highlights**  
- Fully containerized with Docker Compose – spin up the entire stack in one command.  
- Intelligent chunking with automatic OCR fallback for scanned pages ensures no text is left behind.  
- Streaming responses with contextual memory stitch multi‑turn conversations together in real time.  
- Vector search (ChromaDB) and local LLMs (Ollama) keep all data on your machine – privacy by design.  
- Optimised for large PDFs through adjustable chunk sizes and background task processing.

https://github.com/VeeSeven/RapidSummarize

---

## 🏗️ Technical Blueprint

```python
class Developer:
    def __init__(self):
        self.languages = ["Python", "JavaScript", "Java", "SQL"]
        self.backend   = ["FastAPI", "Django", "Flask", "REST APIs"]
        self.frontend  = ["React", "Tailwind", "ChakraUI"]
        self.infra     = ["Docker", "PostgreSQL", "ChromaDB"]
