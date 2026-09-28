# yt-alerts

Automated YouTube upload and live-stream notifications for Discord, powered by GitHub Actions.

## How it works

This workflow polls a YouTube channel's public RSS feed every 5 minutes. When a new video or live stream is detected, it posts a formatted notification to a Discord channel via webhook.

- **Uploads** → "📢 [Channel] just posted something new on YouTube! Go check it out 👇"
- **Live streams** → "📢 [Channel] is LIVE on YouTube! Go check it out 👇"

Both messages include a role ping and the video link.

## Architecture
