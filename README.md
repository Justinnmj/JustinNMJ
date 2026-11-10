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



<!-- ===================================================== -->
<!-- JUSTIN NMJ | PROFESSIONAL GITHUB PROFILE -->
<!-- Repository: JustinNMJ -->
<!-- ===================================================== -->

<div align="center">

# Hi, I'm Justin Nshokano 👋

### Software Developer | BBIT Student | IT & Technology Enthusiast

Building digital solutions through software, technology,
business innovation and continuous learning.

[![GitHub](https://img.shields.io/badge/GitHub-JustinNMJ-181717?style=for-the-badge&logo=github)](https://github.com/JustinNMJ)
[![Profile Views](https://komarev.com/ghpvc/?username=JustinNMJ&style=for-the-badge&color=blue)](https://github.com/JustinNMJ)

**English 🇬🇧 | Français 🇫🇷**

</div>

---

## 👨‍💻 About Me

I am a Bachelor of Business Information Technology (BBIT) student
with a background in Electrical Engineering and a strong interest
in software development, information systems and digital innovation.

I enjoy transforming ideas into practical digital solutions,
exploring new technologies and developing applications that
solve real-world problems.

- 🎓 BBIT Student — Strathmore University
- ⚡ Background in Electrical Engineering
- 💻 Interested in Software Engineering and IT Systems
- 🌍 Interested in African technology and digital entrepreneurship
- 🚀 Building web, mobile and business-oriented applications
- 📚 Continuously learning, experimenting and improving

---

## 🛠️ Technical Skills

### Programming & Development

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Frameworks & Tools

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

### Databases & Systems

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### Business & IT

- Business Information Systems
- Database Design and Management
- IT Support and Computer Systems
- Microsoft Office and Productivity Tools
- Requirements Analysis and Project Documentation
- Electrical and Electronic Engineering Fundamentals

---

## 🚀 Featured Projects

### 1. KaziLink
**Employment & Digital Workforce Platform**

A digital platform concept connecting manual workers, skilled tradespeople
and potential employers in the Democratic Republic of Congo.

Technologies: Flutter, Python, Django, Database Systems.

Status: In Development.

### 2. Chillza Tickets
**Event Management & Ticketing Platform**

A ticketing platform concept designed to facilitate event discovery,
ticket sales, registration and event management across the DRC.

Technologies: Web Development, Backend APIs, Database Systems.

Status: Planning & Design.

### 3. Dr Gloire Consultation
**Healthcare Management Application**

A digital consultation management project focused on appointment
management, patient records and communication.

Technologies: Python, Django, PostgreSQL, APIs.

Repository: https://github.com/Justinnmj/Dr-Gloire

### 4. SNCC Train Reservation System
**Railway Reservation Information System**

An academic information system concept for managing train schedules,
passenger reservations and seat allocation.

Technologies: HTML, CSS, JavaScript, PHP, MySQL.

Status: Academic Project.

### 5. Talk(us)
**Culture, Creativity & Talent Platform**

A platform concept for discovering, sharing and promoting African
culture, creative talent and community initiatives.

Technologies: Flutter, PWA, Backend Development.

Status: Concept & Development Planning.

---

## 📊 GitHub Statistics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=JustinNMJ&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=JustinNMJ&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=JustinNMJ&theme=tokyonight&hide_border=true)

</div>

---

## 🎯 Current Focus

- Developing practical web applications.
- Improving Python and Django development.
- Learning Flutter and cross-platform mobile development.
- Strengthening database architecture and API integration.
- Understanding cybersecurity and computer systems.
- Building technology solutions for African markets.

---

## 🤝 Let's Connect

I am open to collaboration, learning opportunities,
technology projects and professional networking.

**GitHub:** https://github.com/JustinNMJ

---

<div align="center">

### "Learn. Build. Innovate. Repeat."

*Turning knowledge into practical solutions.*

</div>
