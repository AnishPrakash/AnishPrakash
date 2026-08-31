<h1 align="center">Anish Prakash</h1>

<p align="center">
  B.Tech CSE (AI & ML) · VIT Chennai · CGPA 9.2/10<br/>
  Systems programmer · Applied ML · Low-latency infrastructure
</p>

<p align="center">
  <a href="mailto:anish1.prakash@gmail.com">anish1.prakash@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/anish-prakash-6b3725385/">LinkedIn</a>
</p>

---

### What I build

I write production-grade systems — not tutorials, not homework. Everything pinned below is a working implementation with benchmarks, tests, or real results.

- **[VecDB](https://github.com/AnishPrakash/vecdb)** — Custom vector database in Rust. HNSW index, WAL, SQ8 quantization. >95% Recall@10, <1ms P99 on SIFT1M.
- **[LOB Engine](https://github.com/AnishPrakash/lob-engine)** — HFT matching engine in C++20. 27M orders/sec · 42ns P50 · AVX2 SIMD · zero heap allocation on hot path.
- **[Arena](https://github.com/AnishPrakash/arena)** — Deterministic remote code execution judge in Go. Control plane split from execution plane over Redis Streams; ephemeral Docker sandboxes (no network, read-only rootfs, cgroups v2, seccomp, dropped caps). 27.4ms P95 submission latency under a 7,371-job backlog · 9.03% timing CV on pinned cores · zero 5xx and 13,950 correct 429s under burst · ~$0.45 spot compute for a 500-participant 3-hour contest. 18-fixture golden verdict suite in CI.
- **[Specter](https://github.com/AnishPrakash/specter)** ★ — AI supply chain attack intelligence platform. Won MicroCraft VibeAthon 6.0. 5 parallel scanners, 3D threat map, real-time alerts.
- **[stranger](https://github.com/AnishPrakash/stranger)** — Offline supply-chain auditor for lockfiles, in Rust with **zero dependencies** — stdlib only, empty manifest. One 4,357-line file: hand-written RFC 8259 JSON parser, Cargo.lock TOML reader, PEP 508 reader, bounded Damerau-Levenshtein with confusable-glyph folding, npm node-resolution graph engine, ANSI renderer. 9 offline risk rules (install scripts, typosquatting, off-registry sources, integrity mismatch) · `audit` / `diff` / `why` · reproducible builds on Linux + Windows · 58 stdlib-harness tests. Zero Dependency Hackathon 2026, Track A.
- **[OSmosis](https://github.com/AnishPrakash/osmosis)** — Linux kernel behavioral fingerprinting via eBPF. Isolation Forest anomaly detection, zero kernel modification.
- **[Redrob Ranker](https://huggingface.co/spaces/anishprakash/redrob_ranker)** — Ranked 100K candidate profiles in <2min CPU. XGBoost LambdaMART + FAISS + BM25 + adversarial defenses.
- **[qoi-rust](https://github.com/AnishPrakash/qoi-rust)** — Zero-unsafe Rust port of the QOI image format. 27.9M-iteration fuzz run, zero panics.
- **[ARGUS](https://github.com/AnishPrakash/argus)** — Real-time road surveillance system. 4-stage CV pipeline: YOLOv8l base detection (mAP50 80%+) → YOLOv8m emergency vehicle classifier (mAP50 0.85) → EfficientNetB0 helmet violation detector → EfficientNetB0 make/model classifier (196 classes). Selective model execution per-frame via frontend toggles. Live WebSocket dashboard via Supabase Realtime. FastAPI backend · Next.js · Deployed on Railway + Vercel.

---

### Stack

```text
Languages    C · C++20 · Rust · Go · Python
AI / ML      RAG · FAISS/HNSW · XGBoost LambdaMART · Isolation Forest · LLM Orchestration
Systems      eBPF · AVX2 SIMD · NUMA threading · cgroups v2 · seccomp · gRPC · CMake · Embedded / RPi / Arduino
Infra        Docker · Redis Streams · PostgreSQL · GCP · Railway · Vercel
Web          Next.js · React · Supabase · Axum · n8n
```

---

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/C++20-00599C?style=flat&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" />
</p>
