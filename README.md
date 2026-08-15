<h1 align="center">Hi there, I'm Hafsa Mudassar 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=IT+Undergraduate+%7C+BSIT+7th+Semester;Web+Developer+%7C+HTML+%E2%80%A2+CSS+%E2%80%A2+JavaScript;Generative+AI+Enthusiast+%7C+Gemini+API;Looking+for+Internship+Opportunities" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:hafsasheikh598@gmail.com">
    <img src="https://img.shields.io/badge/Email-hafsasheikh598%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Location-Lahore%2C%20Pakistan-2E86AB?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Internships-brightgreen?style=for-the-badge&logo=handshake&logoColor=white" />
</p>

<p align="center">
  I'm an Information Technology undergraduate (BSIT, University of the Punjab, Lahore) passionate about building
  interactive web applications and exploring the power of Generative AI. I enjoy turning ideas into clean, functional
  products — from AI-powered chat tools to real-time interactive games — and I'm currently looking for internship
  or entry-level opportunities to grow as a developer. 🚀
</p>

---

### 🐍 Contribution Snake
![GitHub Snake Animation](https://raw.githubusercontent.com/hafsa-cloud123/hafsa-cloud123/output/github-contribution-grid-snake.svg)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hafsa-cloud123/hafsa-cloud123/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hafsa-cloud123/hafsa-cloud123/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/hafsa-cloud123/hafsa-cloud123/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

<details>
<summary>⚙️ How this snake is generated (setup instructions)</summary>

<br>

This animation is generated automatically using the [platane/snk](https://github.com/Platane/snk) GitHub Action.
To set it up on your own profile repo (<hafsa-cloud123>/<hafsa-cloud123>):

1. Create a new workflow file at .github/workflows/snake.yml in your profile repository with the following content:

yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"   # runs once a day
  workflow_dispatch: {}
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake animation
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push output to "output" branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


2. Commit and push the workflow file — it will run automatically on schedule, or you can trigger it manually from the **Actions** tab.
3. Once it runs, an `output` branch will be created containing the generated SVG files.
4. Reference the SVG in your README using the raw GitHub URL, as shown above (light/dark variants supported via `<picture>`).

</details>

---

### 🛠️ Tech Stack & Tools

**Languages**

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

**Web Development**

<p>
  <img src="https://img.shields.io/badge/DOM%20Manipulation-4B32C3?style=for-the-badge&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/Responsive%20Design-38B2AC?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/UI%2FUX%20Basics-FF6F61?style=for-the-badge&logo=figma&logoColor=white" />
</p>

**AI Tools & APIs**

<p>
  <img src="https://img.shields.io/badge/Google%20Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/REST%20APIs-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Prompt%20Engineering-FF9800?style=for-the-badge&logo=openai&logoColor=white" />
</p>

**Developer Tools**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/MS%20Office-D83B01?style=for-the-badge&logo=microsoftoffice&logoColor=white" />
</p>

---

### 🚀 Featured Projects

| Project | Description | Key Features | Tech Stack |
|---|---|---|---|
| 🤖 **[Gemini Clone (AI Chat App)](hafsa-cloud123)** | An AI-powered chat application built using the Google Gemini API for real-time, context-aware conversations. | • Real-time AI responses<br>• Context-aware chat flow<br>• Clean, minimal chat UI | `HTML5` `CSS3` `JavaScript` `Gemini API` |
| 🧠 **[Quiz Application](hafsa-cloud123)** | A dynamic quiz app that tracks user scores in real time with a smooth, engaging UI. | • Real-time score tracking<br>• Dynamic question rendering<br>• Clean, responsive UI | `HTML5` `CSS3` `JavaScript` |
| ❌⭕ **[Tic-Tac-Toe Game](hafsa-cloud123)** | An interactive two-player game featuring custom win/draw detection logic. | • Custom win/draw detection<br>• Two-player interactive logic<br>• Fully responsive design | `HTML5` `CSS3` `JavaScript` |

> 💡 Replace the `#` links above with your actual repository URLs once ready.

---

### 📊 GitHub Stats & Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=hafsa-cloud123&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hafsa-cloud123&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hafsa-cloud123&theme=tokyonight&hide_border=true" />
</p>



---

### 📫 Contact & Socials

<p align="center">
  <a href="mailto:hafsasheikh598@gmail.com">
    <img src="https://img.shields.io/badge/Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/hafsa-cloud123">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>Thanks for visiting my profile — let's connect and build something great! ✨</i>
</p>
