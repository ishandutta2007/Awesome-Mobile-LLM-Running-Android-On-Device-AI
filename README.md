# Awesome-Mobile-LLM-Running-Android-On-Device-AI

## Top Mobile LLM Running & Android On-Device AI Ecosystem



**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  

*Focused on On-Device Android & iOS LLM Runners, NPU/GPU Edge Acceleration (Qualcomm QNN, Vulkan, OpenCL, Metal), Termux Local Harnesses & Lightweight Edge Models*  

**Last updated: November 2026**



This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Mobile LLM Running & Android On-Device AI**. These tools enable Android/iOS developers, mobile AI engineers, and privacy-focused users to execute quantized LLMs (`GGUF`, `MLC`, `LiteRT`, `ExecuTorch`) locally on smartphones using CPU NEON, Adreno/Mali Vulkan GPUs, and Hexagon/Apple NPUs without internet connectivity.



**Examples** include MLX Server, Ollama, LM Studio, Jan.ai, LocalAI, vLLM, Aphrodite Engine, llama.cpp, Exo, SGLang, and `Soodok/Deepseek-Harness-Local-Android` (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for Android local LLM apps (`PocketPal AI`, `Maid`, `ChatterUI`, `Layla`-style / `Sherpa-ONNX`), mobile inference runtimes (`llama.cpp`, `MLC-LLM`, `ExecuTorch`, `LiteRT`, `MNN`), and Termux local server harnesses — ideal for Android developers, edge AI engineers, and offline mobile power users.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Qualcomm AI Hub](https://qualcomm.com)**  

  Cloud model optimization, quantization, and on-device benchmarking platform compiling LLMs and VLMs specifically for Snapdragon Hexagon NPUs and Adreno GPUs.



- **[Google AI Edge (Gemini Nano & MediaPipe Cloud Tools)](https://google.dev)**  

  Google's commercial and developer ecosystem for deploying Gemini Nano on-device via Android AICore and optimizing custom edge models for mobile hardware.



- **[Apple Foundation Models & Private Cloud Compute](https://apple.com)**  

  Apple's hybrid on-device MLX/CoreML and encrypted cloud inference architecture powering local intelligence on iPhone and iPad.



- **[LM Studio (Desktop & Mobile/Remote Link Ecosystem)](https://lmstudio.ai)**  

  Commercial-friendly local LLM runner and server platform providing curated GGUF/MLX model discovery and local network API serving for mobile companion apps.



- **[Layla AI (Commercial Android Offline LLM App)](https://layla-network.ai)**  

  Commercial mobile-first local AI assistant app running quantized LLMs, vision models, and voice synthesis directly on Android and iOS devices.



- **[Private LLM (iOS/macOS App Store)](https://privatellm.app)**  

  Commercial offline mobile AI application running quantized GGUF models natively on Apple Neural Engine and Metal GPUs with zero cloud telemetry.



- **[Nexa AI (Octopus & On-Device SDK Cloud)](https://nexa.ai)**  

  Edge AI developer platform offering optimized small language models (`Octopus`) and cross-platform NPU/GPU mobile inference SDKs.



- **[RunAnywhere / Cactus Cloud Edge Services](https://together.ai)**  

  Cloud-to-edge model distillation, quantization, and fallback inference platforms bridging local mobile SLMs with cloud frontier models when offline limits are hit.





## Open-Source GitHub Projects



- **[Soodok/Deepseek-Harness-Local-Android](https://github.com)**  

  Open-source local execution harness and setup toolkit engineered to run DeepSeek and quantized LLMs directly on Android hardware.



- **[llama.cpp](https://github.com)**  

  The foundational open-source C/C++ LLM inference engine supporting Android NDK, Termux, ARM NEON/dotprod/i8mm, Vulkan GPU, and Qualcomm KleidiAI/OpenCL acceleration.



- **[PocketPal AI](https://github.com)**  

  Sleek, open-source React Native mobile app (`llama.rn`) enabling users to download, benchmark, and chat offline with GGUF models directly on Android and iOS.



- **[MLC-LLM (Machine Learning Compilation)](https://github.com)**  

  High-performance open-source universal LLM deployment engine compiling quantized models natively for Android OpenCL/Vulkan GPUs, iOS Metal, and WebGPU.



- **[ExecuTorch (PyTorch Edge)](https://github.com)**  

  Meta's official open-source on-device AI inference runtime enabling PyTorch LLMs (`Llama`, `Qwen`, `Gemma`) to run natively on Android and iOS NPUs/GPUs (Qualcomm QNN, MediaTek, CoreML).



- **[Google AI Edge LiteRT (formerly TensorFlow Lite) & MediaPipe LLM Inference](https://github.com)**  

  Open-source on-device machine learning runtime powering fast GPU and NPU execution of Gemma, Phi, and Llama models on Android devices.



- **[MNN (Alibaba Mobile Neural Network)](https://github.com)**  

  Blazing-fast, lightweight open-source deep learning and LLM inference engine optimized specifically for Android/iOS mobile CPUs, OpenCL, Vulkan, and NPU backends (`MNN-LLM`).



- **[Maid (Mobile Artificial Intelligence Distribution)](https://github.com)**  

  Cross-platform open-source Flutter frontend for running local GGUF models via `llama.cpp` on Android alongside remote Ollama/OpenAI API fallback.



- **[ChatterUI](https://github.com)**  

  Feature-rich open-source Android LLM frontend offering local GGUF inference (`llama.rn`), character cards, RAG document chat, and remote API connections.



- **[Ollama](https://github.com)**  

  The most popular open-source local LLM runner and REST server—widely deployed inside Android Termux proot/native environments and as a home-server backend for mobile clients.



- **[Exo](https://github.com)**  

  Open-source peer-to-peer distributed AI cluster engine uniting everyday devices (phones, laptops, tablets, Macs) over LAN to shard and run large LLMs together.



- **[Apple MLX & `mlx-lm`](https://github.com)**  

  Apple's open-source array framework and local LLM server (`mlx_lm.server`) engineered for unified memory architectures across Apple Silicon mobile and desktop devices.



- **[LocalAI](https://github.com)**  

  Drop-in open-source OpenAI-compatible local AI server supporting LLMs, Whisper STT, TTS, and image generation on edge hardware and Linux/Termux setups.



- **[Jan](https://github.com)**  

  Open-source, offline-first AI assistant and local OpenAI-compatible server built on `llama.cpp` with clean model management and mobile/LAN access.



- **[vLLM & Aphrodite Engine & SGLang (Mobile Client Backends)](https://github.com)**  

  High-throughput open-source inference engines (`vLLM`, `Aphrodite`, `SGLang`) commonly paired with mobile frontends over WireGuard/Tailscale for heavy reasoning tasks.



- **[Termux](https://github.com)**  

  Essential open-source Android terminal emulator and Linux environment enabling developers to compile and run `llama.cpp`, `Ollama`, Python agents, and local REST servers natively on Android.



- **[Sherpa-ONNX (k2-fsa)](https://github.com)**  

  Ultra-fast open-source offline speech-to-text, text-to-speech, and speaker identification runtime for Android/iOS, enabling completely offline voice-to-LLM mobile assistants.



### Additional Strong Open-Source Options



- **[llama.rn](https://github.com)** and **[Cactus](https://github.com)** for native React Native and Flutter C++ bindings bringing `llama.cpp` directly into cross-platform mobile apps.

- **[SmolVLM / Qwen2.5-VL / Gemma 3n / Phi-4-mini](https://huggingface.co)** for open-weights `1B–4B` parameter multimodal and text models engineered to fit comfortably inside `6 GB–12 GB` smartphone RAM.

- **[Whisper.cpp](https://github.com)** for offline C/C++ speech recognition on Android and iOS devices with zero cloud latency.

- **[FastLLM](https://github.com)** and **[PowerInfer](https://github.com)** for open-source sparse-activation and memory-bandwidth-optimized LLM inference on consumer and mobile hardware.

- Many community **Termux one-click `llama.cpp` / `Ollama` build scripts**, **Android Vulkan Adreno shader optimizations**, and **offline mobile RAG (`SQLite-vec`) apps**.



**Frameworks for building custom systems**: Combine **llama.cpp** or **ExecuTorch / MLC-LLM** (on-device runtime), **PocketPal AI / ChatterUI** (Android UI), **Sherpa-ONNX** (offline voice I/O), and **Termux** with **Soodok/Deepseek-Harness-Local-Android** for a 100% offline, private mobile AI assistant.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Running quantized LLMs (`3B–8B` parameters) locally on Android smartphones generates sustained CPU/GPU/NPU heat and high battery drain, and Android's Low Memory Killer (`LMK`) may terminate processes that exceed ~50–60% of total device RAM; stick to `Q4_K_M` or `IQ4_XS` quantizations sized to your device's available memory.

- Always download GGUF/MLC model weights from verified, reputable repositories and verify SHA-256 hashes before loading files on personal mobile devices.



---



**Made for Android AI developers, edge ML engineers, privacy advocates, and mobile tinkerers.**  

Let's make on-device mobile LLMs faster, cooler, and open.
