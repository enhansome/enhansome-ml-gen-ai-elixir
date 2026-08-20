<div align="center">

![Awesome ML & GenAI in Elixir logo](https://github.com/user-attachments/assets/19fc503d-1123-4785-b5b2-570b0377c4ba)

# Awesome ML & GenAI in Elixir with stars

A curated list of Machine Learning (ML) and Generative AI (GenAI) packages and resources for the [Elixir](https://elixir-lang.org/) programming language.

Besides giving an overview for experienced Elixir developers, this list can be useful for ML and AI practitioners looking for other ecosystems.

</div>
<br />

## Contents

* [Core Tools](#core-tools)
* [Machine Learning](#machine-learning)
  * [Traditional Machine Learning](#traditional-machine-learning)
  * [Deep Learning](#deep-learning)
  * [Computer Vision](#computer-vision)
  * [Vector Search & Similarity](#vector-search--similarity)
* [Generative AI](#generative-ai)
  * [LLM Tools](#llm-tools)
  * [Agent Frameworks](#agent-frameworks)
  * [Development Tools](#development-tools)
* [Livebooks & Examples](#livebooks--examples)
* [Resources](#resources)

## Core Tools

* [Nx](https://github.com/elixir-nx/nx) ⭐ 2,900 | 🐛 3 | 🌐 Elixir | 📅 2026-08-18 - Tensors for Elixir with compilation to CPU/GPU. It is the base for a lot of other libraries.
* [Explorer](https://github.com/elixir-explorer/explorer) ⭐ 1,292 | 🐛 56 | 🌐 Elixir | 📅 2026-08-09 - Series and dataframes for data exploration in Elixir.
* [Kino](https://github.com/livebook-dev/kino) ⭐ 451 | 🐛 7 | 🌐 Elixir | 📅 2026-06-18 - Render rich and interactive output. Used in Livebook.
* [Pythonx](https://github.com/livebook-dev/pythonx) ⭐ 315 | 🐛 3 | 🌐 Elixir | 📅 2026-05-18 - Embeds a Python interpreter directly into Elixir via NIF, running in the same OS process as the BEAM. Enables Elixir apps and Livebooks to call Python ML libraries directly.
* [Livebook](https://livebook.dev/) - Write interactive and collaborative notebooks, with integrations to databases, messaging, visualization and more.

## Machine Learning

### Traditional Machine Learning

* [Scholar](https://github.com/elixir-nx/scholar) ⭐ 496 | 🐛 12 | 🌐 Elixir | 📅 2026-08-17 - Traditional machine learning tools built on top of Nx. Implements algorithms for:
  * Classification
  * Regression
  * Clustering
  * Dimensionality reduction
  * Metrics and preprocessing
* [EXGBoost](https://github.com/acalejos/exgboost) ⭐ 186 | 🐛 10 | 🌐 Elixir | 📅 2024-06-08 - Decision Trees implemented using the [XGBoost C API](https://xgboost.readthedocs.io/en/latest/c.html).
* [Soothsayer](https://github.com/georgeguimaraes/soothsayer) ⭐ 139 | 🐛 5 | 🌐 Elixir | 📅 2026-06-24 - Time series forecasting library inspired by Facebook's Prophet and NeuralProphet.
* [Mockinjay](https://github.com/acalejos/mockingjay) ⭐ 75 | 🐛 1 | 🌐 Elixir | 📅 2023-09-02 - Implementation of Microsoft's [Hummingbird](https://github.com/microsoft/hummingbird) ⭐ 3,544 | 🐛 75 | 🌐 Python | 📅 2025-07-17 library for converting trained Decision Tree models into Nx tensor computations.
* [Ulam](https://github.com/tmbb/ulam_ex) ⭐ 10 | 🐛 0 | 🌐 HTML | 📅 2024-10-04 - Elixir interface to [Stan](https://mc-stan.org/), a probabilist programming language.

### Deep Learning

* [Axon](https://github.com/elixir-nx/axon) ⭐ 1,689 | 🐛 23 | 🌐 Elixir | 📅 2026-08-18 - Neural Networks for Elixir. Built with Nx.
* [Bumblebee](https://github.com/elixir-nx/bumblebee) ⭐ 1,663 | 🐛 33 | 🌐 Elixir | 📅 2026-08-19 - Pre-trained neural network models on top of Axon. Provides integration with [Hugging Face](https://huggingface.co/).
* [Ortex](https://github.com/elixir-nx/ortex) ⭐ 208 | 🐛 9 | 🌐 Elixir | 📅 2026-02-10 - Wrapper around ONNX. Enables you to run ONNX models using Nx.

### Computer Vision

* [Evision](https://github.com/cocoa-xu/evision) ⭐ 392 | 🐛 7 | 🌐 Elixir | 📅 2026-07-22 - OpenCV bindings for Elixir/Erlang.
* [YOLO](https://github.com/poeticoding/yolo_elixir) ⭐ 291 | 🐛 10 | 🌐 Elixir | 📅 2025-10-13 - Real-time object detection using YOLOv8 models with 38ms processing time and optional Rust NIF for performance.
* [NxImage](https://github.com/elixir-nx/nx_image) ⭐ 22 | 🐛 1 | 🌐 Elixir | 📅 2024-02-19 - Image processing in Nx.

### Vector Search & Similarity

* [ExFaiss](https://github.com/elixir-nx/ex_faiss) ⚠️ Archived - Elixir front-end to Facebook AI Similarity Search (Faiss) for efficient similarity search and clustering of dense vectors.
* [Stephen](https://github.com/georgeguimaraes/stephen) ⭐ 8 | 🐛 7 | 🌐 Elixir | 📅 2026-08-05 - ColBERT-style neural retrieval for Elixir.
* [Leidenfold](https://github.com/georgeguimaraes/leidenfold) ⭐ 5 | 🐛 5 | 🌐 Elixir | 📅 2026-06-23 - Elixir bindings for the Leiden community detection algorithm.

## Generative AI

### LLM Tools

* [Instructor.ex](https://github.com/thmsmlr/instructor_ex) ⭐ 783 | 🐛 41 | 🌐 Elixir | 📅 2025-06-07 - Structured outputs from LLMs using Ecto schemas. Works with OpenAI, llama.cpp and Bumblebee.
* [ReqLLM](https://github.com/agentjido/req_llm) ⭐ 564 | 🐛 2 | 🌐 Elixir | 📅 2026-08-19 - A Req-based package to call LLM APIs that standardizes the API calls and responses for LLM providers.
* [Arcana](https://github.com/georgeguimaraes/arcana) ⭐ 330 | 🐛 4 | 🌐 Elixir | 📅 2026-08-19 - Embeddable RAG library for Elixir/Phoenix with agentic pipelines and dashboard.
* [OpenAI.ex](https://github.com/cyberchitta/openai_ex) ⭐ 216 | 🐛 2 | 🌐 Elixir | 📅 2026-08-13 - OpenAI API client with streaming, file uploads, and Azure OpenAI support.
* [AshAi](https://github.com/ash-project/ash_ai) ⭐ 188 | 🐛 14 | 🌐 Elixir | 📅 2026-08-12 - Structured outputs, vectorization and tool calling for your Ash application with LangChain integration and MCP server capabilities.
* [InstructorLite](https://github.com/martosaur/instructor_lite) ⭐ 144 | 🐛 1 | 🌐 Elixir | 📅 2026-08-17 - Lightweight structured outputs for LLMs using JSON schemas with multi-provider support including OpenAI, Anthropic, and Gemini.
* [Ollama-ex](https://github.com/lebrunel/ollama-ex) ⭐ 139 | 🐛 1 | 🌐 Elixir | 📅 2026-02-10 - Elixir client for Ollama API with support for completions, chat, tools, and function calling.
* [TextChunker](https://github.com/revelrylabs/text_chunker_ex) ⭐ 110 | 🐛 9 | 🌐 Elixir | 📅 2026-08-18 - Semantic text chunking library optimized for vector embedding and RAG applications.
* [Tribunal](https://github.com/georgeguimaraes/tribunal) ⭐ 108 | 🐛 7 | 🌐 Elixir | 📅 2026-07-23 - LLM evaluation framework that provides tools for evaluating and testing LLM outputs, detecting hallucinations, and measuring response quality
* [Rag](https://github.com/bitcrowd/rag) ⭐ 102 | 🐛 7 | 🌐 Elixir | 📅 2025-05-12 - Library for building Retrieval Augmented Generation (RAG) systems with support for vector stores like pgvector and chroma.
* [ClaudeCode](https://github.com/guess/claude_code) ⭐ 94 | 🐛 2 | 🌐 Elixir | 📅 2026-06-05 - SDK for embedding Claude as an agentic AI in Elixir apps with tool calling and MCP integration.
* [Honeycomb](https://github.com/seanmor5/honeycomb) ⭐ 67 | 🐛 11 | 🌐 Elixir | 📅 2026-01-15 - Fast LLM inference service and library built on Elixir, Bumblebee, and EXLA with OpenAI API compatibility.
* [LLM Composer](https://github.com/doofinder/llm_composer) ⭐ 39 | 🐛 3 | 🌐 Elixir | 📅 2026-08-20 - Multi-provider LLM library with routing, fallback, streaming, and cost tracking for OpenAI, Anthropic, Gemini, and more.
* [Gemini.ex](https://github.com/nshkrdotcom/gemini_ex) ⭐ 35 | 🐛 0 | 🌐 Elixir | 📅 2026-08-11 - Elixir client for Google Gemini LLM supporting both AI Studio and Vertex AI.
* [JsonRemedy](https://github.com/nshkrdotcom/json_remedy) ⭐ 33 | 🐛 3 | 🌐 Elixir | 📅 2026-04-04 - JSON repair library for fixing malformed LLM outputs.
* [Mentor](https://github.com/zoedsoupe/mentor) ⭐ 22 | 🐛 6 | 🌐 Elixir | 📅 2025-07-18 - Library for generating validated structured outputs from LLMs with automatic retries and schema validation.
* [DSPEx](https://github.com/nshkrdotcom/ds_ex) ⭐ 18 | 🐛 1 | 🌐 Elixir | 📅 2026-04-09 - DSPy port for Elixir with data-driven prompt optimization.
* [Handwave](https://github.com/martosaur/handwave) ⭐ 10 | 🐛 0 | 🌐 Elixir | 📅 2026-06-03 - LLM-powered control flow for Elixir: conditional logic, text rewriting, and routing decisions via natural language rather than code.
* [Mistral](https://github.com/rodloboz/mistral) ⭐ 9 | 🐛 1 | 🌐 Elixir | 📅 2026-03-02 - Open-source Elixir client for the Mistral AI API covering chat completions, function calling, embeddings, streaming, OCR, fine-tuning, and batch processing.

### Agent Frameworks

* [Jido](https://github.com/agentjido/jido) ⭐ 1,809 | 🐛 4 | 🌐 Elixir | 📅 2026-08-19 - Framework for building autonomous, distributed agent systems with modular actions, stateful agents, and sensors. AI-framework agnostic.
* [LangChain](https://github.com/brainlid/langchain) ⭐ 1,196 | 🐛 30 | 🌐 Elixir | 📅 2026-08-19 - Framework for developing applications powered by language models, with support for OpenAI, Anthropic, Google, and Bumblebee models.
* [Sagents](https://github.com/sagents-ai/sagents) ⭐ 266 | 🐛 3 | 🌐 Elixir | 📅 2026-08-17 - Framework for interactive AI agents with OTP supervision, middleware composition, human-in-the-loop approvals, sub-agent delegation, and a Phoenix LiveView debugger.
* [Jido.AI](https://github.com/agentjido/jido_ai) ⭐ 202 | 🐛 2 | 🌐 Elixir | 📅 2026-08-19 - LLM integration layer for Jido. Provides actions and reasoning strategies (ReAct, Chain-of-Thought, Tree-of-Thoughts) for building intelligent agents with OpenAI, Anthropic, and other providers.
* [SwarmEx](https://github.com/nrrso/swarm_ex) ⭐ 91 | 🐛 2 | 🌐 Elixir | 📅 2024-11-10 - Lightweight library for AI agent orchestration with built-in telemetry and tool integration.
* [Synapse](https://github.com/nshkrdotcom/synapse) ⭐ 49 | 🐛 0 | 🌐 Elixir | 📅 2026-08-12 - Multi-agent orchestration framework with Postgres persistence.
* [Bazaar](https://github.com/georgeguimaraes/bazaar) ⭐ 5 | 🐛 0 | 🌐 Elixir | 📅 2026-02-17 - Elixir SDK for serving AI agent commerce protocols (UCP and ACP) from a single Phoenix handler. Supports Google Shopping agents (UCP) and OpenAI/Stripe agents (ACP) with automatic request/response translation between protocols.

### Development Tools

* [Tidewave Phoenix](https://github.com/tidewave-ai/tidewave_phoenix) ⭐ 846 | 🐛 5 | 🌐 Elixir | 📅 2026-08-19 - AI-powered development assistant for Phoenix web applications that connects editor AI assistants to web framework runtime via MCP.
* [Usage Rules](https://github.com/ash-project/usage_rules) ⭐ 219 | 🐛 1 | 🌐 Elixir | 📅 2026-08-01 - Tool for synchronizing LLM rules files with dependencies to prevent AI hallucinations and ensure consistent usage patterns.
* [claude-code-elixir](https://github.com/georgeguimaraes/claude-code-elixir) ⭐ 168 | 🐛 0 | 🌐 Shell | 📅 2026-04-28 - Collection of Claude Code plugins for Elixir development. Includes LSP integration, formatting and compilation hooks, and thinking skills for Elixir, Phoenix, Ecto, and OTP patterns.
* [Anubis MCP](https://github.com/zoedsoupe/anubis-mcp) ⭐ 167 | 🐛 16 | 🌐 Elixir | 📅 2026-08-17 - SDK for the Model Context Protocol (MCP) with support for multiple transport options (STDIO, HTTP/SSE, WebSocket).
* [Beamlens](https://github.com/beamlens/beamlens) ⭐ 136 | 🐛 14 | 🌐 Elixir | 📅 2026-05-10 - AI-powered runtime intelligence for the BEAM. Lives in your supervision tree and uses LLMs to explain metrics, diagnose incidents, detect anomalies, and trace message queue bottlenecks.
* [MCP Proxy](https://github.com/tidewave-ai/mcp_proxy_elixir) ⚠️ Archived - Proxy that connects STDIO-based MCP clients to HTTP-based Server-Sent Events (SSE) MCP servers.
* [HexDocs MCP](https://github.com/bradleygolden/hexdocs-mcp) ⭐ 70 | 🐛 2 | 🌐 Elixir | 📅 2025-06-18 - Enables semantic search of Elixir package documentation for AI assistants via Model Context Protocol (MCP).
* [llm\_db](https://github.com/agentjido/llm_db) ⭐ 56 | 🐛 1 | 🌐 Elixir | 📅 2026-08-20 - LLM model metadata database with O(1) lookups for provider capabilities, pricing, and context limits. Packaged as a dependency snapshot with no runtime network calls needed.
* [Evals](https://github.com/ash-project/evals) ⭐ 48 | 🐛 6 | 🌐 Elixir | 📅 2026-08-06 - Tool for evaluating AI language models on Elixir code generation with side-by-side model comparisons and automated testing.
* [Alike](https://github.com/georgeguimaraes/alike) ⭐ 45 | 🐛 5 | 🌐 Elixir | 📅 2026-06-19 - Semantic similarity testing library using a wave operator (`<~>`) for assertions. Tests whether sentences convey the same meaning rather than exact matches, ideal for validating LLM outputs.
* [ex\_mcp](https://github.com/azmaveth/ex_mcp) ⭐ 21 | 🐛 3 | 🌐 Elixir | 📅 2026-08-13 - Complete Elixir implementation of the Model Context Protocol (v2025-11-25) with client and server support, multiple transports including native BEAM, and 2600+ tests.
* [LlmGuard](https://github.com/North-Shore-AI/LlmGuard) ⭐ 13 | 🐛 1 | 🌐 Elixir | 📅 2026-04-04 - AI firewall with prompt injection detection, PII redaction, and jailbreak prevention for LLM applications.
* [AgentObs](https://github.com/lostbean/agent_obs) ⭐ 12 | 🐛 0 | 🌐 Elixir | 📅 2026-06-17 - LLM agent observability with telemetry, token tracking, and OpenTelemetry spans following OpenInference conventions.

## Livebooks & Examples

* [Programming Machine Learning](https://github.com/nickgnd/programming-machine-learning-livebooks) ⭐ 209 | 🐛 2 | 🌐 Elixir | 📅 2023-06-02 - Livebook notebooks with code examples for the [Programming Machine Learning book by Paolo Perrotta](https://pragprog.com/titles/pplearn/programming-machine-learning/)
* [José Valim's Livebooks](https://github.com/josevalim/livebooks) ⭐ 205 | 🐛 0 | 📅 2026-03-25 - Livebooks that José used for talks and Advent of Code.
* [Asynchronous Processing in Elixir](https://github.com/whatyouhide/guide_async_processing_in_elixir) ⭐ 155 | 🐛 0 | 📅 2024-01-11 - Interactive guide using Livebook to asynchronous data processing in Elixir.
* [Machine Learning in Elixir](https://github.com/charlieroth/machine-learning-in-elixir) - Livebooks following along with the book [Machine Learning in Elixir by Sean Moriarity](https://pragprog.com/titles/smelixir/machine-learning-in-elixir/)

## Resources

### Books

* [Machine Learning in Elixir - Learning to Learn with Nx and Axon (by Sean Moriarity)](https://pragprog.com/titles/smelixir/machine-learning-in-elixir/)
* [Genetic Algorithms in Elixir - Solve Problems Using Evolution (by Sean Moriarity)](https://pragprog.com/titles/smgaelixir/genetic-algorithms-in-elixir/)

### Videos

* [(2025) Keynote: Elixir's AI Future - Chris McCord](https://www.youtube.com/watch?v=6fj2u6Vm42E)
* [(2025) Keynote: Designing LLM Native systems - Sean Moriarity](https://www.youtube.com/watch?v=R9JRhIKQmqk)
* [(2025) Full-Stack AI with Elixir - George Guimarães](https://www.youtube.com/watch?v=toAIdOVCHCw)
* [(2025) Keynote: Code Generators are Dead. Long Live Code Generators - Chris McCord](https://www.youtube.com/watch?v=ojL_VHc4gLk)
* [(2024) Ship it! A Roadmap for Putting Nx into Production - Christopher Grainger](https://www.youtube.com/watch?v=5FlZHkc4Mq4)
* [(2024) Using LLMs and AI Agents to super power your Phoenix apps - Byron Saltysiak](https://www.youtube.com/watch?v=Hnpt2zv0rVw)
* [(2024) Soothsayer: Using NeuralProphet, Nx and Livebook to Forecast Business Data in Elixir - George Guimarães](https://www.youtube.com/watch?v=3LmKRrLUn5w)
* [(2023) A year in production with Machine Learning on the BEAM](https://www.youtube.com/watch?v=HP86Svk4hzI) (Explorer, Scholar, Bumblebee, Livebook)
* [(2023) Nx-powered decision trees](https://www.youtube.com/watch?v=rbmviKT6HkU) (Nx, EXGBoost)
* [(2023) Building AI apps with Elixir](https://www.youtube.com/watch?v=TfZI5-oQSqI)
* [(2023) MLOps in Elixir: Simplifying traditional MLOps with Elixir](https://www.youtube.com/watch?v=6aVnwj8WQq4) (Nx, Bumbleblee)
* [(2023) Fine-tuning language models with Axon](https://www.youtube.com/watch?v=-iZIZHgHa5M) (Axon)
* [(2023) Data wrangling with Livebook and Explorer](https://www.youtube.com/watch?v=U6nuPjyAUPw) (Livebook, Explorer)
* [(2022) The Future AI Stack by Chris Grainer](https://www.youtube.com/watch?v=Y2Nr4dNu6hI) (Explorer, Axon)
* [(2022) Announcing Bumblebee: pre-trained machine learning models for GPT2, StableDiffusion, and more](https://www.youtube.com/watch?v=g3oyh3g1AtQ) (Livebook, Bumblebee)
* [(2022) Axon: functional programming for deep learning](https://www.youtube.com/watch?v=NWXSiZ-vi-o) (Axon)

### Articles

* (2026) [Why Elixir is the best language for AI](https://dashbit.co/blog/why-elixir-best-language-for-ai) - José Valim makes a data-backed case for Elixir in the AI era: immutability, first-class docs, operational simplicity, and runtime introspection.
* (2026) [Your Agent Framework Is Just a Bad Clone of Elixir](https://georgeguimaraes.com/your-agent-orchestrator-is-just-a-bad-clone-of-elixir/) - George Guimarães argues that Python agent frameworks are independently rediscovering BEAM primitives, and Elixir already solves the hard parts of long-lived agent connections.
* (2025) [Embedding Python in Elixir, it's Fine](https://dashbit.co/blog/running-python-in-elixir-its-fine) - Jonatan Kłosko introduces Pythonx: embedding Python directly in the BEAM via NIF with automatic virtual env management and same-process memory sharing.
* (2025) [Building a MCP Server in Elixir](https://hashrocket.com/blog/posts/building-a-mcp-server-in-elixir) - Hashrocket walks through building a real MCP server using Anubis, letting AI tools like Claude Code and Cursor interact directly with a Phoenix app.
* (2024) [Elixir and Machine Learning in 2024 so far](https://dashbit.co/blog/elixir-ml-s1-2024-mlir-arrow-instructor) - José Valim's mid-year ecosystem update covering Nx's move to MLIR, Apple Silicon support, Explorer's Arrow improvements, and structured outputs via instructor\_ex.
* (2024) [What I mean when I say ML in Elixir is production-ready](https://cigrainger.com/elixirconf-eu-2024-keynote/) - Christopher Grainger makes the case for production ML on the BEAM: Nx.Serving for distributed batching, actor model for model supervision, and native integration with Phoenix, Oban, and Broadway.
* (2024) [AI GPU Clusters, From Your Laptop, With Livebook](https://fly.io/blog/ai-gpu-clusters-from-your-laptop-livebook/) - Chris McCord and José Valim demonstrate scaling to 64 GPU machines simultaneously from a local Livebook using FLAME and Nx's native BEAM clustering.
* (2024) [Training LoRA Models with Axon](https://dockyard.com/blog/2024/10/08/training-lora-models-with-axon) - Sean Moriarity's deep dive on fine-tuning LLMs in pure Elixir using LoRA and Axon's graph rewriting APIs.
* (2024) [Implementing Natural Conversational Agents with Elixir](https://seanmoriarity.com/2024/02/25/implementing-natural-conversational-agents-with-elixir/) - Sean Moriarity builds a voice AI assistant with Whisper, GPT-3.5, and ElevenLabs in Elixir, reducing latency from 4.5s to \~1s with Silero VAD and GPU acceleration.
* (2023) [From Python to Elixir Machine Learning](https://www.thestackcanary.com/from-python-pytorch-to-elixir-nx/) - Nice wrapup on what you gain from the Elixir ecosystem for Machine Learning.

## Contributions

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

This project is licensed under the [CC0 License](LICENSE.md). Feel free to use, share, and adapt the content.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
