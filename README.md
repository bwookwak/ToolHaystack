# ToolHaystack: Stress-Testing Tool-Augmented Language Models in Realistic Long-Term Interactions
[![PDF](https://img.shields.io/badge/PDF-Preprint-red?logo=arxiv)](https://arxiv.org/pdf/2505.23662)
[![Dataset](https://img.shields.io/badge/Dataset-HuggingFace-informational?logo=huggingface)](https://huggingface.co/datasets/LangAGI-Lab/WebPRMCollection_preference_pair)

ToolHaystack is the **first test suites for long-term tool utilization** featured by composable and noisy agent context. It provides three main scenarios that rigorously evaluate the necessary capabilities of TALMs in long-term interaction scenario.


**[NOTE]** The evaluation scripts and code for dataset generation pipeline will be updated soon. Stay tuned!

---

## 🚀 Overview

Recent Tool-Augmented Language Model (TALM) benchmarks have led the rapid growth of language model agents but are limited to single or short-turn scenarios. To tackle this, we propose **ToolHaystack benchmark which evaluates TALMs in a long and multi-task interleaved context** where contextual noise distracts TALMs significantly.

<p align="center">
  <img src="assets/github_main.png" alt="" width="100%"/>
</p>


---

## Dataset: ToolHaystack

The ToolHaystack dataset is available at 🤗 huggingface(https://huggingface.co/datasets/LangAGI-Lab/ToolHaystack)

<p align="center">
  <img src="assets/data_pipeline.png" alt="" width="100%"/>
</p>


### Scenarios
ToolHaystack provides three main scenarios (**Context Recall, Information Shift, Missing Context**) that requires robust long-term context understanding of TALMs.

<p align="center">
  <img src="assets/scenarios.png" alt="" width="100%"/>
</p>


