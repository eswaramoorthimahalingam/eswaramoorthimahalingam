<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eswaramoorthi Mahalingam – Portfolio</title>
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
            max-width: 1000px;
            width: 90%;
            margin: auto;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .section-header {
            margin: 20px 0 10px 0;
            width: 100%;
            text-align: center;
        }
        .neon-divider {
            width: 100%;
            margin: 15px 0;
        }
        .animated-wave {
            width: 100%;
            margin: 20px 0;
        }
        .stats-row {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .stats-row img {
            border-radius: 12px;
        }
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
        .center {
            text-align: center;
        }
        a {
            text-decoration: none;
        }
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
        .motto {
            font-style: italic;
            color: #FF00FF;
            font-size: 1.1rem;
            margin: 20px 0;
        }
        /* Fallback placeholder for broken images */
        .img-fallback {
            display: none;
            color: #00FFFF;
            background: rgba(0, 255, 255, 0.1);
            border: 1px dashed #00FFFF;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            font-size: 1.2rem;
            margin: 20px 0;
        }
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
        <img src="https://capsule-render.vercel.app/api?type=waving&color=0:050510,20:0d0533,40:1a0a4a,60:0d1560,80:1a0533,100:050510&height=280&section=header&text=ESWARAMOORTHI&fontSize=62&fontColor=00FFFF&animation=twinkling&fontAlignY=42&desc=MAHALINGAM&descSize=38&descColor=FF00FF&descAlignY=68&stroke=00FFFF&strokeWidth=2" style="width:100%" alt="Animated header" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';" />
        <div class="img-fallback" style="width:100%; margin:0;">🧑‍💻 ESWARAMOORTHI MAHALINGAM</div>

        <!-- Neon Divider -->
        <img class="neon-divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:FF0080,50:BD00FF,100:00D4FF&height=4&animation=twinkling" alt="divider" onerror="this.style.display='none';" />

        <!-- Typing SVG 1 -->
        <p class="center">
            <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=28&duration=2500&pause=800&color=00FFFF&center=true&vCenter=true&width=860&lines=🤖+Research+Developer+%7C+AI+Lead;🧠+Generative+%26+Agentic+AI+Specialist;🎓+District+Trainer+%7C+Corporate+Trainer;⛓️+Blockchain+%7C+Cloud+%7C+Emerging+Tech;🛸+Drone+Tech+%7C+IoT+%7C+Nano-Science;🚀+Building+the+Future+with+AI" alt="Typing SVG" style="max-width:100%;" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';" />
            <span class="img-fallback" style="display:none;">🤖 Research Developer | AI Lead | Generative & Agentic AI Specialist</span>
        </p>
        <p class="center">
            <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=4000&pause=2000&color=FF00FF&center=true&vCenter=true&width=800&lines=⚡+Tirupur%2C+Tamil+Nadu%2C+India+🇮🇳;⚡+B.Tech+AI+%26+Data+Science+2026;⚡+68%2B+Seminars+·+37%2B+Workshops+·+3%2B+Conferences;⚡+21%2B+Mini+Projects+·+57%2B+Institutional+Trainings;⚡+11%2B+Live+Industry+Products+Deployed" alt="Typing SVG details" style="max-width:100%;" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';" />
            <span class="img-fallback" style="display:none;">⚡ Tirupur, Tamil Nadu, India | B.Tech AI & Data Science 2026</span>
        </p>

        <!-- Profile views and followers -->
        <div class="badge-row">
            <img src="https://komarev.com/ghpvc/?username=eswaramoorthimahalingam&style=for-the-badge&color=FF00FF&label=👁️+PROFILE+VIEWS&labelColor=0D1117" alt="profile views" onerror="this.style.display='none';" />
            <img src="https://img.shields.io/github/followers/eswaramoorthimahalingam?style=for-the-badge&color=00FFFF&labelColor=0D1117&logo=github&label=FOLLOWERS" alt="followers" onerror="this.style.display='none';" />
        </div>

        <!-- Neon Divider -->
        <img class="neon-divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:00D4FF,50:BD00FF,100:FF0080&height=4&animation=twinkling" alt="divider" onerror="this.style.display='none';" />

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

        <!-- Rest of the page is identical to your provided code -->
        <!-- ========== ABOUT ME ========== -->
        <div class="section-header">
            <img src="https://capsule-render.vercel.app/api?type=soft&color=0:050510,50:12043a,100:050510&height=60&section=header&text=🧑‍💻+ABOUT+ME&fontSize=28&fontColor=00FFFF&animation=fadeIn&fontAlignY=65" alt="About Me" style="width:100%;" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';" />
            <div class="img-fallback" style="display:none; width:100%;">🧑‍💻 ABOUT ME</div>
        </div>

        <!-- (Keep the rest of the code exactly as before, from the <div class="clearfix" ...> onward, unchanged) -->
        <!-- ... -->
