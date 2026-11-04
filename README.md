**English** | [Français](README.fr.md)

# Sofien Nefzi

I build data and AI products end to end: the pipeline that brings the data in, the model or agent that works with it, and the app people actually use.

Data & AI Solutions Engineer, based in Tunis.

## What I'm working on

- **Multi-agent systems** with LangGraph, where agents prepare the work and a human approves it before anything leaves the system.
- **Testing LLM features in CI:** text-to-SQL checked on results and data safety before it ships, not on how the SQL looks.
- **AI inside live sessions:** real-time guidance delivered during video calls (LiveKit + LLM).
- **Reporting as code:** Grafana dashboards versioned in Git and provisioned automatically, reading from PostgreSQL views that keep personal data out.

## Public repositories

| Repository | What it is |
| --- | --- |
| [querywarden](https://github.com/NefziSofien/querywarden) | CI gate for text-to-SQL features on PostgreSQL: runs the generated SQL on a test database with a read-only role, compares results with trusted queries, and fails the build on accuracy drops or data leaks. Python, GitHub Action, on PyPI as `querywarden-cli`. Example: [querywarden-example](https://github.com/NefziSofien/querywarden-example). |
| [claude-code-orchestra](https://github.com/NefziSofien/claude-code-orchestra) | Orchestrator for big coding tasks: splits the work, runs 0 to 4 parallel workers, tracks state in one compact file and verifies the final result. Python, tested on Linux, macOS and Windows. |
| [Ai-Agency](https://github.com/NefziSofien/Ai-Agency) | Self-hosted multi-agent system for a marketing agency: specialised agents (strategy, content, SEO, analytics...), a brand consistency check and human approval before publishing. FastAPI, Next.js, n8n, pgvector, Langfuse. |

Most of my client and employer work lives in private repositories. I'm happy to walk through the architecture and code on a call.

## How I build

- A small version running in production beats a large one waiting on a branch.
- The unglamorous parts get done properly: migrations, CI/CD, monitoring, rollbacks.
- An AI agent never sends anything outside the system without human approval.
- Personal data stays out of reporting: dashboards read from views, not raw tables.

## Tools I reach for

- **AI:** LLM APIs, LangGraph, n8n, Langfuse, pgvector
- **Data:** Python, SQL, Pandas, MongoDB, Power BI, Grafana
- **Apps:** TypeScript, React, React Native/Expo, Node.js, NestJS, FastAPI, Supabase, LiveKit
- **Infrastructure:** PostgreSQL, Docker, GitHub Actions, Azure

## Get in touch

Open to collaborating on data and AI projects, and to remote or relocation roles.

[nefzisofien.sn@gmail.com](mailto:nefzisofien.sn@gmail.com) · [LinkedIn](https://linkedin.com/in/sofien-nefzi-) · [Portfolio](https://sofien-nefzi.web.app)
