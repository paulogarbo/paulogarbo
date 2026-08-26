# Paulo Alex

**Full Stack Developer** · Node.js · React · TypeScript · AWS · LLM systems

I build backends that stay up when nobody is watching, and the AI systems that
run on top of them.

Two years shipping production software at a Brazilian software house, across
sixteen codebases: payment platforms, real-time operations APIs, analytics
dashboards and cloud infrastructure. Lately my work has moved toward LLM-backed
systems — agents with retries, idempotent queues and structured output, because
the hard part of an agent was never the prompt.

Based in Taubaté, São Paulo, Brazil (UTC−3). Open to remote roles worldwide.

[Portfolio](https://portfolio-v02-two.vercel.app/) ·
[LinkedIn](https://www.linkedin.com/in/paulo-alex-node/) ·
[Email](mailto:paulexgarbo@gmail.com)

---

## Selected work

**[whatsapp-ai-agent](https://github.com/paulogarbo/whatsapp-ai-agent)** —
A production WhatsApp agent written from scratch with Fastify and TypeScript, no
low-code tooling in the path. Messages are grouped with a debounce in BullMQ,
conversation history lives per user in Redis, and replies go out as text or
voice. The interesting part is the failure paths: atomic Redis operations so no
message is lost under concurrency, per-sender rate limiting written as a Lua
script for atomicity, graceful shutdown, and environment validation at boot.

More at my [portfolio](https://portfolio-v02-two.vercel.app/), including client
platforms I cannot open-source: a real-time operations API, a subscription and
payments backend, and the React front end that sits on top of them.

---

## What I work with

**Languages** — TypeScript, JavaScript, SQL, Python

**Backend** — Node.js, NestJS, AdonisJS, Express, Fastify, REST, GraphQL,
Socket.io

**Frontend** — React, Next.js, Tailwind CSS, Redux, Vite

**Data** — PostgreSQL, MongoDB, Redis, TypeORM, Bull / BullMQ

**Infrastructure** — Docker, AWS (S3, EC2), CI/CD, GitHub Actions, Heroku,
Railway, Linux

**AI** — OpenAI, Claude, LLM agents, RAG, structured output with Zod, n8n,
Whisper

**Quality** — Jest, Testing Library, Swagger / OpenAPI, Git

---

## Currently

Full Stack Developer at **Clicksoft** since August 2024, remote. Cut deployment
time from 2 hours to 15 minutes with CI/CD on GitHub Actions, and manage
infrastructure for 5+ production applications on AWS with Docker.

Finishing a **BSc in Computer Science** at Universidade Anhanguera (8th
semester, graduating December 2026). Certified in **Microsoft Azure AI
Fundamentals (AI-900)**.

Portuguese native, English advanced.
