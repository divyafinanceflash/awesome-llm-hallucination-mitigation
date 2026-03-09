# awesome-llm-hallucination-mitigation
Curated techniques, tools, and research to detect, evaluate, and reduce hallucinations in Large Language Models (LLMs)
![Awesome](https://awesome.re/badge.svg)
![License](https://img.shields.io/badge/license-MIT-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

## Hallucination Mitigation Appraoch

```mermaid
flowchart TD

A[User Prompt] --> B[Prompt Engineering Layer]

B --> C[Retrieval Layer (RAG)]
C --> D[Context Construction]

D --> E[LLM Generation]

E --> F[Verification Layer]

F --> G[Fact Checking]
F --> H[Cross Model Validation]

G --> I[Guardrails & Monitoring]
H --> I

I --> J[Final Response]
