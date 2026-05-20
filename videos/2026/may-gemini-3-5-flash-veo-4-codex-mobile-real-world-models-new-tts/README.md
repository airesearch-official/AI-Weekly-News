# 🚀 AI Weekly News – May 20, 2026
**Gemini 3.5 Is Here, Veo 4 New Video King, Codex Mobile, Real World Models, new TTS — HUGE AI NEWS**

📅 Published: May 20, 2026  
🎥 Watch the full video here:  
[![Watch on YouTube](https://img.youtube.com/vi/f2afaXiZ_2w/0.jpg)](https://youtu.be/f2afaXiZ_2w)

---

## 🔥 Overview
This week in AI is absolutely stacked with major announcements, headlined by Google’s new **Gemini 3.5 Flash** and the advanced **Gemini Omni** model family. These releases focus on faster reasoning, native agentic coordination, and next-generation video generation tools. Meanwhile, AI workflows are becoming increasingly mobile with OpenAI's **Codex Mobile** integration, financial AI makes a massive jump with ChatGPT's Plaid-powered bank synchronization, and the open-source community continues to push the boundaries of real-time video, world simulation, and expressive speech synthesis.

Here’s a full breakdown with source links and insights 👇

---

## 🧠 Frontier Intelligence: Gemini 3.5 & Agentic Ecosystems
- **Gemini 3.5 Flash**: Google’s newest release, designed specifically for high-speed, long-horizon reasoning and agentic tasks. It runs four times faster than comparable frontier models and outperforms Gemini 3.1 Pro on major coding and multi-step workflows. It is generally available across the Google Cloud and developer ecosystem, and powers the new 24/7 personal AI agent, **Gemini Spark**.
- **Gemini UI & Usage Updates**: Usability enhancements rolled out within the Gemini App, featuring cleaner multi-turn agent steering options, faster real-time workspace rendering, and a more structured playground environment.
- **Magic Pointer (Google DeepMind)**: An experimental AI-enabled mouse cursor powered by Gemini. Instead of just tracking coordinates, it uses visual and semantic context to understand what is under the cursor. Users can trigger actions (e.g., "summarize this") via natural voice commands without needing to copy-paste into separate chat windows.
- **HRM-Text 1B (Sapient Intelligence)**: A 1-billion-parameter language model built on the new Hierarchical Reasoning Model (HRM) architecture. It is designed to perform efficient, structured reasoning, achieving competitive performance on benchmarks like MATH and DROP with a significantly reduced token training budget.
- **AMD Agent-Computers**: A new category of localized, AI-optimized PCs powered by processors like the Ryzen AI Max+ 395. These consumer computers are designed to run persistent, multi-agent workflows locally in the background, providing lower latency, lower costs, and enhanced privacy.
- 🔗 [Magic Pointer Project](https://deepmind.google/blog/ai-pointer/)
- 🤗 [HRM-Text 1B on Hugging Face](https://huggingface.co/sapientinc/HRM-Text-1B)
- 📖 [AMD Consumer Agent Computers](https://www.amd.com/en/products/processors/consumer/agent-computers.html)

---

## 📱 Mobile & Personal Finance AI: OpenAI Updates
- **OpenAI Codex Mobile**: An update enabling developers to work with Codex from anywhere using the ChatGPT mobile app. By connecting mobile interfaces to a local or remote desktop machine via a secure relay layer, engineers can monitor agent status, steer coding workflows, and approve diffs on the go.
- **ChatGPT Personal Finance Assistant**: A read-only integration powered by Plaid for ChatGPT Pro subscribers in the US. Users can securely link their credit cards, investment portfolios, and bank accounts to query ChatGPT on real financial trends, balances, subscription costs, and spending habits in one conversational thread.
- 📖 [Work with Codex from Anywhere](https://openai.com/index/work-with-codex-from-anywhere/)
- 📖 [ChatGPT Personal Finance Integration](https://openai.com/index/personal-finance-chatgpt/)

---

## 🌍 World Modeling & Simulation
- **Gemini Omni Video Generation**: A new model family centered on "world understanding." It generates high-fidelity, physics-grounded video from text, image, audio, or video inputs, and allows interactive conversational editing (e.g., changing background styles or perspectives) with SynthID watermarking embedded by default.
- **Starchild 1 (Odyssey)**: Odyssey’s first real-time, multimodal world model capable of generating synchronized audio and video that responds continuously and dynamically to ongoing user input.
- **Agora 1 (Odyssey)**: A multi-agent world model by Odyssey that supports simultaneous interaction for up to four human or AI players in a shared, dynamically generated simulation (demonstrated using a *GoldenEye 007* setup).
- **Sana WVM (Nvidia)**: An efficient 2.6B parameter open-source interactive world model. It generates playable 1-minute 720p virtual environments from text and image prompts on a single GPU, featuring persistent memory to ensure environmental consistency.
- **Dream X World**: A general-purpose interactive world model supporting first-person and coherent third-person perspective generation, along with prompt-driven events for controlled spatial exploration.
- 🔗 [Starchild-1 Official Release](https://odyssey.ml/introducing-starchild-1)
- 🔗 [Agora-1 Multi-Agent System](https://odyssey.ml/introducing-agora-1)
- 🔗 [Sana WVM Project Page](https://nvlabs.github.io/Sana/WM/)
- 🔗 [DreamX World Project Page](https://amap-ml.github.io/DreamX_World/)

---

## 🎬 Advanced Video Synthesis & Editing
- **Warp as History**: A research method from Shanghai Jiao Tong University and Shanghai AI Lab that enables precise camera trajectory control in pretrained video generation models. It converts camera-induced geometric warps into "pseudo-history" tokens, avoiding the need for expensive camera-annotated training.
- **CasualCine (Interactive Video)**: An interactive, autoregressive framework for multi-shot video generation. Uses Content-Aware Memory Routing (CAMR) to route details across shot boundaries, acting as a dynamic directing tool that keeps content coherent.
- **MoCam (Perspective Changer)**: A novel view synthesis framework that decouples geometric alignment and appearance refinement within the diffusion process, allowing users to rotate or change camera perspective around a subject in a video while keeping actions identical.
- **Relit Live (Video Lighting)**: A video relighting framework that creates physically consistent and temporally stable lighting adjustments. Leverages raw reference images in the rendering pipeline to enable realistic lighting edits, object insertion, and scene-level rendering.
- **Phymotion (Physics-Based Video)**: A structured motion reward framework that enforces physical and kinematically plausible movements in generated human videos, minimizing physics glitches like floating bodies or dynamic clipping.
- 🔗 [Warp as History Project](https://yyfz.github.io/warp-as-history/)
- 🔗 [CausalCine Project Page](https://yihao-meng.github.io/CausalCine/)
- 🔗 [MoCam Project Page](https://orange-3dv-team.github.io/MoCam/)
- 🔗 [Relit Live Project Page](https://zhuxing0.github.io/projects/Relit-LiVE/)
- 🔗 [Phymotion Project Page](https://phy-motion.github.io/)

---

## 🎨 Unified Engines, Diffusion & 3D Articulation
- **LANCE (ByteDance Unified Engine)**: An open-source, 3B-parameter unified multimodal model by ByteDance. Employs a dual-stream Mixture-of-Experts (MoE) architecture capable of image/video understanding, generation, and editing within a single efficient pipeline.
- **Asymmetric Flow Models**: A pixel generation method that accelerates diffusion models by keeping generation velocities restricted to a low-rank subspace, powering high-performance models like *AsymFLUX.2-klein-9B*.
- **Fashion Chameleon**: An interactive video-garment customization framework. Uses teacher-student distillation and in-context learning to swap garments in existing video clips in real-time (~23.8 FPS on a single GPU) while preserving motion.
- **ArtiCraft (3D Articulation)**: An agentic system for generating articulated 3D assets. It writes, compiles, and refines Python code representing simulation-ready moving parts (like hinges and joints), automating asset generation and forming the basis of the ArtiCraft-10K dataset.
- **Stream Diffusion V2**: A highly optimized, real-time interactive streaming diffusion engine. Employs a rolling KV cache and motion-aware noise control to maintain temporal consistency and smooth styling on standard consumer hardware.
- **TrackCraft3R (Spatial Tracking)**: Developed by KAIST, TrackCraft3R reframes video diffusion transformers as feed-forward dense 3D trackers. It tracks pixels from a reference frame across video frames with high precision and speed.
- 🔗 [LANCE Project Page](https://lance-project.github.io/)
- 🔗 [Asymmetric Flow Models](https://hanshengchen.com/asymflow/)
- 🔗 [Fashion Chameleon Project](https://quanjiansong.github.io/projects/FashionChameleon/)
- 🔗 [ArtiCraft Project Page](https://articraft3d.github.io/)
- 🔗 [Stream Diffusion V2 Project](https://streamdiffusionv2.github.io/)
- 🐙 [TrackCraft3R on GitHub](https://github.com/cvlab-kaist/TrackCraft3r)

---

## 🎵 Audio, Speech & Translation
- **Open Source Music Generator (Khala)**: Developed by the Central Conservatory of Music, Beijing. A high-fidelity, open-source music generation system. Uses a unified 64-layer residual vector quantization (RVQ) acoustic token hierarchy to generate complete songs (vocals and instrumentation) from text and lyrics.
- **Cineama (Scenema AI)**: A diffusion-based model for expressive, zero-shot voice cloning and speech generation, allowing users to direct natural vocal pacing, emotion, and breath arcs.
- **DramaBox TTS (by Resemble AI)**: An open-source, prompt-driven text-to-speech engine where prompts control stage directions, emotional transitions, whispers, and vocal expressions.
- **Just Dub It (Translation & Lip-Sync)**: A single-model approach to video dubbing. Employs lightweight LoRA adapters on audio-visual diffusion models to jointly translate vocals and generate matching lip-sync/facial expressions, preserving speaker identity.
- 🔗 [Khala Demo & Code](https://khala-music-ai.github.io/Khala-demo/)
- 🔗 [Scenema Audio Platform](https://scenema.ai/audio)
- 🤗 [DramaBox TTS on Hugging Face](https://huggingface.co/ResembleAI/Dramabox)
- 🔗 [Just Dub It Project Page](https://justdubit.github.io/)

---

## 🚀 Wrap Up
This week showcases a clear transition towards seamless execution and localized persistence in AI.
- **Hardware Ready for Agents**: Localized hardware, like AMD’s agent-computers, will shift multi-agent workflows off the cloud and onto our desks.
- **Directing, Not Just Generating**: Frameworks like MoCam, CausalCine, and Warp as History show that video editing is moving from random generation to pixel-perfect camera and styling control.
- **True Mobile Integration**: Between Codex Mobile and ChatGPT's Personal Finance tool, advanced AI capabilities are fitting comfortably inside our pockets.

👉 Are you more excited about locally running multi-agent PCs or the massive speed leaps in Gemini 3.5 Flash?

💬 Drop your thoughts in the video comments:
[Watch the full video on YouTube](https://youtu.be/f2afaXiZ_2w)

---

## 🔗 Follow & Support
- 🐦 Twitter/X: [@airesearch_ai](https://x.com/airesearch_ai)  
- ☕ Support: [Ko-fi](https://ko-fi.com/airesearchs)  
- 🎥 Subscribe for more: [AI Research YouTube](https://www.youtube.com/@airesearchofficial/)

---

#AI #AINews #Gemini35 #Veo4 #CodexMobile #GeminiOmni #WorldModels #AIVideo #DeepMind #NVIDIA #ByteDance

👉 Browse all past episodes here: [AI Weekly News Archive](../../..)
