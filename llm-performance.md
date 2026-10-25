# LLM Performance

Benchmarks, VRAM limits, and inference tuning.

Section page: [LLM Performance in 2026: Benchmarks, Bottlenecks & Optimization](https://www.glukhov.org/llm-performance/)

[Index of all sections](README.md)

## Benchmarks

- [16 GB VRAM LLM benchmarks with llama.cpp (speed and context)](https://www.glukhov.org/llm-performance/benchmarks/best-llm-on-16gb-vram-gpu/) — Compare llama.cpp speeds on a 16 GB GPU for dense and MoE models at 19K, 32K, and 64K context. Tables list VRAM, GPU load, and tokens per second.
- [Agentic LLM Inference Parameters Reference for Qwen 3.6 and Gemma 4](https://www.glukhov.org/llm-performance/benchmarks/agentic-inference-parameters-reference/) — Curated reference of vendor and community inference parameters for Qwen 3.6 and Gemma 4, optimized for agentic workflows and real-world coding systems.
- [BAML vs Instructor: Structured LLM Outputs](https://www.glukhov.org/llm-performance/benchmarks/baml-vs-instruct-for-structured-output-llm-in-python/) — Compare BAML and Instructor frameworks for type-safe structured outputs from LLMs in Python. Learn implementation patterns, performance, and best practices.
- [Comparing LLM Summarising Abilities](https://www.glukhov.org/llm-performance/benchmarks/llm-summarising-comparison/) — LLM Summarising Abilities: llama3 vs phi3
- [Comparing LLMs performance on Ollama on 16GB VRAM GPU](https://www.glukhov.org/llm-performance/benchmarks/choosing-best-llm-for-ollama-on-16gb-vram-gpu/) — Benchmark of 9 LLMs on RTX 4080 16GB with Ollama 0.15.2. Compare tokens/sec, VRAM usage, and CPU offloading for GPT-OSS, Qwen3, Mistral, and more.
- [Comparing NVidia GPU specs suitability for AI](https://www.glukhov.org/llm-performance/benchmarks/comparing-nvidia-gpu-for-ai/)
- [LLM speed performance comparison](https://www.glukhov.org/llm-performance/benchmarks/llms-speed-cpu-vs-gpu/) — Logical Fallacy AI Large Language Models (LLMs) Speed
- [LLM Structured Output Validation in Python That Holds Up](https://www.glukhov.org/llm-performance/benchmarks/llm-structured-output-validation-python/) — Validate LLM JSON in Python with JSON Schema and Pydantic, handle fences and tool args, add repair retries, tests, and production-safe failure handling.
- [LLMs Comparison: Qwen3:30b vs GPT-OSS:20b](https://www.glukhov.org/llm-performance/benchmarks/qwen3-30b-vs-gpt-oss-20b/) — Qwen3:30b vs GPT-OSS:20b: Technical details, performance and speed comparison
- [Logical Fallacy Detection with new LLMs: Gemma2, Qwen2 and MistralNemo](https://www.glukhov.org/llm-performance/benchmarks/gemma2-qwen2-mistral-nemo12b/) — Comparing logical fallacy detection with Gemma2, Qwen2 and Mistral Nemo12b
- [New LLMs comparison - Mistral Small, Gemma 2, Qwen 2.5, Mistral Nemo, LLama3 and Phi](https://www.glukhov.org/llm-performance/benchmarks/mistral-small-gemma2-qwen2-5-mistral-nemo/) — Mistral Small, Gemma 2, Qwen 2.5, Mistral Nemo, LLama3 and Phi - LLM Test comparison
- [NVIDIA DGX Spark vs Mac Studio vs RTX-4080: Ollama Performance Comparison](https://www.glukhov.org/llm-performance/benchmarks/dgx-spark-vs-mac-studio-vs-rtx4080/) — Real-world Ollama performance comparison running GPT-OSS 120b (a 117B parameter MoE model with 5.1B active parameters) across NVIDIA DGX Spark, Mac Studio, and RTX 4080.
- [Qwen 3.6 27B and 35B MTP vs Standard on 16GB GPU](https://www.glukhov.org/llm-performance/benchmarks/comparing-qwen-3-6-mtp-vs-standard/) — Benchmark results for Qwen 3.6 27B and 35B MTP speculative decoding in llama.cpp on RTX 4080 16GB. Token speed, VRAM cost, and optimal --spec-draft-n-max settings.
- [Structured output comparison across popular LLM providers - OpenAI, Gemini, Anthropic, Mistral and AWS Bedrock](https://www.glukhov.org/llm-performance/benchmarks/structured-output-comparison-popular-llm-providers/) — Comparison of Structured output control across popular LLM providers - OpenAI, Gemini, Anthropic, Mistral and AWS Bedrock - with examples in Python
- [The Efficient Frontier of Open Models: Finding the Sweet Spot in 2026](https://www.glukhov.org/llm-performance/benchmarks/efficient-frontier-of-open-models-2026/) — In 2026 the open-model efficient frontier sits at 25-34B: Qwen 3.8 27B and Llama 4 Scout deliver near-frontier capability at a fraction of 70B+ cost.

## Optimization

- [KV Cache on 16 GB GPUs: Making Long Context Actually Fit](https://www.glukhov.org/llm-performance/optimization/kv-cache-16gb-long-context/) — Fit 32K to 128K LLM context into 16 GB VRAM by calculating KV cache cost, choosing cache precision, and tuning llama.cpp, vLLM, or Ollama safely.
- [Speculative Decoding: 20-50% Faster LLM Inference](https://www.glukhov.org/llm-performance/optimization/speculative-decoding/) — Speculative decoding speeds up LLM inference 20-50% with zero quality loss. Draft-verify mechanics, EAGLE-3, P-EAGLE, n-gram, MTP, and setup for llama.cpp, vLLM, SGLang, TensorRT-LLM.

## Hardware

- [LLM Performance and PCIe Lanes: Key Considerations](https://www.glukhov.org/llm-performance/hardware/llm-performance-and-pci-lanes/)
- [The Rise of LLM ASICs: Why Inference Hardware Matters](https://www.glukhov.org/llm-performance/hardware/llm-asics/) — Exploring how specialized inference chips are revolutionizing AI deployment with 10-50× better performance per watt than GPUs, featuring real benchmarks and architectural insights into the future of LLM hardware.

## Ollama

- [How Ollama Handles Parallel Requests](https://www.glukhov.org/llm-performance/ollama/how-ollama-handles-parallel-requests/)
- [How Ollama is using Intel CPU Performance and Efficient Cores](https://www.glukhov.org/llm-performance/ollama/ollama-cpu-cores-usage/) — Test: How Ollama is using Intel CPU Performance and Efficient Cores
- [LLMs with Structured Output: Ollama, Qwen3 & Python or Go](https://www.glukhov.org/llm-performance/ollama/llm-structured-output-with-ollama-in-python-and-go/) — Constraining LLMs with Structured Output — Using Ollama and Qwen3 with examples in Python and Go
- [Memory allocation and model scheduling in Ollama new version - v0.12.1](https://www.glukhov.org/llm-performance/ollama/memory-allocation-in-ollama-new-version/) — Comparison of Memory allocation and model scheduling in new version of Ollama - v0.12.1 vs the previous version
- [Ollama GPT-OSS Structured Output Issues](https://www.glukhov.org/llm-performance/ollama/ollama-gpt-oss-structured-output-issues/) — Ollama GPT-OSS has Structured Output Issues

## Cost

- [Reduce LLM Costs: Token Optimization Strategies](https://www.glukhov.org/llm-performance/cost-effective-llm-applications/) — Howto use token optimization techniques to reduce LLM API costs by up to 80%. Learn prompt compression, caching, batching, and smart model selection strategies for cost-effective AI applications.

## Still at /post/

These pages are still published at the original dated URL.

### Logical fallacy detection

- [Logical Fallacy Detection with LLMs](https://www.glukhov.org/post/2024/05/logical-fallacy-detection-with-llms/) — Comparing different LLMs for detecting Logical Fallacies: llama3 (Meta), phi3 (Microsoft), gemma (Google), Mistral Nemo(Mistral AI) and qwen(Alibaba)
