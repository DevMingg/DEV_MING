<!--타이틀 부분-->







<!--내용 부분-->
<h3 align="center">💻 Tech Stack 💻</h3>
<div align="center">
  <img src="https://img.shields.io/badge/java-ea3c53.svg?style=for-the-badge&logo=java&logoColor=61DAFB" />&nbsp
</div>

</div>

<br>

<br>

<h3 align="center">📚 Studying 📚</h3>
<div align="center">
  <img src="https://img.shields.io/badge/Kotlin -ffbfd2.svg?style=for-the-badge&logo=Kotlin&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Spring Boot-9ad255?style=for-the-badge&logo=Spring Boot&logoColor=white" />&nbsp
<div align="center">
  <img src="https://img.shields.io/badge/mysql -a9cdd1?style=for-the-badge&logo=mysql&logoColor=white" />&nbsp

</div>


<br>

<h3 align="center">🛠 Tools 🛠</h3>
<div align="center">
  <img src="https://img.shields.io/badge/git-F05033.svg?style=for-the-badge&logo=git&logo=Color=white" />&nbsp
  <img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logo=github&logoColor=white" />&nbsp
</div>


<br>

<div align="center">
  <img src="https://img.shields.io/badge/VSCode-2C2C32.svg?style=for-the-badge&logo=visual-studio-code&logoColor=22ABF3" />&nbsp
<!--   <img src="https://img.shields.io/badge/Colab-2C2C32.svg?style=for-the-badge&logo=googlecolab&logoColor=F9AB00" />&nbsp -->
</div>

<br>

<h3 align="center">📫 Contact 📫</h3>
<div align="center">
 
  <a href="mailto:elwlxjf2025@gmail.com">
    <img
      src="https://img.shields.io/badge/elwljxf2025@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>&nbsp
  </a>
</div>

  <a herf="instagam:alsguril">
   <div align= "center">  
<img
      src="https://img.shields.io/badge/alsguril-DD2A7B?style=for-the-badge&logo=instagram&logoColor=white"/>&nbsp
  </a>
</div>


<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=elwlxjf2025&show_icons=true&locale=en" alt="elwlxjf2025" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=elwlxjf2025&" alt="elwlxjf2025" /></p>


<p align="center">
  <a href="http://lovera.maxam.now.sh/">
    <img src="https://user-images.githubusercontent.com/25841814/79395484-5081ae80-7fac-11ea-9e27-ac91472e31dd.png" alt="screenshot" width="500">
  </a>
  <h3 align="center">📌✨productive-box</h3>
</p>

<p align="center">
   <img src="https://img.shields.io/badge/language-typescript-blue?style"/>
   <img src="https://img.shields.io/github/license/maxam2017/productive-box"/>
   <img src="https://img.shields.io/github/stars/maxam2017/productive-box"/>
   <img src="https://img.shields.io/github/forks/maxam2017/productive-box"/>
</p>
<p align="center">
   Are you an early 🐤 or a night 🦉?
   <br/>
   When are you most productive during the day?
   <br/>
   Let's check out in gist!
</p>

---

> This project is inspired by an awesome pinned-gist project.<br/>Find more in https://github.com/matchai/awesome-pinned-gists

## Overview
This project uses GitHub graphQL API to get the commit histories and write into the gist by [rest.js](https://github.com/octokit/rest.js#readme)

## Setup

### Prep work
1. Create a new public GitHub Gist (https://gist.github.com/)
1. Create a token with the `gist` and `repo` scope and copy it. (https://github.com/settings/tokens/new)
   > enable `repo` scope seems **DANGEROUS**<br/>
   > but this GitHub Action only accesses your commit timestamp in repository you contributed.

### Project setup

1. Fork this repo
1. Open the "Actions" tab of your fork and click the "enable" button
1. Edit the [environment variable](https://github.com/maxam2017/productive-box/blob/master/.github/workflows/schedule.yml#L17-L18) in `.github/workflows/schedule.yml`:

   - **GIST_ID:** The ID portion from your gist url: `https://gist.github.com/maxam2017/`**`9842e074b8ee46aef76fd0d493bae0ed`**.
   - **TIMEZONE:** The timezone of your location, eg. `Asia/Taipei` for Taiwan, `America/New_York` for America in New York, etc.

1. Go to the repo **Settings > Secrets**
1. Add the following environment variables:
   - **GH_TOKEN:** The GitHub token generated above.
1. [Pin the newly created Gist](https://help.github.com/en/github/setting-up-and-managing-your-github-profile/pinning-items-to-your-profile)


