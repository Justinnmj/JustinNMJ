## Hi there 👋
**Justinnmj/JustinNMJ** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


  Below is a complete, professional, and visually enhanced GitHub Profile README for **JustinNMJ**. It integrates your bilingual identity, structured skill presentation, project showcase, and dynamic visual elements (stats, streak, typing banner, snake animation). The tone is credible and recruiter-friendly, avoiding overstatement.

---

# 👋 Hi, I'm Justin Nshokano Mirindi

### 💻 BBIT Student @ Strathmore University | Aspiring Software Developer | Digital Innovator

**Building practical solutions. Learning continuously. Growing into a professional developer.**

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=Business+Information+Technology;Software+%26+Web+Development;IT+Systems+%26+Digital+Innovation;Learning+%7C+Building+%7C+Growing" alt="Typing SVG" />
</div>

---

## 🌍 About Me | À propos de moi

🇬🇧 **English**

I am a **Business Information Technology (BBIT)** student at **Strathmore University**, Nairobi, Kenya, with a prior background in Electrical Engineering.

I am passionate about software development, IT infrastructure, business technology, and digital innovation. I enjoy turning ideas into practical digital solutions and solving real-world problems through technology.

🇫🇷 **Français**

Je suis étudiant en **Business Information Technology (BBIT)** à **Strathmore University**, à Nairobi, au Kenya, avec une formation antérieure en génie électrique.

Je suis passionné par le développement logiciel, les infrastructures informatiques, les technologies d'entreprise et l'innovation numérique. J'aime transformer des idées en solutions numériques concrètes et résoudre des problèmes réels grâce à la technologie.

---

## 🧠 What I Do | Ce que je fais

<table>
<tr>
<td width="50%">

### 💻 Software Development
- Web applications
- Mobile applications
- Backend fundamentals
- Programming logic & problem solving

</td>
<td width="50%">

### ⚙️ IT & Engineering
- Computer systems
- Hardware & troubleshooting
- Networking fundamentals
- IT support basics

</td>
</tr>
<tr>
<td width="50%">

### 📊 Business Technology
- Business Information Systems
- Database management
- Digital business solutions
- Process improvement

</td>
<td width="50%">

### 🚀 Digital Innovation
- Startup concepts
- Digital platforms
- Technology entrepreneurship
- Creative problem-solving

</td>
</tr>
</table>

---

## 🛠️ Technologies & Tools

### Programming Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,java,cpp,c,php,js" />
</p>

### Web & Mobile Development

<p>
  <img src="https://skillicons.dev/icons?i=html,css,django,flutter" />
</p>

### Databases & Development Tools

<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgres,git,github,vscode" />
</p>

### Other Tools & Platforms

<p>
  <img src="https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoftoffice&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Networking-Fundamentals-blue?style=for-the-badge" />
</p>

*Technologies I have worked with or am actively learning through coursework and projects.*

---

## 🚀 Featured Projects | Projets Phares

| Project | Description | Status |
|---------|-------------|--------|
| **KaziLink** | Employment platform connecting manual workers and technicians with job opportunities in the DRC | In development |
| **SNCC Reservation System** | Railway reservation and ticket management system | Development initiated |
| **Dr Gloire** | Medical consultation and appointment management platform | Architecture / Development |
| **Chillza Tickets** | Event ticketing and management platform for the DRC | Planning |
| **Talk(us)** | Cultural and talent-sharing community platform | Concept / Architecture |
| **Tom Music Scores** | Digital platform for managing and sharing music scores | Project initiated |

> *Project statuses reflect honest progress: concepts, architecture, prototypes, and active development.*

---

## 📊 GitHub Statistics

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=JustinNMJ&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JustinNMJ&layout=compact&theme=tokyonight&hide_border=true" />
  <br/>
  <img width="95%" src="https://streak-stats.demolab.com?user=JustinNMJ&theme=tokyonight&hide_border=true" />
</div>

---

## 🐍 Contribution Activity

<div align="center">
  <img width="95%" src="https://raw.githubusercontent.com/JustinNMJ/JustinNMJ/output/github-contribution-grid-snake-dark.svg" alt="GitHub contribution snake animation" />
</div>

> **Note:** The snake animation requires a one-time GitHub Actions setup. See the workflow file snippet below to activate it.

---

## 🎯 Current Goals | Objectifs Actuels

- Strengthen my software development skills through consistent practice
- Build and deploy practical web and mobile applications
- Improve my database and system administration knowledge
- Explore Artificial Intelligence and Cybersecurity fundamentals
- Combine business strategy with technical execution
- Contribute to meaningful digital projects in Africa

---

## 🤝 Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-JustinNMJ-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JustinNMJ)

**Open to learning, collaboration, and technology projects.**

*Learning every day. Building for tomorrow. 🚀*

</div>

---

<div align="center">

### ⭐ Thanks for visiting my profile!

</div>

---

## ⚙️ Snake Animation Setup (One-Time)

To activate the snake contribution graph, create the following file in your `JustinNMJ/JustinNMJ` repository:

**`.github/workflows/snake.yml`**

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    permissions:
      contents: write

    steps:
      - name: Generate snake SVG
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

After committing this file, go to the **Actions** tab and run the workflow manually once. The snake will then update daily .

---

## ✅ Key Improvements in This Version

| Aspect | What Changed |
|--------|--------------|
| **Honesty** | Project statuses use precise labels (concept, architecture, initiated, in development) instead of vague claims |
| **Bilingual clarity** | English and French sections are separated cleanly, not mixed sentence-by-sentence |
| **Visual balance** | Skill icons are grouped logically; badges are limited to avoid visual clutter |
| **Professional tone** | "Aspiring Software Developer" and "BBIT Student" accurately reflect your current stage |
| **Actionable setup** | The snake workflow is included so you can activate it immediately |
| **Recruiter-friendly** | Goals and "What I Do" sections signal direction without overpromising |

This README presents you as a serious, self-aware student developer who is actively building skills and shipping real projects—exactly what recruiters and collaborators look for at your stage.
