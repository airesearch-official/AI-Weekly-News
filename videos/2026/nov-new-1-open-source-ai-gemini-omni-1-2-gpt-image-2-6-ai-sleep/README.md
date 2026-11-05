# 🚀 AI Weekly News – November 5, 2026
**NEW #1 OPEN-SOURCE AI MODEL, Gemini Omni 1.2, GPT Image 2.6 & AI That Can Sleep?! — HUGE AI NEWS**

📅 Published: November 5, 2026  
🎥 Watch the full video here:  
[![Watch on YouTube](https://img.youtube.com/vi/ZGRbJyZ4WiY/0.jpg)](https://youtu.be/ZGRbJyZ4WiY)

---

## 🔥 Overview
The AI landscape accelerates into another historic week marked by the crowning of a new open-source intelligence king, self-consolidating memory architectures inspired by biological sleep, major creative platform upgrades, and leaps in physical world modeling. Moonshot AI officially open-sourced the weights for **Kimi K3.1 Pro**—a massive 2.8-trillion parameter MoE model claiming the **#1 open-source title** on global reasoning leaderboards. Google Research introduced the **SLEEP Framework**, enabling LLMs to enter an offline "sleep and dreaming" phase that resolves catastrophic forgetting and assimilates continuous knowledge. OpenAI unveiled **ChatGPT Images 2.6** with native animated GIF synthesis and reusable character anchors, Google expanded **Gemini Omni 1.2 Flash** to 15-second multi-turn video editing, and NVIDIA launched **MotionBricks** to generate 15,000 FPS character and humanoid motions using modular Smart Primitives.

Here’s the complete technical breakdown with verified source links and timestamps 👇

---

## 🧠 Frontier Models, Agent Swarms & Continual Learning
- **Kimi K3.1 Pro (Moonshot AI)**: Moonshot AI’s newly open-sourced flagship Mixture-of-Experts (MoE) foundation model, taking the **#1 open-source AI crown**. Features ~2.8 trillion total parameters (104B active per token), a 1M token context window, and extensive reinforcement learning post-training that rivals leading proprietary frontier models on Terminal-Bench and Humanity’s Last Exam across software engineering, financial reasoning, and 3D/CAD workflows.
- **The SLEEP Framework (Google Research)**: A biological continual-learning paradigm for LLMs introduced by Google Research ("Language Models Need Sleep"). Alternates between an awake interaction phase and an offline sleep phase: **Memory Consolidation** transfers fragile short-term memories into stable low-rank MoE expert modules without disrupting existing weights, while **Dreaming** uses reinforcement learning and router perturbations to rehearse self-generated synthetic curricula.
- **Tencent Hy4 (Hunyuan 4)**: Tencent’s 770B parameter MoE (49B active) multimodal foundation model supporting a 1M token context window. Debuts native visual comprehension alongside computer-use capabilities across CLI and GUI environments, optimized for Blender, CAD, and game engine scripting (Unity, Unreal, Godot).
- **AutoSwarm (HKUDS)**: An open-source multi-agent framework that unifies disparate AI coding agents (Claude Code, Codex, DeepSeek Harness, Muse, WorkBuddy) into a coordinated swarm, resolving responsibility misalignment and cascading dependency failures via shared state coordination.
- **Clover-35B-A3B (DiffuSpace)**: An open-source non-autoregressive block diffusion language model (35B total, 3B active MoE) derived from Qwen 3.6 with a 128K context window. Employs block diffusion to denoise 32 token positions in parallel, delivering extreme inference speeds on structured coding and tool-calling tasks.
- 🤗 [Kimi-K3.1-Pro on Hugging Face](https://huggingface.co/moonshotai/Kimi-K3.1-Pro)
- 📖 [Google Research: The SLEEP Framework](https://research.google/blog/the-sleep-framework-a-new-way-for-llms-to-retain-knowledge-in-continual-learning)
- 📖 [Tencent Hy4 Research](https://hy.tencent.ai/research/hy4?langVersion=en)
- 🐙 [AutoSwarm on GitHub](https://github.com/HKUDS/AutoSwarm)
- 📖 [DiffuSpace Clover-35B Blog](https://diffuspace.ai/blog/clover-35b/)

---

## 🎨 Generative Vision, OCR & Code-Driven Video
- **ChatGPT Images 2.6 (OpenAI)**: OpenAI’s major creative upgrade introducing two specialized API engines: **GPT-Image-2.6 Flare** (rapid layout generation in under 6 seconds) and **GPT-Image-2.6 Sunburst** (maximum detail and typography consistency). Adds native animated GIF generation, reusable character/object reference anchors, image markup API endpoints, and direct SVG export.
- **Gemini Omni 1.2 Flash (Google)**: Google’s upgraded multimodal video generation engine, expanding native clip durations up to 15 seconds. Introduces multi-turn conversational video editing (altering lighting, backgrounds, or assets while preserving subjects) at 30% reduced API pricing ($0.07/sec for 720p).
- **Unlimited-OCR (Baidu)**: An open-source end-to-end document parsing model featuring **Reference Sliding Window Attention (R-SWA)**. Replaces quadratic full-attention layers with constant-size KV cache decoding, processing hundreds of document pages in a single forward pass without OOM errors.
- **SenseNova-6.8-Code2Video (SenseTime)**: A 27B parameter image-text-to-code model with a 512K context window that plans, codes scenes as functions of time, renders previews, and visually refines motion graphics and character animations via iterative code execution.
- **Open-H3-Regenerate-2K (NVIDIA NVlabs)**: An open-weights video refiner that upscales low-resolution video drafts to native 2K and 4K resolution using 3-step Euler denoising, 3D latent upscaling, and NVIDIA’s SoL-Engine running on Blackwell B200 hardware.
- 📖 [Introducing Images 2.6 (OpenAI)](https://openai.com/index/introducing-images-2-6/)
- 📖 [Introducing Gemini Omni 1.2 Flash (Google)](https://blog.google/innovation-and-ai/technology/developers-tools/introducing-gemini-omni-1-2-flash/)
- 🐙 [Baidu Unlimited-OCR on GitHub](https://github.com/baidu/Unlimited-OCR)
- 🐙 [SenseNova-6.8-Code2Video on GitHub](https://github.com/OpenSenseNova/SenseNova-6.8-Code2Video)
- 🔗 [NVIDIA Open-H3-Regenerate-2K](https://nvlabs.github.io/Sana/Open-H3-Regenerate-2K/)

---

## 🗣️ High-Fidelity Audio, Speech Translation & Compact TTS
- **Hy-SimulMT (Tencent Hunyuan)**: An open-source 30.4B MoE (3B active) simultaneous translation model under Apache 2.0. Delivers real-time bidirectional English-Chinese speech-to-speech and speech-to-text translation with an average streaming lag of ~3 seconds and real-time voice cloning.
- **NVIDIA Nemotron 3.5 Transcribe**: An open-weight 34B MoE (4.3B active) Speech-Augmented Language Model (SALM). Supports prompt-steerable transcription, speaker attribution/diarization, and word-level timestamps across 40 languages for audio files up to one hour long.
- **Audio8-TTS-Realistic-0.6B (Edge0)**: A compact 601M parameter DualAR zero-shot voice cloning model supporting 23 languages. Trained via a 3-stage pipeline with Group Relative Policy Optimization (GRPO) driven by a learned perceptual realism critic.
- **Paradee 1.2 (Sahil Mahendrakar)**: An ultra-compact 8M parameter (8.5 MB INT8 ONNX) distilled English TTS model running entirely on a single CPU thread inside web browsers at 25x–60x real-time speed across 4 American and British voices.
- 🐙 [Tencent Hy-SimulMT on GitHub](https://github.com/Tencent-Hunyuan/Hy-SimulMT)
- 🤗 [Nemotron-3.5-Transcribe on Hugging Face](https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Transcribe-30B-A4B)
- 🔗 [Audio8-TTS Realistic Model Page](https://edge0-ai.github.io/Audio8_TTS/realistic-0.6b/)
- 📖 [Paradee 1.2 Documentation](https://www.sahilmahendrakar.com/writings/paradee-1-2)

---

## 🌍 World Models, 3D Physics & Embodied Robotics
- **MotionBricks (NVIDIA NVlabs)**: A modular real-time generative motion in-betweener presented at SIGGRAPH 2026. Operates at up to 15,000 FPS with 2 ms latency using reusable "Smart Primitives" for seamless human animation (SOMA) and Unitree G1 humanoid robot whole-body control.
- **Idol (Speridlabs)**: An open-source single-image 3D Gaussian Splat (.ply) generator under Apache 2.0. Reconstructs complete 3D objects with adjustable Levels of Detail (up to 1M splats) requiring only ~7.2 GB of VRAM on consumer GPUs.
- **PhysAg3D (Peking Univ & Huawei)**: An open-source framework bridging agentic reasoning and 3D generative priors (TRELLIS.2) to turn single 2D images into physically interactive assets with articulated joints and deformable parts.
- **Mundo (NTU S-Lab & SenseTime)**: A generative world model turning static images into interactive 3D scene programs with mass, friction, and collision physics for robotic real-to-sim training and navigation.
- **SceneBloom**: An agentic indoor 3D scene generation pipeline combining hierarchical layout diffusion priors with contract-guided spatial compilation for collision-free embodied AI environments.
- **OverSeer (Runjia Li et al.)**: A multi-agent world model architecture that learns global environmental dynamics beyond the local observational limits of individual agents.
- **UniAct / UniAction (2toinf)**: An embodied foundation model framework utilizing a tokenized universal action space to enable cross-embodiment skill transfer across heterogeneous robotic arms and humanoids.
- **Wave Forcing (SJTU DENG Lab)**: A causal wavefront streaming video generation framework that pipelines intermediate denoised chunks using the WaveRT runtime to achieve speed-of-light real-time streaming diffusion.
- 🔗 [NVIDIA MotionBricks Project](https://nvlabs.github.io/motionbricks/)
- 🔗 [Speridlabs Idol Research](https://speridlabs.com/research/idol)
- 🔗 [PhysAg3D Project Page](https://supra-3d.github.io/PhysAg3D/)
- 🔗 [Mundo World Model](https://mundo-world-model.github.io/)
- 🔗 [SceneBloom Project](https://tinaliu0123.github.io/scenebloom/)
- 🔗 [OverSeer Project](https://runjiali-rl.github.io/OverSeer/)
- 🔗 [UniAction Project](https://uniaction.github.io/)
- 🔗 [Wave Forcing Project](https://sjtu-deng-lab.github.io/WaveForcing/)

---

## 🚀 Wrap Up
This week demonstrates how artificial intelligence is maturing across biological inspiration, raw open scale, and embodied robotics:
- **Open-Source Claims the Summit**: Kimi K3.1 Pro's open weights establish that developer-accessible models can lead global intelligence benchmarks.
- **Biomimetic Memory**: Google's SLEEP framework proves that giving AI an offline "rest" phase to consolidate memories and dream synthetic curricula is key to continual lifelong learning.
- **Production-Ready Visual Workflows**: OpenAI Images 2.6 and Google Omni 1.2 Flash bring long-awaited creative capabilities like animated GIFs, reusable character consistency, and 15-second conversational clip editing.
- **Physical Robotics Unification**: MotionBricks, PhysAg3D, Mundo, and UniAct demonstrate that world modeling and physics-native tokens are bridging digital generative AI into physical robot control.

👉 Which release are you most excited to explore — Kimi K3.1 Pro, AI Sleep, Images 2.6, or MotionBricks?

💬 Drop your thoughts in the video comments:
[Watch the full video on YouTube](https://youtu.be/ZGRbJyZ4WiY)

---

## 🔗 Follow & Support
- 🐦 Twitter/X: [@airesearch_ai](https://x.com/airesearch_ai)  
- ☕ Support: [Ko-fi](https://ko-fi.com/airesearchs)  
- 🎥 Subscribe for more: [AI Research YouTube](https://www.youtube.com/@ReSearchAIs)

---

#AI #AINews #KimiK3 #GeminiOmni #GPTImages #AISleep #MotionBricks #OpenSourceAI #WorldModels #Robotics #TencentHy4

👉 Browse all past episodes here: [AI Weekly News Archive](../../..)
