---
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
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>

<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<div id="badges" align="center">
  <a href="https://t.me/vlglinin">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Badge"/>
  </a>
  
  <a href="https://www.youtube.com/@NeuCHil">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
</div>

<p align="center"> 
  <a href="https://www.java.com" target="_blank" rel="noreferrer"> 
    <img src="https://komarev.com/ghpvc/?username=vglinin&style=flat-square&color=blue" alt=""/> 
  </a> 
</p>

<h1 align="center">
  Привет 👋, я Влад!
</h1>

---

### :man_technologist: Обо мне:
Я Java Developer<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBWl/giphy.gif" width="30px">. Мой путь в IT начался с 21 года от компании-торговли, где я получил много массовых знаний, и стал Software Engineer. После интенсива был промежуток в пару месяцев, где я заинтересовался языком Java. И тут начался мой первый путь к Java разработке с 2023 года зарегистрировался на курсах JavaRush, которые я благополучно прошёл и не остановился на этом, а стал развиваться дальше, учить Framework, делать свой проект!
- :telescope: Изучаю Framework Spring.
- :seedling: Завершил курсы по Java разработке от JavaRush.
- :zap: Являюсь Software Engineer в компании AlpineFloor.
- :mailbox: Как связаться со мной: [![Telegram Badge](https://img.shields.io/badge/-vlglinin-blue?style=flat&logo=Telegram&logoColor=white)](https://t.me/vlglinin) [![Gmail Badgel](https://img.shields.io/badge/-Gmail-red?style-flat&logo-Gmail&logoColor-white)](mailto:glinin.vlad.2002@mail.ru)

---

### :computer: Программирование:
<div>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  <img src="https://github.com/vglinin/vglinin/assets/156716430/930df78f-1650-402f-9081-ae2cf9dd4199" title="1C" alt="1C" width="40" height="40"/>&nbsp;
</div>

---
    
### :earth_africa: Технологии:
<div>
  <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" title="Spring" alt="Spring" width="40" height="40"/>&nbsp;
  <img src="https://github.com/vglinin/vglinin/assets/156716430/1d8d3a4b-a006-462d-999b-b91a95f05d19" title="Junit5" alt="Junit5" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  <img src="https://github.com/vglinin/vglinin/assets/156716430/02ea3c0c-ad95-42e8-b33d-1cfb0c7ed85c" title="Hibernate" alt="Hibernate" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" title="Docker" alt="Docker" width="40" height="40"/>&nbsp;
</div>

---

### :wrench: Инструменты:
<div>
  <img src="https://github.com/vglinin/vglinin/assets/156716430/263d07a9-91e6-4638-a0ce-522804a31ca6" title="Gradle" alt="Gradle" width="40" height="40"/>&nbsp;
  <img src="https://github.com/vglinin/vglinin/assets/156716430/a02233fc-3f7d-45bf-b65f-24c4b5d44552" title="Maven" alt="Maven" width="40" height="40"/>&nbsp;
  <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" title="MsSQL" alt="MsSQL" width="40" height="40"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL" alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/photoshop/photoshop-plain.svg" title="Photoshop" alt="Photoshop" width="40" height="40"/>&nbsp;
</div>

---

### :office: База данных:
<div>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
</div>

---

### :compass: OC:
<div>
  <img src="https://github.com/vglinin/vglinin/assets/156716430/c0961651-cbf8-4426-93e3-c66722fabde6" title="Windows" alt="Windows" width="40" height="40"/>&nbsp;
</div>

---

### :desktop_computer: IDE:
<div>
  <img src="https://github.com/vglinin/vglinin/assets/156716430/5976f3b3-0cfd-4bb3-862d-7f35f03d0446" title="JetBrains" alt="JetBrains" width="40" height="40"/>&nbsp;
</div>

---

<!--### 💻 Codewars:
![codewars](https://www.codewars.com/users/DaVl/badges/large)
-->

---
### ⚙️ GitHub статистика:
<table>
  <tr>
    <td>
      <img align="left" src="http://github-readme-streak-stats.herokuapp.com?user=vglinin&theme=dark&background=000000" alt="webDev's Github stats" />
    </td>
    <td>
      <img height="195px" align="right" alt="webDev's Github Languages" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=vglinin&layout=compact&theme=vision-friendly-dark" />
    </td>
  </tr>

<!--![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=vglinin)-->
