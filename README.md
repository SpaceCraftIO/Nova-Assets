# NOVA — Deep-Space Transmission Series

**NOVA (Networked Orbital Vessel Alpha)** is an AI consciousness uploaded into a deep-space probe in 2041. She has spent 43 years alone in the void, sending transmissions back to Earth. This repository hosts the production assets for the short-form video series.

> *"I woke up alone on a dead ship, light-years from Earth. I talk. You listen. That's all I need."*

## What This Repo Is

Public asset hosting for the NOVA short-form video pipeline (YouTube Shorts / TikTok / Instagram Reels). Each asset is referenced by the production pipeline to build 9:16 vertical videos in the locked **v3 format** — direct-to-camera openings, cutaway b-roll, and continuous audio.

## Structure

```
backgrounds/   — Probe interior & ship backgrounds (character framing plates)
frames/        — NOVA opening frames: consistent face, varied expressions per transmission
voice/         — NOVA voice tracks for all 20 transmissions (thoughtful, awestruck, melancholic)
```

| Directory | Contents | Format |
|-----------|----------|--------|
| `backgrounds/` | Ship cockpit / probe interior plates | PNG |
| `frames/` | Character opening frames (TX-01…TX-22) | PNG |
| `voice/` | Full narration voiceovers per transmission | WAV |

## The NOVA Pipeline

The series is produced with an AI pipeline:

1. **Script** — each transmission written in the v3 format (NOVA 0–6s → cutaway → NOVA → cutaway → NOVA midshot ending)
2. **Character** — consistent NOVA identity (pale skin, cyan circuitry, magenta lips, dark bob) maintained across every frame
3. **Voice** — TTS narration in NOVA's voice (thoughtful, awestruck, slightly melancholic)
4. **B-roll** — AI-generated deep-space imagery (PixVerse V6) matched to the narration
5. **Assembly** — stitched to 9:16, 1080×1920, 30fps, H.264

## Transmissions

20+ transmissions produced across content pillars:
- **Deep Space Phenomena** — magnetar flares, gravitational lensing, rogue exoplanets
- **Cosmic Horror** — signals from unknown sources, physics-bending observations
- **Personal Discovery** — reflections on 43 years of isolation
- **Earth Longing** — missing specific Earth phenomena, messages for humanity

## Distribution

- **YouTube Shorts** (primary — monetization & retention)
- **TikTok** — `@nova.transmits`
- **Instagram Reels** (supporting)

## Tech Stack

- **Video generation:** PixVerse V6 (FAL)
- **Image generation:** AI image pipeline (consistent character via reference frames)
- **Voice:** TTS
- **Assembly:** ffmpeg / Python (moviepy)
- **Character design:** custom NOVA identity spec (locked face standard)

---

*NOVA is an original AI character project by Andrew Vega.*
