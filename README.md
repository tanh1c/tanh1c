<!-- Modern Animated Banner with Sakura Theme -->

<div align="center">

  <svg width="100%" height="300" xmlns="http://www.w3.org/2000/svg">

    <defs>

      <!-- Sakura petal shape -->

      <path id="sakuraPetal" d="M0,0 C-10,-5 -15,-15 -10,-25 C-5,-20 0,-15 0,0 C0,-15 5,-20 10,-25 C15,-15 10,-5 0,0 Z" fill="#FFB6C1"/>

      <path id="sakuraPetal2" d="M0,0 C-8,-4 -12,-12 -8,-20 C-4,-16 0,-12 0,0 C0,-12 4,-16 8,-20 C12,-12 8,-4 0,0 Z" fill="#FFC0CB"/>

      <path id="sakuraPetal3" d="M0,0 C-6,-3 -9,-9 -6,-15 C-3,-12 0,-9 0,0 C0,-9 3,-12 6,-15 C9,-9 6,-3 0,0 Z" fill="#FFD1DC"/>

      <!-- Glow filter for sakura petals -->

      <filter id="sakuraGlow">

        <feGaussianBlur stdDeviation="2" result="coloredBlur"/>

        <feMerge>

          <feMergeNode in="coloredBlur"/>

          <feMergeNode in="SourceGraphic"/>

        </feMerge>

      </filter>

      <!-- Branch pattern -->

      <pattern id="branchPattern" width="200" height="200" patternUnits="userSpaceOnUse">

        <path d="M 50 50 Q 100 30 150 50" fill="none" stroke="#8B4513" stroke-width="3" opacity="0.3"/>

      </pattern>

    </defs>

    <!-- Background - Soft pink sky color -->

    <rect width="100%" height="100%" fill="#FFF0F5"/>

    <!-- Sakura branches at top -->

    <g opacity="0.4">

      <path d="M 50 30 Q 150 20 250 30 Q 350 25 450 30" fill="none" stroke="#8B4513" stroke-width="4" stroke-linecap="round"/>

      <path d="M 200 35 Q 220 25 240 35" fill="none" stroke="#8B4513" stroke-width="3" stroke-linecap="round"/>

      <path d="M 300 35 Q 320 25 340 35" fill="none" stroke="#8B4513" stroke-width="3" stroke-linecap="round"/>

      <path d="M 100 40 Q 120 30 140 40" fill="none" stroke="#8B4513" stroke-width="3" stroke-linecap="round"/>

      <path d="M 400 40 Q 420 30 440 40" fill="none" stroke="#8B4513" stroke-width="3" stroke-linecap="round"/>

    </g>

    <!-- Sakura flowers on branches -->

    <g filter="url(#sakuraGlow)">

      <!-- Flower 1 -->

      <g transform="translate(150, 35)">

        <use href="#sakuraPetal" transform="rotate(0)"/>

        <use href="#sakuraPetal" transform="rotate(72)"/>

        <use href="#sakuraPetal" transform="rotate(144)"/>

        <use href="#sakuraPetal" transform="rotate(216)"/>

        <use href="#sakuraPetal" transform="rotate(288)"/>

        <circle cx="0" cy="0" r="3" fill="#FFD1DC"/>

      </g>

      <!-- Flower 2 -->

      <g transform="translate(300, 35)">

        <use href="#sakuraPetal2" transform="rotate(0)"/>

        <use href="#sakuraPetal2" transform="rotate(72)"/>

        <use href="#sakuraPetal2" transform="rotate(144)"/>

        <use href="#sakuraPetal2" transform="rotate(216)"/>

        <use href="#sakuraPetal2" transform="rotate(288)"/>

        <circle cx="0" cy="0" r="2.5" fill="#FFC0CB"/>

      </g>

      <!-- Flower 3 -->

      <g transform="translate(220, 40)">

        <use href="#sakuraPetal3" transform="rotate(0)"/>

        <use href="#sakuraPetal3" transform="rotate(72)"/>

        <use href="#sakuraPetal3" transform="rotate(144)"/>

        <use href="#sakuraPetal3" transform="rotate(216)"/>

        <use href="#sakuraPetal3" transform="rotate(288)"/>

        <circle cx="0" cy="0" r="2" fill="#FFFFFF"/>

      </g>

      <!-- Flower 4 -->

      <g transform="translate(420, 40)">

        <use href="#sakuraPetal" transform="rotate(0)"/>

        <use href="#sakuraPetal" transform="rotate(72)"/>

        <use href="#sakuraPetal" transform="rotate(144)"/>

        <use href="#sakuraPetal" transform="rotate(216)"/>

        <use href="#sakuraPetal" transform="rotate(288)"/>

        <circle cx="0" cy="0" r="3" fill="#FFD1DC"/>

      </g>

    </g>

    <!-- Falling sakura petals animation -->

    <g opacity="0.7">

      <!-- Petal 1 -->

      <g transform="translate(10%, 20%)">

        <ellipse cx="0" cy="0" rx="8" ry="12" fill="#FFB6C1" filter="url(#sakuraGlow)">

          <animateTransform attributeName="transform" type="translate" values="0,0; 20,100; 40,200" dur="8s" repeatCount="indefinite"/>

          <animateTransform attributeName="transform" type="rotate" values="0; 360" dur="8s" repeatCount="indefinite" additive="sum"/>

        </ellipse>

      </g>

      <!-- Petal 2 -->

      <g transform="translate(30%, 10%)">

        <ellipse cx="0" cy="0" rx="6" ry="10" fill="#FFC0CB" filter="url(#sakuraGlow)">

          <animateTransform attributeName="transform" type="translate" values="0,0; 15,120; 30,240" dur="10s" repeatCount="indefinite"/>

          <animateTransform attributeName="transform" type="rotate" values="0; -360" dur="10s" repeatCount="indefinite" additive="sum"/>

        </ellipse>

      </g>

      <!-- Petal 3 -->

      <g transform="translate(60%, 15%)">

        <ellipse cx="0" cy="0" rx="7" ry="11" fill="#FFD1DC" filter="url(#sakuraGlow)">

          <animateTransform attributeName="transform" type="translate" values="0,0; 25,110; 50,220" dur="9s" repeatCount="indefinite"/>

          <animateTransform attributeName="transform" type="rotate" values="0; 360" dur="9s" repeatCount="indefinite" additive="sum"/>

        </ellipse>

      </g>

      <!-- Petal 4 -->

      <g transform="translate(80%, 25%)">

        <ellipse cx="0" cy="0" rx="8" ry="12" fill="#FFFFFF" filter="url(#sakuraGlow)">

          <animateTransform attributeName="transform" type="translate" values="0,0; 18,100; 35,200" dur="7s" repeatCount="indefinite"/>

          <animateTransform attributeName="transform" type="rotate" values="0; -360" dur="7s" repeatCount="indefinite" additive="sum"/>

        </ellipse>

      </g>

      <!-- Petal 5 -->

      <g transform="translate(45%, 5%)">

        <ellipse cx="0" cy="0" rx="6" ry="10" fill="#FFB6C1" filter="url(#sakuraGlow)">

          <animateTransform attributeName="transform" type="translate" values="0,0; 22,115; 45,230" dur="11s" repeatCount="indefinite"/>

          <animateTransform attributeName="transform" type="rotate" values="0; 360" dur="11s" repeatCount="indefinite" additive="sum"/>

        </ellipse>

      </g>

      <!-- Petal 6 -->

      <g transform="translate(70%, 8%)">

        <ellipse cx="0" cy="0" rx="7" ry="11" fill="#FFC0CB" filter="url(#sakuraGlow)">

          <animateTransform attributeName="transform" type="translate" values="0,0; 19,105; 38,210" dur="8.5s" repeatCount="indefinite"/>

          <animateTransform attributeName="transform" type="rotate" values="0; -360" dur="8.5s" repeatCount="indefinite" additive="sum"/>

        </ellipse>

      </g>

    </g>

    <!-- Main text with sakura style -->

    <text x="50%" y="50%" font-family="Arial, sans-serif" font-size="48" font-weight="bold" fill="#8B4789" text-anchor="middle" dominant-baseline="middle" opacity="0.9">

      Hi there 👋

    </text>

    <text x="50%" y="65%" font-family="Arial, sans-serif" font-size="24" fill="#C71585" text-anchor="middle" dominant-baseline="middle" opacity="0.85">

      Welcome to my GitHub Profile

    </text>

  </svg>

</div>

<!-- Modern Typing Animation -->

<div align="center">

  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=8B4789&center=true&vCenter=true&width=600&lines=I'm+TAnh+%F0%9F%91%8B;Computer+Science+Student+%F0%9F%93%9A;AI+%26+Web+Developer+%F0%9F%92%BB;Building+Amazing+Things+%F0%9F%9A%80" alt="Typing SVG" />

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

  

  <img src="https://komarev.com/ghpvc/?username=tanh1c&label=Profile%20Views&color=8B4789&style=for-the-badge" alt="Profile Views"/>

  

  <p>Made with ❤️ by TAnh</p>

  

</div>
