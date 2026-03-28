# Quan Alex Nguyen — Portfolio Landing Page

## Project Overview

A retro Y2K/MySpace-style personal portfolio page for Quan Alex Nguyen (Technical Support Manager at TeKnowledge, Hanoi, Vietnam).

## Live URLs

| Platform | URL |
|----------|-----|
| **Vercel (primary)** | https://alex-quan-nguyen-portfolio-landing.vercel.app |
| **GitHub Pages** | https://quannguyen-alex.github.io/quan-alex-nguyen-profile/ |

## GitHub Repository

**https://github.com/QuanNguyen-Alex/quan-alex-nguyen-profile**

## Deployment Setup

- **Vercel** is connected to the GitHub repo via the Vercel GitHub App
- Every `git push` to `main` triggers an automatic Vercel redeploy — no manual deploy needed
- Vercel account: `anhquan1990-5904`
- GitHub Pages is also active on the same repo (built from `main` branch, root `/`)

## Workflow

1. Make changes to files locally
2. Claude runs `git add`, `git commit`, `git push` after getting permission
3. Vercel auto-deploys within ~1 minute of push
4. Check deployment status in the GitHub repo's **Deployments** section (right sidebar)

## Project Structure

```
index.html          — main page
css/style.css       — shared retro stylesheet (neon vars, animations)
css/quan-custom.css — Quan-specific overrides (avatar, cert badges, timeline)
js/effects.js       — sparkle trail, snowfall, floating emojis, eyes, popups, matrix rain, Konami code
js/games.js         — Snake, Whack-a-Bug, Cookie Clicker
me.jpeg             — profile photo
```

## Tech Stack

- Plain HTML/CSS/JS — no framework, no build step
- Hosted on Vercel (primary) and GitHub Pages (secondary)
- Fonts: Press Start 2P, Bungee Shade, Rubik Glitch, Silkscreen (Google Fonts)

## Design

- Full retro/Y2K/MySpace aesthetic
- Matrix rain canvas background
- MySpace 2-column layout (left: mood, top 8, playlist, LinkedIn; right: about, stats, career timeline)
- Three mini-games: Snake, Whack-a-Bug, Cookie Clicker
- Fake popup system, sparkle cursor trail, emoji snowfall, mouse-following eyes
- Guestbook, badge shelf, visitor counter, marquee bars

## Session Notes

- Claude should explain git actions and ask permission, then run commands itself
- Vercel GitHub App must be installed at github.com/apps/vercel for auto-deploy to work
