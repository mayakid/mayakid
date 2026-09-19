<div align="center">

# mayakid

### Building AI systems that can be inspected, evaluated, and trusted.

Agents & Tooling · Retrieval & Ranking · Multimodal Robotics

[Open-source contributions](https://github.com/pulls?q=is%3Apr+author%3Amayakid+is%3Amerged) · [Utopia](https://github.com/deeplethe/utopia)

</div>

---

## About

I build applied AI systems at the intersection of **agent engineering, information retrieval, and real-world interaction**. With a background in mathematics, I care about the details that make a prototype dependable: explicit permissions, traceable data, reproducible evaluation, and human oversight.

My work spans enterprise knowledge workflows, candidate retrieval and ranking, and multimodal sensing. I enjoy connecting models to useful tools—and checking that the resulting system does what it claims.

## Engineering focus

| Area | What I work on |
| :--- | :--- |
| **Agent systems** | MCP tools, structured outputs, human approval flows, permission-aware execution, and idempotent writes. |
| **Retrieval & evaluation** | Hybrid lexical and semantic retrieval, two-stage ranking, held-out evaluation, and data leakage prevention. |
| **Multimodal robotics** | Depth cameras, IMUs, voice interaction, sensor pipelines, and separating model suggestions from hardware execution. |
| **Applied ML** | Low-cost spectral sensing, sample-level validation, matched ablations, and end-to-end experimental demos. |

## Selected open-source contributions

Contributing reliability and correctness fixes to [**Utopia**](https://github.com/deeplethe/utopia), an open-source enterprise world model.

- **Temporal retrieval correctness** — apply the result limit after visibility filtering to avoid dropping eligible historical results. [Merged PR #728](https://github.com/deeplethe/utopia/pull/728)
- **MCP error semantics** — surface document and rule read failures as tool errors instead of misleading successful responses. [Merged PR #727](https://github.com/deeplethe/utopia/pull/727) · [#733](https://github.com/deeplethe/utopia/pull/733)
- **Database resource management** — reuse the vector-build connection for index status checks. [Merged PR #734](https://github.com/deeplethe/utopia/pull/734)

## Toolkit

**Languages** · Python · SQL · Rust (working knowledge)  
**AI systems** · LangGraph · RAG · MCP · Tool Calling · Human-in-the-loop  
**Infrastructure** · PostgreSQL · pgvector · Docker · Git  
**Evaluation** · Recall@K · NDCG · Precision · Latency · Ablation studies

---

### 中文概述

关注 Agent 工程、检索排序与多模态交互，拥有数学背景及 AI 应用开发经验。重视权限边界、数据可追溯性、可复现评测与人工确认，持续通过开源贡献改进系统的可靠性与正确性。

<sub>Selected experience is described at a technical level; client identities, private datasets, and internal implementation details are omitted.</sub>
