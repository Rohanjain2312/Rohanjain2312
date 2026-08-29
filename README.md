## Rohan Jain

Applied ML engineer. I build LLM agents and put controls around them so they fail safely.

**Open to ML Engineer, AI Engineer, and Data Scientist roles in the US.**
📫 rohanjain2312@gmail.com

---

### What I work on

Agent reliability, mostly. Retrieval that returns the right thing, recovery loops that do more than retry, gates with real thresholds, and evals that catch a regression before a user does. I care about the engineering around the model more than the model itself.

Before this I spent three and a half years at Goldman Sachs building controls for humans — trade-risk classification, OCR/KYC pipelines, KPI analytics that replaced three FTEs of manual reporting. Same problem, different operator.

---

### Selected work

| Project | What it does | Result |
|---|---|---|
| [Loan Servicing Agent](https://github.com/Rohanjain2312/loan-servicing-agent) | Multi-agent system for syndicated loan documents, ingests a Credit Agreement or Notice PDF and executes the lifecycle action | Confidence-gated human review, deterministic ACT/360 validation, append-only audit log |
| [Self-Healing Code Agent](https://github.com/Rohanjain2312/Self-Healing-Code-Agent) | Generates Python, adversarially tests it, diagnoses failures via a ReAct debugger, repairs iteratively | 37% → 87% across 8 benchmark tasks, same model throughout |
| [GraphBench](https://github.com/Rohanjain2312/graphbench) | Benchmarks GraphRAG against GNN-RAG on multi-hop QA with the scaffold held fixed | `pip install graphbench-kg` |
| [ToolSmith](https://github.com/Rohanjain2312/toolsmith) | Post-training Qwen3-4B for tool-calling via LoRA SFT and step-level GRPO with verifiable sandbox rewards | In progress |
| [FinCompress](https://huggingface.co/spaces/rohanjain2312/FinCompress) | Compression study on FinBERT: structured pruning, distillation, INT8 quantization | 9.1× smaller, Macro F1 improved after pruning 50% of attention heads |

---

### Writing

- [Harness Engineering: The Part of the Agent That's Actually Yours](https://medium.com/@rohanjain2312/harness-engineering-the-part-of-the-agent-thats-actually-yours-ede9e85e4498) — five places my own agent harness was the problem, with numbers from the repos above
- [I Pruned Half of FinBERT's Attention Heads — and It Got Better](https://medium.com/@rohanjain2312/i-pruned-half-of-finberts-attention-heads-and-it-got-better-f17dfbe74d04) — a compression result I had to re-run before I believed it

---

### Background

MS in Applied Machine Learning, University of Maryland. Previously Goldman Sachs, where I went from STEM intern to Business Intelligence Associate over three and a half years. IEEE-published on Alzheimer's MRI classification.

**Stack:** Python · PyTorch · LangGraph · Postgres/pgvector · Neo4j · Docker · AWS · GitHub Actions

---

### Reach me

[Email](mailto:rohanjain2312@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jaroh23/) · [Medium](https://medium.com/@rohanjain2312) · [Hugging Face](https://huggingface.co/rohanjain2312)
