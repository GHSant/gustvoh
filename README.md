### aoba,Muito prazer👋


- 👨‍💻 Procurando por emprego.

- 💌 Contato comigo: gustaziro22@gmail.com

<div align = "center">
  <a href="https://github.com/gustvoh">
  <img height = "180em" src = "https://github-readme-stats.vercel.app/api?username=gustvoh&show_icons=fals&theme=dark&include_all_commits=true&count_private=true" />
  <img height = "180em" src = "https://github-readme-stats.vercel.app/api/top-langs/?username=gustvoh&layout=compact&langs_count=7&theme=dark" />
</div>
 
  <div> 
  <a href="https://www.youtube.com/channel/UCwoBx8cMUyjRW1JKU2nO1jQ" target="_blank"> <img src = "https://img.shields.io/badge/YouTube-FF0000? style = for-the-badge & logo = youtube & logoColor = white "target =" _ blank "> </a>
  <a href="https://www.instagram.com/gu_ssta_/" target="_blank"> <img src = "https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the- emblema & logo = instagram & logoColor = white "target =" _ blank "> </a>
  <a href = "gustaziro22@gmail.com"> <img src = "https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target = "_ blank"> </a>
 
   ![Snake animation](https://github.com/rafaballerini/rafaballerini/blob/output/github-contribution-grid-snake.svg)

   on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
 
</div>
 
  
