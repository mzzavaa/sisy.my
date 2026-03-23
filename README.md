# sisy.my — Personal Expert Profile URLs

**Domain:** sisy.my
**Role:** Core Product — Personal profile URL system (sisy.my/yourname)
**Priority:** Phase 1
**Notion:** See SISY Domain Strategy page

## Purpose
Provides every registered speaker/expert with a personalized, shareable profile URL (e.g., sisy.my/lindamohamed). Acts as the public-facing identity layer of the platform.

## Key Features / Sections
- Vanity URL routing (sisy.my/{username})
- Public speaker profile pages
- Bio, topics, availability, social links
- Embedded video intro / speaker reel
- Booking & contact CTA
- SEO-optimized profile pages

## Monetization
Free tier drives signups; premium profiles via sisy.pro subscription.

## Local Development

Built with [Hugo](https://gohugo.io/). Deployed via GitHub Pages.

```bash
hugo server -D
```

Visit `http://localhost:1313`.

## Deploy

Push to `main`. GitHub Actions builds and deploys automatically via `.github/workflows/deploy.yml`.

## Design System

Shares CSS tokens, typography, and component patterns with sisy.world and sisy.pro.
Single-file CSS at `static/css/style.css`. Same Inter + Playfair Display fonts, same `--clr-accent` tokens, dark mode via `[data-theme="dark"]`.

## SISY Ecosystem

| Domain | Purpose |
|---|---|
| [sisy.world](https://sisy.world) | Platform & waitlist |
| [sisy.my](https://sisy.my) | Expert profile URLs |
| [sisy.pro](https://sisy.pro) | Professional tier |
| [sisy.video](https://sisy.video) | Talk reels |
| [sisy.today](https://sisy.today) | Speaking opportunities |
| [sisy.social](https://sisy.social) | Community |
