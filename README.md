<p align="center">
  <img src="./assets/profile-header.svg" alt="Aarnav Saboo" width="100%">
</p>

## Aarnav Saboo

**Applied AI / LLM engineer** working mostly on local model inference, retrieval systems, RAG pipelines, and tooling for repeatable model workflows.

Most of my projects are small experiment systems rather than end-to-end product demos: define a workload, run it against local models, keep the raw measurements, and compare what actually changed.

### Current work

- **Local inference** — MLX, GGUF / llama.cpp, Ollama, OpenAI-compatible local runtimes, quantized models, warm/cold behaviour, memory and throughput
- **RAG & retrieval** — BM25, embeddings, hybrid retrieval, rank fusion, reranking, chunking experiments, query expansion and retrieval evaluation
- **Model evaluation** — small-model task packs, paired comparisons, long-context experiments, embedding benchmarks and ablation runs
- **Workflow tooling** — experiment manifests, model matrices, batch runners, run artifacts, local routing, SQLite-backed experiment telemetry and reproducible reports

### Selected projects

| Project | What I'm experimenting with |
| :--- | :--- |
| `local-llm-bench` | Repeatable local inference workloads: TTFT, prompt processing, decode throughput, concurrency and raw run artifacts |
| `rag-rerank-pipeline` | Multi-stage retrieval: lexical + dense search, fusion, reranking, evidence packing and local generation |
| `mlx-model-lab` | Apple Silicon / MLX model sweeps, warm vs cold runs, prompt length, generation length and process measurements |
| `gguf-model-bench` | GGUF metadata inspection and llama.cpp prompt-processing / generation benchmark matrices |
| `small-model-evals` | Application-shaped local model task packs with quality, latency and paired model comparisons |
| `rag-ablation-lab` | RAG component ablations with per-query wins, regressions and bootstrap deltas |
| `embedding-bench` | Local embedding model quality, throughput, vector dimensions and paired retrieval comparisons |
| `local-model-router` | Queue-aware routing across a pool of local models with memory, capacity and task constraints |
| `long-context-lab` | Prompt-length × evidence-position experiments with full, retrieval and compression strategies |
| `model-memory-profiler` | Process/system memory timelines for local model workloads |
| `local-inference-observatory` | Local run collection into SQLite with model/runtime/workload summaries |
| `synthetic-rag-data` | Local-model generation of labelled retrieval datasets for RAG experiments |

### Stack

Python · TypeScript · Node.js · MLX · llama.cpp · Ollama · Sentence Transformers · SQLite

---

I like keeping experiments inspectable: raw runs before summaries, simple baselines beside complicated pipelines, and failed ideas in the results when they lose.
