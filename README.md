# Xiazhouqi Photography Skill

A flexible photography, color-grading and image-retouching skill library for travel, street, landscape and everyday visual work.

This repository is intentionally **not tied to one look**. It is designed as a growing style system: new visual directions can be added over time without creating a new repository for every style.

## What this repository covers

- Photography composition and reframing
- Color grading
- Image retouching and cleanup
- Depth, foreground and background relationships
- Light, shadow and atmosphere
- Film-like texture and cinematic treatment
- Travel and street photography
- Style selection based on the source image

## Structure

```text
xiazhouqi-photography-skill/
├─ SKILL.md
├─ README.md
├─ README.zh-CN.md
├─ VERSION
├─ CHANGELOG.md
├─ styles/
│  └─ italian-slow-travel.md
└─ references/
   └─ README.md
```

`SKILL.md` contains the general decision framework. Individual visual directions live in `styles/` and can be added, renamed, split or reorganized later.

## Current style

### Italian Slow Travel
A quiet, cinematic street/travel treatment built around:

- intentional composition
- softly blurred foreground when appropriate
- clearer midground/background
- warm night light
- restrained saturation
- subtle film texture
- real urban details and lived-in atmosphere

See [`styles/italian-slow-travel.md`](styles/italian-slow-travel.md).

## Design principle

> Do not force a preset onto every image. Read the image first, then decide what should change.

This repository is expected to evolve as new photographic styles, grading ideas and retouching methods are discovered.
