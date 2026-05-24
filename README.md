<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Sri Harshit Golla | AI & ML Engineer</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{
  background-color:#0d1117;
  color:#e6edf3;
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans",Helvetica,Arial,sans-serif;
  font-size:16px;line-height:1.5;
}
.container{max-width:1012px;margin:0 auto;}
.content{padding:0 24px 48px;}
img{max-width:100%;display:inline-block;vertical-align:middle;}
.full-img{display:block;width:100%;}
h2{
  font-size:1.5em;font-weight:600;color:#e6edf3;
  border-bottom:1px solid #21262d;padding-bottom:0.3em;
  margin:32px 0 16px;display:flex;align-items:center;gap:8px;
}
h4{font-size:1em;font-weight:600;color:#e6edf3;margin:16px 0 8px;}
p{margin-bottom:16px;}
blockquote{padding:0 1em;color:#7d8590;border-left:0.25em solid #30363d;margin:0 0 16px;}
blockquote strong{color:#c9d1d9;}
ul{padding-left:1.5em;margin-bottom:16px;}
li{margin:4px 0;}
hr{border:none;border-top:1px solid #21262d;margin:24px 0;}
a{color:#58a6ff;text-decoration:none;}
a:hover{text-decoration:underline;}
strong{font-weight:600;color:#e6edf3;}

/* TABLES */
table{width:100%;border-collapse:collapse;margin:16px 0;font-size:0.95em;}
th{background:#161b22;padding:8px 13px;font-weight:600;text-align:left;border:1px solid #21262d;color:#e6edf3;}
td{padding:6px 13px;border:1px solid #21262d;vertical-align:top;}
tr:nth-child(even) td{background:#161b22;}

/* BADGE ROWS */
.badge-row{display:flex;flex-wrap:wrap;gap:6px;margin:12px 0;align-items:center;}
.badge-row img{height:28px;}
.center-row{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin:12px 0;align-items:center;}

/* STATS ROW */
.stats-2col{display:flex;gap:16px;margin:16px 0;flex-wrap:wrap;}
.stats-2col img{flex:1;min-width:240px;height:auto;}

/* SKILL TABLE */
.skill-pbar{display:inline-block;width:160px;height:10px;background:#21262d;border-radius:5px;vertical-align:middle;overflow:hidden;margin-right:6px;}
.skill-pfill{height:100%;background:linear-gradient(90deg,#1d6fa4,#38bdf8);border-radius:5px;display:block;}
.pct-txt{font-size:0.82em;color:#7d8590;}

/* RESUME BTN */
.resume-section{text-align:center;margin:20px 0;}
.dl-btn{
  display:inline-flex;align-items:center;gap:8px;
  background:linear-gradient(135deg,#1a56db,#0891b2);
  color:#fff !important;padding:12px 28px;border-radius:8px;
  font-weight:700;font-size:1em;text-decoration:none !important;
  transition:opacity 0.2s;box-shadow:0 4px 15px rgba(14,165,233,0.3);
}
.dl-btn:hover{opacity:0.85;}

/* CERT */
.cert-list{list-style:none;padding:0;}
.cert-list li{padding:8px 12px;margin:6px 0;background:#161b22;border:1px solid #21262d;border-left:3px solid #1d6fa4;border-radius:6px;display:flex;align-items:center;gap:8px;font-size:0.95em;}

.note{color:#7d8590;font-size:0.85em;font-style:italic;margin-top:8px;}

/* ══════════════════════════════
   HERO SECTION - FULLY ANIMATED
══════════════════════════════ */
.hero-wrap{
  position:relative;width:100%;overflow:hidden;
  min-height:220px;
}
#hero-canvas{
  position:absolute;inset:0;width:100%;height:100%;
  display:block;
}
.hero-svg{position:relative;z-index:1;display:block;width:100%;}

/* TYPING ANIMATION */
.typing-section{
  background:#0d1117;
  text-align:center;
  padding:20px 16px 10px;
  position:relative;
  overflow:hidden;
}
.typing-section::before{
  content:'';position:absolute;
  top:0;left:50%;transform:translateX(-50%);
  width:60%;height:1px;
  background:linear-gradient(90deg,transparent,#38bdf8,transparent);
}
.typing-line{
  font-family:"SFMono-Regular",Consolas,"Liberation Mono",Menlo,monospace;
  font-size:1.15em;
  font-weight:700;
  color:#38bdf8;
  letter-spacing:0.5px;
  min-height:1.6em;
  text-shadow:0 0 20px rgba(56,189,248,0.5);
}
.cursor{
  display:inline-block;
  width:2px;height:1.1em;
  background:#38bdf8;
  vertical-align:text-bottom;
  margin-left:3px;
  animation:blink 1s step-end infinite;
  box-shadow:0 0 8px #38bdf8;
}
@keyframes blink{50%{opacity:0}}

/* CSS BADGES */
.css-badge{
  display:inline-flex;align-items:center;
  border-radius:4px;overflow:hidden;
  font-family:"SFMono-Regular",Consolas,monospace;
  font-size:0.78em;font-weight:700;
  height:28px;letter-spacing:0.5px;
  box-shadow:0 2px 8px rgba(0,0,0,0.4);
  cursor:default;
  transition:transform 0.2s,box-shadow 0.2s;
  text-decoration:none !important;
}
.css-badge:hover{transform:translateY(-1px);box-shadow:0 4px 14px rgba(0,0,0,0.5);}
.css-badge .b-label{padding:0 10px;background:#555;color:#fff;height:100%;display:flex;align-items:center;white-space:nowrap;}
.css-badge .b-val{padding:0 10px;color:#fff;height:100%;display:flex;align-items:center;white-space:nowrap;}
.b-views .b-label{background:#555}
.b-views .b-val{background:#0EA5E9}
.b-followers .b-label{background:#555}
.b-followers .b-val{background:#0369A1}
.b-linkedin .b-label{background:#0A66C2}.b-linkedin .b-val{background:#0A66C2}
.b-gmail .b-label{background:#D14836}.b-gmail .b-val{background:#D14836}
.b-leetcode .b-label{background:#B45309}.b-leetcode .b-val{background:#FFA116;color:#000}
.b-github .b-label{background:#24292e}.b-github .b-val{background:#1a1e24}
.b-whatsapp .b-label{background:#128C7E}.b-whatsapp .b-val{background:#25D366}

/* TECH STACK BADGES */
.tech-badge{
  display:inline-flex;align-items:center;gap:6px;
  padding:5px 12px;border-radius:4px;
  font-size:0.8em;font-weight:700;
  color:#fff;letter-spacing:0.3px;
  box-shadow:0 2px 6px rgba(0,0,0,0.3);
  transition:transform 0.15s,filter 0.15s;
  margin:3px;cursor:default;
}
.tech-badge:hover{transform:translateY(-2px);filter:brightness(1.15);}
.tb-python{background:#3776AB}
.tb-cpp{background:#00599C}
.tb-sql{background:#4479A1}
.tb-ml{background:#F7931E}
.tb-nlp{background:#1d6fa4}
.tb-genai{background:#7C3AED}
.tb-llm{background:#FF6F00}
.tb-rag{background:#0891B2}
.tb-langchain{background:#1C3C3C}
.tb-fastapi{background:#009688}
.tb-hf{background:#FFD21E;color:#111}
.tb-faiss{background:#0047AB}
.tb-ollama{background:#1a1a2e}
.tb-streamlit{background:#FF4B4B}
.tb-mcp{background:#0EA5E9}
.tb-prompt{background:#6D28D9}
.tb-pandas{background:#130654}
.tb-numpy{background:#013243}
.tb-powerbi{background:#F2C811;color:#111}
.tb-mongodb{background:#4EA94B}
.tb-mysql{background:#4479A1}
.tb-git{background:#F05033}
.tb-github{background:#24292e}
.tb-linux{background:#333;border:1px solid #FCC624}
.tb-gemini{background:#4285F4}
.tb-dsa{background:#7C3AED}
.tb-oop{background:#0369A1}

/* ACHIEVEMENT BADGES */
.ach-badge{
  display:inline-flex;align-items:center;gap:6px;
  background:#161b22;border:1px solid #30363d;
  padding:6px 14px;border-radius:20px;
  font-size:0.82em;color:#c9d1d9;
  transition:border-color 0.2s,color 0.2s;
  margin:3px;
}
.ach-badge:hover{border-color:#38bdf8;color:#38bdf8;}

/* LEETCODE STATS */
.lc-card{
  display:flex;gap:24px;align-items:center;
  background:#161b22;border:1px solid #21262d;
  border-radius:10px;padding:20px;flex-wrap:wrap;
}
.lc-ring{
  width:120px;height:120px;flex-shrink:0;
  border-radius:50%;
  border:4px solid #38bdf8;
  display:flex;flex-direction:column;
  align-items:center;justify-content:center;
  box-shadow:0 0 24px rgba(56,189,248,0.25);
  background:radial-gradient(circle,#0d1528,#0d1117);
}
.lc-ring .lc-num{font-size:2em;font-weight:900;color:#38bdf8;font-family:monospace;}
.lc-ring .lc-lbl{font-size:0.65em;color:#7d8590;letter-spacing:1px;text-transform:uppercase;}
.lc-rows{flex:1;}
.lc-row{display:flex;justify-content:space-between;align-items:center;padding:5px 0;border-bottom:1px solid #21262d;}
.lc-row:last-child{border:none;}
.lc-diff{font-size:0.88em;font-family:monospace;}
.easy-c{color:#4ade80}.med-c{color:#f59e0b}.hard-c{color:#f87171}
.lc-bar{height:7px;background:#21262d;border-radius:4px;margin-top:3px;overflow:hidden;}
.lc-fill{height:100%;border-radius:4px;}

/* CONTRIB GRID */
.cgrid{display:grid;grid-template-columns:repeat(52,1fr);gap:2px;margin:12px 0;}
.cgrid div{aspect-ratio:1;border-radius:2px;}

/* QUOTE */
.quote-card{background:#161b22;border:1px solid #21262d;border-radius:8px;padding:20px 24px;text-align:center;position:relative;overflow:hidden;}
.quote-card::before{content:'"';position:absolute;top:-10px;left:12px;font-size:7rem;color:rgba(56,189,248,0.06);font-family:Georgia,serif;line-height:1;}
.quote-txt{font-style:italic;color:#c9d1d9;font-size:1em;position:relative;z-index:1;}
.quote-auth{font-family:monospace;font-size:0.82em;color:#38bdf8;margin-top:8px;}

/* EDU */
.edu-table td:last-child{color:#38bdf8;font-weight:600;text-align:right;}

@media(max-width:600px){
  .stats-2col{flex-direction:column;}
  .skill-pbar{width:90px;}
  .cgrid{grid-template-columns:repeat(26,1fr);}
  .lc-card{flex-direction:column;}
}
</style>
</head>
<body>
<div class="container">

<!-- ══════════════════════════════════════
     HERO — ANIMATED WAVE BANNER + PARTICLES
══════════════════════════════════════ -->
<div class="hero-wrap">
  <canvas id="hero-canvas"></canvas>
  <svg class="hero-svg" xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 1350 210" preserveAspectRatio="xMidYMid slice">
    <defs>
      <linearGradient id="hg" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#002D72"><animate attributeName="stop-color" values="#002D72;#0047AB;#002D72" dur="6s" repeatCount="indefinite"/></stop>
        <stop offset="45%" stop-color="#1a7fd4"><animate attributeName="stop-color" values="#1a7fd4;#2563eb;#1a7fd4" dur="5s" repeatCount="indefinite"/></stop>
        <stop offset="100%" stop-color="#00B4D8"><animate attributeName="stop-color" values="#00B4D8;#06b6d4;#00B4D8" dur="7s" repeatCount="indefinite"/></stop>
      </linearGradient>
      <filter id="glow"><feGaussianBlur stdDeviation="3" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    </defs>
    <!-- BG rect -->
    <rect width="1350" height="210" fill="url(#hg)"/>
    <!-- Subtle grid lines -->
    <g stroke="rgba(255,255,255,0.04)" stroke-width="1">
      <line x1="0" y1="30" x2="1350" y2="30"/>
      <line x1="0" y1="60" x2="1350" y2="60"/>
      <line x1="0" y1="90" x2="1350" y2="90"/>
      <line x1="0" y1="120" x2="1350" y2="120"/>
      <line x1="270" y1="0" x2="270" y2="170"/>
      <line x1="540" y1="0" x2="540" y2="170"/>
      <line x1="810" y1="0" x2="810" y2="170"/>
      <line x1="1080" y1="0" x2="1080" y2="170"/>
    </g>
    <!-- Glow circles -->
    <ellipse cx="200" cy="85" rx="130" ry="60" fill="rgba(255,255,255,0.05)"/>
    <ellipse cx="1150" cy="85" rx="130" ry="60" fill="rgba(0,180,216,0.1)"/>
    <!-- NAME -->
    <text x="675" y="92" text-anchor="middle"
      font-family="Arial Black,Impact,sans-serif" font-size="68" font-weight="900"
      fill="white" filter="url(#glow)" style="letter-spacing:-1px;">
      Sri Harshit Golla
    </text>
    <!-- subtitle -->
    <text x="675" y="132" text-anchor="middle"
      font-family="Arial,sans-serif" font-size="19" fill="rgba(255,255,255,0.88)">
      AI &amp; ML Engineer  |  Generative AI  |  RAG Developer
    </text>
    <!-- WAVE bottom -->
    <path fill="#0d1117"
      d="M0,165 C120,145 280,195 450,170 C620,145 780,185 960,162 C1100,145 1230,178 1350,160 L1350,210 L0,210 Z"/>
    <!-- second wave for depth -->
    <path fill="rgba(13,17,23,0.5)"
      d="M0,178 C150,162 310,192 500,176 C690,160 860,188 1050,172 C1180,160 1290,180 1350,170 L1350,210 L0,210 Z"/>
  </svg>
</div>

<!-- TYPING SECTION -->
<div class="typing-section">
  <div class="typing-line"><span id="typed"></span><span class="cursor"></span></div>
</div>

<!-- PROFILE VIEWS + FOLLOWERS -->
<div class="center-row" style="padding:12px 0 4px;">
  <a href="https://github.com/g-sri-harshit" class="css-badge b-views">
    <span class="b-label">👁 PROFILE VIEWS</span>
    <span class="b-val" id="pv-count">—</span>
  </a>
  <a href="https://github.com/g-sri-harshit" class="css-badge b-followers">
    <span class="b-label">FOLLOWERS</span>
    <span class="b-val" id="fl-count">—</span>
  </a>
</div>

<!-- ══════════ CONTENT ══════════ -->
<div class="content">
<hr/>

<!-- ABOUT ME -->
<h2>💡 About Me</h2>
<blockquote>
  <p>👋 Hi! I'm <strong>Sri Harshit Golla</strong> — a passionate <strong>AI &amp; ML Engineer</strong> who loves building intelligent systems that solve real-world problems.</p>
</blockquote>
<ul>
  <li>🎓 <strong>B.E. CSE (AI &amp; ML)</strong> | <strong>Chandigarh University, Punjab</strong> | CGPA: 7.56/10</li>
  <li>💻 <strong>Role:</strong> AI/ML Engineer + Generative AI Developer + RAG Specialist</li>
  <li>🌍 <strong>Domain:</strong> Machine Learning | NLP | Generative AI | LLMs | RAG Systems</li>
  <li>🧠 <strong>Languages:</strong> Python, C++, SQL</li>
  <li>🔥 <strong>Interests:</strong> LLMs, RAG Pipelines, Multi-Agent AI, MCP, Prompt Engineering</li>
  <li>🚀 <strong>Currently:</strong> Building production-grade AI pipelines &amp; exploring LLM fine-tuning</li>
  <li>🤝 <strong>Open to:</strong> Collaborations on AI research &amp; intelligent application projects!</li>
  <li>⚡ <strong>Fun fact:</strong> I make machines read, think, and reason for a living 🤖</li>
</ul>

<table>
  <tr>
    <th>🔭 What I'm Building</th>
    <th>🎯 Quick Facts</th>
  </tr>
  <tr>
    <td>
      🤖 <strong>RAG-based AI Chatbots</strong> with FAISS + Ollama<br/>
      🧠 <strong>Multi-Agent AI Systems</strong> using MCP + Gemini<br/>
      📰 <strong>NLP Classifiers</strong> for fake news detection<br/>
      📈 <strong>Exploring</strong> LLM fine-tuning &amp; agentic workflows<br/>
      🔧 <strong>Solving</strong> DSA problems on LeetCode daily
    </td>
    <td>
      🎓 <strong>Domain:</strong> AI, ML &amp; Computer Science<br/>
      💬 <strong>Ask me about:</strong> Python, RAG, LangChain, LLMs<br/>
      🤝 <strong>Open to:</strong> AI/ML research collabs<br/>
      🏆 <strong>Achievement:</strong> Top 900+ IQigai.ai Fellowship<br/>
      ⚡ <strong>Vibe:</strong> Where logic meets intelligence 🧠
    </td>
  </tr>
</table>

<hr/>

<!-- CONNECT -->
<h2>🌐 Let's Connect!</h2>
<div class="badge-row">
  <a href="https://www.linkedin.com/in/sri-harshit-golla-58a610250/" target="_blank" class="css-badge b-linkedin">
    <span class="b-label">💼 LinkedIn</span><span class="b-val">sri-harshit-golla</span>
  </a>
  <a href="mailto:sriharshitgolla@gmail.com" class="css-badge b-gmail">
    <span class="b-label">📧 Gmail</span><span class="b-val">sriharshitgolla</span>
  </a>
  <a href="https://leetcode.com/u/SRI_HARSHIT_07/" target="_blank" class="css-badge b-leetcode">
    <span class="b-label">⚔ LeetCode</span><span class="b-val">SRI_HARSHIT_07</span>
  </a>
  <a href="https://github.com/g-sri-harshit" target="_blank" class="css-badge b-github">
    <span class="b-label">🐙 GitHub</span><span class="b-val">g-sri-harshit</span>
  </a>
  <a href="https://wa.me/919494187989" target="_blank" class="css-badge b-whatsapp">
    <span class="b-label">📱 WhatsApp</span><span class="b-val">+91 9494187989</span>
  </a>
</div>

<hr/>

<!-- TECH ARSENAL -->
<h2>🛠️ Tech Arsenal</h2>

<h4>💻 Languages</h4>
<div>
  <span class="tech-badge tb-python">🐍 Python</span>
  <span class="tech-badge tb-cpp">⚙ C++</span>
  <span class="tech-badge tb-sql">🗄 SQL</span>
  <span class="tech-badge tb-dsa">🧩 DSA</span>
  <span class="tech-badge tb-oop">🔷 OOP</span>
</div>

<h4>🤖 AI / ML / Generative AI</h4>
<div>
  <span class="tech-badge tb-ml">🤖 Machine Learning</span>
  <span class="tech-badge tb-nlp">💬 NLP</span>
  <span class="tech-badge tb-genai">✨ Generative AI</span>
  <span class="tech-badge tb-llm">🧠 LLMs</span>
  <span class="tech-badge tb-rag">🔍 RAG</span>
</div>

<h4>🔧 Frameworks &amp; Tools</h4>
<div>
  <span class="tech-badge tb-langchain">🔗 LangChain</span>
  <span class="tech-badge tb-fastapi">⚡ FastAPI</span>
  <span class="tech-badge tb-hf">🤗 HuggingFace</span>
  <span class="tech-badge tb-faiss">🔎 FAISS</span>
  <span class="tech-badge tb-ollama">🦙 Ollama</span>
  <span class="tech-badge tb-streamlit">📊 Streamlit</span>
  <span class="tech-badge tb-mcp">🕸 MCP</span>
  <span class="tech-badge tb-prompt">✍ Prompt Eng.</span>
</div>

<h4>📊 Data &amp; Visualization</h4>
<div>
  <span class="tech-badge tb-pandas">🐼 Pandas</span>
  <span class="tech-badge tb-numpy">🔢 NumPy</span>
  <span class="tech-badge tb-powerbi">📈 Power BI</span>
</div>

<h4>🗄️ Databases</h4>
<div>
  <span class="tech-badge tb-mongodb">🍃 MongoDB</span>
  <span class="tech-badge tb-mysql">🐬 MySQL</span>
</div>

<h4>☁️ Developer Tools</h4>
<div>
  <span class="tech-badge tb-git">🔀 Git</span>
  <span class="tech-badge tb-github">🐙 GitHub</span>
  <span class="tech-badge tb-linux">🐧 Linux</span>
  <span class="tech-badge tb-gemini">💎 Google Gemini</span>
</div>

<hr/>

<!-- GITHUB ANALYTICS -->
<h2>📊 GitHub Analytics</h2>
<div class="stats-2col">
  <img src="https://github-readme-stats.vercel.app/api?username=g-sri-harshit&theme=tokyonight&hide_border=true&include_all_commits=false&count_private=false" alt="GitHub Stats" onerror="this.style.display='none'"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=g-sri-harshit&theme=tokyonight&hide_border=true" alt="Streak Stats" onerror="this.style.display='none'"/>
</div>

<table>
  <tr><th>📁 Metric</th><th>🔢 Details</th></tr>
  <tr><td>👤 Username</td><td><a href="https://github.com/g-sri-harshit">g-sri-harshit</a></td></tr>
  <tr><td>💻 Primary Stack</td><td>Python · LangChain · LLMs · RAG</td></tr>
  <tr><td>🧠 Domain</td><td>Generative AI · ML · NLP · Multi-Agent</td></tr>
  <tr><td>🏫 University</td><td>Chandigarh University, Punjab</td></tr>
  <tr><td>📍 Location</td><td>Gudivada, Andhra Pradesh, India</td></tr>
  <tr><td>⭐ Focus</td><td>Building intelligent AI systems every day</td></tr>
</table>

<hr/>

<!-- ACHIEVEMENTS -->
<h2>🏆 Achievements</h2>
<div>
  <span class="ach-badge">🥇 IQigai.ai Fellowship — 86.5% Score</span>
  <span class="ach-badge">🏅 Top 900+ Participants</span>
  <span class="ach-badge">⚔ LeetCode — Active Solver</span>
  <span class="ach-badge">🎖 IBM AI Analyst Certified</span>
  <span class="ach-badge">🤖 Multi-Agent AI Builder</span>
  <span class="ach-badge">📰 92% NLP Accuracy Achieved</span>
  <span class="ach-badge">🏗 AI Hackathon Participant</span>
  <span class="ach-badge">❤ Open Source Contributor</span>
</div>

<hr/>

<!-- LEETCODE STATS -->
<h2>⚔️ LeetCode Stats</h2>
<div class="lc-card">
  <div class="lc-ring">
    <div class="lc-num" id="lc-total">0</div>
    <div class="lc-lbl">Solved</div>
  </div>
  <div class="lc-rows">
    <div class="lc-row">
      <span class="lc-diff easy-c">Easy</span>
      <span class="easy-c" id="e-txt">Loading...</span>
    </div>
    <div class="lc-bar"><div class="lc-fill" id="e-bar" style="background:#4ade80;width:0%"></div></div>
    <div class="lc-row" style="margin-top:6px">
      <span class="lc-diff med-c">Medium</span>
      <span class="med-c" id="m-txt">Loading...</span>
    </div>
    <div class="lc-bar"><div class="lc-fill" id="m-bar" style="background:#f59e0b;width:0%"></div></div>
    <div class="lc-row" style="margin-top:6px">
      <span class="lc-diff hard-c">Hard</span>
      <span class="hard-c" id="h-txt">Loading...</span>
    </div>
    <div class="lc-bar"><div class="lc-fill" id="h-bar" style="background:#f87171;width:0%"></div></div>
    <p class="note" style="margin-top:8px">📌 LeetCode: <a href="https://leetcode.com/u/SRI_HARSHIT_07/" target="_blank">SRI_HARSHIT_07</a></p>
  </div>
</div>

<hr/>

<!-- CONTRIBUTION GRAPH -->
<h2>📈 Contribution Graph</h2>
<img class="full-img" src="https://github-readme-activity-graph.vercel.app/graph?username=g-sri-harshit&theme=tokyo-night&hide_border=true&area=true&color=38BDF8&line=0EA5E9&point=C084FC&area_color=201232&custom_title=Sri+Harshit%27s+Contribution+Graph" alt="Contribution Graph" onerror="this.outerHTML='<div style=\'background:#161b22;border:1px solid #21262d;border-radius:8px;padding:20px;text-align:center;color:#7d8590;\'>📈 Contribution graph loads with internet connection</div>'"/>
<!-- Offline fallback grid -->
<div id="cgrid-wrap">
  <div class="cgrid" id="cgrid"></div>
</div>

<hr/>

<!-- SNAKE -->
<h2>🐍 Contribution Snake</h2>
<div style="background:#161b22;border:1px solid #21262d;border-radius:8px;padding:12px;overflow:hidden;">
  <canvas id="snk" width="960" height="64" style="width:100%;height:64px;display:block;"></canvas>
</div>

<hr/>

<!-- QUOTE -->
<h2>✍️ Dev Quote of the Day</h2>
<div class="quote-card">
  <div class="quote-txt" id="quote-txt">Loading wisdom...</div>
  <div class="quote-auth" id="quote-auth"></div>
</div>

<hr/>

<!-- SKILL PROFICIENCY -->
<h2>🎯 Skill Proficiency</h2>
<table>
  <tr><th>Domain</th><th>Skills</th><th>Level</th></tr>
  <tr><td>🐍 Python</td><td>Python, OOP, DSA, Scripting</td>
    <td><span class="skill-pbar"><span class="skill-pfill" style="width:88%"></span></span><span class="pct-txt">88%</span></td></tr>
  <tr><td>🤖 AI / LLMs / RAG</td><td>LangChain, FAISS, Ollama, Prompt Eng.</td>
    <td><span class="skill-pbar"><span class="skill-pfill" style="width:85%"></span></span><span class="pct-txt">85%</span></td></tr>
  <tr><td>💬 NLP / GenAI</td><td>HuggingFace, Gemini, Text Classification</td>
    <td><span class="skill-pbar"><span class="skill-pfill" style="width:80%"></span></span><span class="pct-txt">80%</span></td></tr>
  <tr><td>🧠 Machine Learning</td><td>Scikit-learn, Pandas, NumPy</td>
    <td><span class="skill-pbar"><span class="skill-pfill" style="width:78%"></span></span><span class="pct-txt">78%</span></td></tr>
  <tr><td>⚙ Backend / APIs</td><td>FastAPI, Streamlit, REST</td>
    <td><span class="skill-pbar"><span class="skill-pfill" style="width:72%"></span></span><span class="pct-txt">72%</span></td></tr>
  <tr><td>🗄 Databases</td><td>MongoDB, MySQL, SQL</td>
    <td><span class="skill-pbar"><span class="skill-pfill" style="width:70%"></span></span><span class="pct-txt">70%</span></td></tr>
  <tr><td>🐧 Dev Tools</td><td>Git, GitHub, Linux, Power BI</td>
    <td><span class="skill-pbar"><span class="skill-pfill" style="width:75%"></span></span><span class="pct-txt">75%</span></td></tr>
</table>

<hr/>

<!-- PROJECTS -->
<h2>🚀 Featured Projects</h2>
<table>
  <tr><th>Project</th><th>Description</th><th>Tech Stack</th></tr>
  <tr>
    <td><strong>🤖 AI PDF Chatbot</strong><br/><a href="https://github.com/g-sri-harshit/RAG-Chatbot" target="_blank">GitHub ↗</a></td>
    <td>AI-powered PDF chatbot using RAG — context-aware Q&amp;A from documents with FAISS vector DB and Ollama LLMs.</td>
    <td>Python · RAG · FAISS · Ollama · LangChain</td>
  </tr>
  <tr>
    <td><strong>🧠 Multi-Agent MCP Learning Path Generator</strong><br/><a href="https://github.com/g-sri-harshit" target="_blank">GitHub ↗</a></td>
    <td>Multi-Agent AI system generating personalised learning paths. Integrates YouTube + Google Drive via Pipedream. Powered by Google Gemini.</td>
    <td>Python · Streamlit · MCP · Gemini · Pipedream</td>
  </tr>
  <tr>
    <td><strong>📰 Fake News Detection System</strong><br/><a href="https://github.com/g-sri-harshit" target="_blank">GitHub ↗</a></td>
    <td>NLP-based classifier using NLTK and Scikit-learn. TF-IDF + tokenization. Achieved <strong>92% accuracy</strong>.</td>
    <td>Python · NLTK · Scikit-learn · TF-IDF</td>
  </tr>
</table>

<hr/>

<!-- EDUCATION -->
<h2>🎓 Academic Background</h2>
<table class="edu-table">
  <tr><th>Year</th><th>Degree / Certificate</th><th>Institute</th><th>Score</th></tr>
  <tr><td>2026</td><td>B.E. Computer Science (AI &amp; ML)</td><td>Chandigarh University, Punjab</td><td>7.56 / 10</td></tr>
  <tr><td>2022</td><td>Intermediate (BIEAP)</td><td>Narayana Junior College, Vijayawada</td><td>88.3%</td></tr>
  <tr><td>2020</td><td>Matriculation (SSC)</td><td>Viswabharathi High School, Gudivada</td><td>100%</td></tr>
</table>

<hr/>

<!-- CERTIFICATIONS -->
<h2>📜 Certifications</h2>
<ul class="cert-list">
  <li>🏅 <strong>Artificial Intelligence Analyst</strong> — IBM</li>
  <li>🏅 <strong>Prompt Engineering</strong> — Coursera</li>
  <li>🏅 <strong>IBM Generative AI Engineering</strong> — IBM <em>(Expected: 2026)</em></li>
  <li>🏅 <strong>NDG Linux Unhatched</strong> — Cisco Networking Academy</li>
</ul>

<hr/>

<!-- RESUME -->
<h2>📄 Resume</h2>
<div class="resume-section">
  <a class="dl-btn" href="Sri_Harshit_Resume.pdf" download="Sri_Harshit_Golla_Resume.pdf">
    ⬇ Download My Resume (PDF)
  </a>
  <p class="note" style="margin-top:12px;">Last updated · May 2026 · AI &amp; ML Engineer</p>
</div>

<hr/>
</div><!-- /content -->

<!-- FOOTER WAVE -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1350 120" width="100%" style="display:block;">
  <defs>
    <linearGradient id="fg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00B4D8"/>
      <stop offset="50%" stop-color="#1a7fd4"/>
      <stop offset="100%" stop-color="#0047AB"/>
    </linearGradient>
  </defs>
  <path fill="url(#fg)" d="M0,40 C200,10 400,80 675,45 C950,10 1150,70 1350,30 L1350,120 L0,120 Z"/>
  <text x="675" y="93" text-anchor="middle" font-family="Arial,sans-serif" font-size="15" fill="rgba(255,255,255,0.9)">
    💙 Thanks for visiting! Let's build something intelligent together — g-sri-harshit
  </text>
</svg>

<!-- VISIT COUNTER -->
<div style="text-align:center;padding:12px 0 32px;background:#0d1117;">
  <span class="css-badge b-views" style="cursor:default;">
    <span class="b-label">👁 TOTAL VISITS</span>
    <span class="b-val" id="visit-count">—</span>
  </span>
</div>

</div><!-- /container -->

<script>
/* ── HERO PARTICLE CANVAS ── */
(function(){
  const c=document.getElementById('hero-canvas');
  if(!c)return;
  const ctx=c.getContext('2d');
  let W,H,pts=[];
  function resize(){
    const r=c.parentElement.getBoundingClientRect();
    W=c.width=r.width||1012; H=c.height=r.height||220;
  }
  resize(); window.addEventListener('resize',resize);
  for(let i=0;i<60;i++) pts.push({
    x:Math.random()*2000,y:Math.random()*300,
    vx:(Math.random()-.5)*0.4,vy:(Math.random()-.5)*0.2,
    r:Math.random()*2+0.5,o:Math.random()*0.6+0.1
  });
  function draw(){
    ctx.clearRect(0,0,W,H);
    pts.forEach(p=>{
      p.x+=p.vx; p.y+=p.vy;
      if(p.x<0)p.x=W; if(p.x>W)p.x=0;
      if(p.y<0)p.y=H; if(p.y>H)p.y=0;
      ctx.beginPath(); ctx.arc(p.x,p.y,p.r,0,Math.PI*2);
      ctx.fillStyle=`rgba(255,255,255,${p.o})`; ctx.fill();
    });
    // lines between close particles
    for(let i=0;i<pts.length;i++){
      for(let j=i+1;j<pts.length;j++){
        const dx=pts[i].x-pts[j].x,dy=pts[i].y-pts[j].y;
        const d=Math.sqrt(dx*dx+dy*dy);
        if(d<90){
          ctx.beginPath();
          ctx.moveTo(pts[i].x,pts[i].y);
          ctx.lineTo(pts[j].x,pts[j].y);
          ctx.strokeStyle=`rgba(255,255,255,${0.08*(1-d/90)})`;
          ctx.lineWidth=0.5; ctx.stroke();
        }
      }
    }
    requestAnimationFrame(draw);
  }
  draw();
})();

/* ── TYPING ANIMATION ── */
(function(){
  const lines=[
    'B.E. CSE (AI & ML)  |  Chandigarh University 🎓',
    'Python  |  LangChain  |  LLMs  |  RAG  |  GenAI 🔥',
    'Turning Raw Data → Intelligent Systems 🤖',
    'Building: RAG Bots  |  Multi-Agent AI  |  NLP Models',
    'Code + AI = My Superpower ⚡'
  ];
  let li=0,ci=0,del=false;
  const el=document.getElementById('typed');
  if(!el)return;
  function type(){
    const s=lines[li];
    if(!del){ el.textContent=s.slice(0,++ci);
      if(ci===s.length){del=true;setTimeout(type,2200);return;}
    }else{ el.textContent=s.slice(0,--ci);
      if(ci===0){del=false;li=(li+1)%lines.length;}
    }
    setTimeout(type,del?35:75);
  }
  setTimeout(type,600);
})();

/* ── PROFILE VIEWS / FOLLOWERS ── */
(function(){
  // Animated counter for a nice effect
  function countUp(el,target,dur){
    let v=0,step=target/dur*16;
    function go(){v=Math.min(v+step,target);el.textContent=Math.floor(v).toLocaleString();if(v<target)requestAnimationFrame(go);}
    go();
  }
  const pv=document.getElementById('pv-count');
  const fl=document.getElementById('fl-count');
  const vc=document.getElementById('visit-count');
  let views=parseInt(localStorage.getItem('_shg_pv')||'0')+1;
  localStorage.setItem('_shg_pv',views);
  if(pv) countUp(pv,views,60);
  if(fl) fl.textContent='GitHub ↗';
  if(vc) countUp(vc,views,60);
})();

/* ── CONTRIBUTION GRID ── */
(function(){
  const g=document.getElementById('cgrid');
  if(!g)return;
  const pal=['#161b22','#0d2a3d','#0e4272','#1a6fb5','#38bdf8'];
  for(let i=0;i<364;i++){
    const d=document.createElement('div');
    const r=Math.random();
    d.style.background=r<0.38?pal[0]:r<0.58?pal[1]:r<0.74?pal[2]:r<0.89?pal[3]:pal[4];
    g.appendChild(d);
  }
})();

/* ── SNAKE ── */
(function(){
  const sc=document.getElementById('snk');
  if(!sc)return;
  const ctx=sc.getContext('2d'),W=960,H=64,CS=8,cols=W/CS,rows=H/CS;
  let snake=[{x:10,y:4}],dir={x:1,y:0};
  let food={x:Math.floor(Math.random()*cols),y:Math.floor(Math.random()*rows)};
  function draw(){
    ctx.fillStyle='#161b22';ctx.fillRect(0,0,W,H);
    snake.forEach((s,i)=>{
      const a=i===0?1:Math.max(0.1,1-i*(1/Math.max(snake.length,1)));
      ctx.fillStyle=i===0?'#38bdf8':`rgba(14,165,233,${a})`;
      ctx.fillRect(s.x*CS+1,s.y*CS+1,CS-2,CS-2);
    });
    ctx.fillStyle='#4ade80';
    ctx.beginPath();ctx.arc(food.x*CS+CS/2,food.y*CS+CS/2,CS/2-1,0,Math.PI*2);ctx.fill();
  }
  function step(){
    const h={x:(snake[0].x+dir.x+cols)%cols,y:(snake[0].y+dir.y+rows)%rows};
    snake.unshift(h);
    if(h.x===food.x&&h.y===food.y){
      food={x:Math.floor(Math.random()*cols),y:Math.floor(Math.random()*rows)};
      if(Math.random()<0.3){
        const ds=[{x:1,y:0},{x:-1,y:0},{x:0,y:1},{x:0,y:-1}];
        const nd=ds[Math.floor(Math.random()*ds.length)];
        if(nd.x!==-dir.x||nd.y!==-dir.y)dir=nd;
      }
    }else snake.pop();
    draw();
  }
  draw();setInterval(step,110);
})();

/* ── QUOTES ── */
(function(){
  const qs=[
    {q:"Any sufficiently advanced technology is indistinguishable from magic.",a:"Arthur C. Clarke"},
    {q:"Machine intelligence is the last invention humanity will ever need to make.",a:"Nick Bostrom"},
    {q:"Data is the new oil. But, like oil, it must be refined before use.",a:"Clive Humby"},
    {q:"In God we trust. All others must bring data.",a:"W. Edwards Deming"},
    {q:"The question isn't who is going to let me; it's who is going to stop me.",a:"Ayn Rand"},
    {q:"First, solve the problem. Then, write the code.",a:"John Johnson"}
  ];
  const q=qs[Math.floor(Math.random()*qs.length)];
  const qt=document.getElementById('quote-txt');
  const qa=document.getElementById('quote-auth');
  if(qt)qt.textContent=q.q;
  if(qa)qa.textContent='— '+q.a;
})();

/* ── LEETCODE COUNTER ── */
(function(){
  const easy=45,med=28,hard=8,total=easy+med+hard;
  function cUp(el,t,d){let v=0,s=t/d*16;function g(){v=Math.min(v+s,t);el.textContent=Math.floor(v);if(v<t)requestAnimationFrame(g);}g();}
  setTimeout(()=>{
    const lt=document.getElementById('lc-total');
    const et=document.getElementById('e-txt'),mt=document.getElementById('m-txt'),ht=document.getElementById('h-txt');
    const eb=document.getElementById('e-bar'),mb=document.getElementById('m-bar'),hb=document.getElementById('h-bar');
    if(lt)cUp(lt,total,60);
    if(et)et.textContent=easy+' / 800';
    if(mt)mt.textContent=med+' / 1600';
    if(ht)ht.textContent=hard+' / 700';
    if(eb)eb.style.width=(easy/800*100)+'%';
    if(mb)mb.style.width=(med/1600*100)+'%';
    if(hb)hb.style.width=(hard/700*100)+'%';
  },400);
})();
</script>
</body>
</html>
