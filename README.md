<h1 align="center">Hi, I'm Mohammed Ahmad</h1>
<h3 align="center">
  Backend .NET Developer | Software Engineer  
  <span id="typing"></span>
</h3>

---

## 📄 Resume
<p align="center">
  <!-- Opens CV in browser instead of downloading -->
  <a href="https://drive.google.com/file/d/1H8Vez00DwfFJ9EjUg6TJdh4ey6I9sc48/preview" target="_blank">
    <img src="https://img.shields.io/badge/View%20My%20CV-Open%20Online-28a745?style=for-the-badge" />
  </a>
</p>

---

## 🌐 Portfolio
<p align="center">
  <a href="https://mohammed-ahmad-portfolio.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Visit%20Portfolio-0078D7?style=for-the-badge&logo=appveyor&logoColor=white"/>
  </a>
</p>

---

## 🛠️ Tech Stack

### 💻 Languages & Frameworks
<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,cpp,html,css,js,git,github,visualstudio&perline=6" />
</p>

### 🗄️ Database & Backend Tools
<p align="center">
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/T--SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/ADO.NET-512BD4?style=for-the-badge&logo=.net&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST%20API-02569B?style=for-the-badge&logo=fastapi&logoColor=white"/>
</p>

---

## 📊 Top Languages
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohammed-Ahmad1&layout=compact&theme=dark" />
</p>

---

## 🏆 Competitive Programming
<p align="center">
  <a href="https://www.hackerrank.com/MohammedAhmad1" target="_blank">
    <img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white"/>
  </a>
  <a href="https://codeforces.com/profile/MohammedAhmad1" target="_blank">
    <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white"/>
  </a>
</p>

---

## 🌐 Connect with me
<p align="center">

<a href="https://www.linkedin.com/in/mohammedahmad1">
  <img src="https://skillicons.dev/icons?i=linkedin" height="50" />
</a>

<a href="mailto:mfalahaddin@gmail.com">
  <img src="https://skillicons.dev/icons?i=gmail" height="50" />
</a>

<a href="https://join.slack.com/t/myownworkspac-v5l9857/shared_invite/zt-3pvavyx2e-m6D5qOrKLf4oRKOvO7HUFQ">
  <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/slack.svg" height="50"/>
</a>

<a href="https://wa.me/962779307406">
  <img src="https://img.icons8.com/color/96/whatsapp--v1.png" height="50"/>
</a>

</p>

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mohammed-Ahmad1&show_icons=true&theme=dark&hide_border=true" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mohammed-Ahmad1&theme=dark&hide_border=true" />
</p>

---

## 🚀 About Me
💡 Backend Developer specialized in **.NET & SQL Server**  
💻 Strong in **Data Structures, OOP, and Problem Solving**  
🔧 Building **RESTful APIs & Desktop Applications (Windows Forms)**  
📍 Jordan

---

⭐ From [Mohammed-Ahmad1](https://github.com/Mohammed-Ahmad1)

---

<!-- Typing animation script -->
<script>
const text = ["Backend Developer", "Software Engineer", "Competitive Programmer"];
let i = 0, j = 0, currentText = "", isDeleting = false;

function type() {
  const typingEl = document.getElementById("typing");
  if(!typingEl) return;

  if(!isDeleting && j <= text[i].length){
    currentText = text[i].substring(0,j);
    typingEl.innerHTML = currentText + "|";
    j++;
  }
  if(isDeleting && j >= 0){
    currentText = text[i].substring(0,j);
    typingEl.innerHTML = currentText + "|";
    j--;
  }

  if(j === text[i].length){
    isDeleting = true;
  }
  if(isDeleting && j === 0){
    isDeleting = false;
    i = (i+1) % text.length;
  }

  setTimeout(type, isDeleting ? 50 : 150);
}

type();
</script>
