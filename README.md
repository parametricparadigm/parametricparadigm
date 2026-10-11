## Francis Xavier Halstead — Parametric Paradigm

AI / ML infrastructure engineer in Boulder, Colorado. I build and run a self-hosted generative AI
stack on one NVIDIA RTX PRO 6000 Blackwell (96 GB): quantized LLM serving, image and video
generation in ComfyUI, and the Python agent layer that routes work between them.

**Open to remote AI engineering roles and contract work (US).** Contact: flowersbyfriendsli@gmail.com

### What I work on

- **LLM serving:** vLLM and llama.cpp behind OpenAI-compatible APIs, NVFP4 / FP8 / GGUF
  quantization, KV-cache and GPU-memory tuning, several models sharing one GPU.
- **Generative media:** three ComfyUI instances on a patched core, 500+ custom node packs, and
  my own nodes for conditioning, sampling, fast video VAE decode and local-LLM prompting.
  Flux, Qwen-Image, Wan 2.2 and LTX video pipelines.
- **Agents and orchestration:** a FastAPI backend with mixture-of-experts routing across local
  LLMs, RAG, MCP tool servers, VRAM scheduling and an approval-gated policy layer.
- **CUDA stack from source:** PyTorch nightly on CUDA 13.4 for Blackwell (sm_120), with
  SageAttention, flash-attention and CUTLASS compiled locally.

### Stack

Python · FastAPI · PyTorch · CUDA · vLLM · llama.cpp · ComfyUI · MCP · Linux · systemd · Git

### Releases

Node packs and tools from this stack will be published here.
