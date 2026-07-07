# Customization & Configuration Guides

This guide outlines configuration parameters, external dependencies, installation steps, and daily maintenance procedures for keeping your premium GitHub profile updated.

## 🛠️ Configuration & API Reference

### 1. Typing Animation
*   **Provider**: [Readme Typing SVG](https://github.com/DenverCoder1/readme-typing-svg)
*   **URL Pattern**:
    ```text
    https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1000&color=8AB4F8&center=true&vCenter=true&width=435&lines=Building+Intelligent+AI+Systems;Deploying+Robust+ML+Pipelines;Crafting+Premium+Full-Stack+Apps
    ```

### 2. GitHub Stats Card & Languages
*   **Provider**: [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
*   **Configuration**:
    *   `theme`: `tokyonight`
    *   `show_icons`: `true`
    *   `hide_border`: `true`
    *   `include_all_commits`: `true`
    *   `count_private`: `true`
    *   `layout`: `compact` (for Languages card)

### 3. GitHub Streak Stats
*   **Provider**: [GitHub Readme Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)
*   **Configuration**:
    *   `theme`: `tokyonight`
    *   `hide_border`: `true`

### 4. Profile Trophies
*   **Provider**: [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy)
*   **Configuration**:
    *   `theme`: `tokyonight`
    *   `column`: `7`
    *   `no-bg`: `true`
    *   `no-frame`: `true`

### 5. Visitor Counter
*   **Provider**: [GitHub Profile Views Counter](https://github.com/gayanvoice/github-profile-views-counter)
*   **Configuration**:
    *   `color`: `1F2327` (Charcoal)
    *   `style`: `flat-square`

---

## 📦 External Dependencies Used
All badge elements and analytics graphics depend on public open-source serverless tools. No subscription keys are required:
- Shields.io: Badge graphics rendering
- GitHub Readme Stats API: Dynamic profile telemetry
- Demolab Streak Stats: Work consistency visualizer
- Ryo-ma Profile Trophies: Achievements grid

---

## 🚀 Installation & Deployment Instructions

To push this configuration onto your live GitHub profile, run the following commands:

```bash
# Navigate to the workspace directory
cd C:\Users\Het\.gemini\antigravity\scratch\Hetk8406

# Stage all files including assets
git add README.md DESIGN.md CONFIGURATION.md assets/

# Commit the files with clean semantic comments
git commit -m "feat: complete redesign of profile README with premium Bento layout"

# Push updates to your profile repository main branch
git push origin main
```

---

## 🛠️ Customization Guide

### Modifying the Bento Showcase Projects
In `README.md`, under the `### 💻 Featured Projects (Bento Showcase)` header, locate the `<table>` block. You can change titles, descriptions, and code links to fit your actual live repository listings:
```html
<td width="50%" valign="top">
  <h4>🌌 Your Project Title</h4>
  <p>Your custom description summarizing technical impact.</p>
  <code>Python</code> <code>Next.js</code><br/>
  <a href="https://github.com/Hetk8406/your-repo">Codebase</a> | <a href="https://your-demo.link">Live Demo</a>
</td>
```

### Changing the Color Themes
If you ever want to change the dark styling (e.g., from Tokyo Night to Dracula or GitHub Dark):
- Replace `theme=tokyonight` in all image source links with `theme=dracula` or `theme=dark`.

---

## 🧹 Maintenance Guide
- **Repository Exclusions**: If you want to hide specific test repos from being shown in Top Languages/Stats, append `&exclude_repo=test-repo` to the GitHub Stats URL.
- **Troubleshooting Images**: If stats cards display a broken link, verify that your profile visibility settings are not set to completely private.
