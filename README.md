## Ahmad Rishi

**Senior AI / LLM Engineer · AI Team Lead** — Dubai, UAE

I build agentic systems that ship production software: LangGraph multi-agent workflows behind
human approval gates, RAG over enterprise corpora, and the LLMOps underneath both. Currently
leading a 4–6 engineer AI team.

Most of my work lives in private company repositories, so the repos below are **technical case
studies** — architecture, design decisions, trade-offs and the things that went wrong — written
from the real codebases rather than from memory. Every number in them was measured, and where a
component was a teammate's, it says so.

---

### Selected work

| | |
|---|---|
| **[CodeHarbor](https://github.com/ahmadrishi/codeharbor)** | Agentic LLM security scanner — puts a coding agent inside a sandboxed clone and makes it prove every vulnerability it claims. Catches classes of bug a pattern matcher structurally cannot express. |
| **[Agentic Development Board](https://github.com/ahmadrishi/agentic-development-board)** | Internal platform driving business request → spec → code → tests → docs as LangGraph workflows. 16 workflow types over a 46-table persisted state machine, Kafka-dispatched, with human approval gates. |
| **[protoframe](https://github.com/ahmadrishi/protoframe)** | AI UI-design platform. One sentence → a React prototype that compiles in your browser. Includes a deny-by-default CSS allow-list and an offline A/B harness for evaluating design quality. |
| **[Enterprise Knowledge RAG](https://github.com/ahmadrishi/enterprise-knowledge-rag)** | Production RAG over a Jira/Confluence corpus with citations built *by construction*. Preferred over the incumbent tool 240–30–13 in a blind pairwise evaluation. |
| **[AI Agent Kits](https://github.com/ahmadrishi/ai-agent-kits-and-spec-skills)** | Encoding a codebase's real conventions — derived by measuring the repos, not by asking — so AI-generated code passes human review. |
| **[LLM Evaluation Framework](https://github.com/ahmadrishi/llm-evaluation-framework)** | Multi-provider, multi-judge evaluation on real production traffic. Central finding: swapping the judge moved the pass rate **37.4 points** on byte-identical outputs. |

Also: [Chat Assist](https://github.com/ahmadrishi/chat-assist-platform) (multi-tenant chat-agent
SaaS, 40 KB embeddable widget) · [OpenAPI Spec RAG](https://github.com/ahmadrishi/openapi-spec-rag)
· [Passport OCR pipeline](https://github.com/ahmadrishi/passport-ocr-quality-pipeline) ·
[Ziwo telephony suite](https://github.com/ahmadrishi/ziwo-telephony-suite)

---

### What I work with

`Python` `FastAPI` `LangGraph` `LangChain` `MCP` `Claude / GPT / Gemini` `Pinecone` `Milvus`
`LiteLLM` `Langfuse` `Kafka` `Celery` `Redis` `PostgreSQL` `MySQL` `TypeScript` `Next.js` `React`
`Angular` `AWS` `Terraform` `Docker` `Kubernetes`

---

### A note on these write-ups

Producing them meant re-reading every codebase and measuring authorship with `git blame` rather
than trusting recollection. That surfaced claims I'd been making that the source didn't support —
a corpus figure inflated by a pagination bug, components I'd assumed were mine that a teammate
wrote — and those are corrected in the docs and called out in the open. Where a repo documents a
system I contributed to rather than authored, the attribution sits above the fold.

📫 ahmadrishi@gmail.com · [LinkedIn](https://linkedin.com/in/ahmad-rishi)

<!-- updated -->
