# MRB AI — starter

A mobile-friendly static prototype for an AI movie studio. It supports anime, realistic, and mixed visual styles and includes a 10-minute scene planner.

## What works now
- Responsive dark futuristic dashboard
- 10-minute project planning with selectable clip targets
- Scene-by-scene prompt breakdown and character-continuity notes
- Image, audio, story and chat interface placeholders

## What does not work yet
The site does not generate video, images, music, sound or AI chat by itself. The planner creates a local storyboard only. Real generation needs external models/APIs and a secure backend. Free tiers are limited and may change.

## Publish on GitHub Pages from Android
1. Download and unzip this package.
2. On github.com create a public repository named `mrb-ai`.
3. Upload `index.html` from this folder and commit.
4. Open Settings → Pages.
5. Choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
6. GitHub Pages will show the published URL when deployment finishes.

Guide: https://docs.github.com/en/pages/quickstart

## Safe API setup
Never place API keys in this public HTML file. Use a server-side function and store keys as environment secrets. Check provider age requirements, free-tier terms, privacy rules and content policies before connecting accounts or publishing generation features.
