# LitReview-AI 2.0: Autonomous Multi-Agent Research Gap Discovery Framework

[![Python 3.13+](https://img.shields.io/badge/python-3.13+-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Google%20ADK%202.0-orange)](https://github.com)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## 🎯 Abstract & Research Context
In academic research, literature synthesis and research gap discovery suffer from high human cognitive fatigue. This project introduces an autonomous, multi-agent pipeline built using Google's Agent Development Kit (ADK) and the Gemini API. By isolating tasks across a sequential agent workflow, the framework systematically evaluates academic publications to identify under-explored research anomalies without context rot.

## 🧬 System Architecture
The framework employs a strict sequential pipeline consisting of three specialized, decoupled agents acting as a logical conveyor belt:
1. **PaperSearchAgent (Retrieval):** Responsible for executing programmatic queries and extracting relevant academic literature datasets.
2. **SummaryAgent (Synthesis):** Parses complex technical structures, isolating core methodologies, datasets, and performance evaluation metrics.
3. **ResearchGapAgent (Analysis):** Critically cross-references findings to highlight unresolved questions, dataset limitations, and future work opportunities.

```text
[START] ──> PaperSearchAgent ──> SummaryAgent ──> ResearchGapAgent ──> [Discovered Gaps]
