Oiii!! Meu nome é Sabrina Amorim 

# Snake Animation
  - uses: Platane/snk@master
    id: snake-gif
    with:
      github_user_name: camilamaraschin
      svg_out_path: dist/github-contribution-grid-snake.svg
  - uses: crazy-max/ghaction-github-pages@v2.1.3
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


