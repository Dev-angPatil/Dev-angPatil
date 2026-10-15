# ARCHITECTURE.md — Dev-angPatil Profile Architecture

## Layout Hierarchy & Content Architecture

The profile README is organized around a strict inverted-pyramid hierarchy designed to maximize technical signal:

```
┌────────────────────────────────────────────────────────┐
│ 1. Header (Identity & Core Thesis)                     │
│    - Name, Domain Specializations, Focused Bio         │
├────────────────────────────────────────────────────────┤
│ 2. Flagship Project Spotlight (ops-assistant)          │
│    - One-line problem/solution definition              │
│    - Architectural breakdown (Kernel PSI, DAGs, etc.)  │
│    - Verified empirical metrics & benchmark table      │
│    - Repository link & quick access                    │
├────────────────────────────────────────────────────────┤
│ 3. Selected Research & Systems Footprint               │
│    - Clean, unbloated 3-item curated index             │
├────────────────────────────────────────────────────────┤
│ 4. Minimalist Connect                                  │
│    - Direct, text-based contact channels               │
└────────────────────────────────────────────────────────┘
```

## Styling & Token Constraints
- **Markdown Purity:** No raw JavaScript, external iframe embeds, or unstable Heroku widgets.
- **Theme Resilience:** All colors, tables, and typography render with optimal contrast across GitHub Dark, Dark High Contrast, and Light modes.
- **Anti-Bloat Standards:** No animated GIFs, typing badges, vanity streak counters, or skill-matrix grids.
