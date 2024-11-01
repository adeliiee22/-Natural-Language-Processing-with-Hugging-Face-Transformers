# NLP With HuggingFace Transformers

A collection of NLP pipelines using HuggingFace Transformers for various natural language processing tasks. Each pipeline provides unique insights and functionality, making it easier to explore different NLP applications in one place.

![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-red?logo=jupyter&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-orange?logo=huggingface&logoColor=white) ![Transformers](https://img.shields.io/badge/Transformers-yellow?logo=data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQwIDM4OCIgZmlsbD0iI0ZGNzQxRCIgZmlsbC1vcGFjaXR5PSIxIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGQ9Ik02NiA2NEgzMkM5IDE0IDAgNzQgMCAxNDhjMCA3NCA5IDEzNCAzMiAxODBoMzdMOTYgMzMyYy04LTgtMTYtMTUtMjUtMjEtNi0zLTEyLTYtMTgtOS0xNi04LTM0LTEzLTUzLTEzLTggMC0xNiAxLTIzIDItOSAyLTIwIDUtMjggMTAtNyA1LTEzIDExLTE5IDE4LTQgMy04IDctMTIgMTAtNyA1LTEzIDEtMjAtMy0xMC01LTIwLTctMzAtOC0xNi0yMS0zMC00MS0zMy01OS0yLTQzLTE3LTczLTUyLTgzLTUgLTEtOC02LTEwLTEyLTgtMjYgMTEtNDcgMjUtNjUgNDAgLTYgNS0xMSAxMC0xNyAxNS0xNyAxNS0zNSAyNi01NCAzNC0xMiA1LTUgMjItNSAyOSAwIDggMCAxNyAwIDI1LTUgMCAxLTIgMS0yIDAtMTQgMi0yOSAzLTQzIDctMSAyLTIgMS00LTMtMTYtOS0yMy0yNy0xOC00MiAxMC0yNSAxNC00MCA0MC00OCA2My0yIDctOS0yMS0xOS0yMS01NiA1LTc4IDc2LTk5IDE1Mi00LTM1LTUtNzEtMi0xMDYgOC00MSAyNS04MCA1OC0xMTEgMzItMzIgNzEtNTAgMTExLTUyIDQyLTEgODAgMTggMTE2IDQ2IDIyIDIwIDQ0IDM4IDcwIDQ5IDQxIDE5IDgzIDMwIDEyNiAzNCAxNyAxIDM0IDMgNTEgNyAxNCAzIDMxIDcgNDYgNyAxMCAxNiAxOSA0IDM5IDQgNTggMCA1NSA2MSA2OCAxMDUgMSAyIDIgNSAzIDdsNTggNTljMCAxOS0xIDM3LTQgNTYtNCAyMi0xMCA0Mi0yMCA2My01IDEtOS0yLTE2LTYtMTgtMTItMTQtMjQtMjYtMzctMzktNCAzLTggNi0xMiA5LTggNy0xNyAxMi0yNiAxOC0yNiAxNy00OCAzOS03NiA2NC05MiAzNS0yMCA1MS00NSAzNi04Ny0xMS0yOSAxMS02MyA1Mi02MyAxMSAwIDIwIDMgMjkgN3oiLz48cGF0aCBkPSJNMTY4IDY0aC0zNGMyNSA0MiA0MSA5OCA0MSAxNTdoMzZ2LTJhMTQ3IDE0NyAwIDAgMC0zNy0xNTBaTTM2IDE5NmE4MCA4MCAwIDAgMC01NCAxNDJjOC0xNiAxOS0zMCAzMi00MiAxOS0xOSA0My0zMyA2OS00MkgzNloiLz48L3N2Zz4=) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)

## Analyses and Pipelines

This notebook explores a range of NLP tasks, each powered by specific HuggingFace Transformer models. Below is a summary of the pipelines and their potential applications.

---

### 1. Zero-Shot Classification
Zero-shot classification allows text categorization without the need for pre-training on specific categories. This method is incredibly useful in dynamic environments, such as customer feedback analysis or social media trend monitoring, where new or unexpected categories often emerge. By bypassing the need for custom training, zero-shot classification can accelerate deployment in production settings.

---

### 2. Text Generation
Text generation enables the creation of text based on specific inputs or prompts. This feature is versatile and creative, ideal for generating ideas, content, or interactive dialogues like chatbot responses. It can be valuable for content automation, brainstorming, and quickly prototyping text-based applications.

---

### 3. Custom Text Generation with Specific Model and Parameters
This variation of text generation uses a lighter model, such as DistilGPT2, with customizable response length and quantity. It's useful for virtual assistants or automated responses, where response diversity and efficiency are essential to maintaining engaging and non-repetitive interactions.

---

### 4. Fill-mask Pipeline
Fill-mask is an NLP technique for predicting missing words in a sentence, making it beneficial for tasks like autocorrection, sentence completion, and language exercises. This pipeline is especially relevant in educational tools or translation applications, where the model can help complete missing words or phrases based on context.

---

### 5. Named Entity Recognition (NER) Pipeline
NER identifies key entities in text, such as names, locations, or organizations, making it indispensable for data management systems that need to extract specific information from large documents. Automating data collection, such as identifying brands or product names in consumer reviews, becomes more efficient with NER.

---

### 6. Question-Answering Pipeline with Custom Context and Question
The question-answering (QA) pipeline extracts critical information from text by allowing users to ask questions within a given context. This functionality is particularly useful in applications that require automatic responses based on large documents or databases, enhancing information retrieval efficiency.

---

### 7. Sentiment Analysis Pipeline
Sentiment analysis helps understand emotions or sentiments in a given text, which is crucial in customer feedback analysis, like product reviews or social media comments. By categorizing text as positive or negative, it provides valuable insights into customer feelings or overall market trends.

---

### 8. Summarization Pipeline
The summarization pipeline condenses lengthy text into concise, informative summaries. It is ideal for summarizing news articles, reports, or business documents, saving time by transforming lengthy information into digestible summaries that are easier to understand.

---

### 9. Translation Pipeline (Indonesian to English)
The translation pipeline converts text from one language to another—in this case, from Indonesian to English. This is essential for applications requiring multilingual support, especially in contexts like global communication or industries engaging with international users.

---

