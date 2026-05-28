# niuma-prompt

> Multimodal Prompt Engineering Expert — 30+ Models. One skill, all AI content generation.
> 
> v2.1.0 | Developer: Super niuma | MIT

---

## Overview

**niuma-prompt** is the ultimate prompt engineering skill for AI content generation. It covers **all major image generation models** (Midjourney, DALL-E, Stable Diffusion, Flux, GPT Image 2, Nano Banana Pro, and all Chinese domestic models) and **all major video generation models** (Seedance 2.0, Kling 3.0, Sora 2, Runway Gen-4, Pika 2.0, Veo 3, Luma, Wan, Hailuo 3.0, Vidu, HappyHorse, HunyuanVideo).

When an AI agent loads this skill, it instantly gains the ability to craft optimal prompts for any model — understanding each model's unique syntax, parameter system, and best practices.

## Core Features

- 🖼️ **15+ Image Models** — From Midjourney to Jimeng, Flux to Tongyi Wanxiang, each with dedicated formula and parameter guide
- 🎬 **12+ Video Models** — Seedance, Kling, Sora, Runway, Veo, Wan, Hailuo, Vidu, HappyHorse, HunyuanVideo and more
- 🔄 **Cross-model Translation** — 20+ conversion pairs to seamlessly translate prompts between any two models
- ⏱️ **Timestamped Storyboarding** — Frame-precise 0-3s/4-8s/9-12s/13-15s control for all video models
- 📐 **Segmented Extension** — Handoff-frame strategy for videos exceeding 15 seconds
- 🎯 **Progressive Clarification** — Step-by-step conversational flow (duration → aspect → assets → style), never overwhelms users
- 🔍 **Scene-specific Negative Prompts** — Pre-built lookup tables for e-commerce, portrait UGC, cinematic, general video, and landscape
- ✅ **4-Question Validation Checklist** — Every prompt self-verified before delivery
- 🎬 **6 Cinematic Role Templates** — Director, DP, Storyboarder, VFX Artist, Colorist, Sound Designer
- 📊 **Layered Complexity Format** — [ESTABLISHING]/[CAMERA]/[LIGHTING]/[MOTION]/[STYLE] tag-based precision control
- 🎥 **Motion Intensity Tiers** — Subtle / Moderate / Dynamic / Extreme, with exact keyword mapping
- 🏭 **Industry Vertical Support** — E-commerce, home textile, fashion, architecture, food photography
- 🌐 **Bilingual Dual-Channel Output** — EN explanation + ZH copy-paste-ready prompt, `@` tokens preserved in both
- 📋 **10 High-Frequency Issue Solutions** — ID drift, subtitle generation, logo watermark, style drift, twin character, extension jump, audio noise, pronunciation errors, voice mismatch
- 🏷️ **Subject Definition System** — `<主体N>` tag framework for cross-shot character consistency
- ✍️ **Special Character Convention** — Music `()` / SFX `<>` / Dialogue `{}` / Subtitles `【】` / VO `[VO]`
- 🧩 **Task Type Framework** — Reference / Edit / Extend / Combined, each with recommended syntax

## Model Coverage

### Image Generation (15 models)
**International**: Midjourney V7/V8.1, DALL-E 3, Stable Diffusion (SDXL/SD3), Flux Pro, GPT Image 2, Nano Banana Pro
**Chinese Domestic**: Jimeng (Seedream), Tongyi Wanxiang, Kling, Wenxin Yige, Zhipu CogView, Tencent Hunyuan HY (HY-Image-V3.0)

### Video Generation (12 models)
**International**: Seedance 2.0, Kling 3.0, Sora 2, Runway Gen-4/4.5, Pika 2.0, Veo 3/3.1, Luma Dream Machine v3
**Chinese Domestic**: Tongyi Wanxiang (Wan 2.5/2.6/2.7), Hailuo 3.0, Vidu, HappyHorse, HunyuanVideo 1.5

### Multimodal Understanding (3 models)
Tencent Hunyuan HY: Vision 1.5, T1 Vision (deep reasoning), Video Vision

## Quick Start

After loading the skill, simply say:

- *"Write a product showcase video prompt with Seedance 2.0 for a ceramic mug"*
- *"Create a Midjourney prompt for a fashion editorial in Chinese ink-wash style"*
- *"Convert this Kling 3.0 prompt to Sora 2 format"*
- *"Generate a timestamped storyboard for a 15-second xianxia battle scene"*
- *"I need a Hailuo 3.0 music video prompt with beat-sync"*

## Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **v2.1.0** | 2026-05-28 | Task type framework (Reference/Edit/Extend), subject definition system, special character conventions, 10 high-frequency issue solutions |
| v2.0.0 | 2026-05-28 | 9 advanced techniques: progressive clarification, timestamped storyboarding, segmented extension, advanced camera combos, layered complexity, motion intensity tiers, depth layering, mode decision logic, bilingual dual-channel |
| v1.4.0 | 2026-05-28 | Added HappyHorse (Alibaba 15B) |
| v1.3.0 | 2026-05-28 | Tencent Hunyuan HY full multimodal family |
| v1.2.0 | 2026-05-28 | Added GPT Image 2 + Nano Banana Pro |
| v1.1.0 | 2026-05-28 | Added 9 Chinese domestic models |
| v1.0.0 | 2026-05-28 | Initial release (international models) |

## Roadmap

### v2.5 — Video Full Pipeline (ETA: 4 weeks)
- 6 dedicated cinematic role prompt templates with per-model variants
- End-to-end video production workflow (storyboard → shoot → VFX → color → sound)

### v3.0 — New Modalities + Self-Evolution (ETA: 8 weeks)
- 🎵 Audio/Music generation (Suno, Udio, Stable Audio)
- 🧊 3D Model generation (Meshy, Tripo, Luma)
- Weekly automated model capability refresh pipeline
- A/B prompt comparison framework

### v3.5 — Toolchain + Multi-Platform (ETA: 12 weeks)
- `prompt_generator.py` — intent-to-prompt auto-generation
- `prompt_translator.py` — cross-model batch conversion
- `prompt_scorer.py` — automated quality scoring (PromptScore)
- Distribution: ClawdHub + GitHub + SkillHub + Kouzihub + Coze + Feishu

### v4.0 — Ecosystem (ETA: 16 weeks)
- Community knowledge base integration with automated retrieval
- End-to-end automation: intent → generation → scoring → optimization closed loop
- 1000+ real-world case library
- Home textile industry deep integration module

## Installation

```bash
# WorkBuddy / OpenClaw
openclaw skills install niuma-prompt

# ClawdHub
npx skills add niuma-prompt

# Manual
cp SKILL.md ~/.workbuddy/skills/niuma-prompt/
```

## License

MIT © Super niuma

---

_Built by Super niuma — 2026_
