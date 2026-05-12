# GitHub Profile — Assets & Setup Guide

## Folder Structure

```
github.com/ankitraj5ar/ankitraj5ar/
├── README.md                  ← main profile file
└── assets/
    ├── banner.svg             ← hero banner (1200×300)
    ├── banner-dark.svg        ← dark variant (auto-served via GitHub)
    └── preview.png            ← optional: social preview image
```

---

## 1. Banner Concepts

### Option A — Terminal Banner (Recommended)
A dark background (`#0d1117`) with monospace font, showing a simulated terminal prompt:

```
Ankit Raj
$ engineer --mode=backend --focus=distributed-systems
> systems that scale, architectures that last
```

**Tools:** Figma (free), or use this ready-made approach:
- Background: `#0d1117`
- Accent color: `#58a6ff` (GitHub blue)
- Font: `JetBrains Mono` or `Fira Code`
- Size: `1200 × 300px`
- Export as `.svg` for sharp rendering at all sizes

### Option B — Capsule Header (Quickest)
Use `capsule-render`:
```markdown
![header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f2d3d&height=200&section=header&text=Ankit%20Raj&fontSize=50&fontColor=58a6ff&fontAlignY=35&desc=Backend%20%7C%20Distributed%20Systems%20%7C%20Architecture&descAlignY=55&descColor=8b949e)
```

### Option C — Minimal Text Banner (SVG inline)
Paste this directly in your README — no hosting needed:
```svg
<svg width="1200" height="220" viewBox="0 0 1200 220" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect width="1200" height="220" fill="#0d1117"/>
  <text x="60" y="95" font-family="monospace" font-size="42" fill="#58a6ff" font-weight="bold">Ankit Raj</text>
  <text x="62" y="140" font-family="monospace" font-size="16" fill="#8b949e">Software Engineer — Distributed Systems · Backend · ERP Architecture</text>
  <text x="62" y="175" font-family="monospace" font-size="13" fill="#3d4451">$ building systems that survive production</text>
</svg>
```

---

## 2. GitHub Widgets

### Stats Card
```
https://github-readme-stats.vercel.app/api?username=ankitraj5ar
  &theme=tokyonight
  &hide_border=true
  &bg_color=0d1117
  &include_all_commits=true
  &count_private=true
```

### Top Languages
```
https://github-readme-stats.vercel.app/api/top-langs/
  ?username=ankitraj5ar
  &layout=compact
  &theme=tokyonight
  &hide_border=true
```

### Activity Graph
```
https://github-readme-activity-graph.vercel.app/graph
  ?username=ankitraj5ar
  &theme=github-compact
  &hide_border=true
  &area=true
```

### Streak Stats (optional)
```
https://github-readme-streak-stats.herokuapp.com/
  ?user=ankitraj5ar
  &theme=tokyonight
  &hide_border=true
  &background=0d1117
```

---

## 3. Recommended Open-Source Assets

| Asset | URL | Use |
|-------|-----|-----|
| github-readme-stats | vercel.app/api | Stats cards |
| activity-graph | vercel.app/graph | Contribution heatmap |
| capsule-render | vercel.app/api | Styled banners |
| shields.io | shields.io | Minimal badges |
| simpleicons.org | simpleicons.org | Tech logo SVGs |

All are free, open-source, and GitHub-hosted-safe.

---

## 4. Color Palette

| Token | Hex | Usage |
|-------|-----|-------|
| `bg-primary` | `#0d1117` | Main background |
| `accent-blue` | `#58a6ff` | Headings, icons |
| `text-muted` | `#8b949e` | Secondary text |
| `border` | `#21262d` | Dividers |
| `highlight` | `#1f6feb` | Hover / emphasis |

This matches GitHub's own dark mode — your profile feels native, not foreign.

---

## 5. Optional Enhancements

### Self-updating "Currently Reading" section
Use GitHub Actions + a gist to auto-update a "currently reading" or "current focus" badge.

### Pinned Repositories
Pin 6 repos on your profile. Choose ones that:
- show architectural depth
- have good READMEs explaining the *why*, not just the *what*
- cover different domains (messaging, API, data, tooling)

### Repository READMEs
Each pinned repo should have its own architecture diagram (use Mermaid diagrams — native GitHub support):

```markdown
\`\`\`mermaid
graph TD
    A[API Gateway] -->|HTTP| B[Auth Service]
    A -->|Events| C[Kafka Topic]
    C --> D[Worker Service]
    D --> E[(PostgreSQL)]
    D --> F[(Redis Cache)]
\`\`\`
```

---

## 6. What Makes This Profile Stand Out

1. **Terminal aesthetic** — every section looks like a shell session, not a resume
2. **Architecture-first language** — describes systems, not just technologies
3. **JSON/YAML code blocks for tech stack** — readable, structured, credible
4. **No badge spam** — intentional restraint signals seniority
5. **`/etc/principles.conf`** — a hidden gem for engineers who read the whole page
6. **Collapsible section** — rewards curiosity without cluttering the above-fold
7. **Honest "current focus" log** — shows growth trajectory, not a static snapshot
8. **System status section** — creative but not gimmicky

---

*Keep it updated. A stale "current focus" is worse than none at all.*
