# LitReview-AI 2.0: Autonomous Multi-Agent Research Gap Discovery Framework

[![Python 3.13+](https://img.shields.io/badge/python-3.13+-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Google%20ADK%202.0-orange)](https://github.com)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## 🎯 Abstract & Research Context
In academic research, literature synthesis and comprehensive background reviews demand significant cognitive effort and are prone to context degradation across large reading volumes. This project introduces an autonomous multi-agent framework built using Google's Agent Development Kit (ADK) and the Gemini API. By decomposing complex analytical tasks into a sequential agent workflow, the framework systematically evaluates academic publications to map out unaddressed research questions while maintaining strict context boundaries.

## 🧬 System Architecture
The framework partitions literature exploration into an isolated pipeline of three specialized, decoupled agents operating in a strict data sequence:

1. **PaperSearchAgent (Retrieval):** Executes targeted query logic, handles domain filtering, and extracts relevant publication datasets.
2. **SummaryAgent (Synthesis):** Parses complex technical structures to isolate distinct methodologies, baseline datasets, and performance evaluation metrics.
3. **ResearchGapAgent (Analysis):** Cross-references extracted study parameters to identify open challenges, dataset limitations, or structural contradictions in the current literature.

```text
[START] ──> PaperSearchAgent ──> SummaryAgent ──> ResearchGapAgent ──> [Identified Research Gaps]


🚀 Installation & Local Execution
Ensure your environment is configured with Python 3.13+ and that framework dependencies are correctly installed.
# 1. Clone the repository
git clone https://github.com/tahsin1017/LitReview-AI-2.0.git
cd LitReview-AI-2.0

# 2. Install the core Google Agent Development Kit framework
pip install google-adk

# 3. Configure environment variables (Using environment control to protect secrets)
export GEMINI_API_KEY="your_api_key_here"

# 4. Run the validation pipeline locally
python main.py


🎥 System Walkthrough & Output Verification
A 45-second execution walkthrough demonstrating code compilation, pipeline instantiation, and terminal logs is available here:

👉 Watch the Live Demo Pipeline Execution on YouTube

🎓 Academic Citations & Project Genesis
This framework was developed as a production-grade multi-agent architectural implementation for the Google AI Agents: Intensive Vibe Coding Capstone Project (June 2026).
@software{Rafi_LitReview_AI_2026,
  author = {Tahsin Ahmed Rafi},
  title = {LitReview-AI 2.0: Multi-Agent Research Gap Discovery Framework},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub Repository},
  url = {https://github.com/tahsin1017/LitReview-AI-2.0}
}
