# Onboarding Guides

HTML onboarding guides served via GitHub Pages.

**Base URL:** `https://valeriaspace.github.io/onboarding-guides/`

## Structure

```
nh/       — New Hire guides
lead/     — Lead Command Center guides
buddy/    — Buddy guides
```

## How it works

1. n8n workflow fetches skeleton content from Notion
2. Builds personalized HTML guides (NH, Lead, Buddy)
3. Pushes them here via GitHub API
4. GitHub Pages serves them — no sandbox restrictions

Guides are generated per onboarding and named `{name-slug}-{start-date}.html`.
