 DevPilot 🚀

DevPilot is a full-stack, AI-powered GitHub repository analyzer. It leverages advanced vector search and large language models to ingest, process, and analyze GitHub repositories, providing developers with an intelligent chat interface to ask questions, explore codebases, and retrieve insights with real-time streaming support.

✨ Key Features

* **AI-Powered Code Analysis:** Connects with the OpenAI API to understand and explain complex repository structures and code logic.
* **Interactive Chat with Streaming:** Fluid, real-time chat interface featuring session management and streaming support for seamless interaction.
* **Vector Search Database:** Utilizes PostgreSQL with `pgvector` for efficient semantic search and retrieval of code embeddings.
* **Modern Client Interface:** A highly responsive frontend built with Next.js and Tailwind CSS.
* **Robust Backend Operations:** Powered by Spring Boot and Spring AI to handle complex processing and AI integrations securely.
* **Containerized Infrastructure:** Pre-configured Docker environments for zero-headache database and dependency management.

🛠️ Tech Stack

**Frontend:** Next.js, Tailwind CSS
**Backend:** Spring Boot, Spring AI
**AI/LLM:** OpenAI API
**Database:** PostgreSQL with pgvector extension
**DevOps/Deployment:** Docker, Docker Compose

 📁 Project Structure

```text
DevPilot/
├── client/                 # Next.js frontend application
├── backend/                # Backend API and AI processing logic
├── docker/postgres/        # Docker configurations for PostgreSQL & pgvector
├── .vscode/                # Editor configurations
└── docker-compose.yml      # Multi-container orchestration
