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

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,100:161b22&height=70&section=header&text=About&fontSize=26&fontColor=58a6ff&fontAlignY=55" width="100%" alt="About"/>

I'm a third-year B.Tech CSE (Data Science) student who builds full-stack and AI-integrated products, from REST APIs and databases to deployment. I'm looking for **backend / full-stack / software engineering internships**.

- 🎯 **Career goal:** Software Engineer (Full-Stack)
- 💬 **Ask me about:** C++, DSA, MERN stack, Node.js, Express, MongoDB, PostgreSQL, REST APIs, Git, backend development
- 📄 **Resume:** [View resume](https://drive.google.com/drive/folders/1zLCd4_vI87wJ2ZP5tD5sI2nKt8ntizIu?usp=sharing)

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,100:161b22&height=70&section=header&text=Featured%20Projects&fontSize=26&fontColor=58a6ff&fontAlignY=55" width="100%" alt="Featured Projects"/>

<!-- TODO: replace the Live / Code links below with exact URLs -->

| Project | What it does | Stack | Links |
|---|---|---|---|
| **HireSense** | AI-powered resume screening and candidate ranking with explainable ATS scoring (TF-IDF similarity plus an 88-skill spaCy taxonomy) | React, FastAPI, PostgreSQL, spaCy, scikit-learn | [Live](https://hiresense-sepia.vercel.app) · [Code](https://github.com/LakshayAggarwal12?tab=repositories) |
| **TaskFlow** | AI-enhanced project management platform: Kanban boards, sprints, role-based access, analytics, and 4 AI-assisted workflows | MERN, JWT, Groq Llama 3.3, Tailwind | [Live](https://github.com/LakshayAggarwal12?tab=repositories) · [Code](https://github.com/LakshayAggarwal12?tab=repositories) |
| **Nano-Nanny** | Team-built post-discharge healthcare platform with symptom logging and AI-generated health insights | MERN, Gemini API | [Live](https://github.com/LakshayAggarwal12?tab=repositories) · [Code](https://github.com/LakshayAggarwal12?tab=repositories) |

### 🧩 Architecture

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

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,100:161b22&height=70&section=header&text=Tech%20Stack&fontSize=26&fontColor=58a6ff&fontAlignY=55" width="100%" alt="Tech Stack"/>

<p align="center"><b>💻 Core</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,py,js,html,css,react,tailwind,vite,nodejs,express,fastapi,mongodb,postgres&perline=13" alt="Core stack"/>
</p>

<p align="center"><b>🧠 AI / Data</b></p>
<p align="center">
<img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white" alt="spaCy" height="28"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" height="28"/>
<img src="https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini API" height="28"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge" alt="Groq" height="28"/>
</p>

<p align="center"><b>🧰 Tools & Deploy</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,docker,postman,vscode,vercel&perline=6" alt="Tools"/>
</p>

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,100:161b22&height=70&section=header&text=Highlights&fontSize=26&fontColor=58a6ff&fontAlignY=55" width="100%" alt="Highlights"/>

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

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,100:161b22&height=70&section=header&text=Current%20Focus&fontSize=26&fontColor=58a6ff&fontAlignY=55" width="100%" alt="Current Focus"/>

<p align="center">
<img src="https://img.shields.io/badge/Backend_Engineering-58a6ff?style=for-the-badge" alt="Backend Engineering"/>
<img src="https://img.shields.io/badge/SQL_%26_DBMS-4169E1?style=for-the-badge" alt="SQL and DBMS"/>
<img src="https://img.shields.io/badge/System_Design-8b949e?style=for-the-badge" alt="System Design"/>
<img src="https://img.shields.io/badge/Docker_%26_Kubernetes-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker and Kubernetes"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
</p>

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,100:161b22&height=70&section=header&text=Stats%20Dashboard&fontSize=26&fontColor=58a6ff&fontAlignY=55" width="100%" alt="Stats Dashboard"/>

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

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,100:161b22&height=70&section=header&text=Connect&fontSize=26&fontColor=58a6ff&fontAlignY=55" width="100%" alt="Connect"/>

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