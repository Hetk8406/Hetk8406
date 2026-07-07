# Premium Personal Branding Design Specification

This document details the branding specs, folder structures, and assets utilized to deliver the premium dark-themed developer profile for **Het Kikani**.

## 🎨 Branding Philosophy

The profile utilizes a cohesive, slate-gray/dark charcoal layout designed to represent craftsmanship, technical depth, and structured clarity. By avoiding overly colorful rainbow palettes and meme overlays, it builds immediate credibility with recruiters and collaborators looking for high-quality software engineering and AI/ML work.

### Color Palette Specification
- **Primary Background**: `#0D1117` (GitHub Dark Default) / `#1A1B26` (Tokyo Night Card Theme)
- **Primary Accents**: `#8AB4F8` (Soft Cyan Blue for key tags)
- **Neutral Accent**: `#C9D1D9` (Crisp light gray for text)
- **Secondary Accent**: `#FFA116` (Warn gold / LeetCode orange for minor labels)

---

## 📂 Repository Folder Structure

Ensure your profile repository matches the layout below when committing to GitHub:

```text
Hetk8406/
├── assets/
│   ├── hero_banner.png          # AI/ML-Themed Abstract Hero Banner (1200x400)
│   └── icons/                   # Custom local branding SVGs (Optional)
├── README.md                    # Primary rendered landing profile
├── DESIGN.md                    # Personal branding and layout specs (This file)
└── CONFIGURATION.md             # Customization, configurations, and maintenance guides
```

---

## 🌟 Visual Specifications

### 1. Hero Banner Specification
- **Dimensions**: `1200px` x `400px` (3:1 aspect ratio)
- **Style**: Neural network nodes, abstract linear gradients, dark slate backdrop.
- **Path**: Located at `assets/hero_banner.png` (using relative markdown references for offline & mobile compatibility).

### 2. Typing Animation Configuration
- **Host**: `readme-typing-svg.demolab.com`
- **Configuration**:
  - `font`: `Fira Code`
  - `size`: `18px`
  - `color`: `8AB4F8` (Teal-blue match)
  - `center`: `true`
  - `lines`: "Building Intelligent AI Systems", "Deploying Robust ML Pipelines", "Crafting Premium Full-Stack Apps"

### 3. Analytics & Badges Sources
- **Trophies**: `github-profile-trophy.vercel.app` (Theme: `tokyonight`, `no-bg: true`, `no-frame: true`)
- **Stats Card**: `github-readme-stats.shion.dev` (Theme: `tokyonight`, `hide_border: true`)
- **Streak Card**: `streak-stats.demolab.com` (Theme: `tokyonight`, `hide_border: true`)
- **Visitor Count**: `komarev.com/ghpvc/` (Style: `flat-square`, `color: 1F2327`)
