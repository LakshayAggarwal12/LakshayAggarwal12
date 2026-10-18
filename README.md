<div align="center">

<!-- 1. Animated header (twinkling starfield) -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=200&section=header&text=Lakshay%20Aggarwal&fontSize=45&fontColor=58a6ff&animation=twinkling&fontAlignY=35&desc=Software%20Developer%20|%20MERN%20Stack%20|%20Backend%20|%20Generative%20AI&descAlignY=55&descSize=18&descColor=8b949e" width="100%"/>

<!-- 2. Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Software+Developer+%7C+MERN+Stack;Backend+Engineering+%7C+Generative+AI;Building+in+public+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<!-- 3. Status badges -->
<img src="https://img.shields.io/badge/Open%20to-Internships-3fb950?style=for-the-badge" alt="Open to Internships"/>
<img src="https://img.shields.io/badge/Batch-2028-58a6ff?style=for-the-badge" alt="Batch 2028"/>
<img src="https://img.shields.io/badge/Based%20in-India-ff9933?style=for-the-badge" alt="Based in India"/>

<br/><br/>

<!-- 4. Animated terminal intro (self-hosted) -->
<img src="./profile/terminal.svg" width="85%" alt="Animated terminal intro"/>

</div>

<a id="about"></a>

<h2 align="center">▰▰▰ 👋 ABOUT ▰▰▰</h2>

I'm a third-year B.Tech CSE (Data Science) student who builds full-stack and AI-integrated products, from REST APIs and databases to deployment. I'm looking for **backend / full-stack / software engineering internships**.

- 🎯 **Career goal:** Software Engineer (Full-Stack)
- 💬 **Ask me about:** C++, DSA, MERN stack, Node.js, Express, MongoDB, PostgreSQL, REST APIs, Git, backend development
- 📄 **Resume:** [View resume](https://drive.google.com/drive/folders/1zLCd4_vI87wJ2ZP5tD5sI2nKt8ntizIu?usp=sharing)

<h2 align="center">▰▰▰ 🚀 FEATURED PROJECTS ▰▰▰</h2>

<!-- TODO: replace the Live / Code links below with exact URLs -->

| Project | What it does | Stack | Links |
|---|---|---|---|
| **HireSense** | AI-powered resume screening and candidate ranking with explainable ATS scoring (TF-IDF similarity plus an 88-skill spaCy taxonomy) | React, FastAPI, PostgreSQL, spaCy, scikit-learn | [Live](https://hiresense-sepia.vercel.app) · [Code](https://github.com/LakshayAggarwal12?tab=repositories) |
| **TaskFlow** | AI-enhanced project management platform: Kanban boards, sprints, role-based access, analytics, and 4 AI-assisted workflows | MERN, JWT, Groq Llama 3.3, Tailwind | [Live](https://github.com/LakshayAggarwal12?tab=repositories) · [Code](https://github.com/LakshayAggarwal12?tab=repositories) |
| **Nano-Nanny** | Team-built post-discharge healthcare platform with symptom logging and AI-generated health insights | MERN, Gemini API | [Live](https://github.com/LakshayAggarwal12?tab=repositories) · [Code](https://github.com/LakshayAggarwal12?tab=repositories) |

<h3 align="center">🧩 Architecture</h3>

<details>
<summary><b>HireSense</b> architecture</summary>

```mermaid
flowchart LR
    A["React + Vite"] -->|REST| B["FastAPI"]
    B --> C["Parsers<br/>pdfplumber / python-docx"]
    B --> D["NLP<br/>spaCy skills + TF-IDF + ATS checks"]
    B --> E[("PostgreSQL")]
    C --> D
    D --> E
```

</details>

<details>
<summary><b>TaskFlow</b> architecture</summary>

```mermaid
flowchart LR
    subgraph Vercel
        A["React + Tailwind<br/>Kanban · Sprints · Analytics"]
    end
    subgraph Render
        B["Express API<br/>JWT auth + role-based access"]
    end
    A -->|REST + JWT| B
    B --> C[("MongoDB<br/>aggregation pipelines")]
    B --> D["Groq Llama 3.3<br/>task drafting · label suggestions<br/>natural language search · sprint summaries"]
    D -.->|AI output returned for user review| A
```

</details>

<h2 align="center">▰▰▰ 🛠️ TECH STACK ▰▰▰</h2>

<p align="center"><b>💻 Core Stack</b></p>
<p align="center">
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" height="32"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" height="32"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" height="32"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" height="32"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" height="32"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" height="32"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" height="32"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" height="32"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" height="32"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" height="32"/>
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" height="32"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" height="32"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" height="32"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" height="32"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" height="32"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" height="32"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" height="32"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" height="32"/>
<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" alt="Socket.io" height="32"/>
</p>

<p align="center"><b>🧠 AI/Data</b></p>
<p align="center">
<img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white" alt="spaCy" height="32"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" height="32"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq" height="32"/>
</p>

<p align="center"><b>🧰 Tools & Deploy</b></p>
<p align="center">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" height="32"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" height="32"/>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" height="32"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" height="32"/>
<img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm" height="32"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" height="32"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" alt="Render" height="32"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" height="32"/>
</p>

<h2 align="center">▰▰▰ 🏆 HIGHLIGHTS ▰▰▰</h2>

<table align="center">
  <tr>
    <td align="center" width="33%">
      <h3>🥇</h3>
      <b>Semi-Finalist</b><br/>
      Economic Times<br/>AI Hackathon 2026
    </td>
    <td align="center" width="33%">
      <h3>💼</h3>
      <b>AI Intern</b><br/>
      IBM Virtual Internship<br/>Built and deployed HireSense
    </td>
    <td align="center" width="33%">
      <h3>🧩</h3>
      <b>250+ DSA Problems</b><br/>
      LeetCode and<br/>GeeksforGeeks
    </td>
  </tr>
</table>

<h2 align="center">▰▰▰ 🎯 CURRENT FOCUS ▰▰▰</h2>

<p align="center">
<img src="https://img.shields.io/badge/Backend_Engineering-58a6ff?style=for-the-badge" alt="Backend Engineering"/>
<img src="https://img.shields.io/badge/SQL_%26_DBMS-4169E1?style=for-the-badge" alt="SQL and DBMS"/>
<img src="https://img.shields.io/badge/System_Design-8b949e?style=for-the-badge" alt="System Design"/>
<img src="https://img.shields.io/badge/Docker_%26_Kubernetes-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker and Kubernetes"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
</p>

<h2 align="center">▰▰▰ 📊 STATS DASHBOARD ▰▰▰</h2>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/Lakshay_Aggarwal12?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode stats" width="90%"/>
</p>

<details>
<summary>📊 GitHub stats</summary>

<p align="center">
  <img src="./profile/stats.svg" height="180" alt="GitHub Stats"/>
  <img src="./profile/top-langs.svg" height="180" alt="Top Languages"/>
</p>

</details>

<!-- 3D graph is generated by .github/workflows/3d-contrib.yml. Run that workflow once before this image appears. -->
<p align="center">
  <img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution graph" width="100%"/>
</p>

<h2 align="center">▰▰▰ 🔗 CONNECT ▰▰▰</h2>

<p align="center">
  <a href="https://www.linkedin.com/in/lakshay-aggarwal-dev" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://leetcode.com/u/Lakshay_Aggarwal12/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
  <a href="mailto:lakshaydev1205@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://drive.google.com/drive/folders/1zLCd4_vI87wJ2ZP5tD5sI2nKt8ntizIu?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"/>
  </a>
  <img src="https://img.shields.io/badge/Discord-lakshay__1205-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord: lakshay_1205"/>
</p>

<p align="center">
  <sub>⭐️ Thanks for stopping by. Feel free to explore my pinned repos or drop a message via any link above.</sub>
  <br/>
  <a href="#about"><sub>↑ Back to top</sub></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=120&section=footer&text=Thanks%20for%20visiting!%20%F0%9F%9A%80&fontSize=20&fontColor=58a6ff&animation=fadeIn" width="100%"/>