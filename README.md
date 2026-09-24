# Hasan Özkan

**Founder & product engineer.** I build products end to end — domain model,
backend, mobile, infrastructure and the delivery pipeline around them — and I
work with AI coding agents as part of the team, under the same gates as
everyone else.

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
| Backend | Python, FastAPI, SQLAlchemy/Alembic, PostgreSQL (pgvector, PostGIS), Kafka, Redis |
| Mobile | React Native / Expo, TypeScript; Flutter |
| AI | LLM gateways and tool-calling assistants, speech-to-text, RAG over Postgres |
| Platform | Kubernetes (k3s), Flux, Helm, Terraform, Cloudflare, self-hosted CI runners |
| Quality | Contract snapshots (OpenAPI/AsyncAPI), import-linter architecture rules, SonarCloud, gitleaks |

### Sample projects

Independent, from-scratch illustrations of the patterns above — small enough
to read in one sitting, each with its gates verified.

| Repository | What it shows |
|---|---|
| [spec-driven-ddd-sample](https://github.com/hasanozkan/spec-driven-ddd-sample) | A modular monolith where specs lead: numbered rules traced to tests, bounded contexts that can only talk through events, policy as data, API contracts in review |

More on the way: a GitOps reference platform and an agent-assisted
engineering playbook.
