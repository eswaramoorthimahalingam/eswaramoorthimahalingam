<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eswaramoorthi Mahalingam – Portfolio</title>
    <!-- JetBrains Mono for code & typing SVG -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: #050510;
            color: #c9d1d9;
            font-family: 'JetBrains Mono', monospace;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            min-height: 100vh;
            padding: 20px 0;
            line-height: 1.6;
        }
        .container {
            max-width: 960px;
            width: 90%;
            margin: auto;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        /* Section headers */
        .section-header {
            margin: 20px 0 10px 0;
            width: 100%;
            text-align: center;
        }
        /* Neon dividers */
        .neon-divider {
            width: 100%;
            margin: 15px 0;
        }
        /* Animated waves */
        .animated-wave {
            width: 100%;
            margin: 20px 0;
        }
        /* Stats images centering */
        .stats-row {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .stats-row img {
            border-radius: 12px;
        }
        /* Tables */
        table {
            border-collapse: collapse;
            margin: 15px auto;
            background-color: rgba(13, 17, 23, 0.6);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.1);
            font-size: 0.95rem;
        }
        th, td {
            padding: 12px 18px;
            text-align: left;
        }
        th {
            background-color: rgba(0, 255, 255, 0.1);
            color: #00FFFF;
            font-weight: 700;
            letter-spacing: 1px;
        }
        td {
            color: #c9d1d9;
        }
        tr:not(:last-child) td {
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }
        /* Collapsible details */
        details {
            background: rgba(13, 17, 23, 0.7);
            border: 1px solid rgba(0, 255, 255, 0.2);
            border-radius: 12px;
            padding: 15px 20px;
            margin: 15px 0;
            width: 100%;
            transition: all 0.3s ease;
        }
        details[open] {
            background: rgba(13, 17, 23, 0.9);
            border-color: #FF00FF;
        }
        summary {
            font-weight: 700;
            color: #00FFFF;
            cursor: pointer;
            font-size: 1.05rem;
            outline: none;
            margin: -15px -20px;
            padding: 15px 20px;
            border-radius: 12px;
            transition: background 0.2s;
        }
        summary:hover {
            background: rgba(0, 255, 255, 0.1);
        }
        details[open] summary {
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            margin-bottom: 15px;
            color: #FF00FF;
        }
        /* Code blocks */
        .code-block {
            background: #0d1117;
            border: 1px solid rgba(255, 0, 128, 0.3);
            border-radius: 8px;
            padding: 20px;
            margin: 15px 0;
            overflow-x: auto;
            font-family: 'JetBrains Mono', monospace;
            color: #00FFFF;
            text-align: left;
            white-space: pre-wrap;
            box-shadow: 0 0 15px rgba(189, 0, 255, 0.2);
            line-height: 1.5;
            max-width: 100%;
        }
        .code-block span.comment {
            color: #8b949e;
        }
        .code-block span.keyword {
            color: #FF00FF;
        }
        .code-block span.string {
            color: #00FFAA;
        }
        /* Float image */
        .float-right {
            float: right;
            margin-left: 20px;
            margin-bottom: 20px;
        }
        .clearfix::after {
            content: "";
            display: table;
            clear: both;
        }
        /* Badges */
        .badge-row {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin: 10px 0;
        }
        .badge-row img, .badge-row a img {
            display: inline-block;
            margin: 0;
        }
        /* Center text */
        .center {
            text-align: center;
        }
        /* Links */
        a {
            text-decoration: none;
        }
        /* Social icons */
        .social-icons {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin: 15px 0;
        }
        .social-icons a img {
            transition: transform 0.2s;
        }
        .social-icons a img:hover {
            transform: scale(1.1);
        }
        /* Motto quote */
        .motto {
            font-style: italic;
            color: #FF00FF;
            font-size: 1.1rem;
            margin: 20px 0;
        }
        /* Responsive adjustments */
        @media (max-width: 600px) {
            .stats-row {
                flex-direction: column;
                align-items: center;
            }
            .stats-row img {
                max-width: 95%;
                height: auto;
            }
        }
    </style>
</head>
<body>
    <div class="container">

        <!-- ========== ANIMATED HEADER ========== -->
        <img src="https://capsule-render.vercel.app/api?type=waving&color=0:050510,20:0d0533,40:1a0a4a,60:0d1560,80:1a0533,100:050510&height=280&section=header&text=ESWARAMOORTHI&fontSize=62&fontColor=00FFFF&animation=twinkling&fontAlignY=42&desc=MAHALINGAM&descSize=38&descColor=FF00FF&descAlignY=68&stroke=00FFFF&strokeWidth=2" style="width:100%" alt="Animated header" />

        <!-- Neon Divider -->
        <img class="neon-divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:FF0080,50:BD00FF,100:00D4FF&height=4&animation=twinkling" alt="divider" />

        <!-- Typing SVG 1 -->
        <p class="center">
            <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=28&duration=2500&pause=800&color=00FFFF&center=true&vCenter=true&width=860&lines=🤖+Research+Developer+%7C+AI+Lead;🧠+Generative+%26+Agentic+AI+Specialist;🎓+District+Trainer+%7C+Corporate+Trainer;⛓️+Blockchain+%7C+Cloud+%7C+Emerging+Tech;🛸+Drone+Tech+%7C+IoT+%7C+Nano-Science;🚀+Building+the+Future+with+AI" alt="Typing SVG" style="max-width:100%;" />
        </p>
        <p class="center">
            <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=4000&pause=2000&color=FF00FF&center=true&vCenter=true&width=800&lines=⚡+Tirupur%2C+Tamil+Nadu%2C+India+🇮🇳;⚡+B.Tech+AI+%26+Data+Science+2026;⚡+68%2B+Seminars+·+37%2B+Workshops+·+3%2B+Conferences;⚡+21%2B+Mini+Projects+·+57%2B+Institutional+Trainings;⚡+11%2B+Live+Industry+Products+Deployed" alt="Typing SVG details" style="max-width:100%;" />
        </p>

        <!-- Profile views and followers -->
        <div class="badge-row">
            <img src="https://komarev.com/ghpvc/?username=eswaramoorthimahalingam&style=for-the-badge&color=FF00FF&label=👁️+PROFILE+VIEWS&labelColor=0D1117" alt="profile views" />
            <img src="https://img.shields.io/github/followers/eswaramoorthimahalingam?style=for-the-badge&color=00FFFF&labelColor=0D1117&logo=github&label=FOLLOWERS" alt="followers" />
        </div>

        <!-- Neon Divider -->
        <img class="neon-divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:00D4FF,50:BD00FF,100:FF0080&height=4&animation=twinkling" alt="divider" />

        <!-- Social Links -->
        <div class="social-icons">
            <a href="https://linkedin.com/in/eswaramoorthimahalingam"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
            <a href="mailto:eswaramoorthimahalingam@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
            <a href="https://www.eswaramoorthimahalingam.blog"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
            <a href="https://orcid.org/0009-0000-5941-85499"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
            <a href="mailto:eswaramoorthimahalingam@ieee.org"><img src="https://img.shields.io/badge/IEEE-00629B?style=for-the-badge&logo=ieee&logoColor=white" alt="IEEE"></a>
            <a href="https://github.com/eswaramoorthimahalingam"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
        </div>

        <br>

        <!-- ========== ABOUT ME ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:12043a,100:050510&height=60&section=header&text=🧑‍💻+ABOUT+ME&fontSize=28&fontColor=00FFFF&animation=fadeIn&fontAlignY=65" alt="About Me" style="width:100%;" />
        </div>

        <div class="clearfix" style="width:100%;">
            <img class="float-right" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="320" alt="AI animation" style="max-width:100%;" />
            <div class="code-block">
                ╔══════════════════════════════════════════════════════╗<br>
                ║    RESEARCH DEVELOPER  ·  AI LEAD  ·  TRAINER       ║<br>
                ╚══════════════════════════════════════════════════════╝<br><br>
                <span class="keyword">class</span> EswaramoorthiMahalingam:<br><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">name</span>      = <span class="string">"Eswaramoorthi Mahalingam"</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">location</span>  = <span class="string">"Tirupur, Tamil Nadu, India 🇮🇳"</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">degree</span>    = <span class="string">"B.Tech – AI & Data Science (2026)"</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">college</span>   = <span class="string">"Christ The King Engineering College"</span><br><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">roles</span>     = [<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"Research Developer @ Gateway Software Solutions"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"AI Lead – Enterprise AI Solutions"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"District Trainer – Rotaract District 3203"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"Corporate Trainer & Technology Speaker"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;]<br><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">expertise</span> = [<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"Generative AI & LLM Fine‑tuning"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"Agentic AI & Multi‑Agent Systems"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"Cloud Architecture (AWS/GCP)"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"Blockchain‑inspired Systems"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"IoT, Drone Tech, Nano‑Science"</span>,<br>
                &nbsp;&nbsp;&nbsp;&nbsp;]<br><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">vision</span> = (<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"I am deeply inspired by the pioneers of modern science and technology. "</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"My passion lies at the intersection of AI, quantum realms, and advanced robotics — "</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"where I strive to invent, innovate, and build solutions that shape tomorrow. "</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="string">"Curiosity is my engine; execution is my craft."</span><br>
                &nbsp;&nbsp;&nbsp;&nbsp;)<br><br>
                &nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">motto</span>  = <span class="string">"Innovation begins when knowledge meets execution."</span>
            </div>
        </div>

        <div class="badge-row" style="justify-content: flex-start; width:100%;">
            <img src="https://img.shields.io/badge/⚡_STATUS-Building%20the%20Future-00FFFF?style=for-the-badge&labelColor=0D1117" alt="status" />
        </div>

        <br style="clear:both;">

        <!-- ========== TECH STACK ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:1a0533,100:050510&height=60&section=header&text=🛠️+TECH+STACK+%26+TOOLS&fontSize=28&fontColor=FF00FF&animation=fadeIn&fontAlignY=65" alt="Tech Stack" style="width:100%;" />
        </div>

        <h3 class="center">⚡ Languages & Core</h3>
        <p class="center"><img src="https://skillicons.dev/icons?i=python,java,html,css,js,matlab&theme=dark&perline=6" alt="languages" /></p>

        <h3 class="center">🤖 AI, GenAI & Agentic AI</h3>
        <div class="badge-row">
            <img src="https://img.shields.io/badge/LLMs_(GPT,_Claude,_Gemini)-412991?style=for-the-badge&logo=openai&logoColor=white" alt="LLMs">
            <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain">
            <img src="https://img.shields.io/badge/RAG_Systems-BD00FF?style=for-the-badge&logo=openai&logoColor=white" alt="RAG">
            <img src="https://img.shields.io/badge/Multi--Agent_AI-000000?style=for-the-badge&logo=robotframework&logoColor=white" alt="Multi-Agent">
            <img src="https://img.shields.io/badge/Prompt_Engineering-FF0080?style=for-the-badge&logo=openai&logoColor=white" alt="Prompt Eng">
        </div>

        <h3 class="center">☁️ Cloud & DevOps</h3>
        <p class="center"><img src="https://skillicons.dev/icons?i=aws,gcp,git,github,vscode,docker&theme=dark&perline=6" alt="cloud" /></p>

        <h3 class="center">🛸 Hardware & Emerging Tech</h3>
        <div class="badge-row">
            <img src="https://img.shields.io/badge/IoT-00979D?style=for-the-badge&logo=arduino&logoColor=white" alt="IoT">
            <img src="https://img.shields.io/badge/Drone_Tech-1B1B1B?style=for-the-badge&logo=dji&logoColor=white" alt="Drone">
            <img src="https://img.shields.io/badge/Nano--Science-5C6BC0?style=for-the-badge&logo=atom&logoColor=white" alt="Nano">
            <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="RPi">
            <img src="https://img.shields.io/badge/Blockchain-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white" alt="Blockchain">
        </div>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== WORK EXPERIENCE ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:0d1a3a,100:050510&height=60&section=header&text=💼+WORK+EXPERIENCE&fontSize=28&fontColor=00FFFF&animation=fadeIn&fontAlignY=65" alt="Work Experience" style="width:100%;" />
        </div>

        <details>
            <summary>🏢 Research Developer — Gateway Software Solutions (Current)</summary>
            <div class="badge-row" style="justify-content: flex-start;">
                <img src="https://img.shields.io/badge/AI%20R&D-412991?style=flat-square&logo=openai&logoColor=white" alt="AI R&D">
                <img src="https://img.shields.io/badge/Agentic%20AI-000000?style=flat-square&logo=robotframework&logoColor=white" alt="Agentic">
                <img src="https://img.shields.io/badge/Cloud%20Architecture-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="Cloud">
            </div>
            <ul>
                <li>🧠 Lead AI R&D for enterprise AI applications and intelligent automation systems</li>
                <li>🤖 Develop Generative AI & Agentic AI solutions (multi‑agent, RAG, autonomous workflows)</li>
                <li>☁️ Architect and deploy cloud‑native platforms (AWS/GCP)</li>
                <li>🚀 Drive product innovation, technical consulting, and digital transformation</li>
            </ul>
        </details>

        <details>
            <summary>🏢 E‑one Technologies — Project Developer (GenAI) | Jan 2025 – Mar 2025</summary>
            <div class="badge-row" style="justify-content: flex-start;">
                <img src="https://img.shields.io/badge/OutSystems-E83D18?style=flat-square&logo=outsystems&logoColor=white" alt="OutSystems">
                <img src="https://img.shields.io/badge/GenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="GenAI">
            </div>
            <ul>
                <li>🚀 Built production‑ready full‑stack web apps with embedded GenAI on OutSystems</li>
                <li>⚡ Developed intelligent workflows and AI‑assisted business applications</li>
            </ul>
        </details>

        <details>
            <summary>🏢 SkillMaven — Project Developer (Cloud) | Jan 2025 – Feb 2025</summary>
            <div class="badge-row" style="justify-content: flex-start;">
                <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
                <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP">
            </div>
            <ul>
                <li>☁️ Built and deployed resource‑based real‑time projects on AWS console</li>
                <li>🔧 Managed cloud infrastructure and resource provisioning hands‑on</li>
            </ul>
        </details>

        <details>
            <summary>🏢 Aarvee Enterprises — Drone Tech Trainee | Sep 2024 – Oct 2024</summary>
            <div class="badge-row" style="justify-content: flex-start;">
                <img src="https://img.shields.io/badge/Drone%20Tech-1B1B1B?style=flat-square&logo=dji&logoColor=white" alt="Drone">
                <img src="https://img.shields.io/badge/IoT-00979D?style=flat-square&logo=arduino&logoColor=white" alt="IoT">
            </div>
            <ul>
                <li>🛸 Hands‑on drone design, assembly, and integration</li>
                <li>🤖 Developed autonomous navigation skills and sensor‑fusion techniques</li>
            </ul>
        </details>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== LIVE INDUSTRY PRODUCTS ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:1a0533,100:050510&height=60&section=header&text=🚀+LIVE+INDUSTRY+PRODUCTS&fontSize=28&fontColor=FF00FF&animation=fadeIn&fontAlignY=65" alt="Industry Products" style="width:100%;" />
        </div>

        <table>
            <tr><th>Project</th><th>Role</th><th>Domain</th></tr>
            <tr><td>The Indian Commerce</td><td>AI Lead & Product Consultant</td><td>AI, E‑Commerce, Automation</td></tr>
            <tr><td>BookYourTurf (Web + Mobile)</td><td>AI Lead</td><td>SportsTech, SaaS</td></tr>
            <tr><td>Aayubakwath</td><td>AI Lead</td><td>AI Implementation, Digital Transformation</td></tr>
            <tr><td>Studio Space</td><td>AI Lead & Associate Lead</td><td>Business Automation, Web Platforms</td></tr>
            <tr><td>Ponni Wood Carving</td><td>AI & Technology Consultant</td><td>Digital Branding, AI Automation</td></tr>
            <tr><td>YeaahDhum Iyarkaiyagam</td><td>AI & Digital Solutions Consultant</td><td>Business Transformation, Web Optimization</td></tr>
            <tr><td>Micro Science</td><td>AI Solutions Developer</td><td>EdTech, AI‑powered Learning</td></tr>
            <tr><td>Fruition InnoviX</td><td>AI Lead & Product Consultant</td><td>Innovation, Digital Transformation</td></tr>
            <tr><td>Rajah Hospital</td><td>AI Solutions Consultant</td><td>Healthcare AI, Digital Health</td></tr>
            <tr><td>Ariomac Fashion</td><td>AI & Technology Consultant</td><td>FashionTech, E‑Commerce</td></tr>
            <tr><td>Menmitha Food Products</td><td>AI & Digital Solutions Consultant</td><td>FoodTech, Automation</td></tr>
        </table>

        <p class="center"><img src="https://img.shields.io/badge/Total%20Live%20Products-11%2B-00FFFF?style=for-the-badge&labelColor=0D1117" alt="total products" /></p>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== RESEARCH & PROJECTS ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:0d1a3a,100:050510&height=60&section=header&text=🔬+RESEARCH+%26+PROJECTS&fontSize=28&fontColor=00FFFF&animation=fadeIn&fontAlignY=65" alt="Research Projects" style="width:100%;" />
        </div>

        <table>
            <tr><th>Project</th><th>Stack</th><th>Role</th><th>Period</th></tr>
            <tr><td>🗳️ Advanced Hybrid Voting System</td><td>Blockchain, AWS, Smart Contracts</td><td>R&D Lead</td><td>Dec 2024–Mar 2025</td></tr>
            <tr><td>🛸 Hybrid Surveillance System (Garuda Aerospace Hackathon)</td><td>ML, Drone, Dual Power</td><td>Team Head & Dev</td><td>Oct–Dec 2024</td></tr>
            <tr><td>🏠 IoT Smart Vehicle Control (ATAL Tinkering Lab)</td><td>IoT, Smartphone, Automation</td><td>Team Head & Dev</td><td>Oct–Dec 2020</td></tr>
            <tr><td>🤖 Enterprise GenAI & Agentic AI Solutions</td><td>LLMs, RAG, Multi-Agent, Cloud</td><td>Architect & Developer</td><td>2024–Now</td></tr>
            <tr><td>☁️ Cloud‑Based Enterprise Apps</td><td>AWS, GCP, Serverless</td><td>Cloud Architect</td><td>2024–Now</td></tr>
        </table>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== TRAINING & SPEAKING ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:1a0533,100:050510&height=60&section=header&text=🎤+TRAINING+%26+SPEAKING&fontSize=28&fontColor=FF00FF&animation=fadeIn&fontAlignY=65" alt="Training & Speaking" style="width:100%;" />
        </div>

        <div class="badge-row">
            <img src="https://img.shields.io/badge/Institutions%20Trained-57%2B-FF0080?style=for-the-badge&labelColor=0D1117" alt="Institutions">
            <img src="https://img.shields.io/badge/Workshops%20Delivered-79%2B-00FFFF?style=for-the-badge&labelColor=0D1117" alt="Workshops">
            <img src="https://img.shields.io/badge/Guest%20Lectures-56%2B-BD00FF?style=for-the-badge&labelColor=0D1117" alt="Lectures">
        </div>

        <details>
            <summary>📊 Domain‑wise Training Distribution</summary>
            <table>
                <tr><th>Domain</th><th>Engagements</th><th>Share</th></tr>
                <tr><td>Generative AI (GenAI) Development</td><td>30</td><td>52.6%</td></tr>
                <tr><td>Embedded Systems & IoT</td><td>9</td><td>15.8%</td></tr>
                <tr><td>Cloud Computing</td><td>6</td><td>10.5%</td></tr>
                <tr><td>Java Full Stack & J2EE</td><td>3</td><td>5.3%</td></tr>
                <tr><td>AI‑IoT Integration</td><td>3</td><td>5.3%</td></tr>
                <tr><td>Blockchain Technology</td><td>2</td><td>3.5%</td></tr>
                <tr><td>Vibe Coding (AI‑Assisted Dev)</td><td>2</td><td>3.5%</td></tr>
                <tr><td>Computer Hardware & Networking</td><td>1</td><td>1.8%</td></tr>
                <tr><td>Agentic AI Prototyping</td><td>1</td><td>1.8%</td></tr>
            </table>
        </details>

        <details>
            <summary>🏫 Institutional Engagement Record (57+ Colleges & Batches)</summary>
            <p class="center">Includes engineering, arts & science, polytechnic colleges, and open batches across Tamil Nadu.</p>
            <p class="center"><img src="https://img.shields.io/badge/Full%20List%20Available%20on%20Request-0D1117?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Full list available on request"></p>
        </details>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== GITHUB STATS ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:0d1a3a,100:050510&height=60&section=header&text=📊+GITHUB+ANALYTICS&fontSize=28&fontColor=00FFFF&animation=fadeIn&fontAlignY=65" alt="GitHub Analytics" style="width:100%;" />
        </div>

        <div class="stats-row">
            <img height="175" src="https://github-readme-stats.vercel.app/api?username=eswaramoorthimahalingam&show_icons=true&theme=radical&hide_border=true&bg_color=050510&title_color=00FFFF&icon_color=FF00FF&text_color=c9d1d9&border_radius=12&include_all_commits=true&count_private=true" alt="GitHub Stats" />
            <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=eswaramoorthimahalingam&layout=compact&theme=radical&hide_border=true&bg_color=050510&title_color=00FFFF&text_color=c9d1d9&langs_count=8&border_radius=12" alt="Top Languages" />
        </div>

        <br>

        <p class="center"><img src="https://streak-stats.demolab.com?user=eswaramoorthimahalingam&theme=radical&hide_border=true&background=050510&ring=00FFFF&fire=FF00FF&currStreakLabel=00FFFF&sideLabels=BD00FF&dates=8B949E&currStreakNum=FFFFFF&sideNums=FFFFFF&border_radius=12" alt="GitHub Streak" style="max-width:100%;" /></p>

        <p class="center"><img src="https://github-readme-activity-graph.vercel.app/graph?username=eswaramoorthimahalingam&theme=react-dark&bg_color=050510&color=00FFFF&line=BD00FF&point=FF00FF&area=true&hide_border=true" alt="Activity Graph" style="max-width:100%;" /></p>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== TROPHIES ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:1a0533,100:050510&height=60&section=header&text=🏆+TROPHY+WALL&fontSize=28&fontColor=FF00FF&animation=fadeIn&fontAlignY=65" alt="Trophy Wall" style="width:100%;" />
        </div>

        <p class="center"><img src="https://github-profile-trophy.vercel.app/?username=eswaramoorthimahalingam&theme=radical&no-frame=true&no-bg=true&row=1&column=7&margin-w=6" alt="Trophies" style="max-width:100%;" /></p>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== ACHIEVEMENTS ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:0d1a3a,100:050510&height=60&section=header&text=🏅+ACHIEVEMENTS+%26+IMPACT&fontSize=28&fontColor=00FFFF&animation=fadeIn&fontAlignY=65" alt="Achievements" style="width:100%;" />
        </div>

        <table>
            <tr><th>Badge</th><th>Achievement</th><th>Count</th></tr>
            <tr><td>🥇</td><td>Outstanding Performance Award</td><td>×1</td></tr>
            <tr><td>🥈</td><td>Best Performance Awards</td><td>×2</td></tr>
            <tr><td>🌟</td><td>Best Student of the Year</td><td>×1</td></tr>
            <tr><td>⚽</td><td>Sports – Athletics & Football</td><td>12+</td></tr>
            <tr><td>📋</td><td>Conferences · Workshops · Seminars</td><td>3 · 37 · 68</td></tr>
            <tr><td>🔬</td><td>Mini Projects Completed</td><td>21+</td></tr>
            <tr><td>🎤</td><td>Guest Lectures & Training Workshops</td><td>56+ · 79+</td></tr>
            <tr><td>🏭</td><td>Industry Products Deployed</td><td>11+</td></tr>
        </table>

        <!-- ========== EDUCATION ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:1a0533,100:050510&height=60&section=header&text=🎓+EDUCATION&fontSize=28&fontColor=FF00FF&animation=fadeIn&fontAlignY=65" alt="Education" style="width:100%;" />
        </div>

        <table>
            <tr><th>Degree</th><th>Institution</th><th>Graduation</th></tr>
            <tr><td>B.Tech — Artificial Intelligence & Data Science</td><td>Christ The King Engineering College, Coimbatore</td><td>2026</td></tr>
        </table>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== CURRENTLY LEVELING UP ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:0d1a3a,100:050510&height=60&section=header&text=📚+CURRENTLY+LEVELING+UP&fontSize=28&fontColor=00FFFF&animation=fadeIn&fontAlignY=65" alt="Leveling Up" style="width:100%;" />
        </div>

        <div class="code-block">
╔══════════════════════════════════════════════════════════════════╗<br>
║                   SKILL TREE  ·  2026 BUILD                     ║<br>
╠══════════════════╦═══════════════════════════════════════════════╣<br>
║  🤖 Generative AI ║  LLM Fine‑tuning · Prompt Eng. · RAG        ║<br>
║  🧠 Agentic AI    ║  Multi‑Agent Systems · Autonomous Workflows ║<br>
║  ⛓️  Blockchain   ║  Hybrid Voting · Smart Contracts             ║<br>
║  ☁️  Cloud Arch.  ║  AWS Solutions Architect · GCP Pro           ║<br>
║  🛸 Drone Auto.  ║  Computer Vision · Flight Control             ║<br>
║  🔬 Nano‑Science ║  Nanomaterials · Emerging Applications        ║<br>
║  🚀 Space Tech   ║  Satellite Systems · Aerospace                ║<br>
╚══════════════════╩═══════════════════════════════════════════════╝
        </div>

        <div class="badge-row">
            <img src="https://img.shields.io/badge/GenAI-LLM%20Fine--tuning-412991?style=for-the-badge&labelColor=050510" alt="GenAI">
            <img src="https://img.shields.io/badge/Agentic_AI-Multi--Agent_Systems-000000?style=for-the-badge&labelColor=050510" alt="Agentic AI">
            <img src="https://img.shields.io/badge/Blockchain-Smart%20Contracts-F7931A?style=for-the-badge&labelColor=050510" alt="Blockchain">
            <img src="https://img.shields.io/badge/AWS-Solutions%20Architect-FF9900?style=for-the-badge&labelColor=050510" alt="AWS">
            <img src="https://img.shields.io/badge/Drones-Autonomous%20Nav-00979D?style=for-the-badge&labelColor=050510" alt="Drones">
            <img src="https://img.shields.io/badge/Nano--Science-Emerging%20Tech-5C6BC0?style=for-the-badge&labelColor=050510" alt="Nano">
            <img src="https://img.shields.io/badge/Space%20Tech-Satellite%20Sys-BD00FF?style=for-the-badge&labelColor=050510" alt="Space">
        </div>

        <!-- Animated wave -->
        <img class="animated-wave" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" alt="wave" />

        <!-- ========== CONNECT ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:1a0533,100:050510&height=60&section=header&text=🌐+CONNECT+WITH+ME&fontSize=28&fontColor=FF00FF&animation=fadeIn&fontAlignY=65" alt="Connect" style="width:100%;" />
        </div>

        <div class="social-icons">
            <a href="https://linkedin.com/in/eswaramoorthimahalingam"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
            <a href="mailto:eswaramoorthimahalingam@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
            <a href="https://www.eswaramoorthimahalingam.blog"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
            <a href="https://orcid.org/0009-0000-5941-85499"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
            <a href="mailto:eswaramoorthimahalingam@ieee.org"><img src="https://img.shields.io/badge/IEEE-00629B?style=for-the-badge&logo=ieee&logoColor=white" alt="IEEE"></a>
            <a href="https://github.com/eswaramoorthimahalingam"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
        </div>

        <p class="center">📍 <b>4/661, Nochipalayam Pirivu, Palladam Road, Tirupur – 641 605, Tamil Nadu, India</b></p>

        <br>

        <p class="center"><img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400" alt="rocket" style="max-width:100%;" /></p>

        <p class="motto center">"Innovation begins when knowledge meets execution. The future belongs to those who build solutions, not just learn technologies."</p>

        <br>

        <!-- ========== ANIMATED FOOTER ========== -->
        <img class="neon-divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:FF0080,50:BD00FF,100:00FFFF&height=4&animation=twinkling" alt="footer divider" />

        <img src="https://capsule-render.vercel.app/api?type=waving&color=0:050510,20:0d0533,50:1a0a4a,80:0d1560,100:050510&height=160&section=footer&animation=twinkling&fontColor=00FFFF" alt="wave footer" style="width:100%;" />

    </div>
</body>
</html>
