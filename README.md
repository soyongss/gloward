# gloward · 心向

A growing home for **gloward · 心向** — psychology-informed digital tools, interactive experiences, prototypes, and experiments designed to make meaningful action easier to start and sustain.

The repository begins with lightweight browser-based tools, but it is intentionally broader than a static-site collection. Future projects may include richer web apps, product prototypes, research-informed exercises, dashboards, and other digital experiences.

## Projects

| Project | Description | Status |
| --- | --- | --- |
| **Small Step** | A gentle weekly routine tool that turns meaningful intentions into small, repeatable actions and supports weekly review. | Live / evolving |

## Current structure

```text
.
├── index.html              # gloward project hub / GitHub Pages home
├── .nojekyll               # Serve current static files directly
├── 404.html
├── README.md
└── small-step/
    └── index.html          # Small Step browser app
```

As the repository grows, individual projects can keep their own folders and technology stacks instead of being forced into one structure.

## GitHub Pages

The current public-facing pages are designed to be served from the `main` branch, repository root (`/`).

Expected URLs after GitHub Pages is enabled:

- Project hub: `https://soyongss.github.io/gloward/`
- Small Step: `https://soyongss.github.io/gloward/small-step/`

## Product principles

Gloward projects aim to translate evidence-informed psychology into practical, approachable experiences. The focus is not on maximizing productivity, but on helping people notice what matters, reduce friction, take a workable next step, and learn from what actually happens.

Typical design principles:

- **Meaning before optimization** — connect action to what matters.
- **Lower the starting threshold** — make the next step small enough to begin.
- **Make progress visible** — turn small actions into usable evidence.
- **Review and adjust** — treat plans as experiments, not rigid rules.
- **Keep the experience gentle and clear** — avoid unnecessary complexity.

## About Small Step

**Small Step** is the first interactive project in this repository. It provides a simple weekly loop:

1. Choose a few meaningful actions.
2. Define the smallest workable version of each action.
3. Mark what actually happened during the week.
4. Review the week and adjust the next step.

The current version stores data locally in the browser and does not require an account or backend.

---

**gloward · 心向**  
Psychology-informed tools for values, action, and everyday growth.
