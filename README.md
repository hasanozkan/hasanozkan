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
| [llm-tool-calling-assistant](https://github.com/hasanozkan/llm-tool-calling-assistant) | An AI system built to ship: provider-neutral LLM gateway, validated tool contracts, writes that wait for the user, prompt-injection defence, budgets, and evals as a CI gate |
| [ai-native-engineering](https://github.com/hasanozkan/ai-native-engineering) | How AI coding agents work inside a team: a playbook (principles, the loop, gates, memory, approval boundaries, failure patterns), templates, and tested gate tools |
| [spec-driven-ddd-sample](https://github.com/hasanozkan/spec-driven-ddd-sample) | A modular monolith where specs lead: numbered rules traced to tests, bounded contexts that can only talk through events, policy as data, API contracts in review |
| [gitops-reference](https://github.com/hasanozkan/gitops-reference) | Flux on a laptop in one command: ordered reconciliation onto restricted workloads, and a merge in the app repo becoming a deploy through a Git commit; end-to-end tested on kind in CI |

The four fit together: the DDD sample is the service, gitops-reference deploys
it, the assistant is an AI system built on the same discipline, and the
playbook is how the work gets done.
