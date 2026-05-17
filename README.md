# NVIDIA Is a 10-Layer Cake

An interactive map of NVIDIA's developer ecosystem — **146 components across 10 layers**, from hardware silicon at the bottom to programs, portals, and community at the top.

Click any component to see its developer journey: how developers arrive, the step-by-step workflow, where they go next, and the known friction points.

## The 10 layers

| # | Layer | What it covers |
|---|---|---|
| 10 | Programs, Portals & Community | Developer portals, registries, certifications, programs, community |
| 09 | Applications & Verticals | DRIVE, Isaac, Omniverse, Clara, Aerial, NemoClaw, Earth-2, … |
| 08 | Cloud Inference APIs | build.nvidia.com, AWS Bedrock, OpenRouter, Together, Fireworks, … |
| 07 | Self-hosted Inference & Serving | NIM, vLLM, Triton, SGLang, Ollama, Dynamo, … |
| 06 | Models | Nemotron 3 family, Llama-Nemotron, Parakeet, GR00T, Cosmos, … |
| 05 | AI Training & Fine-tuning | NeMo Framework, Megatron-LM, Isaac Lab, TAO Toolkit, … |
| 04 | ML Frameworks & Runtime | PyTorch+CUDA, TensorRT, RAPIDS, DALI, Warp, … |
| 03 | Compute Platform (CUDA) | CUDA Toolkit, cuBLAS, Nsight, CUTLASS, HPC SDK, … |
| 02 | System Software | Drivers, Container Toolkit, GPU Operator, MIG/MPS, DOCA, … |
| 01 | Hardware / Silicon | H100/H200/B200, Grace, DGX SuperPOD, MGX, Quantum-X800, … |

## Local preview

Open `index.html` in any modern browser. No build step, no dependencies.

## Deploy to Vercel

```sh
vercel deploy
```

Static HTML at root — Vercel auto-detects and serves with zero config.

## Notes on accuracy

Content verified May 2026 against NVIDIA's official sources and active third-party hosting platforms. Some items announced at GTC 2026 (Vera Rubin, Dynamo 1.0, BlueField-4, NemoClaw, Newton, DSX Blueprint) are included.

If you spot anything stale or wrong, open an issue.
