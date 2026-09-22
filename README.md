<!-- ══════════════ HEADER ══════════════ -->
<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=7AA2F7&center=true&vCenter=true&width=560&lines=Jecquar+Aguilan;Full-stack+%2B+computer+vision;Building+Course4Ward+%26+PWDe)

</div>

> Fourth-year IT student at Saint Louis University, Baguio City.
> Full-stack apps and computer-vision tooling. Currently looking for an OJT placement.

<!-- ══════════════ STATS ══════════════ -->
<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=AguilanJec&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github)

![Streak Stats](https://streak-stats.demolab.com?user=AguilanJec&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AguilanJec&layout=compact&theme=tokyonight&hide_border=true&langs_count=6)

![Trophies](https://github-profile-trophy.vercel.app/?username=AguilanJec&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7)

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=AguilanJec&theme=tokyo-night&hide_border=true&area=true)

![Visitors](https://komarev.com/ghpvc/?username=AguilanJec&style=flat-square&color=7AA2F7&label=Profile+Views)

</div>

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Computer Vision & Mobile**

![MediaPipe](https://img.shields.io/badge/MediaPipe-4285F4?style=flat-square)
![FaceMesh](https://img.shields.io/badge/FaceMesh-4285F4?style=flat-square)
![Blendshape V2](https://img.shields.io/badge/Blendshape_V2-4285F4?style=flat-square)
![Android](https://img.shields.io/badge/Android-34A853?style=flat-square&logo=android&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)

---

## Projects

| Name | What it does | Stack |
| :--- | :--- | :--- |
| [**Course4Ward**](https://github.com/SLU-STiers/Course4Ward) | Three-tier academic system: TypeScript frontend, backend service, and a separate Python AI service. I built the batch per-admission-day order summarization and a role-based route mapping to unblock the frontend. | TypeScript · Python · CSS |
| [**PWDe**](https://github.com/AguilanJec/PWDe) | Android accessibility app that lets PWDs play mobile esports hands-free — head movement and facial gestures drive a virtual cursor instead of touch input. Fork of `google/project-gameface`, 4 commits ahead of upstream. | Java · Android · MediaPipe |

<sub>Two private repos are still in progress — happy to walk through them on request.</sub>

---

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AguilanJec)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jecquar-ravent-aguilan-a82170430/)

</div>

<!--
══════════════ SNAKE ANIMATION ══════════════

The workflow below writes to an `output` branch. Run it once, then uncomment
the <picture> tag here. Don't commit the `output` branch by hand.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AguilanJec/AguilanJec/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AguilanJec/AguilanJec/output/github-snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/AguilanJec/AguilanJec/output/github-snake.svg" />
</picture>

</div>

══════════════════════════════════════════════
-->

<!--
══════════════ SNAKE WORKFLOW — save as .github/workflows/snake.yml ══════════════

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Generate snake SVGs
        uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: AguilanJec
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

════════════════════════════════════════════════════════════════════════════════
-->
