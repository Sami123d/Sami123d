# Sami Ahmed

Full-stack developer in Karachi, Pakistan. I build web apps (React, Next.js, Angular), Node/NestJS/Express APIs, and LLM-powered apps and automations (Gemini, LangGraph, n8n).
Computer Science graduate, SMIU Karachi.

📫 [samiahmedtech@gmail.com](mailto:samiahmedtech@gmail.com) · [LinkedIn](https://www.linkedin.com/in/sami-ahmed-420931215/)

---

## What the repositories show

Every line below links to code you can read. Each README states the project's real status, including what is unfinished.

| Area | Evidence |
|------|----------|
| **AI agents & LLM apps** | [linkedin-ai-studio](https://github.com/Sami123d/linkedin-ai-studio) (multi-step Gemini/Ollama agent pipeline, pgvector RAG) · [dialogflow-chatbot](https://github.com/Sami123d/dialogflow-chatbot) · [job-app-agent-extended](https://github.com/Sami123d/job-app-agent-extended) · [nexus-support-extended](https://github.com/Sami123d/nexus-support-extended) |
| **Full-stack web** | [Currency-App](https://github.com/Sami123d/Currency-App) (Angular) · [Blog-Management](https://github.com/Sami123d/Blog-Management) (React) |
| **Backend / APIs** | [Currency-Backend-Api](https://github.com/Sami123d/Currency-Backend-Api) (NestJS) · [Blog-Management-API](https://github.com/Sami123d/Blog-Management-API) (Express + MongoDB, JWT) |
| **Automation & scraping** | [linkedin-ai-studio](https://github.com/Sami123d/linkedin-ai-studio) (3 n8n workflows: trend collection, publishing, analytics) · [NexaScraper](https://github.com/Sami123d/NexaScraper) (my contributions to a fork: OpenStreetMap source, Playwright scraper fix) |
| **Testing & CI** | Tested repos run GitHub Actions: Vitest, Jest + Supertest with in-memory MongoDB, Nest e2e tests, pytest |

---

## Featured projects

### [LinkedIn AI Studio](https://github.com/Sami123d/linkedin-ai-studio)
**Next.js 16 · Prisma 7 · Supabase (Postgres + pgvector) · n8n · Gemini / Ollama**
n8n collects trends from 10 sources. Agents then research, plan, write and review a LinkedIn post, drawing on a personal knowledge base searched with pgvector. The user approves and schedules the post, n8n publishes it, and a daily job pulls back likes and comments. Every AI step keeps an audit log. 21 Vitest tests; CI on GitHub Actions.
*Status:* implemented in code. LinkedIn publishing has not yet been tested against a real LinkedIn developer app, and the [live site](https://linkedin-ai-studio-alpha.vercel.app) shows only the public landing and login pages.

### [Currency Converter](https://github.com/Sami123d/Currency-App) + [API](https://github.com/Sami123d/Currency-Backend-Api)
**Angular 21 + Material · NestJS 11 · Vercel**
Converts between currencies at latest or historical rates, and keeps conversion history in the browser. The NestJS backend keeps the exchange-rate API key on the server, validates input and returns proper 400/502 errors. Tests on both sides (Vitest specs; Nest unit + e2e tests with the provider mocked). [Live demo](https://currency-app-psi-self.vercel.app).

### [Samilog — Blog platform](https://github.com/Sami123d/Blog-Management) + [API](https://github.com/Sami123d/Blog-Management-API)
**React 19 + Vite · Express 5 · MongoDB · JWT · ImageKit**
JWT access and refresh tokens, author and admin roles, posts with drafts, search, pagination, comments and image uploads. The API has 13 integration tests (Jest + Supertest + in-memory MongoDB).

### [Dialogflow Chatbot](https://github.com/Sami123d/dialogflow-chatbot)
**Next.js 16 · Node WebSocket server · Dialogflow ES**
Real-time chat UI. A WebSocket server forwards messages to Dialogflow's detectIntent API and includes a sample fulfilment webhook. Has tests and CI.



### Extended open-source projects
Repositories that build on other people's MIT-licensed code. Each README credits the original author and lists exactly what I changed.
- [job-app-agent-extended](https://github.com/Sami123d/job-app-agent-extended): added a provider-agnostic LLM interface, SQLite history API, PDF export, Docker and a pytest suite.
- [nexus-support-extended](https://github.com/Sami123d/nexus-support-extended): LangGraph support agent. Added a real LLM fallback, a Docker startup fix, SSN/card masking and tests.
- [ai-client-onboarding-extended](https://github.com/Sami123d/ai-client-onboarding-extended): added PDF export and email via Resend, and fixed Netlify functions that crashed on load. Vitest suite.

---

## Tech I've used in these repos

**Frontend:** TypeScript, React, Next.js, Angular, Tailwind CSS, Angular Material, Vite
**Backend:** Node.js, Express, NestJS, FastAPI (in extended projects), REST, WebSockets
**Data:** MongoDB/Mongoose, PostgreSQL/Prisma, Supabase, pgvector, SQLite
**AI & automation:** Gemini, Ollama, Dialogflow ES, LangGraph, n8n, Playwright
**Tooling:** Git, GitHub Actions, Vitest, Jest, Supertest, pytest, Docker, Vercel
