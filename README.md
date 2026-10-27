# Hi, I'm Rubén Rangel 👋

**Senior full-stack software engineer and AI builder, based in Medellín, Colombia.**
Building software since 2006: backends that scale, frontends that don't break, and AI agents that work in production, not just in demos.

🌐 [rubenrangel.org](https://rubenrangel.org) · ✍️ [Blog (EN)](https://rubenrangel.org/en/blog) · [Blog (ES)](https://rubenrangel.org/es/blog) · 💼 [LinkedIn](https://www.linkedin.com/in/rubenerangelg/) · 📧 rubenrang@gmail.com

---

## 🔨 What I'm building now

- **[pyme-contable](https://github.com/rubenerangel/pyme-contable)**: concept-based accounting for construction SMBs in Colombia. Field reports, purchases and subcontractor payments generate journal entries from versioned rules (withholdings, ICA, AIU, advances, retainage). Laravel, PostgreSQL with row-level security for multi-company isolation, and React. Built with a team of locked-down AI agents (coder, tester, code, security and performance reviewers) guarded by hooks.
- **[arrow-fin](https://github.com/rubenerangel/arrow-fin)**: daily snapshot of positions, P&L and risk for CME futures, streamed in real time over WebSocket. Multi-tenant isolation enforced in the data layer, not in each query. TypeScript.
- **[LeadBrief](https://github.com/rubenerangel/leadbrief)** *(work in progress)*: a RAG system that writes cited contact briefs for sales reps. Every claim must cite the retrieved note it came from, and when context is missing it says so instead of making things up. Laravel queues, PostgreSQL + pgvector, and local models on Ollama (`llama3.2:3b` for generation, `nomic-embed-text` for 768-dim embeddings) at zero inference cost. Requirements are defined against ISO/IEC 25010, with planned evals for citation validity, unsupported claims and prompt injection, and a [measured CPU latency baseline](https://github.com/rubenerangel/leadbrief/blob/main/docs/NFR.md).
- **[ai-agent-demo](https://github.com/rubenerangel/ai-agent-demo)**: an AI agent that resolves e-commerce refund claims by deciding on its own which tools to call (function calling on the Anthropic Messages API), with its step-by-step reasoning replayed in the browser. [Try it live](https://rubenrangel.org/en/agent-demo).

## 📚 What I'm learning now

- **Terraform** (since April 2026): [tf-exp](https://github.com/rubenerangel/tf-exp), a lab with GitHub Actions where every PR gets a plan comment, merges apply to dev and prod needs manual approval. Keyless AWS auth through OIDC, one IAM role per environment, remote state in S3 with native locking.
- **Kubernetes** (since June 2026): orchestration and self-healing deployments, alongside Terraform.
- **Docker**: [go-docker-vercel](https://github.com/rubenerangel/go-docker-vercel), a Go server whose multi-stage build went from 354 MB to 16 MB ([write-up](https://rubenrangel.org/en/blog/from-354-mb-to-16-mb-docker-under-the-hood-multi-stage-and-vercel-deploy)). Plus [ecr-lab](https://github.com/rubenerangel/ecr-lab), image builds pushed to AWS ECR from GitHub Actions.

## 🤖 How I work with AI

I've built with Claude since late 2024, not just chatted with it: agents with locked-down roles, skills and tools, where the instruction guides the agent and **code** stops it.

- [Four AI agents build my code. The most valuable one knows nothing.](https://rubenrangel.org/en/blog/four-ai-agents-build-my-code-the-most-valuable-one-knows-nothing): test-first agents, and a reviewer with no context that finds what everyone else missed.
- [Stripe puts its AI agents in boxes. I did the same with my accounting system.](https://rubenrangel.org/en/blog/stripe-puts-its-ai-agents-in-boxes-i-did-the-same-with-my-accounting-system): deterministic gates around unattended agents.
- [My blog posts to LinkedIn automatically, but not without me](https://rubenrangel.org/en/blog/my-blog-posts-to-linkedin-automatically-but-not-without-me): Claude drafts, a human approves.
- [Venezuela Aid Directory](https://rubenrangel.org/en/ayudavenezuela): built in one day after the 2026 earthquake, with a public REST API and AI moderation on Claude Haiku.

## 💼 Selected work

| Project | What | Stack |
|---|---|---|
| **SproutLoud** (acquired by Ansira) | Through-channel marketing SaaS connecting brands with local partners. 4 years, remote team USA/Colombia. | PHP, Laravel, Vue 2/3, React, Datadog |
| **Imaginamos** | Serverless microservices on AWS with infrastructure as code. | NestJS, TypeScript, AWS Lambda, API Gateway, DynamoDB, S3, CDK, Redis, Jest |
| **Tres Astronautas** | REST API for real estate property management. | NestJS, MongoDB Atlas, Docker, AWS ECS Fargate + ECR, Firebase, Wompi |

## 🧰 Stack

**Backend:** PHP · Laravel · Node.js · NestJS · Go · Java + Spring Boot (new features on 3 microservices consuming Kafka streams)
**Frontend:** Vue.js · React · Angular · TypeScript
**AI:** Claude (Anthropic API, agents, skills, tool calling) · LLM integration · RAG with pgvector and local models on Ollama (in progress)
**Data:** PostgreSQL (pgvector, row-level security) · MySQL · MongoDB · DynamoDB · Redis · SQLite
**Cloud & DevOps:** AWS (Lambda, ECS, ECR, S3, Lightsail) · GCP · Docker · GitHub Actions · Terraform · Cloudflare
**Practices:** TDD · hexagonal architecture · dependency injection · CI/CD

---

<sub>Rubén Rangel (Rubén Enrique Rangel G.) · 🇪🇸 Escribo en español e inglés: [rubenrangel.org/es](https://rubenrangel.org/es)</sub>
