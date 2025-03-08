+++
title = "Build Your Own Perplexity AI Using Ollama and Msty"
date = "2025-03-08T15:25:19+05:30"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = "Pawan"
authorTwitter = "pawanadubey" #do not include @
cover = ""
tags = ["", ""]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
+++

Perplexity is an AI-powered search engine that provides answers by referring to internet sources. It allows users to switch between different large language models (LLMs) to process and generate responses. However, switching models is only available in the Pro version.

If you want a similar solution that runs on your own machine, you can use **Ollama** and **Msty**. This will allow you to have a **custom AI assistant** that can work locally and access the internet when needed.

---

## What is Ollama?

**Ollama** is a tool that lets you **download and run LLM models** locally on your machine. It provides a simple way to work with AI models without needing cloud-based services.

### Installing Ollama

To install Ollama:

1. Go to [Ollama’s official website](https://ollama.com/download).
2. Download the setup file for your operating system.
3. Install it following the on-screen instructions.

Once installed, you can check all the available models at [Ollama’s model library](https://ollama.com/library). Some popular models include:

- **Llama 3**
- **Mistral**
- **DeepSeek**
- **Phi 4**

### Running an AI Model with Ollama

To download and run **Llama 3**, use the following command in your terminal or command prompt:

```sh
ollama run llama3
```

Similarly, you can install and run other models using their respective names.

### Using Ollama with an API

By default, Ollama runs in the **command-line interface (CLI)**, but it also provides an **API** for developers. You can start the API server with:

```sh
ollama serve
```

This allows applications to communicate with your local AI model. You can find the full API guide [here](https://github.com/ollama/ollama/blob/main/docs/api.md).

---

## What is Msty?

**Msty** is a desktop application that provides a **user-friendly interface** to interact with AI models. It supports both local and online AI models and also allows them to access the internet.

### Installing Msty

To install Msty:

1. Visit [Msty’s official download page](https://docs.msty.app/getting-started/download).
2. Download the installer for your operating system.
3. Install it by following the instructions.

### Using Msty

Once installed, open Msty, and you will see a user interface similar to **Perplexity AI**. Msty allows you to:

- Switch between **different local AI models** (e.g., Llama 3, Mistral).
- **Enable internet access** for AI models to fetch external information.
- Adjust **temperature, max output tokens, and context window size** for better control over AI responses.

---

## Conclusion

By combining **Ollama** and **Msty**, you can create a **powerful AI assistant** that runs on your own machine, similar to Perplexity AI. Ollama lets you run AI models locally, while Msty provides an easy-to-use interface and internet access for better answers.

If you are interested in AI but want more control over **models, privacy, and cost**, this setup is a great alternative. Try it out and build your own AI-powered assistant!