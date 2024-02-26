<!-- Introduction -->
# Hi there, I'm Kakelay! 👋 
![Kakelay's GitHub stats](https://github-readme-stats.vercel.app/api?username=kakelay&show_icons=true&theme=radical&bg_color=ffffff&title_color=ffa500&text_color=000000&icon_color=ffa500)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kakelay&layout=compact)
### 📈 Total contributions and streaks
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=kakelay)

 
<table width="320px">
    <tbody>
        <tr valign="top">
            <td width="80px" align="center">
            <span><strong>Flutter</strong></span><br>
            <img height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" alt="Flutter Logo">
            </td>
            <td width="80px" align="center">
            <span><strong>Java</strong></span><br>
            <img height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
            </td>
            <td width="80px" align="center">
            <span><strong>HTML</strong></span><br>
            <img height="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg">
            </td>
            <td width="80px" align="center">
            <span><strong>CSS</strong></span><br>
            <img height="32px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg">
            </td>
        </tr>
        <tr valign="top">
            <td width="80px" align="center">
            <span><strong>Node</strong></span><br>
            <img height="32px" src="[https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg](https://miro.medium.com/v2/resize:fit:800/1*v2vdfKqD4MtmTSgNP0o5cg.png)">
            </td>
            <td width="80px" align="center">
            <span><strong>git</strong></span><br>
            <img height="32px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg">
            </td>
            <td width="80px" align="center">
            <span><strong>GitHub</strong></span><br>
            <img height="32px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg">
            <td width="80px" align="center">
            <span><strong>Canva</strong></span><br>
            <img height="32px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg">
            </td>
        </tr>
    </tbody>
</table>



- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9


 
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>Bob: Hi Bob
    Bob->>Alice: Hi Alice
 
