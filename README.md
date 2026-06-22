# 🎬 Awesome Seedance 2.5 — API, Prompts & Complete Guide

> The ultimate resource for Seedance 2.5 — ByteDance's next-gen AI video generation model. Covers API integration, prompt engineering, camera controls, multimodal workflows, and curated examples.

[![Seedance 2.5](https://img.shields.io/badge/Seedance-2.5-blue)](https://seed.bytedance.com)
[![Powered by MuAPI](https://img.shields.io/badge/Powered%20by-MuAPI-6366f1?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0tMSAxNHYtNGgtMnYtMmg0djZoLTJ6bTAtOFY2aDJ2MmgtMnoiLz48L3N2Zz4=)](https://muapi.ai?utm_source=github&utm_medium=badge&utm_campaign=awesome-seedance-2.5)
[![Stars](https://img.shields.io/github/stars/Anil-matcha/awesome-seedance-2.5-api-prompts?style=social)](https://github.com/Anil-matcha/awesome-seedance-2.5-api-prompts)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Related Projects

- [Seedance-2-API](https://github.com/Anil-matcha/Seedance-2-API) — Python SDK for Seedance 2.x API — text-to-video, image-to-video, character consistency
- [seedance2-comfyui](https://github.com/Anil-matcha/seedance2-comfyui) — Run Seedance 2 inside ComfyUI with custom nodes
- [n8n-nodes-seedance2](https://github.com/Anil-matcha/n8n-nodes-seedance2) — Automate Seedance 2 video generation in n8n workflows
- [seedance-2.0-watermark-remover](https://github.com/SamurAIGPT/seedance-2.0-watermark-remover) — Remove watermarks from Seedance generated videos
- [seedance-2-generator](https://github.com/SamurAIGPT/seedance-2-generator) — Ready-made Next.js SaaS built on Seedance 2

---

## Table of Contents

- [What is Seedance 2.5?](#what-is-seedance-25)
- [Seedance 2.5 vs 2.0 — What's New](#seedance-25-vs-20--whats-new)
- [Capabilities](#capabilities)
- [API Reference (MuAPI)](#api-reference-muapi)
  - [Text-to-Video](#1-seedance-25-text-to-video-t2v)
  - [Image-to-Video](#2-seedance-25-image-to-video-i2v)
  - [Video Extension](#3-seedance-25-video-extension)
  - [Polling for Results](#polling-for-results)
  - [Parameters](#muapi-parameters)
- [Prompt Engineering Guide](#prompt-engineering-guide)
- [Prompt Engineering Guide](#prompt-engineering-guide)
  - [The 6-Step Formula](#the-6-step-formula)
  - [Camera Movement Vocabulary](#camera-movement-vocabulary)
  - [Lighting Keywords](#lighting-keywords)
  - [Multimodal Reference Syntax](#multimodal-reference-syntax)
- [Prompt Templates by Category](#prompt-templates-by-category)
  - [Cinematic / Film](#cinematic--film)
  - [Social Media / UGC](#social-media--ugc)
  - [Anime & Stylized](#anime--stylized)
  - [Advertising / Product](#advertising--product)
  - [Multi-Shot Sequences](#multi-shot-sequences)
- [Advanced Workflows](#advanced-workflows)
- [Tips & Best Practices](#tips--best-practices)
- [API Providers Comparison](#api-providers-comparison)
- [Resources & Links](#resources--links)

---

## What is Seedance 2.5?

**Seedance 2.5** is ByteDance's latest AI video generation model, built on the Seed video foundation. It is a significant upgrade over Seedance 2.0, with a focus on:

- **Multi-shot storytelling** — generate longer, cinematically coherent narratives from a single prompt
- **Character & brand consistency** — maintain the same face, clothing, and style across all shots
- **Director-grade camera control** — precise rack focus, crane shots, whip pans, and more
- **Native audio synchronization** — tighter lip-sync and sound design baked in at generation time
- **Better physics & motion stability** — realistic fluid dynamics, cloth simulation, and crowd motion

Seedance 2.5 accepts **text, images, video clips, and audio** as input and outputs **MP4 video with synchronized audio**.

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
| Max resolution | 1080p | 1080p+ |
| Max duration | 15s | Longer sequences |

---

## Capabilities

- **Text-to-Video** — generate video from a text prompt alone
- **Image-to-Video** — animate a still image with motion
- **Video-to-Video** — restyle or extend an existing video clip
- **Audio-to-Video** — sync visuals to a provided audio track
- **Multi-modal** — combine text + image + audio in one generation
- **AI Dance / Motion Transfer** — make people, pets, or characters perform dance movements

### Supported Input Formats
- Images: JPEG, PNG, WebP (up to 9 images)
- Video: MP4, MOV (up to 3 clips, 15s total)
- Audio: WAV, MP3 (up to 3 files)

### Output Specs
- Resolutions: 480p, 720p, 1080p
- Durations: 4–15 seconds per clip
- Aspect Ratios: `21:9` `16:9` `4:3` `1:1` `3:4` `9:16`
- Format: MP4 with synchronized audio

---

## API Reference (MuAPI)

The fastest way to access Seedance 2.5 via API is through **[MuAPI](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)** — a unified media API gateway with reliable uptime, competitive pricing, and no per-provider account setup.

**Get your API key:** [muapi.ai](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

```bash
x-api-key: YOUR_MUAPI_KEY
Base URL: https://api.muapi.ai/api/v1
```

---

### 1. Seedance 2.5 Text-to-Video (T2V)

**Endpoint:** `POST https://api.muapi.ai/api/v1/seedance-2.5-t2v`

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.5-t2v" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "A lone astronaut walks across a red Martian desert at golden hour, wide angle, cinematic",
      "aspect_ratio": "16:9",
      "duration": 10,
      "quality": "high"
  }'
```

**Python:**
```python
import requests

response = requests.post(
    "https://api.muapi.ai/api/v1/seedance-2.5-t2v",
    headers={"x-api-key": "YOUR_API_KEY", "Content-Type": "application/json"},
    json={
        "prompt": "A lone astronaut walks across a red Martian desert at golden hour, wide angle, cinematic",
        "aspect_ratio": "16:9",
        "duration": 10,
        "quality": "high"
    }
)
request_id = response.json()["request_id"]
```

---

### 2. Seedance 2.5 Image-to-Video (I2V)

**Endpoint:** `POST https://api.muapi.ai/api/v1/seedance-2.5-i2v`

Reference input images in your prompt using `@image1`, `@image2`, etc.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.5-i2v" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "@image1 — the camera slowly pushes in as she turns to face us, hair blowing in the wind",
      "images_list": ["https://example.com/photo.jpg"],
      "aspect_ratio": "16:9",
      "duration": 8,
      "quality": "high"
  }'
```

**Python:**
```python
response = requests.post(
    "https://api.muapi.ai/api/v1/seedance-2.5-i2v",
    headers={"x-api-key": "YOUR_API_KEY", "Content-Type": "application/json"},
    json={
        "prompt": "@image1 — the camera slowly pushes in as she turns to face us, hair blowing in the wind",
        "images_list": ["https://example.com/photo.jpg"],
        "aspect_ratio": "16:9",
        "duration": 8,
        "quality": "high"
    }
)
request_id = response.json()["request_id"]
```

---

### 3. Seedance 2.5 Video Extension

**Endpoint:** `POST https://api.muapi.ai/api/v1/seedance-2.5-extend`

Seamlessly extend an existing Seedance 2.5 clip while maintaining style and character consistency.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.5-extend" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "request_id": "YOUR_ORIGINAL_REQUEST_ID",
      "prompt": "She continues walking into the foggy distance",
      "duration": 6
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
| `prompt` | string | — | required | Text description. Use `@image1`, `@image2` to reference inputs |
| `images_list` | array | URLs | — | Input images for I2V (up to 9) |
| `aspect_ratio` | string | `21:9` `16:9` `4:3` `1:1` `3:4` `9:16` | `16:9` | Output aspect ratio |
| `duration` | int | `4`–`15` | `10` | Duration in seconds |
| `quality` | string | `basic` `high` | `basic` | `high` = 1080p priority |
| `remove_watermark` | bool | `true` `false` | `false` | Remove MuAPI watermark |

> **Playground:** [muapi.ai/playground](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)

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

---

### Multimodal Reference Syntax

When passing images, videos, or audio alongside your prompt, reference them with `@Tags`:

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

## Prompt Templates by Category

### Cinematic / Film

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

### Social Media / UGC

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

### Anime & Stylized

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

### Advertising / Product

```
A sleek black electric car races along a coastal highway at golden hour, 
low tracking shot alongside the vehicle, salt spray and motion blur, 
cut to close-up of the steering wheel and dashboard, premium automotive 
ad aesthetic, orchestral score.
```

```
A barista pours a perfect latte art rose in a minimalist café, extreme 
close-up rack focus, warm tungsten practical lighting, steam rising, 
slow motion pour, ASMR coffee sounds.
```

---

### Multi-Shot Sequences

```
[0:00–0:04] AERIAL WIDE — Drone shot descending toward a mountain summit at dawn.
[0:04–0:09] MEDIUM — A hiker reaches the peak, arms raised, facing away from camera.
[0:09–0:15] CLOSE-UP — Her face turns to us, wind in her hair, tears in her eyes, sunrise light.
Style: Inspirational brand film, Hans Zimmer-style score, no dialogue.
```

---

## Advanced Workflows

### Character Consistency Across Shots

1. Start with a clear reference image of your character (`@Image1`)
2. Describe physical attributes explicitly in every shot: *"same woman, mid-30s, red dress, dark curly hair"*
3. Lock the lighting style in your opening prompt and repeat it per shot
4. Use `maintain character appearance throughout` as a trailing constraint

### Brand-Safe Style Fusion

```
[Brand palette: navy blue, warm gold, clean white]
A product (@Image1) sits on a marble surface, soft natural window light, 
navy and gold color grade, luxury minimal aesthetic, slow push in, 
brand colors maintained throughout, no text overlays.
```

### AI Dance / Motion Transfer

```
@Image1 is a person standing in a neutral pose. Apply full-body dance 
choreography — contemporary hip-hop style, maintain their exact face and 
clothing, smooth 24fps motion, rhythmic bass-driven audio sync, 9:16 vertical.
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

---

## Resources & Links

- [Seedance Official (ByteDance)](https://seed.bytedance.com/en/seedance2_0)
- [MuAPI — Seedance 2.5 API Access](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
- **Muapi Playgrounds:**
  - Seedance 2.5 *(coming soon)*: [I2V](https://muapi.ai/playground/seedance-2.5-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [T2V](https://muapi.ai/playground/seedance-2.5-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
  - Seedance 2.1 *(coming soon)*: [I2V](https://muapi.ai/playground/seedance-2.1-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [T2V](https://muapi.ai/playground/seedance-2.1-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
  - Seedance 2.0 Mini *(coming soon)*: [I2V](https://muapi.ai/playground/seedance-2.0-mini-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5) · [T2V](https://muapi.ai/playground/seedance-2.0-mini-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-seedance-2.5)
- [Seedance 2.5 Release Notes](https://www.openpr.com/news/4555789/seedance-2-5-released-next-level-multi-shot-ai-video)
- [Seedance Prompt Guide by invideo.io](https://invideo.io/blog/seedance-2-0-prompt-guide/)
- [BytePlus ModelArk Docs](https://docs.byteplus.com/en/docs/ModelArk)

---

## Contributing

PRs welcome! Add prompts, correct parameters, share API code examples, or link to new Seedance 2.5 resources. Open an issue to suggest a new category.

---

## License

MIT
