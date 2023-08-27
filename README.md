### Olá eu sou Leticia Ast



- 🔭 Atualmente estou trabalhando com Python, Web Scraping.
- 🌱 Atualmente estou aprendendo Mongo e Pandas. 
- 💬 Ask me about Python, Django, Web Scraping.
- 📫 How to reach me: https://www.linkedin.com/in/leticia-ast/ ou leticiasistemasads@gmail.com

<div>
  <img height= "180em" src = "https://github-readme-stats.vercel.app/api?username=letdevx&icons=true&theme=cobalt"/>
  <img height= "180em" src = "https://github-readme-stats.vercel.app/api/top-langs/?username=letdevx&layout=compact&theme=cobalt"/>
</div> 


 Snake Animation
  - uses: Platane/snk@master
    id: snake-gif
    with:
      github_user_name: letdevx
      svg_out_path: dist/github-contribution-grid-snake.svg
  - uses: crazy-max/ghaction-github-pages@v2.1.3
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
