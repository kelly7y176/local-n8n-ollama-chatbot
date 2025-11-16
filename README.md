# 🤖 Local AI Chatbot with n8n and Ollama

This project deploys a fully local, self-hosted AI chatbot with conversation memory, using Docker, n8n (for the visual workflow), and Ollama (for the local AI model).

The chatbot runs entirely on your machine, ensuring privacy and zero cloud costs.

<!-- Cover -->
<br />
<div>
   <img align="left" align="left" alt="HTML" width="100%" style="padding-right:10px;" src="https://i.imgur.com/Y8GmtsY.jpeg" />   
</div>

## ⚙️ Setup and Prerequisites

- **Docker Desktop** must be installed and running.
- **Ollama** must be installed and running on your host machine (macOS/Windows/Linux).
- **Minimum Requirements:** 8GB RAM (16GB recommended).
- 

## 🚀 Quick Start

### 1. Install the Model

We use the lightweight and fast Phi-3 model to ensure quick response times on consumer hardware:

```bash
ollama pull phi3:3.8b
