# AI Cookbook: From Building Blocks to Agentic Systems

Welcome to the **AI Cookbook** repository! This project is a comprehensive, hands-on guide designed to help developers master modern AI patterns—transitioning from basic LLM calls to production-grade, multi-agent autonomous architectures and advanced retrieval systems.

---

## Author & Introduction

Hi there! I am **[Abhishek Rajput]**, an AI engineer and developer passionate about building scalable, intelligent systems. 

I created this cookbook to bridge the gap between simple LLM prompting and complex real-world AI applications. Whether you are exploring how agents make decisions, implementing structured Agentic RAG, or building hybrid search engines from scratch, this repository provides battle-tested architectures, clean code patterns, and practical recipes to accelerate your engineering journey.

* **GitHub:** [https://github.com/Abhishek140305)


---

## Repository Structure & Overview

This cookbook breaks down agent engineering into modular components:

### 1. Agents & Architectural Complexity (`/agents`)
* **Agent Building Blocks (`/building-blocks`):** Foundational primitives covering intelligence, stateful memory, tool definition, runtime validation, flow control, automated error recovery, and feedback loops.
* **Complexity Evolution (`/agent-complexity`):** Step-by-step evolution from a simple augmented LLM to complex multi-agent workflows[cite: 1]:
  * `1-augmented-llm.py`: Grounding models with external context[cite: 1].
  * `2-prompt-chains.py`: Deterministic sequential reasoning[cite: 1].
  * `3-tool-calling-agent.py`: Dynamic tool execution[cite: 1].
  * `4-agent-harness.py`: Robust agent harness with runtime observability[cite: 1].
  * `5-multi-agent.py`: Collaborative, role-based multi-agent swarms[cite: 1].

### 2. Context & Web Integration (`/context/web`)
* Dynamic web context fetching and scraping[cite: 1].
* Web-search-augmented agents for live fact retrieval[cite: 1].
* Internal handbook query agents leveraging localized knowledge bases[cite: 1].

### 3. Knowledge & Information Retrieval (`/knowledge`)
* **Agentic RAG (`/agentic-rag`):** Advanced autonomous RAG systems with streaming step analysis, structured outputs, and incident runbook synthesis[cite: 1].
* **Docling Pipeline (`/docling`):** End-to-end multimodal document parsing, extraction, semantic chunking, embedding, and vector search[cite: 1].
* **Hybrid Retrieval (`/hybrid-retrieval`):** Merging BM25 lexical search with dense vector embeddings using Reciprocal Rank Fusion (RRF), cross-encoder re-ranking, and BEIR benchmarking[cite: 1].

---

## Quickstart

### Prerequisites
* Python 3.12+[cite: 1]
* OpenAI API Key[cite: 1] (or Anthropic API Key[cite: 1] depending on the target agent)

### Installation

```bash
# Clone the repository
git clone [https://github.com/Abhishek140305/agentic-ai-blueprint]x
cd agentic-ai-blueprint

# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate   # On Windows use: .venv\Scripts\activate

# Install core dependencies
pip install openai requests python-dotenv pydantic docling