# Python + Vite Build

BuildNinja configuration for Open WebUI's frontend.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/open-webui/open-webui |
| **Branch** | main |
| **Stack** | Python (FastAPI) + SvelteKit (Vite) |
| **License** | MIT |

## About Open WebUI

Open WebUI is an extensible, feature-rich, and user-friendly self-hosted AI platform designed to operate entirely offline. It supports various LLM runners like Ollama and OpenAI-compatible APIs.

**Key Features:**
- Effortless setup with Docker or Kubernetes
- Ollama/OpenAI API integration
- Local RAG integration with 9 vector database options
- Native Python function calling
- Multilingual support (i18n)
- Pipelines plugin framework

**Tech Stack:**
- Backend: Python FastAPI
- Frontend: SvelteKit with Vite
- Database: SQLite/PostgreSQL

## What This Demonstrates

- Hybrid Python + JavaScript projects
- Vite-based frontend builds
- Force install (`npm install -f`) for complex dependencies
- Building popular AI/ML projects

## Agent Requirements

- Node.js 18+
- npm

## Build Steps

| Step | Command | Description |
|------|---------|-------------|
| 1 | `npm install -f` | Install dependencies (force) |
| 2 | `npm run build` | Build the frontend |

## Artifacts

- `src/` - Source files
