# LLM Hosting

Ollama, llama.cpp, vLLM, Docker Model Runner, and the frontends in front of them.

Section page: [LLM Hosting in 2026: Local, Self-Hosted and Cloud Infrastructure Compared](https://www.glukhov.org/llm-hosting/)

[Index of all sections](README.md)

## Comparisons

- [Docker Model Runner vs Ollama: Which to Choose?](https://www.glukhov.org/llm-hosting/comparisons/docker-model-runner-vs-ollama-comparison/) — Compare Docker's new Model Runner with Ollama for local LLM deployment. Detailed analysis of performance, ease of use, GPU support, API compatibility, and when to choose each solution for your AI workflow in 2025.
- [llama.cpp vs Ollama in 2026: Which Runtime Should You Run?](https://www.glukhov.org/llm-hosting/comparisons/llama-cpp-vs-ollama/) — Compare llama-server and Ollama for local LLM hosting in 2026: GGUF management, APIs, GPU control, KV cache, model lifetime, and migration triggers.
- [Local LLM Hosting: Complete 2025 Guide - Ollama, vLLM, LocalAI, Jan, LM Studio & More](https://www.glukhov.org/llm-hosting/comparisons/hosting-llms-ollama-localai-jan-lmstudio-vllm-comparison/) — Comprehensive comparison of 12+ local LLM tools: Ollama, vLLM, LocalAI, Jan, LM Studio, Lemonade, Msty & more. API maturity, tool calling, GGUF support, benchmarks.
- [Ollama to vLLM: When to Migrate Your Local LLM Server](https://www.glukhov.org/llm-hosting/comparisons/ollama-to-vllm-migration/) — Learn when to migrate from Ollama to vLLM. Migration signals, planning steps, Docker Compose setup, and a practical checklist for moving your local LLM server.
- [ROCm vs Vulkan for AMD Local LLM Hosting: 2026 Guide](https://www.glukhov.org/llm-hosting/comparisons/amd-rocm-vs-vulkan-llm-hosting/) — Compare AMD ROCm and Vulkan backends for llama.cpp, Ollama, LM Studio, vLLM and TGI, with build commands, verification checks and a practical 2026 verdict.

## Ollama

- [Comparison of Hugo Page Translation quality - LLMs on Ollama](https://www.glukhov.org/llm-hosting/ollama/translation-quality-comparison-llms-on-ollama/) — qwen3 8b, qwen3 14b, qwen3 30b, devstral 24b and mistral small 24b
- [First Signs of Ollama Enshittification](https://www.glukhov.org/llm-hosting/ollama/ollama-enshittification/) — Overview of the First Signs of Ollama Enshittification
- [Go SDKs for Ollama - overview with examples](https://www.glukhov.org/llm-hosting/ollama/using-ollama-in-go/) — Go clients for Ollama: SDK comparison and Qwen3/GPT-OSS examples
- [Integrating Ollama with Python: REST API and Python Client Examples](https://www.glukhov.org/llm-hosting/ollama/ollama-python-examples/) — Learn how to connect your Python applications to Ollama using both the REST API and the official Python client — with examples for chat, text generation, and 'thinking' models like qwen3.
- [Move Ollama Models to Different Drive or Folder](https://www.glukhov.org/llm-hosting/ollama/move-ollama-models/) — Describes Ollama Model location on Ubuntu and Windows and how to move this Ollama Bin and Model Directory to different folder
- [Ollama behind a reverse proxy with Caddy or Nginx for HTTPS streaming](https://www.glukhov.org/llm-hosting/ollama/ollama-behind-reverse-proxy/) — Expose Ollama securely behind Caddy or Nginx with automated HTTPS, optional Basic Auth or SSO front gates, and correct streaming and WebSocket proxying.
- [Ollama CLI Cheatsheet: ls, serve, run, ps + commands (2026 update)](https://www.glukhov.org/llm-hosting/ollama/ollama-cheatsheet/) — Ollama CLI cheatsheet: ollama serve command, ollama run command examples, ollama ps, and model management.
- [Ollama in Docker Compose with GPU and Persistent Model Storage](https://www.glukhov.org/llm-hosting/ollama/ollama-in-docker-compose/) — Run Ollama as a reproducible single-node LLM server using Docker Compose. Configure OLLAMA_HOST and OLLAMA_MODELS, keep models on persistent volumes, enable NVIDIA GPUs, and upgrade safely with rollbacks.
- [Remote Ollama access via Tailscale or WireGuard, no public ports](https://www.glukhov.org/llm-hosting/ollama/ollama-remote-access/) — Patterns for running Ollama on a home lab or office box and reaching it safely from remote devices. Covers OLLAMA_HOST binding, Tailscale or WireGuard, firewall pinning, and a tight security checklist.
- [Testing Deepseek-r1 on Ollama](https://www.glukhov.org/llm-hosting/ollama/deepseek-r1-on-ollama/) — deepseek-r1 on ollama
- [Using Ollama Web Search API in Go](https://www.glukhov.org/llm-hosting/ollama/ollama-web-search-in-go/) — Master Ollama's native Web Search API with Go. Learn to implement web_search and web_fetch, build intelligent search agents with tool calling, and create production-ready Go applications with complete code examples.
- [Using Ollama Web Search API in Python](https://www.glukhov.org/llm-hosting/ollama/ollama-web-search-in-python/) — Master Ollama's native Web Search API with Python. Learn to use web_search and web_fetch functions, build intelligent search agents with tool calling, and integrate with MCP servers for Cline and Codex.

## llama.cpp

- [llama.cpp Quickstart with CLI and Server](https://www.glukhov.org/llm-hosting/llama-cpp/) — Install llama.cpp, run GGUF models with llama-cli, and serve OpenAI-compatible APIs using llama-server. Key flags, examples, and tuning tips with a short commands cheatsheet
- [Llama-Server Router Mode - Dynamic Model Switching Without Restarts](https://www.glukhov.org/llm-hosting/llama-cpp/llama-server-router-mode/) — How to configure llama-server router mode for dynamic model loading and switching. Covers models.ini setup, systemd service, API usage, and honest comparison to Ollama and llama-swap.
- [Unload All llama.cpp Router Models Without Restarting](https://www.glukhov.org/llm-hosting/llama-cpp/unload-llama-cpp-router-models/) — Learn how to unload every loaded llama.cpp router model with curl and jq, free VRAM safely, and avoid restarting llama-server in local LLM workflows.

## vLLM

- [vLLM Quickstart: High-Performance LLM Serving](https://www.glukhov.org/llm-hosting/vllm/vllm-quickstart/) — Complete vLLM setup guide with Docker, OpenAI API compatibility, PagedAttention optimization. Compare vLLM vs Ollama vs Docker Model Runner for production.

## Docker Model Runner

- [Adding NVIDIA GPU Support to Docker Model Runner](https://www.glukhov.org/llm-hosting/docker-model-runner/adding-nvidia-gpu-support-to-docker-model-runner/) — Complete guide to enable NVIDIA GPU acceleration for Docker Model Runner. Step-by-step instructions for configuring CUDA support, Docker daemon settings, and verifying GPU usage for AI model inference.
- [Docker Model Runner Cheatsheet: Commands & Examples](https://www.glukhov.org/llm-hosting/docker-model-runner/docker-model-runner-cheatsheet/) — Docker Model Runner cheatsheet with commands, examples, and best practices. Learn docker model pull, run, package, and configuration options for deploying AI models locally with Docker's official LLM tool.
- [Docker Model Runner: Context Size Config Guide](https://www.glukhov.org/llm-hosting/docker-model-runner/context-size-in-docker-model-runner/) — Complete guide to configuring context sizes in Docker Model Runner. Learn workarounds for docker-compose limitations, using docker model configure, and packaging models with custom context sizes.

## LLM frontends

- [Choosing Best LLM for Perplexica](https://www.glukhov.org/llm-hosting/llm-frontends/perplexica-best-llm/) — Which model llama3.1, mistral nemo, mistral large, mixtral, gemma2, qwen2, phi3 command-r - for Perplexica
- [Farfalle vs Perplexica - selfhosted AI search engines](https://www.glukhov.org/llm-hosting/llm-frontends/farfalle-vs-perplexica/) — Comparing Farfalle and Perplexica - UI, content generation and prompts effectiveness
- [Open WebUI: Self-Hosted LLM Interface](https://www.glukhov.org/llm-hosting/llm-frontends/open-webui-overview-quickstart-and-alternatives/) — Complete guide to Open WebUI: a powerful self-hosted web interface for Ollama and OpenAI-compatible APIs with RAG, multi-user auth, and Docker deployment.
- [Open-Source Chat UIs for LLMs on Local Ollama Instances](https://www.glukhov.org/llm-hosting/llm-frontends/chat-ui-for-local-ollama-llms/) — Open WebUI, Page Assist, AnythingLLM and others
- [Self-hosting Perplexica - with Ollama](https://www.glukhov.org/llm-hosting/llm-frontends/selfhosting-perplexica-ollama/) — Install and configure Perplexica with Ollama
- [Vane (Perplexica 2.0) Quickstart With Ollama and llama.cpp](https://www.glukhov.org/llm-hosting/llm-frontends/vane-perplexica-2/) — Self-host Vane (Perplexica 2.0) with Docker, wire it to SearxNG, and use local LLMs via Ollama or llama.cpp. History, features, API.

## Self-hosting

- [Data Gravity: The Real Cost of API-First AI](https://www.glukhov.org/llm-hosting/self-hosting/data-gravity-ai-vendor-lockin/) — Data gravity is the force pulling AI workflows toward one provider. The four-stage lock-in mechanism, a scoring checklist, and how to stay portable.
- [LLM Self-Hosting and AI Sovereignty](https://www.glukhov.org/llm-hosting/self-hosting/llm-selfhosting-and-ai-sovereignty/) — Why and how self-hosted LLMs support AI sovereignty: control, data residency, and compliance for orgs and nations.

## Cloud

- [Cloud LLM Providers](https://www.glukhov.org/llm-hosting/cloud/cloud-llm-providers/)

## Other runtimes

- [llama.swap Model Switcher Quickstart for OpenAI-Compatible Local LLMs](https://www.glukhov.org/llm-hosting/llama-swap/) — Install and configure llama-swap (llama.swap), hot-swap local models via OpenAI or Anthropic APIs, compare with Ollama and LM Studio, and troubleshoot common errors.
- [LocalAI QuickStart: Run OpenAI-Compatible LLMs Locally](https://www.glukhov.org/llm-hosting/local-ai/) — Learn to install LocalAI, load models from the gallery or Hugging Face, and serve an OpenAI-compatible API plus Web UI for chat, embeddings, images and audio on your own hardware.
- [SGLang QuickStart: Install, Configure, and Serve LLMs via OpenAI API](https://www.glukhov.org/llm-hosting/sglang/) — Install SGLang with uv, pip, or Docker; configure YAML and server flags; then serve Hugging Face LLMs with an OpenAI-compatible API plus native /generate and offline Engine examples.
- [TGI - Text Generation Inference - Install, Config, Troubleshoot](https://www.glukhov.org/llm-hosting/tgi/) — A practical guide to installing Hugging Face TGI, launching your first LLM endpoint, tuning key flags, and fixing the failures you will meet.
