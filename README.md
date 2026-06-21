🇷🇺 [Русский](README.md) · 🇬🇧 [English](README.en.md) · 🇪🇸 [Español](README.es.md)

# MuzloProm AI Clips

**AI-клипы из фото под музыку**

> Showcase без кода. Исходники — приватный репозиторий.

---

## Задача

AI-клипы из фото под музыку.

## Функционал

Фото + фрагмент MP3 → сцена OpenAI → video Qwen WAN → субтитры → Telegram.

## Польза для бизнеса

Масштабирует контент-маркeting без монтажёра; быстрый UGC для соцсетей.

## Стек

FastAPI · aiogram · MySQL · OpenAI · Qwen WAN · ffmpeg

## Архитектура

![Architecture](assets/muzloprom-diagram.svg)

## Запуск

```bash
uvicorn app.main:app --host 0.0.0.0 --port 8100
```

**Статус:** ✅ Завершён

**Case Study:** [05-muzloprom-ai-clips.md](https://github.com/alexanderomobile/portfolio/blob/main/case-studies/ru/05-muzloprom-ai-clips.md)

[@alexanderomobile](https://github.com/alexanderomobile)
