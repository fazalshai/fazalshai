# ⚡ Hi, I'm Fazal Shaik 👋
### AI Systems & High-Performance Infrastructure Engineer

I build distributed agent runtimes, real-time voice streaming pipelines, sub-millisecond semantic caches, and secure API gateways. My engineering focus centers on high-concurrency systems (Rust/Go/C#/.NET) and browser-native GPU computing (WebGPU/WASM) for secure, low-latency AI deployment.

---

## 🛠️ Featured Architectural Masterpieces

| Repository | Tech Stack | Architecture & Engineering Highlights |
| :--- | :--- | :--- |
| [**AgentMesh**](https://github.com/fazalshai/agentmesh) | `Rust` `Tokio` `Axum` | **Concurrent LLM Agent Runtime:** Orchestrates parallel tool-call DAGs using Tokio green threads. Features a recursive OpenAI/Ollama planning loop, and real-time state traces streamed over upgraded WebSockets. |
| [**DeepRAG**](https://github.com/fazalshai/deeprag) | `Python` `LangGraph` `Qdrant` | **Self-Correcting RAG Engine:** Multi-agent retrieval graph with a semantic feedback loop. Combines dense (Qdrant) and sparse (BM25) search via RRF, query-rewriting nodes, and an in-memory cache. |
| [**BrowserMind**](https://github.com/fazalshai/browsermind) | `WebGPU` `TS` `Workers` | **Browser-Native AI Client:** Local LLM text generation compiled on WebGPU device pointers (with WASM fallback). Runs background Web Workers to maintain 60 FPS UI responsiveness. |
| [**PromptShield**](https://github.com/fazalshai/promptshield) | `C#` `.NET 8` `YARP` | **Enterprise AI Gateway:** High-performance reverse proxy built on YARP. Intercepts OpenAI JSON payloads to execute regex jailbreak filters, bi-directional PII masking, and trigram Jaccard caches. |
| [**EchoAgent**](https://github.com/fazalshai/echoagent) | `Go` `WebSockets` | **Streaming Voice AI Infrastructure:** Multiplexes audio PCM chunks over WebSockets. Implements RMS-based VAD (Voice Activity Detection) and barge-in interruption to flush active TTS audio buffers. |
| [**MiniRedis**](https://github.com/fazalshai/miniredis) | `Go` `net (TCP)` | **In-Memory Database from Scratch:** Single-process TCP database implementing raw REdis Serialization Protocol (RESP) parser and concurrent `sync.Map` storage. Compatible with standard `redis-cli`. |
| [**SemanticCache**](https://github.com/fazalshai/semanticcache) | `Rust` `Axum` `Tokio` | **Vector Cache Service:** Sub-millisecond concurrent vector cache. Evaluates similarity of dense query embeddings using thread-safe `RwLock` and optimized iterator cosine scores. |

---

## 💻 Tech Stack & Toolbelt

* **Languages:** Rust, Go, C# (.NET 8), Python, TypeScript, SQL, Bash
* **Systems / Web Engines:** Tokio, Axum, YARP Proxy, ASP.NET Core, FastAPI, Gorilla WebSockets, Node.js
* **Vector Ops / Cache:** Qdrant (Dense), BM25 (Sparse), Semantic Trigram Cache, Redis, MiniRedis (RESP), SemanticCache (Rust)
* **AI & Edge Compute:** WebGPU, WebWorkers, WASM, Transformers.js (v3), Deepgram API, OpenAI API

---

## 📊 Live Metrics & GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=fazalshai&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" alt="Fazal's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fazalshai&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</p>

---

## 📬 Connect with Me

* Pinned Repositories: Check out [AgentMesh](https://github.com/fazalshai/agentmesh), [DeepRAG](https://github.com/fazalshai/deeprag), [BrowserMind](https://github.com/fazalshai/browsermind), [PromptShield](https://github.com/fazalshai/promptshield), [EchoAgent](https://github.com/fazalshai/echoagent), [MiniRedis](https://github.com/fazalshai/miniredis), and [SemanticCache](https://github.com/fazalshai/semanticcache).

