[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
![](https://komarev.com/ghpvc/?username=dxrshxnw&style=for-the-badge&abbreviated=true)


<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<br><br><br>
### Languages

<p align="left">
  <a href="#">
      <img src="images/cpp.svg" alt="cpp badge" style="vertical-align:top margin:6px 4px">
  </a>  
  <a href="#">
      <img src="images/python.svg" alt="python badge" style="vertical-align:top margin:6px 4px">
  </a>
  <a href="#">
      <img src="images/c.svg" alt="c badge" style="vertical-align:top margin:6px 4px">
  </a>
</p>  


### Socials
<p align="left">
  <a href="#">
      <img src="images/discord.svg" alt="discord badge" style="vertical-align:top margin:6px 4px">
  </a>  
  <a href="#">
      <img src="images/spotify.png" alt="spotify badge" style="vertical-align:top margin:6px 4px">
  </a>
</p>  
<!--
**dxrshxnw/dxrshxnw** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
