#  Free LLM Integration with Groq API & Hugging Face

##  Project Overview

This project demonstrates how to integrate **Large Language Models (LLMs)** into applications **for free** using two powerful platforms:

- **Groq Cloud API**
- **Hugging Face**

The project is composed of **two Jupyter notebooks**, each showing a different way to use AI models in applications without paid subscriptions.
The main goal is to **find, test, and integrate free AI models** that can be used in real projects.

# [Groq_Api.ipynb](Groq_Api.ipynb)


##  Overview

This notebook demonstrates how to integrate a **Large Language Model (LLM)** into an application using the **Groq Cloud API**.

The focus of this notebook is to show how developers can **use powerful AI models for free** by leveraging Groq’s cloud-based infrastructure and API.

---

## What is Groq?

**Groq** is a company that builds high-performance **AI acceleration platforms** and provides a **cloud API** that allows developers to run large language models with extremely fast inference.

Groq offers a **free API tier**, making it possible to experiment with and integrate AI models into applications at no cost.

---

##  Objective

The objectives of this notebook are:

- Integrate a language model using the Groq API
- Demonstrate free access to LLMs through Groq
- Clean and format model outputs
- Present results in a readable Markdown format

---

##  Libraries Used

The following Python libraries are used in this notebook:

- **`groq`**  
  Used to connect to and interact with the Groq Cloud API.

- **`re`**  
  Used to remove or substitute unwanted `<think></think>` tags from the model output.

- **`IPython.display.Markdown`**  
  Used to render the model responses in a clean and readable Markdown format inside the notebook.

---

## Workflow

1. Initialize the Groq client
2. Send prompts to the selected model
3. Receive the model response
4. Clean the output by removing `<think></think>` sections
5. Display the final response using Markdown formatting

---
#  [Llama.ipynb](Llama.ipynb)

##  Overview

This notebook demonstrates how to use a **LLaMA-based language model** from **Hugging Face**.

Hugging Face provides access to a wide collection of **free and open-source models**, allowing developers to integrate powerful AI capabilities into their applications without paid APIs.

---

## What’s Used

- A **LLaMA model** hosted on Hugging Face
- Hugging Face libraries for model loading and inference

---

##  Purpose

- Use an open-source LLM for free
- Run and test models locally or in a notebook
- Explore Hugging Face as an alternative to API-based solutions

---

##  Key Takeaway

Hugging Face enables **free, flexible, and open** access to modern language models, making it ideal for experimentation and learning.



