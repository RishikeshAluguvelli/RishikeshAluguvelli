# Rishikesh Reddy Aluguvelli

**AI/ML Engineer · Austin, TX** — I build ML systems that reach production: LLM inference and agents, retrieval and recommendation at scale, and reinforcement-learning policies for robotics.

Founding AI/ML engineer at **Spice**, where I own the ML surface of two shipped products (web, iOS & Android): hybrid search over **400K+ podcast episodes**, a real-time shorts recommender serving **600K+ clips**, LLM agent platforms, and GPU video pipelines. Previously Programmer Analyst at **Amazon** (2019–2023) and graduate TA for AI at **University at Buffalo**.

🌐 **[Portfolio — rishikeshaluguvelli.github.io](https://rishikeshaluguvelli.github.io/)** · [LinkedIn](https://www.linkedin.com/in/rishikesh-aluguvelli/)

---

## Start here

| Project | Why it's interesting |
|---|---|
| **[EdgeChat](https://github.com/RishikeshAluguvelli/EdgeChat)** | A fully offline, on-device AI chat app for iPhone — llama.cpp on Metal, vision, document reading, and long-conversation memory (KV-prefix reuse, background compaction, on-device RAG). 24 tok/s median decode on an iPhone 15 Plus; airplane mode works. Swift/SwiftUI, with CI and an engine test suite. |
| **[autonomous-racing-stack](https://github.com/RishikeshAluguvelli/autonomous-racing-stack)** | A complete ROS autonomy stack: online SLAM, particle-filter localisation, A* global planning that re-routes around obstacles, and a 20 Hz sampling-based local planner. Zero collisions lapping a track only ~1.4 m wide, 0.11 m mean localisation error. |
| **[scaling-lab](https://github.com/RishikeshAluguvelli/scaling-lab)** | Two levers past the LLM weight-read wall, built from scratch and benchmarked on H100/H200: speculative decoding (EAGLE-3 at 1.86× under vLLM, with the rejection-sampling proof) and Megatron-style tensor parallelism — honest negative results included. |
| **[microgpt](https://github.com/RishikeshAluguvelli/microgpt)** | A GPT trained from scratch in **pure Python — zero dependencies**. Tokenizer, reverse-mode autograd, transformer, Adam and sampling, all hand-written in one annotated notebook. |

## All projects

**LLM systems & inference**

- [scaling-lab](https://github.com/RishikeshAluguvelli/scaling-lab) — speculative decoding & tensor parallelism from first principles, benchmarked under vLLM
- [attention-lab](https://github.com/RishikeshAluguvelli/attention-lab) — MHA/GQA/MQA/MLA at decode, naive vs FlashAttention-2/3 at prefill (13.1× and 33× measured)
- [kv-cache-lab](https://github.com/RishikeshAluguvelli/kv-cache-lab) — KV-cache latency, serving capacity and low-bit quantization on Qwen2.5-7B / H100
- [microgpt](https://github.com/RishikeshAluguvelli/microgpt) — a GPT from scratch in pure Python, zero dependencies

**RL & robotics**

- [autonomous-racing-stack](https://github.com/RishikeshAluguvelli/autonomous-racing-stack) — SLAM, AMCL, A* and local planning on ROS Noetic
- [rl-miniworld-navigation](https://github.com/RishikeshAluguvelli/rl-miniworld-navigation) — PPO from pixels in 3D, plus a custom obstacle environment
- [rl-sheep-herding](https://github.com/RishikeshAluguvelli/rl-sheep-herding) — multi-agent shepherding with curriculum PPO (5 dogs, 25 sheep)
- [rl-halfcheetah-ppo](https://github.com/RishikeshAluguvelli/rl-halfcheetah-ppo) — custom residual feature extractor, and a documented PPO policy collapse
- [rl-mountaincar-a2c](https://github.com/RishikeshAluguvelli/rl-mountaincar-a2c) — entropy vs short-horizon GAE ablation on a sparse-reward classic

**Multimodal & vision**

- [chat-with-videos](https://github.com/RishikeshAluguvelli/chat-with-videos) — multimodal RAG that answers from the pixels and returns the proving clip (BridgeTower + LLaVA + LanceDB)
- [VerticalMaker](https://github.com/RishikeshAluguvelli/VerticalMaker) — landscape → 9:16 video with active-speaker tracking, CPU-only

**On-device & apps**

- [EdgeChat](https://github.com/RishikeshAluguvelli/EdgeChat) — offline AI chat for iPhone: llama.cpp + Metal, vision, documents, long-term memory

---

*Full write-ups with demos, metrics and findings for every project: [rishikeshaluguvelli.github.io](https://rishikeshaluguvelli.github.io/)*
