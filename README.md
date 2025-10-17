# AI‑Enabled Knowledge Assistant

RAG service that ingests PDFs and answers domain questions; pluggable vector stores.

## Tech Stack
Java, Spring Boot, LangChain4j, FAISS/Pinecone/MongoDB Atlas, OpenAI, Docker

## Screenshots / Demos
_Add images or links here (e.g., Vercel/Render demo)._

## Quick Start
```bash
# 1) Initialize repo locally
git init
git add .
git commit -m "chore: initial scaffolding"
# 2) Create GitHub repo with the same name as this folder
# 3) Set remote and push
git branch -M main
git remote add origin https://github.com/<your-username>/ai-knowledge-assistant.git
git push -u origin main
```

## Roadmap
- [ ] Add minimal backend endpoint (Spring Boot) and healthcheck
- [ ] Add minimal React UI scaffold (Vite) with API call
- [ ] Write README usage with sample requests/responses
- [ ] Add CI (GitHub Actions) for build + tests
- [ ] Add Dockerfile & docker-compose (app + db + message broker)
- [ ] Deploy demo (Render/Vercel/Railway/AWS) and link above

## License
MIT © Padma Yamapuram
