<p align="center">
  <img src="./assets/profile-header.svg" alt="Aarnav Saboo — language models, retrieval and applied NLP" width="100%">
</p>

<p align="center">
  <a href="#selected-projects">Projects</a> &nbsp;·&nbsp;
  <a href="#how-i-work">How I work</a> &nbsp;·&nbsp;
  <a href="https://aarnavsaboo.github.io/">Portfolio ↗</a>
</p>

## Hi, I'm Aarnav.

I build and experiment with **LLM integrations, retrieval-augmented generation and structured NLP workflows**. I'm interested in the steps between a document and a useful result: preparing the text, retrieving context, connecting a model and checking its output.

Most of the code here is **Python** and **TypeScript**. I like being able to follow a result back through the pipeline and understand why it happened.

## Selected projects

| Project | What it does |
| :--- | :--- |
| **[RAG Chunk Kit](https://github.com/aarnavsaboo/rag-chunk-kit)**<br>Python · Information retrieval | Document ingestion, overlapping chunks, BM25 and optional dense retrieval. Includes source-linked context assembly and retrieval evaluation. |
| **[AI Provider Router](https://github.com/aarnavsaboo/ai-provider-router)**<br>TypeScript · Model integrations | A shared interface for OpenAI-compatible endpoints and Ollama. Task routing, explicit fallbacks, retries, cancellation and bounded batch execution. |
| **[LLM JSON Guard](https://github.com/aarnavsaboo/llm-json-guard)**<br>Python · Structured extraction | JSON Schema validation, entity-span checks and bounded regeneration with feedback. Includes an async interface and batch-output evaluation. |

These are evolving open-source projects. Each includes runnable offline examples, tests and notes on the implementation's trade-offs.

## How I work

**Keep context traceable.** Preserve the source and offsets, not just the retrieved text.

**Make behaviour explicit.** Document what gets retried, where a request goes and what a validation result actually establishes.

**Start with something testable.** Small fixtures and clear failure cases before bigger abstractions.

<details>
<summary><strong>A closer look at the implementations</strong></summary>

- [Retrieval, chunk boundaries and evaluation](https://github.com/aarnavsaboo/rag-chunk-kit/blob/main/docs/design.md)
- [Provider adapters, fallback routes and circuit handling](https://github.com/aarnavsaboo/ai-provider-router/blob/main/docs/design.md)
- [Structured extraction and validation feedback](https://github.com/aarnavsaboo/llm-json-guard/blob/main/docs/design.md)

</details>

---

[More about me and the projects →](https://aarnavsaboo.github.io/)
