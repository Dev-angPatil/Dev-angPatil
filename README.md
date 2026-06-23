<p align="center">
  <img src="images/header-banner.svg" width="800" alt="Devang Patil Skyline Banner" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Share+Tech+Mono&size=20&duration=3000&pause=1000&color=00F2FE&center=true&vCenter=true&width=600&lines=CS+Student+%26+System+Architect;Full-Stack+Web+%26+Android+Developer;Creator+of+FocusOS+%26+IntentOS;SRE+%26+AI%2FML+Enthusiast" alt="Typing SVG" />
  </a>
</p>

---

<p align="center">
  <a href="https://dev-angpatil.github.io/Dev-angPatil/">
    <img src="images/play-btn.svg" width="250" alt="Play Neon Tetris" />
  </a>
</p>

---

<p align="center">
  <img src="images/profile-card.svg" width="800" alt="Devang's RPG Character Card" />
</p>

---

## 🎮 Cyberpunk Neon Tetris Game

This repository serves as Devang's official GitHub profile page and hosts **Neon Tetris**, a web-based cyberpunk-themed arcade experience written in vanilla HTML5, Canvas, and CSS.

### Key Game Features:
- **WebGL-style 2D Canvas**: High-fidelity neon lighting shadows and active cell glow effects.
- **Web Audio API Synthesizer**: Generates dynamic retro sound frequencies programmatically (movement clicks, rotation sine sweeps, line-clear arpeggios, and descending sawtooth game-over notes) without external audio file loading.
- **Ghost Projection**: Shows real-time block drop guides for precision landing.
- **Dynamic Speed Calibration**: Automatically scales drops speed (reducing millisecond intervals) on level completions.
- **Responsive Layout**: Adjusts layout for mobile display and includes overlay panels for touch gestures.

---

## 🛠️ Tech Stack & Equipment Inventory

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,python,kotlin,go,js,ts,react,nextjs,tailwind,android,mysql,postgres,mongodb,docker,git,githubactions" alt="Tech Stack" />
  </a>
</p>

---

## 📂 Project Structure

```text
Dev-angPatil/
├── .github/
│   └── workflows/
│       └── main.yml        # CI/CD pipeline building contribution grid snake
├── images/
│   ├── header-banner.svg   # Skyline profile banner
│   ├── profile-card.svg    # Character stat board card
│   ├── play-btn.svg        # Neon button linking to game deploy
│   └── github-contribution-grid-snake.svg
├── index.html              # Neon Tetris game implementation page
└── README.md               # GitHub Profile README file (this file)
```

---

## 🚀 How to Run the Game Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Dev-angPatil/Dev-angPatil.git
   cd Dev-angPatil
   ```
2. **Open index.html**:
   Double click the `index.html` file or launch it using any local HTTP static server (e.g. `npx serve` or Live Server extension).
3. **Play**:
   - Use `A` / `D` or `Arrow Keys` to move left and right.
   - Use `W` or `Up Arrow` to rotate.
   - Use `S` or `Down Arrow` for soft drop.
   - Use `Space` for instant hard drop.
   - Press `P` to pause/resume.

---

## 📊 System Diagnostics & Metrics

<p align="center">
  <!-- GitHub Readme Stats Card (Synthwave/Outrun Customized Theme) -->
  <img src="https://github-readme-stats.vercel.app/api?username=Dev-angPatil&show_icons=true&bg_color=0c081e&title_color=00f2fe&text_color=ffffff&icon_color=ff007f&border_color=ff007f" height="170" alt="GitHub Stats" />
  &nbsp;&nbsp;
  <!-- GitHub Streak Card (Customized Theme) -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dev-angPatil&background=0c081e&ring=ff007f&fire=ffaa00&currStreakNum=00f2fe&sideNums=ffffff&sideLabels=8b80b6&dates=ffffff" height="170" alt="GitHub Streak Stats" />
</p>

---

## 🐍 Contribution Grid Journey

<p align="center">
  <!-- Generated via Snake Action -->
  <img src="images/github-contribution-grid-snake.svg" alt="Contribution Grid Snake" />
</p>

<p align="center" style="font-family: monospace; font-size: 11px; color: #8b80b6;">
  🚀 <i>Automated grid scan sweeps every 24 hours. Last execution status: ONLINE.</i>
</p>

---

## 🤖 AI Developer Notes

### Context & Second Brain Mapping
- **Second Brain Notes**: Review active tasks and profile preferences under:
  [Ctx - Dev-angPatil Context](file:///home/deu/Documents/Technical%20&%20Academins/10%20AI/Context/Coding%20Repos/Dev-angPatil/Ctx%20-%20Dev-angPatil%20Context.md) and [Ctx - Dev-angPatil Inbox](file:///home/deu/Documents/Technical%20&%20Academins/10%20AI/Context/Coding%20Repos/Dev-angPatil/Ctx%20-%20Dev-angPatil%20Inbox.md).

### Codebase Invariants
- **Web Audio API context rules**: Browser security prevents synthesizing audio until the user interacts with the page. Sound is initialized asynchronously via click listeners on the main start button.
- **Tetris Board Size**: The play grid is strictly defined as `12 columns` by `24 rows` scaled by `20` within the canvas. Changing block grids requires adjustments to the matrix bounds in `index.html`.
- **Snake Action Workflow**: The contribution grid snake is generated automatically by a GitHub action workflow running daily. Do not modify the target filename in `/images/github-contribution-grid-snake.svg` directly as it will break the automated generation pipeline.
