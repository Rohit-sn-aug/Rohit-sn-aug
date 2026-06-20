<h1 align="center">Hi 👋, I'm Rohit Singh</h1>

<h3 align="center">
QA Engineer (SDET) | Java Developer | AI Enthusiast | Full Stack Developer in Progress 🚀
</h3>

<p align="center">
<a href="https://github.com/Rohit-sn-aug">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&center=true&vCenter=true&width=700&lines=QA+Engineer+(SDET);Java+Developer;AI+%26+ML+Enthusiast;Future+Full+Stack+Developer;Always+Learning+Something+New" />
</a>
</p>
## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=Rohit-sn-aug&show_icons=true&theme=tokyonight)

![](https://github-readme-streak-stats.herokuapp.com/?user=Rohit-sn-aug&theme=tokyonight)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=Rohit-sn-aug&layout=compact&theme=tokyonight)

## 🏆 Achievements

![](https://github-profile-trophy.vercel.app/?username=Rohit-sn-aug&theme=algolia&row=1&column=7)

## 🛠 Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=java,python,javascript,nodejs,html,css,mysql,postgresql,firebase,git,github,vscode" />
</p>

## 🧪 QA Engineering Skills

✔ Functional Testing

✔ Regression Testing

✔ Smoke Testing

✔ Sanity Testing

✔ UAT Testing

✔ API Testing

✔ Cross Browser Testing

✔ Integration Testing

✔ Exploratory Testing

✔ Agile Methodology

## 🌐 Portfolio

<a href="https://unrivaled-banoffee-a023c6.netlify.app/" target="_blank">
<img src="https://img.shields.io/badge/View%20Portfolio-000?style=for-the-badge&logo=netlify&logoColor=white">
</a>

## 📫 Connect With Me

<p align="left">
<a href="mailto:singhrohit8927@gmail.com">
<img src="https://skillicons.dev/icons?i=gmail" />
</a>

<a href="https://github.com/Rohit-sn-aug">
<img src="https://skillicons.dev/icons?i=github" />
</a>
</p>

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"

  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Rohit-sn-aug
          outputs: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


## 🐍 Contribution Snake

![Snake animation](https://github.com/Rohit-sn-aug/Rohit-sn-aug/blob/output/github-contribution-grid-snake.svg)



<!--
**Rohit-sn-aug/Rohit-sn-aug** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
