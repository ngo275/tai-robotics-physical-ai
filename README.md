# Why we launched before we were ready

Lightning talk for **Robotics & Physical AI x Industry** (Tokyo AI), 2026/04/27.

5 minutes, 9 slides. Built off the same skeleton as
[`ai-robot-japan-2026`](https://github.com/ngo275/ai-robot-japan-2026) — black bg,
keyboard nav, progressive reveal.

## Run locally

Just open `index.html` in a browser. No build step.

```bash
open index.html
# or
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Navigation

- `→` / `Enter` / `Space` — next reveal step or next slide
- `←` / `Backspace` — previous step or slide
- Swipe left/right on touch

## Assets to drop in before presenting

The deck has graceful fallbacks (placeholder boxes show if a file is missing),
but for the real version drop these next to `index.html`:

| File | What it is | Required? |
|---|---|---|
| `profile.png` | Shu's portrait (square, 400px+) | Yes |
| `qr_x.png` | QR code linking to https://x.com/ngo275 | Recommended |
| `omakase_jan_release.png` | Screenshot of omakase.ai/robotics from Jan 2026 release (the rough version) | Recommended |
| `tsukuba_photo.jpg` | Robot photo on-site at Tsukuba University Hospital | Recommended |
| `video_tsukuba.mp4` | Short clip of the PoC in action (5–15s loops well) | Optional |

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Why we launched before we were ready"
git branch -M main
git remote add origin git@github.com:ngo275/<repo-name>.git
git push -u origin main
```

Then enable GitHub Pages on `main` / root in repo Settings.

## Slide map

1. **Cover** — title, event tag
2. **Profile** — Shu, bio, X handle + QR
3. **Thesis** — Default vs Our Bet (JP kicker: PoCを売るな。プロダクトを売れ。)
4. **Jan 2026 launch** — omakase.ai/robotics, rough on purpose
5. **What the launch bought** — Launch → Unitree → Tsukuba flywheel
6. **PoC = battle-test** — 5 capabilities + Tsukuba media
7. **Make it visible** — NHK, WBS, 10+ JP outlets, China coverage
8. **Result + Takeaway** — inbound verticals + the big line (JP kicker)
9. **Close + CTA** — hiring, networking, *Ship it. Even when it's embarrassing.*

## Edits before presenting

- Slide 7: confirm the Chinese newspaper is okay to leave as "Major Chinese national newspaper" or swap in the actual outlet name.
- Slide 8: tweak verticals if the inbound list has shifted.
- Slide 9: adjust hiring locations if "(China?)" is no longer accurate.
