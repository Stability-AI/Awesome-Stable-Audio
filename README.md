# Awesome Stable Audio [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> A curated list of projects, tools, models, UIs, and resources for **Stable Audio**. Contributions welcome!



## Contents

- [Official Resources](#official-resources)
- [Integrations and Extensions](#integrations-and-extensions)
- [Papers](#papers)

---

## Official Resources

| Resource | Description |
|----------|-------------|
|[Stable Audio Tools Research Repository](https://github.com/Stability-AI/stable-audio-tools) | Backwards-compatible repo for training and inference of all stable audio models |
|[Stable Audio 3 Repository](https://github.com/Stability-AI/stable-audio-3) | Official Stable Audio 3 inference and fine-tuning repo |
|[Stable Audio API](https://platform.stability.ai/docs/api-reference#tag/Stable-Audio) | Official API for Stable Audio |
|[HuggingFace Post-trained Models](https://huggingface.co/collections/stabilityai/stable-audio-3) | All official model weights, LoRAs, and spaces. |
|[HuggingFace Base Models, Autoencoders, and Optimizations](https://huggingface.co/collections/stabilityai/stable-audio-3-extra) | All official model weights, LoRAs, and spaces. |
|[HuggingFace Space](https://huggingface.co/spaces/stabilityai/stable-audio-3) | Interactive online demo on HuggingFace Zero GPU. |
|[Harmonai Discord](https://discord.gg/cKpvjey8b) | Community chat and support. |
|[SAME Autoencoder Project Page](https://stability-ai.github.io/SAME/) | High-quality, stereo audio compression that produces 256-dim continuous latents at 4096x downsampling.  |
|[Stable Audio Open Project Page](https://stability-ai.github.io/stable-audio-open-demo/) | Stable Audio Open demo |
|[Stable Audio 3 Docs](https://github.com/Stability-AI/stable-audio-3/tree/main/docs) | Prompt guides, fine-tuning, inference, model overview |
|[Stable Audio Tools Docs](https://github.com/Stability-AI/stable-audio-tools/tree/main/docs) | General Stable Audio docs |



## Integrations and Extensions
### Comfy UI
- [Stable Audio 3 Docs](https://docs.comfy.org/tutorials/audio/stable-audio/stable-audio-3)
- [Stable Audio Open Docs](https://docs.comfy.org/tutorials/audio/stable-audio/stable-audio-1)

### Fal
- [Stable Audio 3 Medium](https://fal.ai/models/fal-ai/stable-audio-3/medium/text-to-audio)
- [Stable Audio 3 Small SFX](https://fal.ai/models/fal-ai/stable-audio-3/small/sfx/text-to-audio)
- [Stable Audio 3 Small Music](https://fal.ai/models/fal-ai/stable-audio-3/small/music/text-to-audio)
- [Stable Audio 2.5](https://fal.ai/models/fal-ai/stable-audio-25/text-to-audio)
- [Stable Audio 1](https://fal.ai/models/fal-ai/stable-audio)

### LoRA fine-tuning
- [Underfit](https://github.com/dada-bots/underfit) by [@dadabots](https://x.com/dadabots/)

### More from the community
#### Stable Audio 3
| Resource | Description |
|----------|-------------|
| [Macbook Pro fast inference demo](https://x.com/dadabots/status/2057237391983640811) | Fast inference on Apple Silicon by [@dadabots](https://x.com/dadabots/) |
| [Promptless Mood steering](https://guglielmocamporese.github.io/blog/audio-mood-steering/) | Steering Stable Audio 3 by attaching inference-time probes to the diffusion transformer by [@gucamporese](https://x.com/gucamporese) |
| [DAW Plugin](https://github.com/betweentwomidnights/gary4juce) | JUCE-based DAW plugin by [@thepatch_kev](https://x.com/thepatch_kev)|
| [Ableton Extension](https://github.com/betweentwomidnights/sa3-ableton-extension) | Ableton Live extension by [@thepatch_kev](https://x.com/thepatch_kev) |
| [Speech-operated Terminal Looper](https://github.com/sonicfieldlabs/oram) | Voice-controlled terminal looper by [@sonic_field](https://x.com/sonic_field)|
| [Sample Varations Plugin](https://github.com/maxgraf96/stable-audio-3) | Sample variation generation JUCE plugin by [@maxgraf__](https://x.com/maxgraf__) |
| [theDAW](https://github.com/gantasmo/theDAW) | Browser-based DAW for Stable Audio 3 by [@gantasmo](https://x.com/gantasmo) |
| [LoopMaster](https://github.com/LevonFrench/LoopMasterSA) | A generative loop explorer by [@hotghettomusic](https://x.com/hotghettomusic) |
| [SAO-Doh](https://github.com/mtsandra/stable-audio-tools-v2) | [FlowEdit](https://arxiv.org/abs/2412.08629) implementation to generate intermediate sonic states between a source sample and a target description by team [hack-a-lil](https://musichackspace.org/events/hackathon-boston-june-2026/teams/434) ([Aleksandra Teng Ma](https://github.com/mtsandra), [Nithya Shikarpur](https://x.com/NithyaIsMe), [Cameron McCoy](https://www.linkedin.com/in/cameron-mccoy-/))
| [Stable Audio 3 inpainting UI](https://github.com/lyramakesmusic/sa3-inpainter-ui) | Browser UI for Stable Audio 3, includes LoRA training with auto-captioning by [@\_lyraaaa_](https://x.com/_lyraaaa_)|
| [StableAudioKit](https://github.com/olilarkin/StableAudioKit) | Swift package and CLI for python-less MLX Stable Audio 3 inference on Apple Platforms by [@olilarkin](https://github.com/olilarkin) |
| [Motif: Maqam generation plugin](https://github.com/thejadalmasri/motif_hack/) | A LoRA adapter of Stable Audio 3 + JUCE VST plugin for microtonal Arabic maqam music generation by [Jad Al Masri](https://www.instagram.com/jadalmasriofficial), [Thiago Santos](https://www.linkedin.com/in/thiagoosantos/), [Rithik Kundu](https://www.linkedin.com/in/rithik-kundu/), [Michael Tomasi](https://www.linkedin.com/in/mtomasi/), and [Chris Powers](https://www.linkedin.com/in/chris-powers-2bba2a160/)
| [Framenta](https://github.com/MAz-Codes/Fragmenta) | Fully-featured, offline desktop app for Stable Audio 3, including LoRA training, audio annotation, and performance mode by [@MAz-Codes](https://github.com/MAz-Codes) | 

## Papers
| Year | Paper |
|----------|-------------|
|2026|[Stable Audio 3](https://arxiv.org/abs/2605.17991) |
|2026|[SAME: A Semantically-Aligned Music Autoencoder](https://arxiv.org/abs/2605.18613) |
|2026|[Low-Resource Guidance for Controllable Latent Audio Diffusion](https://arxiv.org/abs/2603.04366) |
|2025|[Fast Text-to-Audio Generation with Adversarial Post-Training (Stable Audio Open Small)](https://arxiv.org/abs/2505.08175) |
|2025|[Stable Audio Open](https://arxiv.org/abs/2407.14358) |
|2024|[Long-Form Music Generation With Latent Diffusion (Stable Audio 2)](https://arxiv.org/abs/2404.10301) |
|2024|[Fast Timing-Conditioned Latent Audio Diffusion (Stable Audio)](https://arxiv.org/abs/2402.04825) |
