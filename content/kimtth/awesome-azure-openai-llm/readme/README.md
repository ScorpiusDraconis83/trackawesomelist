# Awesome Azure Openai Llm Overview

a curated list of 🔎Azure OpenAI, 🦙Large Language Models, and 🌌 references with 🎋notes.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/kimtth/awesome-azure-openai-llm/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 kimtth/awesome-azure-openai-llm](https://github.com/kimtth/awesome-azure-openai-llm) · ⭐ 331 · 🏷️ LLM

[ [Daily](/content/kimtth/awesome-azure-openai-llm/README.md) / [Weekly](/content/kimtth/awesome-azure-openai-llm/week/README.md) / Overview ]

---

# Azure OpenAI + LLM (Large Language Model)

![Static Badge](https://img.shields.io/badge/llm-azure_openai-blue?style=flat-square) <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a> ![GitHub Created At](https://img.shields.io/github/created-at/kimtth/awesome-azure-openai-llm?style=flat-square)

This repository contains references to Azure OpenAI, Large Language Models (LLM), and related services and libraries.

🔹Brief each item on a few lines as possible. <br/>
🔹The dates are determined by the date of the commit history, the Article published date, or the Paper v1 issued date. <br/>
🔹Capturing a chronicle and key terms of that rapidly advancing field. <br/>
🔹Disclaimer: Please be aware that some content may be outdated.

## Table of contents

*   **Section 1** 🎯: [RAG](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#rag-retrieval-augmented-generation)
    *   [RAG (Retrieval-Augmented Generation)](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#what-is-the-rag-retrieval-augmented-generation)
    *   [RAG Design & Application](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#advanced-rag)
    *   [LlamaIndex](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#llamaindex)
    *   [Vector DB](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/rag.md/#vector-database-comparison)
*   **Section 2** 🌌: [Azure OpenAI](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/aoai.md/#azure-openai-and-reference-architecture)
    *   [Microsoft LLM Framework](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/aoai.md/#microsoft-azure-openai-relevant-llm-framework)
    *   [Copilot Products & Azure OpenAI Service](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/aoai.md/#copilot-products)
    *   [Azure Reference Architecture](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/aoai.md/#azure-reference-architectures)
*   **Section 3** 🌐: [LLM Applications](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/app.md/#applications-and-frameworks)
    *   [LLM Frameworks & Applications](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/app.md/#applications-frameworks-and-user-interface-uiux)
    *   [Caching, UX, Proposals & Other topics](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/app.md/#caching)
    *   [LLMs for Robotics](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/app.md/#llm-for-robotics-bridging-ai-and-robotics)
    *   [Awesome demo](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/app.md/#awesome-demo)
*   **Section 4** 🤖: [Agent](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent.md/#agent)
    *   [Agent Design Patterns](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent.md/#agent-design-patterns)
    *   [Agent Frameworks & Applications](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/agent.md/#agent-framework)
*   **Section 5** 🏗️: [Semantic Kernel & DSPy](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/sk_dspy.md/#microsoft-semantic-kernel-and-stanford-nlp-dspy)
    *   [Semantic Kernel](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/sk_dspy.md/#semantic-kernel): Micro-orchestration
    *   [DSPy](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/sk_dspy.md/#dspy): Optimizer frameworks
*   **Section 6** 🛠️: [LangChain](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/langchain.md/#langchain-features-usage-and-comparisons)
    *   [LangChain Features](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/langchain.md/#langchain-feature-matrix--cheetsheet): Macro & Micro-orchestration
    *   [LangChain Agent & Criticism](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/langchain.md/#langchain-chain-type-chains--summarizer)
    *   [LangChain vs Competitors](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/langchain.md/#langchain-vs-competitors)
*   **Section 7** 🧠: [Prompting & Finetuning](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#prompt-engineering-finetuning-and-visual-prompts)
    *   [Prompt Engineering](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#prompt-engineering)
    *   [Finetuning](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#finetuning): PEFT (e.g., LoRA), RLHF, SFT
    *   [Quantization & Optimization](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#quantization-techniques)
    *   [Other Techniques](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#other-techniques-and-llm-patterns): e.g., MoE
    *   [Visual Prompting](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/prompt_ft.md/#visual-prompting--visual-grounding)
*   **Section 8** 🏄‍♂️: [Challenges & Abilities](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#large-language-model-challenges-and-solutions)
    *   [AGI Discussion](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#agi-discussion)
    *   [OpenAI Products & Roadmap](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#openais-roadmap-and-products)
    *   [Context Constraints](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#context-constraints): e.g., RoPE
    *   [Trust & Safety](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#trustworthy-safe-and-secure-llm)
    *   [LLM Abilities](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/chab.md/#large-language-model-is-abilities)
*   **Section 9** 🌍: [LLM Landscape](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#large-language-model-landscape)
    *   [LLM Taxonomy](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#large-language-models-in-2023)
    *   [Open-Source LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#open-source-large-language-models)
    *   [Domain-Specific LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#llm-for-domain-specific): e.g., Software development
    *   [Multimodal LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#mllm-multimodal-large-language-model)
    *   [Generative AI Landscape](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/llm.md/#generative-ai-landscape)
*   **Section 10** 📚: [Surveys & References](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/survey_ref.md/#survey-and-reference)
    *   [LLM Surveys](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/survey_ref.md/#survey-on-large-language-models)
    *   [Building LLMs](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/survey_ref.md/#build-an-llms-from-scratch-picogpt-and-lit-gpt): from scratch
    *   [LLMs for Korean & Japanese](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/survey_ref.md/#llm-materials-for-east-asian-languages)
*   **Section 11** 🧰: [AI Tools & Extensions](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/ai_tool.md/#general-ai-tools-and-extensions)
    *   [AI Tools & Extensions](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/ai_tool.md/#section-10-general-ai-tools-and-extensions)
*   **Section 12** 📊: [Datasets](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/dataset.md/#section-11-datasets-for-llm-training)
    *   [LLM Training Datasets](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/dataset.md/#datasets-for-llm-training)
*   **Section 13** 📝: [Evaluations](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/eval.md/#section-12-evaluating-large-language-models--llmops)
    *   [LLM Evaluation & LLMOps](https://github.com/kimtth/awesome-azure-openai-llm/blob/main/README.md/section/eval.md/#evaluating-large-language-models--llmops)
*   **Contributors** 👀:
    *   [Contributors](#contributors)
*   **Symbols** 🔑:
    *   `ref`: external URL
    *   `doc`: archived doc
    *   `cite`: the source of comments
    *   `cnt`: number of citations
    *   `git`: GitHub link
    *   `x-ref`: Cross reference
    *   📺: youtube or video

## **Contributors**

<a href="https://github.com/kimtth/awesome-azure-openai-llm/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kimtth/awesome-azure-openai-llm" />
</a>

ⓒ `https://github.com/kimtth` all rights reserved.

