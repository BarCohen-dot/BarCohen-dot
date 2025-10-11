<!-- Cyber / Data Science Banner -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Bar Cohen | Data Scientist</title>
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background-color: white; /* שאר הדף לבן */
      color: black;
    }

    /* Header עם רקע שחור */
    header {
      background-color: black;
      color: #00FF00;
      height: 200px; /* גובה Header */
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      font-size: 2em;
    }

    .typing {
      border-right: 3px solid #00FF00; /* קו מהבהב */
      white-space: nowrap;
      overflow: hidden;
    }
  </style>
</head>
<body>
  <header>
    <div class="typing" id="typing-text"></div>
  </header>

  <main>
    <p>זהו תוכן הדף מתחת ל־Header. כאן כל התוכן רגיל, צבע הרקע לבן.</p>
  </main>

  <script>
    const text = "Bar Cohen | Data Scientist; Architecting Digital Resilience";
    const typingElement = document.getElementById('typing-text');
    let index = 0;

    function type() {
      if (index < text.length) {
        typingElement.innerHTML += text.charAt(index);
        index++;
        setTimeout(type, 100);
      } else {
        setTimeout(() => {
          typingElement.innerHTML = "";
          index = 0;
          type();
        }, 2000);
      }
    }

    type();
  </script>
</body>
</html>



<!-- Profile Views -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=barcohen&label=visitors&color=blue&style=flat-square" alt="Profile views"/>
</p>

---

🎓 **Graduate in Information Systems (B.Sc)** with a specialization in **Data Science**.  
I’m passionate about transforming data into actionable insights through **Machine Learning (ML)**, **Artificial Intelligence (AI)**, and **Software Engineering**, with a focus on **Cybersecurity**.

---

<!-- Skills Icons -->
<p align="center">
  <img src="https://skillicons.dev/icons?i=py,jupyter,anaconda,r,pandas,numpy,sklearn,tableau,powerbi,tensorflow,sqlserver,mysql,postgresql,java,html,css,bootstrap,js,php,azure,docker,linux,vscode,git,bash,github&theme=dark" alt="Full Tech Stack" title="Python, R, SQL, ML, Cloud, Cybersecurity Tools" />
</p>

---

## 🚀 Career Overview

I started as a **Practical Mechanical Engineer** and **IDF Technical Team Member**, developing strong analytical and problem-solving skills.  
This led me to specialize in **Information Systems** & **Data Science**, bridging technology, data, and innovation.

---

## 🎯 Focus Areas

* Building intelligent, data-driven systems  
* Developing predictive ML models  
* Designing scalable, secure, and resilient software solutions  

💡 My final project focused on predicting **cybersecurity incidents at Microsoft** using machine learning to improve system resilience.

---

## 🌱 Driven & Adaptable

I thrive on continuous learning, growth, and collaboration.  
I combine technical depth with curiosity, creativity, and a proactive approach to problem-solving.

---

## 🤝 Let’s Collaborate!

Open to projects involving **AI**, **ML**, **data-driven applications**, or **cybersecurity**, especially innovative ones with real-world impact.

---

## ⚡ Fun Fact

Outside of tech, I explore **innovative product ideas**, smart systems, and **AI-driven solutions** that simplify daily life and enhance user experience.

---

## 📫 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/bar--cohen-" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/BarCohen-dot" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

