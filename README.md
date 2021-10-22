![Electron.js](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=Electron&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Skyline-9/Google-Messages-App">
    <img src="google-messages-icon.png" alt="Logo" width="140" height="140" >
  </a>

  <h3 align="center">Google Messages App</h3>

  <p align="center">
    MacOS Desktop app for Google Messages built using Electron
    <br />
    <br />
    <a href="https://github.com/Skyline-9/Google-Messages-App/releases/tag/v1.0.0"><strong>Download latest release here »</strong></a>
    <br />
    <br />
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
    </li>
    <li><a href="#build">Build</a></li>
  </ol>
</details>

<!-- INTRODUCTION -->
## Introduction
  
Tired of opening Google Messages in a browser tab and then having to search through 1000 tabs when a notification appears? This project leverages your OS's built in notifiation system and acts like a "native" desktop app.

Note: this project is not associated with Google, and I am not affiliated with google in any way.

<!-- Build -->
## Build

Make sure you install all the dependencies first with
```bash
yarn global add nativefier
```

To build this app, run
```
nativefier -n "Google Messages" -i "google-messages-icon.icns" "https://messages.google.com/web"
```

<!-- MARKDOWN LINKS & IMAGES -->
[license-shield]: https://img.shields.io/github/license/Skyline-9/U2-Background-Removal?style=for-the-badge
[license-url]: https://github.com/Skyline-9/Google-Messages-App/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&labelColor=blue
[linkedin-url]: https://www.linkedin.com/in/richardluorl
