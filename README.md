<!-- <h1 data-importer="text" align="left">Hey 👋 , I'm Hafsa</h1>

###

<p data-importer="text" align="left">Full-stack web developer passionate about building clean, functional, and user-friendly applications.</p>

###

<h2 data-importer="text" align="left">A passionate web developer from Pakistan.</h2>

###

<p data-importer="text" align="left">✨ Creating bugs since 2022 (and shipping fixes just as fast)<br>📚 I'm currently learning System Design, Cloud Deployment & API Architecture<br>🎯 Goals: Build scalable, production-ready web applications and grow as a full-stack engineer<br>🎲 Fun fact: My best debugging happens at 2 AM with zero explanation why<br>💬 Ask me about: Next.js, React, MySQL, REST APIs, Authentication<br>📫 Reach me at: hafsasheikh598@gmail.com</p>

###

<h2 data-importer="text" align="left">I code with</h2>

###

<div data-importer="techs" align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40" alt="nextjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="40" alt="tailwindcss logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" height="40" alt="linkedin logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
</div>

###

<div data-importer="socials" align="left">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="52" height="40" alt="youtube logo"  />
</div>

###

<div data-importer="socials" align="left">
</div>

### -->
# Hi there, I'm Hafsa Mudassar 👋

[![Email](https://img.shields.io/badge/Email-hafsasheikh598%40gmail.com-blue?style=for-the-badge&logo=gmail)](mailto:hafsasheikh598@gmail.com)
[![Location](https://img.shields.io/badge/Location-Lahore%2C%20Pakistan-green?style=for-the-badge&logo=googlemaps)](#)
[![Education](https://img.shields.io/badge/BSIT-7th%20Semester-orange?style=for-the-badge)](#)

A motivated **Information Technology Undergraduate** at the *University of the Punjab*, passionate about building interactive web applications and integrating Generative AI into real-world tools. 

---

### 🛠️ Tech Stack & Skills

**Languages & Web Development**  
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black)

**AI Integration & Tools**  
![Google Gemini](https://img.shields.io/badge/Google%20Gemini%20API-886FBF?style=flat-square&logo=googlegemini&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat-square&logo=github&logoColor=white)

---

### 🐍 Contribution Snake

![Snake Animation](https://github.com/hafsa-mudassar/hafsa-mudassar/blob/output/github-contribution-grid-snake.svg)

---

### 🚀 Featured Projects

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[Gemini AI Clone](#)** | A conversational AI chat interface integrating Google Gemini API for real-time response generation. | `JavaScript` `Gemini API` `HTML/CSS` |
| **[Dynamic Quiz App](#)** | Interactive quiz platform with real-time score calculation and clean UI state management. | `JavaScript` `DOM Manipulation` `CSS3` |
| **[Tic-Tac-Toe Game](#)** | Two-player interactive web game featuring custom win/draw logic and responsive layout. | `HTML5` `CSS3` `JavaScript` |

---

### 📊 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hafsa-mudassar&show_icons=true&theme=radial" alt="Hafsa's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hafsa-mudassar&layout=compact&theme=radial" alt="Top Languages" width="48%" />
</p>

---

### 📫 Connect with Me

- **Email:** [hafsasheikh598@gmail.com](mailto:hafsasheikh598@gmail.com)
- **Location:** Lahore, Punjab, Pakistan
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
