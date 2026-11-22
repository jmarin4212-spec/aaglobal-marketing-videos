# AA Global marketing videos

Finished vertical shorts (1080x1920, ~20-30 s) in English and Spanish, built by the `/short-video` pipeline.

## Where the files are

Each video is one **GitHub Release**, tagged `<date>-<slug>` (for example `2026-11-21-crown-cap`). Every release has these files:

| File | Use |
|---|---|
| `en-video_music.mp4` | Reels, Shorts, X (theme music baked in) |
| `en-video_clean.mp4` | TikTok (voice only, add a trending sound in the app) |
| `es-video_music.mp4` | Spanish: Reels, Shorts, X |
| `es-video_clean.mp4` | Spanish: TikTok |
| `credits.txt` | Pexels b-roll credits |

Direct download link pattern (no login needed):

```
https://github.com/jmarin4212-spec/aaglobal-marketing-videos/releases/download/<tag>/<file>
```

## Finding new videos

[`videos.json`](videos.json) lists every published video, newest first, with its tag, date, title and direct file URLs. Check it for tags you have not handled yet.
