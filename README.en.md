🇷🇺 [Русский](README.md) · 🇬🇧 [English](README.en.md) · 🇪🇸 [Español](README.es.md)

# MuzloProm AI Clips

**AI music clips from photos**

> Showcase only (no source code). Code in a private repository.

---

## Problem

AI music clips from photos.

## Features

Photo + MP3 → OpenAI scene → Qwen WAN video → subtitles → Telegram delivery.

## Business value

Scales content marketing without an editor; fast UGC for social media.

## Stack

FastAPI · aiogram · MySQL · OpenAI · Qwen WAN · ffmpeg

## Architecture

![Architecture](assets/muzloprom-diagram.svg)

## Run

```bash
uvicorn app.main:app --host 0.0.0.0 --port 8100
```

**Status:** ✅ Production-ready

**Case Study:** [05-muzloprom-ai-clips.md](https://github.com/alexanderomobile/portfolio/blob/main/case-studies/en/05-muzloprom-ai-clips.md)

[@alexanderomobile](https://github.com/alexanderomobile)
