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
| Backend | C# / .NET Core, Python, FastAPI, SQLAlchemy/Alembic, PostgreSQL (pgvector, PostGIS), Kafka, Redis |
| Mobile | React Native / Expo, TypeScript; Flutter |
| Platform | AWS, Kubernetes (k3s), Flux, Helm, Terraform, Cloudflare, self-hosted CI runners |
| Quality | Contract snapshots (OpenAPI/AsyncAPI), import-linter architecture rules, SonarCloud, gitleaks |

### Background

Sixteen years across the stack, and each era left something I still use.
I started with desktop and classic web — Delphi, WinForms and WPF, ASP.NET
Web Forms, PHP, Java — on top of SQL Server and Oracle (T-SQL, PL/SQL). That
is where I learned data modelling, transactions and what users actually do
with software. .NET Core and service architectures came next, and today the
work is Python, LLM systems and platforms run from Git. The older tools are
retired; the lessons are in everything above.

### Sample projects

Independent, from-scratch illustrations of the patterns above — small enough
to read in one sitting, each with its gates verified.

| Repository | What it shows |
|---|---|
| [llm-tool-calling-assistant](https://github.com/hasanozkan/llm-tool-calling-assistant) | An AI system built to ship: provider-neutral LLM gateway, validated tool contracts, writes that wait for the user, prompt-injection defence, budgets, and evals as a CI gate |
| [ai-native-engineering](https://github.com/hasanozkan/ai-native-engineering) | How AI coding agents work inside a team: a playbook (principles, the loop, gates, memory, approval boundaries, failure patterns), templates, and tested gate tools |
| [spec-driven-ddd-python](https://github.com/hasanozkan/spec-driven-ddd-python) | A modular monolith where specs lead: numbered rules traced to tests, bounded contexts that can only talk through events, policy as data, API contracts in review |
| [spec-driven-ddd-dotnet](https://github.com/hasanozkan/spec-driven-ddd-dotnet) | The same domain in C# / .NET 10 from byte-identical specs and the same HTTP contract — bounded contexts as assemblies, architecture and gates as tests; CI runs the Python smoke test against it |
| [library-mobile](https://github.com/hasanozkan/library-mobile) | A contract-first React Native (Expo) client: types generated from both services' contracts with a CI drift gate, honest mocks, live tests against the real services, and one approval card for human- and AI-proposed changes |
| [gitops-reference](https://github.com/hasanozkan/gitops-reference) | Flux on a laptop in one command: ordered reconciliation onto restricted workloads, and a merge in the app repo becoming a deploy through a Git commit; end-to-end tested on kind in CI |

The six fit together: the DDD samples (Python and .NET, one spec) are the service, the mobile app is its client, gitops-reference deploys
it, the assistant is an AI system built on the same discipline, and the
playbook is how the work gets done.
