<!-- Modern Animated Banner with SVG -->

<div align="center">

  <img src="https://raw.githubusercontent.com/tanh1c/tanh1c/main/banner.svg" alt="Banner" width="100%"/>

</div>

<!-- Alternative: Inline SVG Banner with Sakura Theme -->

<div align="center">

  <svg width="100%" height="300" xmlns="http://www.w3.org/2000/svg">

    <defs>

      <!-- Sakura petal pattern -->

      <pattern id="sakuraPattern" width="80" height="80" patternUnits="userSpaceOnUse">

        <circle cx="40" cy="40" r="3" fill="#FFB6C1" opacity="0.3"/>

        <path d="M 40 20 Q 35 25 30 20 Q 35 15 40 20" fill="#FFC0CB" opacity="0.2"/>

        <path d="M 60 40 Q 55 35 60 30 Q 65 35 60 40" fill="#FFB6C1" opacity="0.2"/>

        <path d="M 40 60 Q 45 55 50 60 Q 45 65 40 60" fill="#FFC0CB" opacity="0.2"/>

        <path d="M 20 40 Q 25 45 20 50 Q 25 55 20 50" fill="#FFB6C1" opacity="0.2"/>

      </pattern>

      <!-- Grid pattern for subtle texture -->

      <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">

        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(255,182,193,0.15)" stroke-width="1"/>

      </pattern>

      <!-- Glow filter for sakura petals -->

      <filter id="glow">

        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>

        <feMerge>

          <feMergeNode in="coloredBlur"/>

          <feMergeNode in="SourceGraphic"/>

        </feMerge>

      </filter>

      <!-- Sakura petal shape -->

      <path id="sakuraPetal" d="M 0 0 Q -10 -5 -15 0 Q -10 5 0 0 Q 10 5 15 0 Q 10 -5 0 0" fill="#FFB6C1" opacity="0.4"/>

    </defs>

    <!-- Background with sakura color -->

    <rect width="100%" height="100%" fill="#FFF0F5"/>

    <!-- Sakura pattern overlay -->

    <rect width="100%" height="100%" fill="url(#sakuraPattern)"/>

    <!-- Grid overlay -->

    <rect width="100%" height="100%" fill="url(#grid)"/>

    <!-- Floating sakura petals -->

    <use href="#sakuraPetal" x="15%" y="25%" filter="url(#glow)">

      <animateTransform attributeName="transform" type="rotate" values="0 0 0;360 0 0" dur="20s" repeatCount="indefinite"/>

      <animate attributeName="opacity" values="0.3;0.6;0.3" dur="4s" repeatCount="indefinite"/>

    </use>

    <use href="#sakuraPetal" x="85%" y="75%" filter="url(#glow)">

      <animateTransform attributeName="transform" type="rotate" values="360 0 0;0 0 0" dur="25s" repeatCount="indefinite"/>

      <animate attributeName="opacity" values="0.4;0.7;0.4" dur="5s" repeatCount="indefinite"/>

    </use>

    <use href="#sakuraPetal" x="70%" y="20%" filter="url(#glow)">

      <animateTransform attributeName="transform" type="rotate" values="0 0 0;360 0 0" dur="18s" repeatCount="indefinite"/>

      <animate attributeName="opacity" values="0.2;0.5;0.2" dur="3.5s" repeatCount="indefinite"/>

    </use>

    <use href="#sakuraPetal" x="25%" y="70%" filter="url(#glow)">

      <animateTransform attributeName="transform" type="rotate" values="360 0 0;0 0 0" dur="22s" repeatCount="indefinite"/>

      <animate attributeName="opacity" values="0.3;0.6;0.3" dur="4.5s" repeatCount="indefinite"/>

    </use>

    <!-- Decorative circles with sakura colors -->

    <circle cx="10%" cy="20%" r="50" fill="#FFB6C1" opacity="0.2" filter="url(#glow)">

      <animate attributeName="r" values="50;60;50" dur="4s" repeatCount="indefinite"/>

    </circle>

    <circle cx="90%" cy="80%" r="60" fill="#FFC0CB" opacity="0.25" filter="url(#glow)">

      <animate attributeName="r" values="60;70;60" dur="5s" repeatCount="indefinite"/>

    </circle>

    <circle cx="75%" cy="15%" r="40" fill="#FFE4E1" opacity="0.3" filter="url(#glow)">

      <animate attributeName="r" values="40;50;40" dur="3.5s" repeatCount="indefinite"/>

    </circle>

    <!-- Main text with sakura accent -->

    <text x="50%" y="50%" font-family="Arial, sans-serif" font-size="48" font-weight="bold" fill="#8B4A6B" text-anchor="middle" dominant-baseline="middle" filter="url(#glow)">

      Hi there 👋

    </text>

    <text x="50%" y="65%" font-family="Arial, sans-serif" font-size="24" fill="#C85A7A" text-anchor="middle" dominant-baseline="middle">

      Welcome to my GitHub Profile

    </text>

  </svg>

</div>

<!-- Modern Typing Animation -->

<div align="center">

  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=C85A7A&center=true&vCenter=true&width=600&lines=I'm+TAnh+%F0%9F%91%8B;Computer+Science+Student+%F0%9F%93%9A;AI+%26+Web+Developer+%F0%9F%92%BB;Building+Amazing+Things+%F0%9F%9A%80" alt="Typing SVG" />

</div>

---

<!-- About Section -->

## 🚀 About Me

<div align="center">

🎓 **3rd-year Computer Science Student** @ **Ho Chi Minh City University of Technology (HCMUT)**  

💻 **Passionate Developer** exploring **AI · Machine Learning · Full-Stack Development**  

🌱 Currently diving deep into **CUDA Programming & Large Language Models**  

⚡ Fun fact: I love building projects that combine **AI** and **modern web technologies**

</div>

---

<!-- Tech Stack -->

## 💻 Tech Stack & Tools

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend & Database

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

### AI & ML

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

### Tools & Platforms

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

![VSCode](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

<!-- GitHub Stats -->

## 📊 GitHub Analytics

<div align="center">

  

  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=tanh1c&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true"/>

  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tanh1c&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>

  

</div>

<div align="center">

  

  <!-- Fixed GitHub Streak - Using alternative service -->

  <img src="https://streak-stats.demolab.com/?user=tanh1c&theme=tokyonight&hide_border=true&border_radius=10" alt="GitHub Streak"/>

  

</div>

<div align="center">

  

  <!-- Contribution Graph -->

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=tanh1c&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true" alt="GitHub Activity Graph"/>

  

</div>

---

<!-- Featured Projects -->

## 🌟 Featured Projects

### 🤖 AI & Machine Learning

<div align="center">

| Project | Description | Tech Stack |

|---------|-------------|------------|

| **[Word2Vec-PyCUDA](https://github.com/tanh1c/Word2Vec-PyCUDA)** | High-performance Word2Vec implementation using PyCUDA for GPU acceleration | `Python` `CUDA` `NVIDIA` |

| **[Lottery Prediction](https://github.com/tanh1c/lottery-prediction)** | ML-based number analysis and prediction system | `Python` `Machine Learning` |

</div>

### 🌐 Web Development

<div align="center">

| Project | Description | Tech Stack |

|---------|-------------|------------|

| **[HCMUT Tutor](https://github.com/tanh1c/hcmut-tutor)** | Comprehensive Learning Management System with modern UI/UX | `TypeScript` `React` `Full-Stack` |

| **[Student Schedule](https://github.com/tanh1c/student-schedule)** | Interactive timetable web application | `JavaScript` `Web App` |

| **[Envelope-2025](https://github.com/tanh1c/envelope-2025)** | Modern UI/UX web project | `JavaScript` `Frontend` |

| **[Stake Clone](https://github.com/tanh1c/stake-clone)** | Web application clone project | `JavaScript` `Web Development` |

| **[Tutor Web](https://github.com/tanh1c/tutor-web)** | Web-based tutoring platform | `JavaScript` `Web App` |

</div>

### 📚 Academic Projects

<div align="center">

| Project | Description | Tech Stack |

|---------|-------------|------------|

| **[MM241 Assignment](https://github.com/tanh1c/MM241-Assignment)** | Mathematical Modeling Assignment - Fall 2024 | `Python` `Mathematics` |

</div>

---

<!-- Project Highlights with Cards -->

## 💡 Project Highlights

<div align="center">

  <table>

    <tr>

      <td width="50%" align="center">

        <h3>🚀 HCMUT Tutor</h3>

        <p>Full-featured Learning Management System built with TypeScript</p>

        <a href="https://github.com/tanh1c/hcmut-tutor">View Project →</a>

      </td>

      <td width="50%" align="center">

        <h3>⚡ Word2Vec-PyCUDA</h3>

        <p>GPU-accelerated Word2Vec implementation for high-performance NLP</p>

        <a href="https://github.com/tanh1c/Word2Vec-PyCUDA">View Project →</a>

      </td>

    </tr>

  </table>

</div>

---

<!-- Social Links -->

## 📫 Connect With Me

<div align="center">

  

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chu-nguyen-tuan-anh-624a0b380/)

  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tanh1c)

  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anh.chunguyentuan@hcmut.edu.vn)

  

</div>

<div align="center">

  

  📧 **Email:** anh.chunguyentuan@hcmut.edu.vn

  

</div>

---

<!-- Footer -->

<div align="center">

  

  <img src="https://komarev.com/ghpvc/?username=tanh1c&label=Profile%20Views&color=C85A7A&style=for-the-badge" alt="Profile Views"/>

  

  <p>Made with ❤️ by TAnh</p>

  

</div>
