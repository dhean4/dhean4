# Hi, I'm Daniel

I am a Product engineer. For six-plus years I've built B2B SaaS and data-heavy products
with remote teams, and lately I've found the work I enjoy most on the AI side: computer-vision
pipelines that feed real dashboards, tool-calling and MCP servers, and agents that earn a
person's trust one decision at a time. I like building things people lean on every day, and
I like getting a little better at this every week.

I'm comfortable in Python (FastAPI), Node (NestJS, Express), Java (Spring Boot) and .NET on
the back end, React/Next.js and Angular on the front, Postgres and event-driven plumbing in
between, deployed on AWS, GCP or Azure with GitHub Actions. I care less about which stack
than about whether the thing holds up when a real person leans on it, and I try to write
READMEs that say what is not finished as clearly as what is.

I'm still relatively new to building with language models, and that is the part I most want
to get better at. The projects below are how I'm doing that in public.

## Projects I'd point you to first

**[ShelfSense](https://github.com/dhean4/shelfsense)** — retail and cold-chain operations
for small distributors in Lagos. A field agent photographs a shelf, the system reads it,
drafts the reorder, and holds the bigger calls for a manager to approve.
Fridges stream temperatures; a sustained fault becomes a technician proposal, also held for
approval. Multi-tenant Postgres with row-level security, a 100-case eval set replayed in CI
with a regression gate, every model call traced and priced.
_Python, FastAPI, Next.js, Claude, MCP, Langfuse_

**[SafeGate](https://github.com/dhean4/safegate)** — a content-safety gateway that sits in
front of an LLM. Each prompt goes through classification, policy and response stages, then
is blocked, rewritten or allowed, and every decision lands in an audit trail.
[Live](https://safegate-fawn.vercel.app) · _FastAPI, Angular, Claude_

**[TaskFlow](https://github.com/dhean4/task-manager)** — a Kanban task manager with
drag-and-drop. Small, finished and deployed; I built it to get properly comfortable with
Angular signals. [Live](https://task-manager-eight-phi-65.vercel.app) · _Angular, TypeScript_

## Also worth a look

- [curate](https://github.com/dhean4/label-error-triage) — ranks the labels in a detection
  dataset most worth a human's attention, then measures whether fixing them moved the model.
- [ragbench](https://github.com/dhean4/ragbench) — a harness for measuring how RAG pipeline
  choices change answer quality, latency and token usage, with confidence intervals.
- [expense-tracker-api](https://github.com/dhean4/expense-tracker-api) — a small, complete
  REST API in ASP.NET Core with EF Core, Postgres and JWT auth.

## Writing and research

- [Medium](https://medium.com/@danielibisagba) — notes on building AI systems that know
  when to ask a human.
- [Comparative analysis of AI-based search algorithms in solving 8 puzzle problems](https://link.springer.com/article/10.1186/s42269-024-01274-3)
  — Bulletin of the National Research Centre (SpringerOpen), 2024. Co-authored during my
  computer science degree. I'm now pursuing a master's in computer science with a research
  focus on artificial intelligence.

## Get in touch

[LinkedIn](https://www.linkedin.com/in/danielibisagba/) · [X](https://x.com/IDhean_)

Open to senior full-stack and AI engineering roles with a team building something hard,
remote or with relocation.
