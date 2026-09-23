<div align="center">

# 🏴‍☠️ Olá, eu sou o Kain!
### ⚡ Desenvolvedor Full-Stack & Entusiasta Tech

<br/><br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=E63946&center=true&vcenter=true&width=550&lines=Navegando+pelo+mar+do+desenvolvimento+web...;Focado+nos+projetos+NUVE+e+SolShield!;Especialista+em+JavaScript+%7C+Node.js+%7C+CSS;Em+busca+do+One+Piece+dos+c%C3%B3digos!)](https://git.io/typing-svg)

---

### ⚔️ Tecnologias & Equipamentos do Bando

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>

</div>

<br/>

## 🍖 Diário de Bordo (Sobre Mim)

<table border="0" width="100%">
  <tr>
    <td width="65%" valign="top">
      <br/>
      <ul>
        <li>🚀 <b>Projetos Principais:</b> Construindo e aprimorando o <b>NUVE</b> e o <b>SolShield</b>.</li>
        <li>💻 <b>Especialidade:</b> Desenvolvimento Web dinâmico no ecossistema <b>JavaScript</b>.</li>
        <li>🎯 <b>Recompensa Buscada:</b> Domínio total de arquiteturas modernas e APIs.</li>
        <li>🎮 <b>Passatempos:</b> Assistir <i>One Piece</i>, jogar e criar projetos empolgantes nas horas vagas.</li>
      </ul>
    </td>
    <td width="35%" align="center" valign="middle">
      <!-- GIF Luffy Gear 5 / One Piece -->
      <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3A1dWg0OXJsa2h3eGUzbzZ1Mmw2ZHJ3OTBvdHR0dzVvdWVsczh1ZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/W23bkTpy4vDNoUTrLD/giphy.gif" width="180px" style="border-radius: 12px;" alt="Luffy GIF"/>
    </td>
  </tr>
</table>

<br/>

## 🐉 Snake Game (Grid de Contribuições)
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *" # Roda a cada 12 horas
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push Snake SVG to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kaindev-bot/kaindev-bot/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kaindev-bot/kaindev-bot/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/kaindev-bot/kaindev-bot/output/github-contribution-grid-snake.svg">
</picture>

</div>

<br/>

---

<div align="center">

<!-- GIF Chapéus de Palha / Tripulação -->
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaWgwcXBzMTNldnA1cDZsdDFuYTYwdWR0NWlhbnF6bW00eWplYjU2MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/13fTar4VVaFlG8/giphy.gif" width="320px" style="border-radius: 8px;" alt="Straw Hats Crew"/>

<br/><br/>

> *"Se você não arriscar a sua vida, não poderá criar um futuro!"*  
> — **Monkey D. Luffy 👒**

</div>
