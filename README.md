# Hasan Özkan

**Tech Lead & AI Architect** — AI systems and software architecture.

I lead teams through AI transformation by treating it as an engineering
problem, not a demo: LLM-powered products on a sound domain model,
delivered through GitOps, with AI coding agents working inside the same
specs, conventions and CI gates as the rest of the team.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-hasanozkan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasanozkan/)
[![Email](https://img.shields.io/badge/Email-hasanozkan07%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:hasanozkan07@gmail.com)

### How I build

- **Spec-driven, domain-driven.** Behaviour is written first as numbered
  rules; bounded contexts own their language and talk through events; the
  architecture is enforced by the build, not by review comments.
- **GitOps all the way down.** Everything that runs is declared in Git and
  reconciled by Flux; merging is deploying; infrastructure is Terraform.
- **Measure, don't assume.** A gate is trusted only after it has been broken
  on purpose and seen to fail.
- **Agent-assisted engineering.** Coding agents work from the same specs,
  conventions and CI gates as people, with a shared, versioned memory of
  what the team has learned.

### Stack I work in

| Area | Tools |
|---|---|
| AI | LLM gateways & model routing, tool-calling assistants, speech-to-text, RAG on PostgreSQL/pgvector, evaluation and guardrails |
| Backend | Python, FastAPI, SQLAlchemy/Alembic, PostgreSQL (pgvector, PostGIS), Kafka, Redis |
| Mobile | React Native / Expo, TypeScript; Flutter |
| Platform | Kubernetes (k3s), Flux, Helm, Terraform, Cloudflare, self-hosted CI runners |
| Quality | Contract snapshots (OpenAPI/AsyncAPI), import-linter architecture rules, SonarCloud, gitleaks |

### Sample projects

Independent, from-scratch illustrations of the patterns above — small enough
to read in one sitting, each with its gates verified.

| Repository | What it shows |
|---|---|
| [spec-driven-ddd-sample](https://github.com/hasanozkan/spec-driven-ddd-sample) | A modular monolith where specs lead: numbered rules traced to tests, bounded contexts that can only talk through events, policy as data, API contracts in review |

More on the way: an AI-native engineering playbook (how coding agents work
inside a team's specs and gates) and a GitOps reference platform.
