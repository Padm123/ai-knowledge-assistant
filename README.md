# 🧠 AI Knowledge Assistant (RAG-based Document Q&A)

An intelligent assistant that lets users upload documents and ask questions, powered by **Java Spring Boot**, **React**, and **Retrieval-Augmented Generation (RAG)** using OpenAI embeddings.

This project demonstrates full-stack development, authentication, secure API design, and an AI-enhanced knowledge workflow.

---

## ✨ Features

| Feature | Status | Description |
|--------|:------:|-------------|
| User Registration & Login (JWT Auth) | ✅ | Secure authentication using Spring Security + JWT |
| Document Upload | ✅ | Upload `.txt` / `.md` / `.pdf` files |
| Text Chunking + Embedding | ✅ | Splits content & generates embeddings for RAG |
| Chat / Ask Questions | ⚙️ In Progress | Uses semantic similarity to answer based on documents |
| Vector Search | ⚙️ In Progress | Improving ranking & response quality |

---

## 🏗️ Architecture
React (Vite) UI
↓
JWT Auth in localStorage
↓
Spring Boot Backend (REST)
↓
Document Storage + JPA
↓
OpenAI Embeddings (RAG)


---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot 3
- Spring Security + JWT
- Spring Data JPA
- H2/PostgreSQL (local dev vs prod)
- OpenAI Embeddings API

### Frontend
- React (Vite)
- TypeScript
- TailwindCSS
- JWT stored client-side

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USER/ai-knowledge-assistant.git

