<div align="center">

# 👋 Hi, I'm Prakhar Dixit

### Software Engineer • AI Developer • Cybersecurity Enthusiast

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=2500&pause=1000&color=00E5FF&center=true&vCenter=true&width=700&lines=Building+AI+Powered+Applications;Full+Stack+Developer;Cybersecurity+Enthusiast;Python+Developer;Always+Learning+New+Technologies" />

</div>

---

# 🚀 About Me

🎓 B.Tech Computer Science Engineering (AI & ML)

💻 Passionate about building production-ready applications.

🤖 Interested in Artificial Intelligence, Backend Development, Cybersecurity and Cloud Computing.

🌱 Currently Learning

- System Design
- Docker
- Kubernetes
- Machine Learning
- Reverse Engineering

⚡ Fun Fact

I enjoy creating software that solves real-world problems.

---

# 💻 Tech Stack

## Languages

<p>

<img src="https://skillicons.dev/icons?i=python,cpp,c,java,kotlin,javascript,typescript"/>

</p>

## Frontend

<p>

<img src="https://skillicons.dev/icons?i=react,nextjs,html,css,tailwind"/>

</p>

## Backend

<p>

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi"/>

</p>

## Database

<p>

<img src="https://skillicons.dev/icons?i=postgres,mongodb,supabase,mysql"/>

</p>

## Tools

<p>

<img src="https://skillicons.dev/icons?i=docker,git,github,linux,vscode,androidstudio,postman"/>

</p>

---

# 📈 GitHub Stats

<p align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Prakhar-dixit01&show_icons=true&theme=tokyonight"/>

<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=Prakhar-dixit01&theme=tokyonight"/>

</p>

---

# 📊 Most Used Languages

<p align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prakhar-dixit01&layout=compact&theme=tokyonight"/>

</p>

---

# 📈 Activity Graph

<p align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Prakhar-dixit01&theme=tokyo-night"/>

</p>

---

# 🏆 GitHub Trophies

<p align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Prakhar-dixit01&theme=tokyonight&row=2&column=4"/>

</p>

---

# 🚀 Featured Projects

| Project | Description |
|----------|-------------|
| 🤖 DeviceScope AI | AI Powered Device Diagnostics |
| 🏢 CRM SaaS | Complete CRM Platform |
| 📊 Business Analyzer | AI Business Opportunity Analyzer |
| 📧 Cold Email AI | AI Outreach Platform |
| 🔐 Cyber Toolkit | Ethical Hacking Utilities |

---

# 📫 Connect With Me

<p>

<a href="mailto:dixit001prakhar@gmail.com">
<img src="https://skillicons.dev/icons?i=gmail"/>
</a>

<a href="https://github.com/Prakhar-dixit01">
<img src="https://skillicons.dev/icons?i=github"/>
</a>

<a href="https://linkedin.com">
<img src="https://skillicons.dev/icons?i=linkedin"/>
</a>

</p>

---

<div align="center">

### ⭐ Thanks for visiting my profile ⭐

</div>





name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:

      - uses: Platane/snk@v3

        with:

          github_user_name: Prakhar-dixit01

          outputs: dist/github-contribution-grid-snake.svg
