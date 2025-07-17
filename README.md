# TEXT-SUMMARIZATION-TOOL

COMPANY: CODTECH IT SOLUTIONS PVT.LTD

NAME : PATEL SOHAM VIKRAMBHAI

INTERN ID:CT04DG2984

DOMAIN : Artificial Intelligence

DURATION : 4 WEEKS

MENTOR: NEELA SANTOSH

# 📝 Simple Text Summarizer using LangChain + Ollama (Phi-3)

This repository contains a minimal yet powerful Python-based application that performs **automatic text summarization** using a **local language model (LLM)** via [Ollama](https://ollama.com/) and the [LangChain](https://www.langchain.com/) framework. It leverages the **Phi-3** language model, one of the most efficient and compact open-source models, to summarize long pieces of text into concise, human-readable summaries. This solution is lightweight, easy to run locally, and ideal for research, education, or integration into larger AI workflows.

---

## 🧠 Project Description

As the volume of digital content continues to grow, the ability to quickly extract meaningful information from long documents becomes increasingly important. Whether you're dealing with research papers, news articles, documentation, or reports, summarization helps reduce cognitive overload by presenting the essential information in a shorter form.

This project demonstrates a **local-first AI solution** that achieves this goal by combining the **Phi-3 language model** running via **Ollama** and **LangChain’s prompt orchestration** features. The script is highly readable and acts as a great starting point for developers, students, and researchers who want to:

- Build custom summarization workflows.
- Learn how to run LLMs locally with minimal setup.
- Avoid cloud dependency and keep data private.

The application flow is simple:
1. A long input text is passed to the summarization function.
2. A prompt is dynamically constructed using LangChain’s `PromptTemplate` to ask the model to summarize the text in a specific word count.
3. The prompt is fed to the locally running **Phi-3** model via `Ollama`.
4. The model returns a summary, which is printed out or returned for further use.

The project avoids sending data to cloud APIs, making it **privacy-friendly**, **cost-effective**, and suitable for **offline environments** like research labs, local servers, or edge devices.

---

## Output: -

<img width="1778" height="663" alt="Image" src="https://github.com/user-attachments/assets/526d193b-e8bc-4cf6-820f-446040fc0e45" />


