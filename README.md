# 🎬 Awesome Seedance 2.5 — API, Prompts & Complete Guide

> The ultimate resource for Seedance 2.5 — ByteDance's next-gen AI video generation model. Covers API integration, prompt engineering, camera controls, multimodal workflows, and 30+ curated production-ready prompt examples.

[![Seedance 2.5](https://img.shields.io/badge/Seedance-2.5-blue)](https://seed.bytedance.com)
[![Powered by MuAPI](https://img.shields.io/badge/Powered%20by-MuAPI-6366f1?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0tMSAxNHYtNGgtMnYtMmg0djZoLTJ6bTAtOFY2aDJ2MmgtMnoiLz48L3N2Zz4=)](https://muapi.ai?utm_source=github&utm_medium=badge&utm_campaign=awesome-seedance-2.5)
[![Stars](https://img.shields.io/github/stars/Anil-matcha/awesome-seedance-2.5-api-prompts?style=social)](https://github.com/Anil-matcha/awesome-seedance-2.5-api-prompts)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📺 Video Tutorial

[![How to Access Seedance 2.5 API (Step-by-Step Guide)](https://img.youtube.com/vi/Uszlw7H4VP4/maxresdefault.jpg)](https://www.youtube.com/watch?v=Uszlw7H4VP4)

**[How to Access Seedance 2.5 API (Step-by-Step Guide)](https://www.youtube.com/watch?v=Uszlw7H4VP4)** — a full walkthrough of getting an API key and making your first Seedance 2.5 call via [MuAPI](https://muapi.ai/seedance-2.5?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5).

---

## Related Projects

- [Seedance-2.5-API](https://github.com/SamurAIGPT/Seedance-2.5-API) — Python wrapper for the Seedance 2.5 API — text-to-video, image-to-video, character consistency

- [Seedance-2-API](https://github.com/Anil-matcha/Seedance-2-API) — Python SDK for Seedance 2.x API — text-to-video, image-to-video, character consistency
- [seedance2-comfyui](https://github.com/Anil-matcha/seedance2-comfyui) — Run Seedance 2 inside ComfyUI with custom nodes
- [seedance2.5-comfyui](https://github.com/Anil-matcha/seedance2.5-comfyui) — Native Seedance 2.5 ComfyUI custom nodes and example workflows
- [n8n-nodes-seedance2](https://github.com/Anil-matcha/n8n-nodes-seedance2) — Automate Seedance 2 video generation in n8n workflows
- [seedance-2.0-watermark-remover](https://github.com/SamurAIGPT/seedance-2.0-watermark-remover) — Remove watermarks from Seedance generated videos
- [seedance-2-generator](https://github.com/SamurAIGPT/seedance-2-generator) — Ready-made Next.js SaaS built on Seedance 2
- [ai-creator-academy](https://github.com/Anil-matcha/ai-creator-academy) — free curriculum teaching creators how to monetize Seedance and other generative AI models
- [seedance-2-mcp](https://github.com/Anil-matcha/seedance-2-mcp) — Focused MCP server for Seedance 2 generation from AI assistants
- [seedance-2.5-mcp](https://github.com/Anil-matcha/seedance-2.5-mcp) — Focused MCP server for Seedance 2.5 Preview generation with 720p/480p selection

---
- [awesome-flux-3-api-prompts](https://github.com/Anil-matcha/awesome-flux-3-api-prompts) — FLUX 3 API guide, prompts, and parameters
- [Flux-3-Dev-API](https://github.com/Anil-matcha/Flux-3-Dev-API) — Python wrapper for Black Forest Labs' FLUX 3 (Dev variant) — text-to-image, image-to-image, text-to-video, image-to-video

## Table of Contents

- [What is Seedance 2.5?](#what-is-seedance-25)
- [Seedance 2.5 vs 2.0 — What's New](#seedance-25-vs-20--whats-new)
- [Capabilities](#capabilities)
- [API Reference (MuAPI)](#api-reference-muapi)
  - [Text-to-Video](#1-seedance-25-text-to-video-t2v)
  - [Image-to-Video](#2-seedance-25-image-to-video-i2v)
  - [Spicy (T2V / I2V)](#2b-seedance-25-spicy-t2v--i2v)
  - [First & Last Frame](#3-seedance-25-first--last-frame)
  - [Omni Reference](#4-seedance-25-omni-reference)
  - [Polling for Results](#polling-for-results)
  - [Parameters](#muapi-parameters)
- [Prompt Engineering Guide](#prompt-engineering-guide)
  - [The 6-Step Formula](#the-6-step-formula)
  - [Camera Movement Vocabulary](#camera-movement-vocabulary)
  - [Lighting Keywords](#lighting-keywords)
  - [Multimodal Reference Syntax](#multimodal-reference-syntax)
  - [Shot Script Format](#shot-script-format-advanced)
- [Prompt Library](#prompt-library)
  - [🌟 Featured Cinematic Prompts](#-featured-cinematic-prompts)
  - [🎨 Visual Effects & Typography](#-visual-effects--typography)
  - [👗 Fashion & Lifestyle](#-fashion--lifestyle)
  - [🌊 Nature & Documentary](#-nature--documentary)
  - [📦 Advertising & Product](#-advertising--product)
  - [🎭 Cultural & Artistic](#-cultural--artistic)
  - [🚀 Sci-Fi & Concept Film](#-sci-fi--concept-film)
  - [🔗 Multi-Reference Generation](#-multi-reference-generation)
  - [✂️ Video Editing & Compositing](#️-video-editing--compositing)
  - [🎬 Cinematic / Film Templates](#-cinematic--film-templates)
  - [📱 Social Media / UGC Templates](#-social-media--ugc-templates)
  - [🌸 Anime & Stylized Templates](#-anime--stylized-templates)
  - [🏎️ Multi-Shot Sequence Templates](#️-multi-shot-sequence-templates)
  - [🛍️ E-Commerce & Product Display](#️-e-commerce--product-display)
  - [🍽️ Food & Beverage](#️-food--beverage)
  - [💄 Beauty & Fashion Close-Ups](#-beauty--fashion-close-ups)
- [Browse Prompts by Category](#browse-prompts-by-category)
- [Advanced Workflows](#advanced-workflows)
- [Tips & Best Practices](#tips--best-practices)
- [API Providers Comparison](#api-providers-comparison)
- [FAQ](#faq)
- [Resources & Links](#resources--links)

---

## What is Seedance 2.5?

**Seedance 2.5** is ByteDance's latest AI video generation model, built on the Seed video foundation. It is a significant upgrade over Seedance 2.0, with a focus on:

- **30-second native video** — generate longer single-clip outputs for ads, product demos, educational clips, and story-driven sequences
- **Multi-shot storytelling** — generate cinematically coherent narratives from a single prompt
- **Character & brand consistency** — maintain the same face, clothing, and style across all shots
- **Director-grade camera control** — precise rack focus, crane shots, whip pans, and more
- **Native audio synchronization** — tighter lip-sync and sound design baked in at generation time
- **Better physics & motion stability** — realistic fluid dynamics, cloth simulation, and crowd motion
- **Rich multimodal references** — guide generations with up to 20 images, 6 reference video clips, and 6 reference audio clips per request (Omni Reference endpoint)
- **Controllable video editing** — adjust backgrounds, replace products, change models, or refine local details while preserving the larger shot
- **Sharper long-clip quality** — noticeably less blur build-up even after 3 consecutive video extensions
- **Better instruction following** — more accurate on negative prompts (e.g. "no subtitles / no bgm"), timestamp-based shot instructions, and multi-language prompts
- **Fewer generation artifacts** — reduced duplicate-person ("twinning") glitches, reduced celebrity-face/IP likeness risk, and less carried-over source-platform watermarking

Seedance 2.5 accepts **text, images, video clips, and audio** as input and outputs video with synchronized audio in **MP4** (standard, default) or **MOV** (high color-fidelity, recommended for multi-step video extension/editing) format.

---

## Seedance 2.5 vs 2.0 — What's New

| Feature | Seedance 2.0 | Seedance 2.5 |
|---|---|---|
| Multi-shot coherence | Basic | Director-grade, single-pass |
| Character consistency | Good | Excellent (cross-shot) |
| Camera controls | Standard | Advanced (rack focus, crane, whip pan) |
| Audio sync / lip-sync | Present | Enhanced, tighter |
| Physics / motion | Standard | Improved cloth & fluid sim |
| Style fusion | Basic | Brand-safe style fusion |
| Max resolution (launch) | 480p / 720p | 480p / 720p (1080p & 4K planned, not yet enabled) |
| Max duration | 15s | 30s native single clip |
| Video editing | Not supported | Background swap, object removal, style transfer |
| Reference images | Up to 9 | Up to 20 (Omni Reference) |
| Reference video clips | Up to 3 (15s total) | Up to 6 (Omni Reference) |
| Reference audio clips | Up to 3 (15s total) | Up to 6 (Omni Reference) |
| Output container | MP4 only | MP4 (default) or MOV (yuv444p, high color-fidelity) |

---

## Capabilities

- **Text-to-Video** — generate video from a text prompt alone
- **Image-to-Video** — animate a still image with motion
- **Video-to-Video** — restyle or extend an existing video clip
- **Audio-to-Video** — sync visuals to a provided audio track
- **Multi-modal** — combine text + image + audio in one generation
- **AI Dance / Motion Transfer** — make people, pets, or characters perform dance movements
- **Video Editing** — inpaint, remove objects, transfer styles while preserving composition

### Supported Input Formats
- Images: JPEG, PNG, WebP, BMP, TIFF, GIF, HEIC/HEIF (up to 20 images per request via Omni Reference)
- Video: MP4, MOV, 480p–4K source resolution (up to 6 reference clips via Omni Reference)
- Audio: WAV, MP3 (up to 6 reference clips via Omni Reference)

### Output Specs
- Resolutions: 480p, 720p at launch (1080p and 4K planned, not yet enabled)
- Durations: 4–30 seconds per clip
- Aspect Ratios: `21:9` `16:9` `4:3` `1:1` `3:4` `9:16`
- Format: MP4 (H.264, yuv420p, AAC audio — default) or MOV (H.264 4:4:4, yuv444p, PCM audio — higher color fidelity, best for repeated extension/editing)

---

## API Reference (MuAPI)

The fastest way to access Seedance 2.5 via API is through **[MuAPI](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)** — a unified media API gateway with reliable uptime, competitive pricing, and no per-provider account setup.

**Get your API key:** [muapi.ai](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

Seedance 2.5 is an early-access build on MuAPI, gated to Pro/Business plan accounts. It ships as 8 endpoints — a 720p and 480p tier for each of Text-to-Video, Image-to-Video, First & Last Frame, and Omni Reference.

```bash
x-api-key: YOUR_MUAPI_KEY
Base URL: https://api.muapi.ai/api/v1
```

---

### 1. Seedance 2.5 Text-to-Video (T2V)

**Endpoint:** `POST https://api.muapi.ai/api/v1/seedance-2.5-text-to-video` ($0.60/sec, 720p)
**480p tier:** `POST https://api.muapi.ai/api/v1/seedance-2.5-text-to-video-480p` ($0.30/sec)
**Playground:** [720p](https://muapi.ai/playground/seedance-2.5-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [480p](https://muapi.ai/playground/seedance-2.5-text-to-video-480p?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.5-text-to-video" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "A lone astronaut walks across a red Martian desert at golden hour, wide angle, cinematic",
      "aspect_ratio": "16:9",
      "duration": 10
  }'
```

**Python:**
```python
import requests

response = requests.post(
    "https://api.muapi.ai/api/v1/seedance-2.5-text-to-video",
    headers={"x-api-key": "YOUR_API_KEY", "Content-Type": "application/json"},
    json={
        "prompt": "A lone astronaut walks across a red Martian desert at golden hour, wide angle, cinematic",
        "aspect_ratio": "16:9",
        "duration": 10
    }
)
request_id = response.json()["request_id"]
```

---

### 2. Seedance 2.5 Image-to-Video (I2V)

**Endpoint:** `POST https://api.muapi.ai/api/v1/seedance-2.5-image-to-video` ($0.60/sec, 720p)
**480p tier:** `POST https://api.muapi.ai/api/v1/seedance-2.5-image-to-video-480p` ($0.30/sec)
**Playground:** [720p](https://muapi.ai/playground/seedance-2.5-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [480p](https://muapi.ai/playground/seedance-2.5-image-to-video-480p?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

This endpoint takes a single `image_url` (not a list) plus a `prompt`.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.5-image-to-video" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "The camera slowly pushes in as she turns to face us, hair blowing in the wind",
      "image_url": "https://example.com/photo.jpg",
      "aspect_ratio": "16:9",
      "duration": 8
  }'
```

**Python:**
```python
response = requests.post(
    "https://api.muapi.ai/api/v1/seedance-2.5-image-to-video",
    headers={"x-api-key": "YOUR_API_KEY", "Content-Type": "application/json"},
    json={
        "prompt": "The camera slowly pushes in as she turns to face us, hair blowing in the wind",
        "image_url": "https://example.com/photo.jpg",
        "aspect_ratio": "16:9",
        "duration": 8
    }
)
request_id = response.json()["request_id"]
```

---

### 2b. Seedance 2.5 Spicy (T2V / I2V)

**Endpoints:** `POST https://api.muapi.ai/api/v1/seedance-2.5-spicy-text-to-video` · `POST https://api.muapi.ai/api/v1/seedance-2.5-spicy-image-to-video` ($0.60/sec, 720p only — no 480p tier)
**Playground:** [T2V](https://muapi.ai/playground/seedance-2.5-spicy-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [I2V](https://muapi.ai/playground/seedance-2.5-spicy-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

Relaxed-moderation siblings of the flagship T2V/I2V models. Same request shape and pricing as the standard 720p tier, with a more permissive content policy.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.5-spicy-text-to-video" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "A dramatic, high-contrast noir scene, bold lighting, cinematic",
      "aspect_ratio": "16:9",
      "duration": 8
  }'
```

---

### 3. Seedance 2.5 First & Last Frame

**Endpoint:** `POST https://api.muapi.ai/api/v1/seedance-2.5-first-last-frame` ($0.60/sec, 720p)
**480p tier:** `POST https://api.muapi.ai/api/v1/seedance-2.5-first-last-frame-480p` ($0.30/sec)
**Playground:** [720p](https://muapi.ai/playground/seedance-2.5-first-last-frame?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [480p](https://muapi.ai/playground/seedance-2.5-first-last-frame-480p?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

Generates a smooth keyframe-driven transition between a start and end image. Pass `images_list` as exactly `[first_frame_url, last_frame_url]`.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.5-first-last-frame" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "Smooth cinematic transition, camera drifts forward as the scene morphs from day to night",
      "images_list": ["https://example.com/start-frame.jpg", "https://example.com/end-frame.jpg"],
      "aspect_ratio": "16:9",
      "duration": 8
  }'
```

---

### 4. Seedance 2.5 Omni Reference

**Endpoint:** `POST https://api.muapi.ai/api/v1/seedance-2.5-omni-reference` ($0.72/sec, 720p)
**480p tier:** `POST https://api.muapi.ai/api/v1/seedance-2.5-omni-reference-480p` ($0.36/sec)
**Playground:** [720p](https://muapi.ai/playground/seedance-2.5-omni-reference?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [480p](https://muapi.ai/playground/seedance-2.5-omni-reference-480p?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

Blends up to 20 reference images, 6 reference video clips, and 6 reference audio files into one guided generation — use images for environment/style, videos for camera motion and rhythm, audio for mood.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.5-omni-reference" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "Blend the reference images into a neon-lit night market scene, matching the camera rhythm and mood of the reference video and audio",
      "images_list": ["https://example.com/ref1.jpg", "https://example.com/ref2.jpg"],
      "videos_list": ["https://example.com/ref-motion.mp4"],
      "audios_list": ["https://example.com/ref-mood.mp3"],
      "aspect_ratio": "16:9",
      "duration": 10
  }'
```

---

### Polling for Results

All MuAPI endpoints return a `request_id`. Poll until `status` is `completed`:

```python
import time, requests

def wait_for_result(request_id, api_key, poll_interval=5, timeout=300):
    start = time.time()
    while time.time() - start < timeout:
        res = requests.get(
            f"https://api.muapi.ai/api/v1/status/{request_id}",
            headers={"x-api-key": api_key}
        ).json()
        if res["status"] == "completed":
            return res["outputs"][0]
        elif res["status"] == "failed":
            raise Exception(res.get("error", "Generation failed"))
        time.sleep(poll_interval)
    raise TimeoutError("Generation timed out")

video_url = wait_for_result(request_id, "YOUR_API_KEY")
print(f"Video: {video_url}")
```

---

### MuAPI Parameters

| Parameter | Type | Options | Default | Description |
|---|---|---|---|---|
| `prompt` | string | — | required | Text description of the desired video |
| `image_url` | string (URL) | — | — | Single input image — Image-to-Video endpoint only |
| `images_list` | array (URLs) | — | — | First & Last Frame: exactly 2 URLs `[first_frame, last_frame]`. Omni Reference: up to 20 reference images |
| `videos_list` | array (URLs) | — | — | Omni Reference only — up to 6 reference video clips |
| `audios_list` | array (URLs) | — | — | Omni Reference only — up to 6 reference audio clips |
| `aspect_ratio` | string | `16:9` `9:16` `1:1` `4:3` `3:4` `21:9` `9:21` | `16:9` | Output aspect ratio |
| `duration` | int | `4`–`30` | `5` | Duration in seconds |
| `seed` | int | `-1`–`4294967295` | random | Reproducible generation seed (`-1` = random) |
| `webhook_url` | string (URL) | — | — | Optional webhook to notify on completion |

> **Playground:** [muapi.ai/playground](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

---

### Resolution → Pixel Dimensions

Seedance 2.5 adjusted the 480p pixel dimensions slightly from Seedance 2.0. 720p is unchanged.

| Aspect Ratio | 480p (2.5) | 720p |
|---|---|---|
| `16:9` | 854×480 | 1280×720 |
| `9:16` | 480×854 | 720×1280 |
| `1:1` | 640×640 | 960×960 |
| `4:3` | 752×560 | 1112×834 |
| `3:4` | 560×752 | 834×1112 |
| `21:9` | 992×432 | 1470×630 |

---

### Native API Parameters (Direct Volcano Ark / BytePlus Integration)

If you're calling Seedance 2.5 directly rather than through MuAPI's simplified schema, these are the full set of public request parameters:

| Parameter | Type | Description |
|---|---|---|
| `duration` | int | Video length in seconds. Range: `-1` (auto) or `4`–`30`. Default `5`. |
| `resolution` | string | `480p` or `720p` (1080p/4K planned). Default `720p`. |
| `ratio` | string | `16:9` `4:3` `1:1` `3:4` `9:16` `21:9` `adaptive`. `adaptive` lets the model pick the best ratio from the first frame / prompt. |
| `output_format` | string | `mp4` (default, standard color) or `mov` (yuv444p/yuv444p10le, best for extend/edit chains — recommend using `mov` for both input and output when extending a clip repeatedly). |
| `bitrate_mode` | string | `standard` (CRF 18) or `high` (CRF 11, 3–5× larger file, more detail). Default `high` for Seedance 2.5. |
| `camera_fixed` | bool | `true` biases the model toward a locked-off camera. Default `false`. |
| `generate_audio` | bool | Native Volcano Ark parameter for synchronized voice/SFX/music generation; not yet confirmed available on the current MuAPI early-access endpoints. |
| `return_last_frame` | bool | Returns the final frame as a watermark-free PNG for chaining into another generation. |
| `watermark` | bool | Whether the output carries a visible watermark. |
| `content.role` | string | Marks a reference asset's purpose: `first_frame`, `last_frame`, `reference_image`, `reference_video`, `reference_audio`. |
| `seed` | int | `-1` to `4294967295`. Same seed does not guarantee identical output, but keeps generations in the same neighborhood. |

---

## Prompt Engineering Guide

### The 6-Step Formula

Structure your prompts using this formula for best results. **The first 20–30 words carry the most weight** — Seedance locks in the subject and core action from the opening.

```
[SUBJECT] + [ACTION] + [ENVIRONMENT] + [CAMERA] + [STYLE] + [CONSTRAINTS]
```

**Target length: 60–100 words.**

**Example:**
```
A young chef (subject) carefully plates a dish with tweezers (action) 
in a Michelin-star restaurant kitchen at midnight (environment), 
close-up rack focus from hands to face (camera), 
warm tungsten lighting, cinematic 35mm film grain (style), 
no jump cuts, maintain consistent kitchen background (constraints).
```

---

### Camera Movement Vocabulary

Use these exact terms in your prompts for precise camera control:

| Movement | Prompt Keyword |
|---|---|
| Move toward subject | `slow push in` / `dolly in` |
| Move away from subject | `pull back` / `dolly out` |
| Horizontal slide | `tracking shot left/right` |
| Vertical rise | `crane up` / `boom up` |
| Follow subject | `steadicam follow shot` |
| Rotate around subject | `orbit shot` / `360 arc` |
| Quick pan | `whip pan left/right` |
| Lock still | `static shot` / `locked off camera` |
| Overhead | `bird's eye view` / `top-down` |
| Low angle | `worm's eye view` / `low angle` |
| Shaky, urgent | `handheld camera` |
| Smooth glide | `gimbal shot` |
| Background blur | `rack focus to subject` |
| First-person drone | `FPV continuous long take` |

---

### Lighting Keywords

> **Lighting descriptions have the biggest single impact on video quality.** One strong lighting keyword beats ten adjectives.

| Look | Keyword |
|---|---|
| Film-quality warmth | `golden hour cinematography` |
| Night scene | `tungsten practical lighting` |
| Drama / mystery | `chiaroscuro lighting` |
| Studio clean | `soft box three-point lighting` |
| Neon / cyberpunk | `neon-drenched night scene` |
| Documentary | `natural available light` |
| Horror | `harsh under-lighting` |
| Beauty / fashion | `butterfly lighting` |
| Outdoor overcast | `diffused cloudy daylight` |
| Underwater | `volumetric light beams through water` |
| Sci-fi epic | `high dynamic range, realistic sci-fi texture` |

---

### Multimodal Reference Syntax

`@Tags` are a prompt-writing convention, not a literal API field — the actual request just sends `images_list` / `videos_list` / `audios_list` (see [MuAPI Parameters](#muapi-parameters)) alongside a `prompt` that references them in order. Referencing assets by position in your prose (`@Image1`, `@Video1`, `@Audio1`) helps the model map each reference to the right role:

```
@Image1 — reference a still image input
@Image2 — second image input
@Video1 — reference a video clip input
@Audio1 — reference an audio file input
```

**Example multimodal prompt:**
```
@Image1 is the main character. @Audio1 is the background score. 
She walks through a neon-lit Tokyo alley at night, camera tracking 
alongside her, cinematic depth of field, rain-soaked streets reflecting 
the neon signs, sync the footsteps to @Audio1.
```

---

### Shot Script Format (Advanced)

For multi-shot videos, use timecodes to control pacing:

```
[0:00–0:03] WIDE SHOT — Aerial view of a volcanic island at sunrise, slow push in.
[0:03–0:08] MEDIUM SHOT — A researcher emerges from a tent, looks toward the volcano, rack focus to her face.
[0:08–0:15] CLOSE-UP — Her eyes reflecting the distant glow, golden hour light, handheld slight tremor.
Style: BBC Planet Earth, 4K cinematic, natural sound design.
```

---

## Prompt Library

### 🌟 Featured Cinematic Prompts

#### 1. Steampunk Clockwork Odyssey

```
A premium, highly cinematic 30-second 3D motion-graphics sequence in an exquisite steampunk and vintage miniature-landscape style, paired with continuous, fluid orbiting and penetrating camera movement.
[0-10s]: Macro close-up of an antique brass clock face. It miraculously unfolds layer by layer into interlocking rotating gear rings and volumetric mist. The camera dives downward through the gears as a mechanical ornithopter spirals upward from a miniature canyon made of stacked aged books.
[10-20s]: The camera glides forward along the ornithopter's path and seamlessly passes into a rapidly spinning ornate brass zoetrope, where galloping mechanical horses appear as projected light and shadow. The projection leaps out of the box, instantly transforming into a brass levitating cable car traveling along glowing copper rails through a forest of mechanical gears, bathed in cinematic golden-hour light.
[20-30s]: The camera elegantly pans downward. Below the cable car, a delicate wind-up wooden mechanical sailing ship cuts through deep-blue glass waves. At the end of the waves, the scene seamlessly evolves into a glowing giant moon. Silhouettes of explorers holding swaying lanterns struggle along a crystal-vein mountain ridge beneath the stars. The camera spirals smoothly outward through ethereal clouds and returns to the grand ticking brass clock face.
Technical specifications: hyper-real mechanical textures, rich brass and gold tones, cinematic shallow depth of field. Smooth, continuous seamless travel shots, with a strong epic feeling and fantasy-adventure atmosphere.
```

- **Best for:** T2V — 30s
- **Aspect Ratio:** 16:9

---

#### 2. Crystal Ball Match-Cut Brand Film

```
A fast-paced, cinematic match-cut short film synchronized to dynamic electronic beats. A flawless crystal ball remains fixed at the center of the frame throughout, with a glowing logo engraved inside. The crystal ball stays in extremely sharp focus while the background switches at high speed in perfect sync with powerful music hits.
Scene 1: Macro close-up. Cinematic water splashes fly around the crystal ball, refracting complex light and shadow.
Scene 2: Morning vintage cafe. The crystal ball sits on a raw wooden tabletop; the background shows rising coffee steam and blurred commuters outside the window.
Scene 3: Golden-hour evening. A skateboarder casually tosses and catches the crystal ball with one hand; the background is a rapidly receding street scene with beautiful sunset backlight.
Scene 4: A feverish music festival. Hands raise the crystal ball high, refracting dazzling stage lasers in the background.
Scene 5: A lively family-party dining table. The crystal ball rests in the center, surrounded by blurred figures clinking glasses and reaching for food.
Scene 6: A dim cinema. Two hands hold the crystal ball while faint light from a giant screen flows across its surface.
Scene 7: The crystal ball sits on a violently vibrating speaker diaphragm, then cuts seamlessly with the music climax to the center of spinning DJ turntables.
Scene 8: Outdoor camping at night. The background becomes warm campfire light and swaying string-light bokeh.
Final toss: On the final bass hit, the crystal ball is thrown high out of the top of the frame. Cut instantly to a pure black background, with minimalist white text appearing in the center.
Edit tightly to the energetic BGM rhythm with beat-matched transitions. Use top-tier cinematic color grading, realistic glass refraction and transmission, complex ray tracing, and global illumination. Keep the subject ultra-sharp while the background carries strong dynamic blur and high visual impact.
```

- **Best for:** T2V — 30s
- **Aspect Ratio:** 16:9

---

#### 3. Window-to-Eye Concept Film

> Requires 5 reference images passed as `@image1`–`@image5`

```
A cinematic brand-concept short film. @image1 is the first frame. The image shakes slightly as the camera slowly pushes in toward tree shadows rapidly receding outside the window. The retreating shadows accelerate, then suddenly cut to @image2 where the speed slows dramatically and the camera glides gently forward along a stream with birdsong and flowers.
The camera tilts downward into the water, with bubble sound effects underwater. A group of orange jellyfish swims gracefully past the lens @image3. The camera slowly pulls back; a school of small fish crosses the frame and moves from the water into the window interior @image4. A girl looks left and right, watching the fish.
The camera slowly pulls back and the image falls out of focus. It refocuses as the picture becomes clear again, then switches to the rhythm of the music: Chinese garden flower window @image5 with rotating light, church stained-glass window, airplane cabin window, dome skylight, bay window, venetian blinds, European dormer window, door peephole, camera viewfinder frame, bird eye, and finally a human-eye close-up.
The image holds on the human eye close-up. The eye closes and the screen goes black, then suddenly opens again with a brand reveal at the center of the eye on a bass hit.
```

- **Best for:** I2V — 30s, 5 reference images
- **Aspect Ratio:** 16:9

---

### 🎨 Visual Effects & Typography

#### 4. Multilingual Creative Typography Loop

```
A 15-second seamless looping creative typography animation video, 4K, 30 fps. Each language lasts about 1.2 seconds. Transitions are created through text dissolving, morphing, or drifting into particles, with no hard cuts. The background music has a clear rhythm and strong beat hits.
0-1.2s Chinese "创造" (Create): Op-art pure black background. Black-and-white concentric circles expand outward from the center to form a visual tunnel. The white 3D Chinese characters slowly protrude from the center toward the camera in bold sans-serif form, with subtle edge shadows. The circles ripple and distort like water as the text advances.
1.2-2.4s English "Create": The Chinese characters dissolve into ink-like particles and reassemble into "Create". Neon cyan and magenta gradients flow across the letters. The background becomes a dark grid with scanning light beams. The word stretches slightly with elastic motion on the beat.
2.4-3.6s Japanese: The English letters shatter into paper-like fragments and fold into Japanese kanji. The background becomes warm washi paper texture with soft gold dust. The characters appear as brush ink, then gain a glossy lacquer edge.
3.6-4.8s Korean: Ink strokes curve into Hangul. The background shifts to a clean white design space with floating geometric blocks. The text is pearl white with a fine blue rim light.
4.8-6.0s French: Letters bloom like perfume vapor over a deep burgundy background. The accent mark appears as a small sparkling stroke, landing precisely on the beat.
6.0-7.2s Spanish: Warm orange and deep blue mosaic tiles rotate into place. The text becomes sunlit, thick, and sculptural, with long shadows sliding across it.
7.2-8.4s Arabic: Particles sweep from right to left and become elegant Arabic calligraphy. The background turns midnight blue with gold star-like specks. The strokes glow softly and flow like liquid metal.
8.4-9.6s Hindi: The letters emerge from colorful powder and festival-like particles. The background carries saffron, teal, and pink gradients, with soft cloth texture.
9.6-10.8s Thai: The typography forms from water ripples and glass reflections. The background is a luminous tropical green with highlights like sunlight through leaves.
10.8-12.0s Russian: The text appears as frosted crystal on a cold blue background. Fine ice particles fly outward as the letters lock into place.
12.0-13.2s Portuguese: The letters swing in with a playful tiled-wave motion, using bright green and yellow accents. The background feels clean, sunny, and energetic.
13.2-15.0s Finale: All words from different languages orbit inward as particles and assemble around the central text. The background becomes a deep black stage with a radiant circular light ring. The final frame holds briefly, then the light ring collapses back into the first concentric-circle tunnel, creating a perfect loop.
```

- **Best for:** T2V — 15s loop
- **Aspect Ratio:** 16:9

---

### 👗 Fashion & Lifestyle

#### 5. Haute Couture Dream Bokeh Film

```
Overall style: a 30-second couture brand-level visual blockbuster with strong cinematic polish and premium texture. Emphasize dreamy bokeh, silky motion-blur transitions, volumetric lighting, and ultra-real material detail.
[0-5s] Dreamlike prologue and macro close-up: an ultra-high-definition macro shot of a slender hand reaching into the air. The fingertips touch colorful star-like bokeh. As the fingers pass through the light, the points of light turn into flowing silk threads and wrap around the wrist.
[5-12s] High-fashion entrance: a model in an elegant couture silhouette walks through a dark reflective space. The dress surface alternates between translucent gauze, liquid metal, and glittering crystals. The camera circles slowly, catching rim light and delicate fabric motion.
[12-20s] Surreal transformation: the bokeh expands into floating flower petals and glass fragments. The model turns gently; light flows across the face and shoulders, and the scene transitions through smooth motion blur into a brighter dreamlike stage.
[20-30s] Finale: the model pauses under a halo of warm light. Silk, petals, and crystal particles spiral upward and dissolve into a clean brand-style ending frame. Keep the tone refined, dreamlike, luxurious, and cinematic.
```

- **Best for:** T2V — 30s
- **Aspect Ratio:** 3:4

---

#### 8. Retro Suede Boots Brand Concept Film

```
A 30-second premium brand-concept short film with strong visual tension. The opening uses a surreal upside-down perspective. The camera flips with gravity to show a model wearing vintage suede boots stepping lightly across rolling red dunes. Macro close-ups reveal the matte nap of the boot surface and coarse red sand grains clinging to it.
Then cut into a montage full of weightlessness and dreamlike color: young male and female models fall backward lightly through amber wind-sand currents and cold edge rim light. The camera rapidly cuts to razor-sharp facial close-ups, where sand passes over eyelashes dusted with tiny gold particles. Fabrics, hair, and sand move in slow motion.
The middle section shows boots landing on mirror-like wet sand, footsteps turning into rippling liquid gold. The camera glides along the boot edge, then passes through a swirl of red dust into an abstract desert runway. Final shot: the model stands alone on a dune ridge at sunset. Red sand rises behind the body like a curtain, forming a clean, high-fashion brand silhouette. Use cinematic grading, premium commercial texture, realistic suede and sand detail, elegant rhythm, and no clutter.
```

- **Best for:** T2V — 30s
- **Aspect Ratio:** 16:9

---

### 🌊 Nature & Documentary

#### 6. Deep-Sea Coral Reef Jellyfish Scene

```
A deep-sea coral reef scene in a tropical underwater world with a blue overall tone. Large areas of healthy, thriving colorful living coral, including branching coral, brain coral, plate coral, and soft sea-fan coral. Schools of tropical fish swim naturally through the reef. The foreground is clear and vivid; the background gradually shifts blue-gray with reduced contrast. Natural light from above is filtered through seawater, forming soft volumetric beams. Tiny suspended particles and slight water movement are visible. Soft coral sways gently and fish movement is smooth and coordinated. Add a group of translucent pale-purple glowing jellyfish, 8 to 12 in total, slowly appearing in different sizes. Their umbrella bodies pulse gently with flowing tentacles, moving elegantly through the coral reef while the whole scene stays calm, realistic, and dreamlike.
```

- **Best for:** T2V — 10–15s
- **Aspect Ratio:** 1:1

---

#### 7. Floating Desert Museum Cinematic Film

```
Cinematic and premium. A golden desert at dawn. A minimalist white art-museum building floats above the dunes, with delicate stone texture and soft reflections on its surface. Sunlight passes through windblown sand to form volumetric rays, and distant dunes have clear layers. The shot begins with an ultra-wide desert panorama and slowly pushes forward through drifting sand into the floating building. Inside are suspended sculptures, translucent silk installations, and a character wearing a white robe, with the fabric moving naturally in the wind. The camera performs a smooth orbit around the character. At the end, the building walls slowly open, revealing a huge sunrise and a silent desert horizon.
```

- **Best for:** T2V — 20–30s
- **Aspect Ratio:** 1:1

---

### 🎭 Cultural & Artistic

#### 9. Peking Opera Heritage Short Film

```
A short film about the intangible cultural heritage of Peking Opera, cinematic, warm, restrained, and rooted in Eastern aesthetics. In a traditional troupe backstage area and handcraft workshop, an old master quietly makes opera headdresses, arranges costumes, and paints facial makeup. The hand details are delicate; silk threads, beads, pigments, and embroidered patterns have rich texture. A young apprentice watches seriously nearby, then carefully receives a tool and completes a small step under the master's guidance. The master straightens the apprentice's headwear and collar, as if gently passing on both a craft and an emotion. In the final shot, the young performer is fully dressed and stands beside the stage just before entering. A soft light illuminates the costume and side profile, creating a quiet, moving inheritance moment.
```

- **Best for:** T2V — 20–30s
- **Aspect Ratio:** 3:4

---

#### 12. Silk Road Pomegranate Folk Animation

```
Overall style: mineral-pigment flat animation with Eastern and Silk Road decorative aesthetics. Use cinnabar red, ochre, malachite green, ultramarine, and gold accents, with paper and mural textures. Keep the image layered and flat; do not use live-action photography or 3D realism. The rhythm moves from stillness to motion and back to stillness, emphasizing the abundant journey "from land to cup" with lively Western-Regions-style music.
Shot 1, first fruit on the branch, abundant opening (0-4s): Ochre and cinnabar color blocks bloom across a Silk Road painting surface. A pomegranate branch stretches in from the right. Leaves and fruit are outlined with decorative linework. A ripe pomegranate slowly appears, and gold dust glints around it.
Shot 2, fruit splitting and seeds flowing (4-9s): The pomegranate gently opens. Red seeds pour out like jewels, forming rhythmic patterns across the paper. The movement is decorative rather than realistic, with mineral-pigment particles and mural texture.
Shot 3, Silk Road journey (9-16s): The seeds become a flowing red path. Camels, merchants, patterned fabrics, and distant city silhouettes appear as flat decorative motifs. The camera pans horizontally like a handscroll, with layered mountains, clouds, and gold outlines.
Shot 4, harvest and sharing (16-23s): The red path returns to an orchard and a table. Hands place pomegranates, cups, and fruit plates in a symmetrical composition. The palette becomes richer and warmer, creating a festive sense of abundance.
Shot 5, final stillness (23-30s): Pomegranate juice fills a cup. The surface of the liquid reflects gold ornament patterns. The whole image slowly settles into a mural-like poster composition, with fruit, leaves, cups, and Silk Road motifs arranged around the center.
```

- **Best for:** T2V — 30s
- **Aspect Ratio:** 3:4

---

### 🚀 Sci-Fi & Concept Film

#### 10. Oceanic Civilization Epic Sci-Fi Film

```
Theme: "The Fallen Theater: Oceanic Civilization". Epic sci-fi, Dune x Interstellar atmosphere, no real human characters, sculptural lifeforms.
[0-5s | Cosmic opening: the ocean as planetary memory] A deep-blue ocean fills the panoramic frame. The deep water shows layered structures like a liquid universe inside a planet. The camera slowly descends vertically from high altitude, passing through clouds and sea mist into the ocean surface. The surface ripples like metallic film and refracts irregular cracks of sunlight.
[5-10s | Entering the ruins] The camera breaks through the water and continues downward. Giant stone columns and alien temple structures appear beneath the sea. They look like the remains of a lost civilization, covered in coral-like mineral growth. Volumetric light pierces the water, revealing suspended stardust-like particles.
[10-18s | Sculptural lifeforms] Massive sculptural organisms awaken among the ruins. Their bodies resemble stone, shell, and polished metal, moving slowly and solemnly. They do not behave like animals but like living monuments. The camera spirals around them, emphasizing scale, ritual, and sacred silence.
[18-25s | Collapse and reconstruction] The alien temple begins to collapse without chaos. Blocks, columns, and fragments float apart, then reorganize into a new monumental structure. Water currents, dust, and light wrap around the architecture as if an ancient ceremony is being performed.
[25-30s | Abyssal finale] The camera pulls back to reveal the entire oceanic civilization as a colossal temple hidden under the sea. A grand spiral of stardust and water forms above it. The image should feel sacred, lonely, immense, and cinematic, with high dynamic range and realistic sci-fi texture.
```

- **Best for:** T2V — 30s
- **Aspect Ratio:** 16:9

---

#### 11. Mechanical Flower Bloom Brand Film

```
Theme: "Mechanical Flower Bloom". Highlight the video-generation model's strengths in lighting, art detail, realism, camera movement, and cinematic character. The overall style is a high-end technology brand advertisement with strong visual impact. Use a one-shot macro push-in: begin with a metal flower bud in darkness, gradually enter the precision mechanical structure inside the petals, and end with the mechanical flower fully blooming as light spreads outward in a climactic frame. Require realistic physical lighting, refined metal and glass materials, delicate mechanical motion, stable composition, cinematic color grading, and no text.
```

- **Best for:** T2V — 15–30s
- **Aspect Ratio:** 1:1

---

### 🔗 Multi-Reference Generation

#### 13. One-Shot Rooms With Shifting Worlds

> Requires 5 reference images (`@image1`–`@image5`)

```
One continuous shot. The camera smoothly follows a person in a black coat (refer to @image1) walking from left to right through six connected rooms with different tones and atmospheres. Every room has the same structure: white walls, light herringbone wood floors, French double floor-to-ceiling windows, and white sheer curtains, based on @image2. Only the scenery outside the window and the indoor mood change. The protagonist walks at a constant speed and passes through every open doorway in the walls.
0-5s: First room, American-comic fight theme. The protagonist enters and fights a character (@image3), who is defeated.
5-10s: Second room, warm felt style. Outside the window is a sunflower field (@image4). The room has warm orange soft light, and a painter is painting sunflowers (@image5). After entering, the protagonist also becomes felt-style.
10-15s: Third room, sadness theme. The entire image becomes black-and-white comic freeze-frame animation. Rain falls outside, and the interior is cold, gray, and low-key. A person sits alone in an empty room.
15-20s: Fourth room, cyberpunk neon city. The windows reveal rain-soaked skyscrapers and colorful lights. Reflections slide across the floor and the protagonist's coat.
20-25s: Fifth room, festival night. Fireworks fill the sky outside, colorful indoor light flickers, and the protagonist is pulled into a cheering atmosphere.
25-30s: Final room, blank white space. The protagonist stands in the center and snaps their fingers. With the snap sound, the screen turns black and a brand word appears in the center. Overall: cinematic, high-fashion advertising style, with lighting determined entirely by the outside scene, strong emotional contrast, and no extra text.
```

- **Best for:** I2V — 30s, 5 reference images
- **Aspect Ratio:** 16:9

---

#### 17. Fruit Cookie Commercial

> Requires 1 reference image + 2 reference videos (`@image1`, `@video1`, `@video2`)

```
Bright, colorful advertising-film style. Fruit-flavored cookies are the main subject, including strawberry, apple, grape, and orange flavors. The strawberry flavor refers to @image1. Cookies and their matching fruits are arranged in strong, orderly geometric arrays. The overall image is clean, premium, and rhythmic. The opening uses fruit to quickly establish visual focus, referencing the composition of @video1 as the music beat enters. Then different flavored cookies are lined up neatly, with close-up cuts inspired by the motion and camera movement of @video2. In the climax, one cookie breaks open, fruit juice and crumbs burst outward in a controlled, beautiful way, and the four flavors rotate into a final symmetrical product layout. Use bright lighting, crisp textures, lively rhythm, and no messy background.
```

- **Best for:** I2V — 15–30s, mixed references
- **Aspect Ratio:** 16:9

---

#### 18. Desert Horned Lizard Grapefruit Ad

> Requires 1 reference image (`@image1`)

```
3D animated advertisement style, bright and transparent colors, with strong freshness and impact in the fruit flesh and juice. The overall feeling should be like a high-quality commercial animated short with a little exaggerated humor. The desert horned lizard character is cute, lively, and expressive, based on @image1. The visual texture should reference the soft natural light, delicate fuzz/skin texture, dreamy macro depth of field, and realistic yet playful feeling in the reference image.
0-3s: A sun-scorched desert. The air is distorted by heat, the sand is hot, and the distance looks smoky. A tiny desert horned lizard crawls slowly, looking exhausted and thirsty.
3-8s: The lizard discovers a giant grapefruit half-buried in the sand. The orange fruit flesh glows with juicy freshness. The lizard's eyes widen dramatically.
8-14s: It bites into the grapefruit. Juice bursts out like a small fountain. The desert sand around it instantly becomes cool and wet, with fruit pulp and droplets flying in slow motion.
14-20s: The fruit juice expands into a sparkling orange sea. The lizard is splashed into the water and pops up with a confused expression. The sea surface glitters like juice lit by sunlight. Use exaggerated splashing and wave sounds with comic timing.
20-23s: Sudden cut to a white screen. Centered brand text and slogan with a clean refreshing brand sound.
23-29s: Cut back from white. The desert horned lizard now lounges on a floating grapefruit, wearing tiny sunglasses and holding a straw cup, drifting slowly across the "juice sea" on vacation. Orange pulp, small ice cubes, and cool splashes float around. The sky turns bright blue and the mood changes from survival to holiday.
29-30s: The lizard leans back contentedly on the grapefruit. The camera pulls away and freezes on a refreshing, bright summer composition.
```

- **Best for:** I2V — 30s, 1 character reference image
- **Aspect Ratio:** 16:9

---

#### 19. Youth Racing Short Film

> Requires 1 reference image (`@image1`)

```
A 30-second cinematic youth racing story in 2D animation style. The protagonist is a young rider driving a motorcycle in a high-level race. The overall style is passionate, youthful, emotionally strong, and cinematic, with a complete beginning, development, turn, and conclusion, and a clear emotional arc. Use only two kinds of camera movement: high-speed follow shots and slow-motion orbit shots. Dialogue is minimal and should appear naturally like fragments of memory: sincere, gentle, restrained, not slogan-like, and not overly sentimental. Avoid disaster tone, negative expression, or exaggerated sci-fi. Focus on love, support, comeback, and upward flight within youth racing.
0-6s: High-speed follow shot. The rider starts the race, engines roaring. The camera follows close to the rear wheel and side profile. The city track, lights, and speed lines pass rapidly.
6-12s: Slow-motion orbit. The rider remembers a gentle voice and a supporting hand. Brief memory flashes appear through light and motion, not full dialogue.
12-20s: High-speed follow. The rider accelerates through a curve, overtaking others with clean motion. The rhythm becomes hotter and brighter.
20-27s: Slow-motion orbit. The motorcycle leaps briefly in the air. Memories bloom behind the rider as warm light and flowers. A gentle smiling voice says, "Go on."
27-30s: The camera circles the motorcycle in midair in slow motion. Push the emotions of passion, tenderness, freedom, and upward flight to the climax. Floral effects open behind the rider, then brand logo appears based on @image1.
```

- **Best for:** I2V — 30s, 1 logo/brand reference
- **Aspect Ratio:** 16:9

---

#### 20. FPV Multilingual Landscape Flight

> Requires 11 reference images (`@image1`–`@image11`)

```
A one-shot FPV drone first-person video, 33 seconds of continuous long take with no edits, jump cuts, or transitions. The camera begins inside high-altitude clouds and follows a continuous descending flight path through clouds, mist, light and shadow, valleys, waterfalls, lake surface, flower fields, city architecture, and a ground-level plaza. The video sequentially presents 11 clear and independent language display blocks. Each block shows only its corresponding single-language text, with no mixing, no overlay, and no additional languages.
0-3s: In @image1, clouds naturally form the first text block.
3-6s: The camera passes through mist and mountain light. The next language text appears formed by drifting vapor.
6-9s: The shot dives along a waterfall. The text is shaped from falling water and spray.
9-12s: It skims across a lake. Reflections on the water surface form another language block.
12-15s: It flies above a flower field. Petals and color bands form the next text.
15-18s: It enters an old street. Signs, flags, or architecture create a single-language display.
18-21s: It passes through a modern city canyon. Glass reflections and LED surfaces shape the next block.
21-24s: The camera moves through a plaza with people and light banners. Another language appears clearly.
24-27s: It dives close to the ground, where shadows and pavement patterns form text.
27-30s: The camera rises slightly. Multiple light paths guide the viewer toward the final language block.
30-33s: The shot arrives at an open plaza. All previous visual elements converge into a clean final composition, while still keeping each language display clear and separate.
```

- **Best for:** I2V — 30s, up to 11 reference images
- **Aspect Ratio:** 16:9

---

#### 21. Global Flower Thank-You Film

```
Live-action realistic style, fast editing, cinematic, 4K, 24 fps, warm natural light, real human performance, natural lip sync, no subtitles. Use the passing of a flower as the core visual clue for the whole video. The flower moves rapidly from one country to another, connecting different regions and people around the world. In every scene, a person receives the flower, gives a sincere smile, and says "thank you" in the local language. The overall rhythm is light, smooth, and dynamic, emphasizing real street/life atmosphere, warm cross-cultural connection, and emotional transmission between people.
0-3s: The flower is handed from one person to another on a bright street. Natural smile and clear local-language "thank you".
3-6s: Match cut to another country. The handover continues through a market or everyday neighborhood.
6-9s: The flower passes through a train station, cafe, or small square. The person receiving it looks surprised, then smiles.
9-12s: A coastal or riverside street scene. Wind, sunlight, and natural camera shake add realism.
12-18s: Rapid montage through several countries. Each time, the flower remains the visual anchor while faces, clothing, streets, and languages change.
18-24s: The pace slows slightly. People from different backgrounds gather in a public space, passing the flower with warmth and laughter.
24-30s: Final wide shot. The flower returns to the center of a diverse group. Everyone looks toward the camera with gentle smiles. End on a warm, natural, globally connected feeling.
```

- **Best for:** T2V — 30s
- **Aspect Ratio:** 16:9

---

### ✂️ Video Editing & Compositing

#### 22. Energy Bow Jungle Edit

> Requires 1 reference video + 1 reference image

```
Keep the character, jungle environment, camera movement, composition, action rhythm, and duration of @video1 unchanged. A blue-white energy bow and glowing arrow (@image1) slowly appear in the character's hands. The bow gradually forms from faint electric arcs and particles, with delicate flowing current texture, slight volumetric light, and a stable energy silhouette. During the draw, the arrow condenses into a bright energy arrow at the center of the bowstring. The instant the character releases, the arrow shoots out at high speed, leaving a bright, slender, continuous, sharp energy trail.
```

- **Best for:** Video Editing (V2V)
- **Requires:** 1 input video + 1 prop reference image

---

#### 23. Object Removal & Inpainting

> Requires 1 reference video

```
Remove the unwanted foreground element from @video1 and naturally inpaint the removed area. Keep all background subjects, environment, distant scenery, atmospheric perspective, and camera composition completely unchanged. The completed background should match the surrounding environment, generating natural sky, foliage, and ground details. Avoid smearing, flicker, deformation, ghosting, or jumping. Ensure temporal consistency across frames, continuous motion, natural edges, and an overall look like original live-action footage.
```

- **Best for:** Video Editing / Inpainting
- **Requires:** 1 input video

---

#### 24. Style Transfer — Medieval Setting

> Requires 1 reference video + 3 reference images

```
Transform the plain two-person martial-arts video @video1 into an empty-hand probing exchange before a cold-weapon duel. Replace the scene with a medieval stone-castle platform, ancient courtyard ground, mountain fortress exterior platform, or simple stone-brick duel arena. The background should include castle walls, wind, mist, distant mountain lines, and flat stone ground (@image1). Replace the clothing of the dark-clothed person with @image2 and the light-clothed person with @image3. Keep the original action rhythm and body motion, but make the atmosphere more restrained, tense, and cinematic, as if the duel is about to begin.
```

- **Best for:** Video Style Transfer
- **Requires:** 1 input video + costume/background reference images

---

### 🎬 Cinematic / Film Templates

```
A weathered detective (50s, trench coat) lights a cigarette on a rain-soaked 
New York street at 3am, neon signs reflecting in puddles, slow dolly back 
to reveal the city behind him, film noir style, 35mm grain, chiaroscuro 
lighting, no dialogue.
```

```
Timelapse of storm clouds rolling over the Scottish Highlands, heather 
fields swaying in the wind below, golden sunset breaking through on the 
horizon, aerial pull-back reveal, Terrence Malick style cinematography.
```

---

### 📱 Social Media / UGC Templates

```
A girl unboxes a luxury skincare set on a marble countertop, close-up of 
her hands removing tissue paper, product reveal in warm soft-box lighting, 
9:16 vertical, lifestyle aesthetic, satisfying ASMR sound design.
```

```
POV shot walking through a busy Tokyo street market at dusk, neon signs, 
food stalls, crowds, handheld camera, cinéma vérité style, authentic 
ambient street sounds, 9:16 vertical.
```

---

### 🌸 Anime & Stylized Templates

```
A lone samurai stands on a cherry blossom cliff at twilight, petals falling 
in slow motion around him, wide establishing shot, Studio Ghibli art style, 
painterly brush strokes, soft orchestral music, no dialogue.
```

```
Cyberpunk anime girl with neon pink hair walks through a holographic market 
on a rain-soaked megacity street, tracking shot, Makoto Shinkai lighting, 
bokeh depth of field, synthwave ambient audio.
```

---

### 🏎️ Multi-Shot Sequence Templates

```
[0:00–0:04] AERIAL WIDE — Drone shot descending toward a mountain summit at dawn.
[0:04–0:09] MEDIUM — A hiker reaches the peak, arms raised, facing away from camera.
[0:09–0:15] CLOSE-UP — Her face turns to us, wind in her hair, tears in her eyes, sunrise light.
Style: Inspirational brand film, Hans Zimmer-style score, no dialogue.
```

---

### 🛍️ E-Commerce & Product Display

Seedance 2.5's multi-image reference input and 30s duration make it well suited to product-detail and livestream-style commerce clips — the format most storefronts need but rarely have footage for.

#### 25. Garment On-Body Turn Display

> Requires 1 reference image (`@image1`)

```
Studio product video for an online storefront. A model wears the garment shown in @image1 and performs a slow 360-degree turn under soft, even three-point lighting against a seamless neutral backdrop. Camera holds a static medium shot at chest height. Fabric drape, seam detail, and stitching should read clearly as the model turns. Close on sleeve cuff and hem texture for 2 seconds at the 20s mark before returning to the full turn. No music, subtle rustle of fabric only.
```

- **Best for:** I2V — 20–30s, 1 product reference image
- **Aspect Ratio:** 9:16 (mobile storefront) or 1:1 (marketplace grid)

---

#### 26. Jewelry Macro Light-Catch

> Requires 1 reference image (`@image1`)

```
Macro product shot of the ring/necklace in @image1 rotating slowly on an invisible turntable against a black-to-charcoal gradient background. A single moving key light sweeps across the piece so facets and metal catch and release specular highlights in sequence. Shallow depth of field, rack focus from setting to stone. End on a static hero frame with the full piece in crisp focus, ready for a price/logo overlay.
```

- **Best for:** I2V — 10–15s, 1 product reference image
- **Aspect Ratio:** 1:1

---

### 🍽️ Food & Beverage

#### 27. Latte Art Pour Close-Up

```
Overhead-to-side transition shot in a bright cafe. Steamed milk pours in a thin ribbon into a cup of espresso, forming a rosette latte-art pattern in real time. Camera starts top-down on the cup, then tilts to a 45-degree angle as the barista sets it on a wooden counter. Warm morning light, shallow depth of field, gentle steam rising, no dialogue, ambient cafe sound only.
```

- **Best for:** T2V — 8–12s
- **Aspect Ratio:** 1:1

---

#### 28. Molten Dessert Reveal

```
Macro close-up of a chocolate lava cake being cut open with a spoon on a dark ceramic plate. Warm molten chocolate slowly flows out and pools around the base as steam rises. Camera holds static, then slowly pushes in as the flow reaches its peak. Rich, warm restaurant lighting with a soft highlight on the glossy chocolate surface, no text, no dialogue, subtle ambient clink of cutlery.
```

- **Best for:** T2V — 8–10s
- **Aspect Ratio:** 4:3

---

### 💄 Beauty & Fashion Close-Ups

#### 29. Skincare Serum Drop

> Requires 1 reference image (`@image1`)

```
Macro beauty shot of the serum bottle from @image1. A single drop of translucent serum falls in slow motion onto a wet, dewy skin surface, rippling outward on impact. Cool, clean studio lighting with soft rim light on the bottle in the background. Camera holds still on the point of impact, shallow depth of field, no dialogue, minimal ambient sound.
```

- **Best for:** I2V — 6–10s
- **Aspect Ratio:** 1:1

---

#### 30. Lipstick Swatch Macro

```
Macro shot of a lipstick bullet swatching color onto the back of a hand against a clean white background. The camera tracks slowly along the swatch line as it's drawn, capturing texture, pigment saturation, and slight sheen. Bright, even beauty lighting, no shadows on the swatch. Ends on a static close-up of the lipstick bullet and the finished swatch in frame together.
```

- **Best for:** T2V — 6–8s
- **Aspect Ratio:** 1:1

---

## Browse Prompts by Category

| Category | Prompts | Best Mode |
|---|---|---|
| Cinematic / Featured | 1–3, 9–12 | T2V / I2V |
| Visual Effects & Typography | 4 | T2V |
| Fashion & Lifestyle | 5, 8 | T2V |
| Nature & Documentary | 6, 7 | T2V |
| Sci-Fi & Concept Film | 10, 11 | T2V |
| Multi-Reference Generation | 13, 17–21 | I2V |
| Video Editing & Compositing | 22–24 | V2V |
| E-Commerce & Product Display | 25, 26 | I2V |
| Food & Beverage | 27, 28 | T2V |
| Beauty & Fashion Close-Ups | 29, 30 | T2V / I2V |

---

## Advanced Workflows

### Character Consistency Across Shots

1. Start with a clear reference image of your character (`@image1`)
2. Describe physical attributes explicitly in every shot: *"same woman, mid-30s, red dress, dark curly hair"*
3. Lock the lighting style in your opening prompt and repeat it per shot
4. Use `maintain character appearance throughout` as a trailing constraint

### Brand-Safe Style Fusion

```
[Brand palette: navy blue, warm gold, clean white]
A product (@image1) sits on a marble surface, soft natural window light, 
navy and gold color grade, luxury minimal aesthetic, slow push in, 
brand colors maintained throughout, no text overlays.
```

### AI Dance / Motion Transfer

```
@image1 is a person standing in a neutral pose. Apply full-body dance 
choreography — contemporary hip-hop style, maintain their exact face and 
clothing, smooth 24fps motion, rhythmic bass-driven audio sync, 9:16 vertical.
```

### 30-Second Epic via Shot Script

For maximum narrative impact at full 30-second duration:

```
[0:00–0:05] COSMIC WIDE — Establish the world from high altitude, slow descent.
[0:05–0:12] MEDIUM — Introduce the central subject with deliberate camera movement.
[0:12–0:20] CLOSE-UP MONTAGE — 3–4 rapid detail shots, texture and emotion.
[0:20–0:27] ACTION PEAK — Climax moment with motion blur or dramatic reveal.
[0:27–0:30] FREEZE/PULL-OUT — Final hero frame or brand logo reveal.
Style: [Director reference], [lighting keyword], no jump cuts.
```

---

## Tips & Best Practices

- **Front-load the subject and action** — the first 20–30 words determine the output more than anything else
- **One lighting keyword > ten adjectives** — `golden hour cinematography` beats `warm, beautiful, glowing, soft, rich, vibrant...`
- **Be explicit about what NOT to do** — `no jump cuts`, `no text overlays`, `no camera shake` prevent common artifacts
- **Use film/director references as style anchors** — `Wes Anderson symmetry`, `Roger Deakins lighting`, `Wong Kar-wai color grade`
- **For 9:16 vertical**, explicitly state it and design composition for mobile framing (subjects centered, headroom at top)
- **Iterate on lighting first** — if a generation looks flat, add or change the lighting keyword before anything else
- **Use seeds for reproducibility** — save the seed of a generation you like to iterate from the same base
- **For 30-second videos**, use timecoded shot scripts to maintain narrative structure and pacing
- **For object removal / inpainting**, be explicit about what to preserve and what to remove — temporal consistency is key
- **For style transfer**, always anchor clothing, background, and lighting references separately for maximum control
- **Multimodal references**: order matters — list the most important reference first; the model weights early references more heavily

---

## API Providers Comparison

| Provider | Seedance 2.5 | API Key Required | Playground | Pricing |
|---|---|---|---|---|
| **[MuAPI](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)** | ✅ | Single key | ✅ Yes | Competitive |
| BytePlus ModelArk | ✅ | Per-provider setup | Limited | Enterprise |
| Direct ByteDance | Limited access | Waitlist | Internal only | — |

> MuAPI provides the simplest path to production — one API key, one base URL, unified billing.

---

## FAQ

**Does Seedance 2.5 generate audio automatically?**
Audio synthesis is a native Volcano Ark/BytePlus capability but is not yet confirmed as enabled on the current 480p/720p early-access endpoints — don't rely on synchronized audio output until a provider explicitly documents it for Seedance 2.5.

**Why isn't 1080p/4K available yet?**
Seedance 2.5 launched with 480p/720p output only, via 8 endpoints (Text-to-Video, Image-to-Video, First & Last Frame, Omni Reference — each with a 720p and 480p tier). Higher resolutions are planned but not yet enabled — treat any 1080p/4K claim as roadmap, not a guaranteed current parameter.

**How many reference images/videos/audio clips can I use?**
The Omni Reference endpoint accepts up to 20 reference images, 6 reference video clips, and 6 reference audio clips per request. The Image-to-Video endpoint takes a single input image; the First & Last Frame endpoint takes exactly two (start + end).

**Should I use MP4 or MOV output?**
Use MP4 (default) for a single final render. Use MOV (`yuv444p`) as both input and output when you plan to chain multiple video-extension or editing passes — it avoids the color-fidelity loss that compounds across generations.

**My multi-shot prompt isn't following the timecodes precisely — why?**
Timecode adherence improves with shorter, clearer per-shot descriptions and a consistent style line at the end. Avoid packing more than 4–6 shots into a single 30s script.

**Can I keep a character consistent without training a LoRA?**
Yes — pass a clear reference image via `@image1` and repeat the same physical description across every shot/extension. This is the fastest path to consistency without any training step; see [Advanced Workflows](#advanced-workflows).

---

## Resources & Links

- [Seedance Official (ByteDance)](https://seed.bytedance.com/en/seedance2_0)
- [MuAPI — Seedance 2.5 API Access](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
- **MuAPI Playgrounds:**
  - Seedance 2.5 Text-to-Video: [720p](https://muapi.ai/playground/seedance-2.5-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [480p](https://muapi.ai/playground/seedance-2.5-text-to-video-480p?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [Spicy](https://muapi.ai/playground/seedance-2.5-spicy-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
  - Seedance 2.5 Image-to-Video: [720p](https://muapi.ai/playground/seedance-2.5-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [480p](https://muapi.ai/playground/seedance-2.5-image-to-video-480p?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [Spicy](https://muapi.ai/playground/seedance-2.5-spicy-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
  - Seedance 2.5 First & Last Frame: [720p](https://muapi.ai/playground/seedance-2.5-first-last-frame?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [480p](https://muapi.ai/playground/seedance-2.5-first-last-frame-480p?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
  - Seedance 2.5 Omni Reference: [720p](https://muapi.ai/playground/seedance-2.5-omni-reference?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [480p](https://muapi.ai/playground/seedance-2.5-omni-reference-480p?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
  - Seedance 2.1: [I2V](https://muapi.ai/playground/seedance-2.1-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [T2V](https://muapi.ai/playground/seedance-2.1-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
  - Seedance 2.0 Mini: [I2V](https://muapi.ai/playground/seedance-2.0-mini-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [T2V](https://muapi.ai/playground/seedance-2.0-mini-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
- [Seedance 2.5 Release Notes](https://www.openpr.com/news/4555789/seedance-2-5-released-next-level-multi-shot-ai-video)
- [Seedance Prompt Guide by invideo.io](https://invideo.io/blog/seedance-2-0-prompt-guide/)
- [BytePlus ModelArk Docs](https://docs.byteplus.com/en/docs/ModelArk)

---

## Contributing

PRs welcome! Add prompts, correct parameters, share API code examples, or link to new Seedance 2.5 resources. Open an issue to suggest a new category.

---

## License

MIT
