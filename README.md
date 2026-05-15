<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#000000"/>
      <stop offset="50%" stop-color="#0a0800"/>
      <stop offset="100%" stop-color="#000000"/>
    </linearGradient>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softglow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="18"/>
    </filter>
    <filter id="smallglow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <clipPath id="clip">
      <rect width="900" height="280"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="900" height="280" fill="url(#bg)"/>

  <!-- Ambient glow blob -->
  <ellipse cx="450" cy="140" rx="260" ry="100" fill="#f59e0b" opacity="0.04" filter="url(#softglow)">
    <animate attributeName="opacity" values="0.03;0.07;0.03" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="rx" values="260;300;260" dur="5s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Horizontal scan lines -->
  <rect width="900" height="1" y="60"  fill="#f59e0b" opacity="0.04"/>
  <rect width="900" height="1" y="120" fill="#f59e0b" opacity="0.04"/>
  <rect width="900" height="1" y="180" fill="#f59e0b" opacity="0.04"/>
  <rect width="900" height="1" y="240" fill="#f59e0b" opacity="0.04"/>

  <!-- Top border line with animation -->
  <line x1="0" y1="1" x2="900" y2="1" stroke="#f59e0b" stroke-width="1.5" opacity="0.5">
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3s" repeatCount="indefinite"/>
  </line>
  <line x1="0" y1="279" x2="900" y2="279" stroke="#f59e0b" stroke-width="1.5" opacity="0.5">
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3s" repeatCount="indefinite"/>
  </line>

  <!-- Corner brackets -->
  <polyline points="8,30 8,8 30,8"   fill="none" stroke="#f59e0b" stroke-width="2.5" opacity="0.9"/>
  <polyline points="870,8 892,8 892,30"  fill="none" stroke="#f59e0b" stroke-width="2.5" opacity="0.9"/>
  <polyline points="8,250 8,272 30,272"  fill="none" stroke="#f59e0b" stroke-width="2.5" opacity="0.9"/>
  <polyline points="870,272 892,272 892,250" fill="none" stroke="#f59e0b" stroke-width="2.5" opacity="0.9"/>

  <!-- Small decorative dots top row -->
  <circle cx="440" cy="32" r="1.5" fill="#f59e0b" opacity="0.5"/>
  <circle cx="450" cy="32" r="1.5" fill="#f59e0b" opacity="0.8"/>
  <circle cx="460" cy="32" r="1.5" fill="#f59e0b" opacity="0.5"/>

  <!-- MAIN NAME — with pulse glow -->
  <text x="450" y="138"
        text-anchor="middle"
        font-family="'Courier New', Courier, monospace"
        font-size="62"
        font-weight="bold"
        letter-spacing="6"
        fill="#f59e0b"
        filter="url(#glow)"
        clip-path="url(#clip)">
    AKHILESH KUMAR
    <animate attributeName="opacity" values="0.9;1;0.85;1;0.9" dur="4s" repeatCount="indefinite"/>
  </text>

  <!-- Subtitle -->
  <text x="450" y="178"
        text-anchor="middle"
        font-family="'Courier New', Courier, monospace"
        font-size="13"
        letter-spacing="5"
        fill="#78716c">
    FULLSTACK  ·  AI BUILDER  ·  PRODUCT THINKER
  </text>

  <!-- Animated dot wave at bottom -->
  <circle cx="360" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.0s" repeatCount="indefinite"/>
  </circle>
  <circle cx="380" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="400" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="420" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="440" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="460" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="1.0s" repeatCount="indefinite"/>
  </circle>
  <circle cx="480" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="520" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="540" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="560" cy="222" r="2.5" fill="#f59e0b" filter="url(#smallglow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.4s" begin="0.0s" repeatCount="indefinite"/>
  </circle>
</svg>

<div align="center">

![header](https://raw.githubusercontent.com/UserAkku/UserAkku/main/header.svg)

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&pause=1500&color=F59E0B&center=true&vCenter=true&width=600&lines=Next.js+%7C+TypeScript+%7C+MERN+%7C+Tailwind;LangChain+%7C+LangGraph+%7C+RAG+%7C+Agentic+AI;n8n+Automations+%7C+Python+%7C+Prisma;Tableau+%7C+Looker+Studio+%7C+Technical+SEO;building+things+no+one+asked+for+%F0%9F%94%A5)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-f59e0b?style=flat-square&logo=linkedin&logoColor=000)](https://www.linkedin.com/in/akhilesh-kumar-736794313/)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-f59e0b?style=flat-square&logo=github&logoColor=000)](https://github.com/UserAkku)&nbsp;
![Views](https://komarev.com/ghpvc/?username=UserAkku&style=flat-square&color=f59e0b&labelColor=000000&label=views)

<br/>

[![Holopin Badges](https://holopin.me/userakku)](https://holopin.io/@userakku)

</div>

<br/>

---

Not your average dev.

I write code, wire up AI agents, automate pipelines with n8n, read data in Tableau & Looker, think in systems, and still care about whether the button looks right on mobile. 6 months at **Nocage** taught me that the best engineers think like product people — you're not done when it compiles, you're done when it *works for a human*.

Right now I'm deep in **Web3**, building fast on new ideas, and figuring out how agentic AI actually breaks in production. Too many side projects. Not enough hours. Perfect.

---

### stack

<div align="center">

<img src="https://skillicons.dev/icons?i=nextjs,react,ts,js,nodejs,express&theme=dark&perline=6"/>
<img src="https://skillicons.dev/icons?i=mongodb,postgres,prisma,tailwind,python,git&theme=dark&perline=6"/>

`LangChain` &nbsp;·&nbsp; `LangGraph` &nbsp;·&nbsp; `RAG` &nbsp;·&nbsp; `Agentic AI` &nbsp;·&nbsp; `n8n` &nbsp;·&nbsp; `Tableau` &nbsp;·&nbsp; `Looker Studio` &nbsp;·&nbsp; `Technical SEO`

</div>

---

### work

**Nocage** *(formerly BridgeIn)* &nbsp;—&nbsp; Full Stack Developer Intern &nbsp;·&nbsp; `6 months`

Built production pages in **Next.js + TypeScript**. Owned **Technical SEO** end-to-end — architecture, Core Web Vitals, crawlability. Pushed UI/UX quality on live features. Then stepped outside the codebase: ran competitor analysis, mapped growth strategies, studied user behaviour. Learned that shipping code is the easy part.

---

### projects

> *pinned below — go look 👇*

<div align="center">
<table>
<tr>
<td align="center" width="50%">

**[Project Name ↗](https://github.com/UserAkku/repo-1)**
`Next.js` `TypeScript` `MongoDB`
<br/><sub>one line — what problem it solves</sub>

</td>
<td align="center" width="50%">

**[Project Name ↗](https://github.com/UserAkku/repo-2)**
`LangGraph` `RAG` `Python` `n8n`
<br/><sub>one line — what problem it solves</sub>

</td>
</tr>
<tr>
<td align="center" width="50%">

**[Project Name ↗](https://github.com/UserAkku/repo-3)**
`React` `Node.js` `PostgreSQL` `Prisma`
<br/><sub>one line — what problem it solves</sub>

</td>
<td align="center" width="50%">

**[Project Name ↗](https://github.com/UserAkku/repo-4)**
`Next.js` `LangChain` `MongoDB`
<br/><sub>one line — what problem it solves</sub>

</td>
</tr>
</table>
</div>

---

### activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=UserAkku&bg_color=000000&color=f59e0b&line=f59e0b&point=ffffff&area=true&hide_border=true&area_color=140d00&radius=6" width="96%"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api?username=UserAkku&show_icons=true&hide_border=true&bg_color=000000&title_color=f59e0b&text_color=78716c&icon_color=f59e0b&include_all_commits=true&count_private=true" height="150"/>
&nbsp;
<img src="https://streak-stats.demolab.com/?user=UserAkku&hide_border=true&background=000000&stroke=f59e0b&ring=f59e0b&fire=ef4444&currStreakLabel=f59e0b&sideLabels=78716c&dates=52525b" height="150"/>

</div>

---

<div align="center">
<br/>

```
"most people wait for the right moment.
 i just start building."
```

<br/>

![footer](https://capsule-render.vercel.app/api?type=shark&color=000000&height=60&section=footer&reversal=true)

</div>
