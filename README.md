── COPY FROM HERE ─────────────────────────────────────────────────────────────────────

You are a world-class GitHub Profile README designer. Read my resume below and generate
a complete, production-ready GitHub Profile README.md.

Study these profiles for design reference:
  github.com/trinib/trinib              (neon cyberpunk dynamic style)
  github.com/DenverCoder1/DenverCoder1  (typing animation + streaks)
  github.com/Platane/snk               (snake animation style)

── EXTRACT FROM RESUME ───────────────────────────────────────────────────────────────

- Full name, GitHub username, location, email, LinkedIn URL
- Role and one-line tagline
- All languages, frameworks, cloud tools, databases, DevOps tools
- Work experience: companies, roles, dates, locations, impact numbers
- Top 3 projects: name, stack, description, key metrics
- Achievements: hackathon wins, competition ranks, LeetCode stats, awards
- Education: degree, college, year, CGPA
- Hobbies or personal details

── DESIGN THEME ──────────────────────────────────────────────────────────────────────

Theme: CYBERPUNK / NEON GREEN & PURPLE
Color palette:
  Primary accent  → #00FF88  (neon green)
  Secondary accent→ #A855F7  (electric purple)
  Background      → #0a0a0a  (near black)
  Text            → #E2E8F0  (soft white)
  Highlight       → #F59E0B  (amber)

All stats cards, streak, and language cards must use:
  bg_color=0a0a0a
  title_color=00FF88
  icon_color=A855F7
  text_color=E2E8F0

── BUILD THESE 13 SECTIONS IN ORDER ─────────────────────────────────────────────────

1. HERO BANNER — use a VENOM / DRAGON wave style banner:
   https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=12,20,24
   &height=200&section=header&text=[NAME]&fontSize=48&fontColor=00FF88
   &animation=fadeIn&fontAlignY=38&desc=[TAGLINE]&descAlignY=65&descSize=18
   &descColor=A855F7

2. TYPING HEADER — 4 rotating lines, demolab.com only:
   https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=26
   &duration=2500&pause=800&color=00FF88&center=true&vCenter=true&width=800
   &lines=[LINE1];[LINE2];[LINE3];[LINE4]
   Wrap inside a centered div. Use neon-green color (00FF88).
   Encode: space=+  |=%7C  #=%23  +=%2B

3. VISITOR COUNTER + SOCIAL BADGES — all on one centered line:
   Profile views  → https://komarev.com/ghpvc/?username=[u]&label=Profile+Views&color=00FF88&style=for-the-badge
   LinkedIn badge → https://img.shields.io/badge/LinkedIn-Connect-A855F7?style=for-the-badge&logo=linkedin&logoColor=white
   LeetCode badge → https://img.shields.io/badge/LeetCode-[N]%2B_Solved-F59E0B?style=for-the-badge&logo=leetcode&logoColor=black
   Email badge    → https://img.shields.io/badge/Gmail-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white
   Use style=for-the-badge on ALL badges in this section (bigger, bolder look).

4. CODE-BLOCK ABOUT ME — write in primary language (Java / Python / JS).
   Left-align the code block. Right-align this GIF (width=360):
   <img align="right" width="360" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif"/>
   Variables: name, role, location, os, ide, stack[], currentlyLearning[], funFact, motto().
   Add a field:  String[] aiTools = {"GitHub Copilot", "Gemini AI"};

5. TECH BADGES — use style=for-the-badge (bigger than flat-square), grouped:

   ╔══ LANGUAGES ══╗
   https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
   https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
   https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black

   ╔══ FRONTEND ══╗
   https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
   https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
   https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white

   ╔══ BACKEND ══╗
   https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white
   https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white
   https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white
   https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white

   ╔══ DATABASES ══╗
   https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white
   https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white

   ╔══ TOOLS & AI ══╗
   https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white
   https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white
   https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white
   https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white
   https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white
   https://img.shields.io/badge/GitHub_Copilot-181717?style=for-the-badge&logo=github&logoColor=white
   https://img.shields.io/badge/Gemini_AI-8E75B2?style=for-the-badge&logo=google&logoColor=white
   https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white
   https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white

   Add a thin neon-green HTML divider between each category group:
   <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920"/>

6. GITHUB STATS — neon dark theme (bg_color=0a0a0a):
   https://github-readme-stats.vercel.app/api?username=[u]&show_icons=true
   &theme=radical&hide_border=true&include_all_commits=true&count_private=true
   &bg_color=0a0a0a&title_color=00FF88&icon_color=A855F7&text_color=E2E8F0&border_radius=12

7. TOP LANGUAGES — compact, same colors:
   https://github-readme-stats.vercel.app/api/top-langs/?username=[u]&layout=compact
   &theme=radical&hide_border=true&bg_color=0a0a0a&title_color=00FF88
   &text_color=E2E8F0&langs_count=8&border_radius=12
   Place Stats and Languages side-by-side in <div align="center"> with two <a> tags.

8. STREAK STATS — neon style, demolab.com only:
   https://streak-stats.demolab.com?user=[u]&theme=dark&hide_border=true
   &background=0a0a0a&ring=00FF88&fire=F59E0B&currStreakLabel=00FF88
   &sideLabels=A855F7&dates=8B949E&currStreakNum=E2E8F0&sideNums=E2E8F0
   &stroke=0a0a0a&border_radius=12
   Center it in a <div align="center">.

9. ACTIVITY GRAPH — vercel, neon:
   https://github-readme-activity-graph.vercel.app/graph?username=[u]&theme=high-contrast
   &bg_color=0a0a0a&color=00FF88&line=A855F7&point=F59E0B&area=true&hide_border=true
   Full width, centered.

10. TROPHY WALL — vercel, no-frame + no-bg:
    https://github-profile-trophy.vercel.app/?username=[u]&theme=radical
    &no-frame=true&no-bg=true&row=1&column=7&margin-w=6
    Centered.

11. WORK EXPERIENCE — collapsible <details><summary> block per role.
    Style the summary line with emoji: 🏢 Company · 💼 Role · 📅 Dates · 📍 Location
    Inside each block:
      - A blockquote listing tech used as inline code snippets: `Java` `Spring Boot` etc.
      - 3–4 bullet points with bold impact numbers.
    If no work experience: add a styled callout box (blockquote) saying they are actively
    seeking internships, with a mailto link to their email.

12. FEATURED PROJECTS — centered markdown table with emoji column headers.
    Columns: 🗂️ Project | ⚙️ Stack | 🚀 Highlights & Metrics
    One row per project. Link the project name to its repo.
    Add a "Demo" badge column using:
    https://img.shields.io/badge/Demo-Live-00FF88?style=flat-square

13. ACHIEVEMENTS — centered markdown table.
    Columns: 🏆 | Achievement | Details with exact numbers.
    Below achievements, add EDUCATION as a separate centered table:
    Columns: 🎓 Degree | 🏛️ Institution | 📅 Period | 📊 Score

    CURRENTLY LEARNING — fenced code block (no language tag so it renders plainly):
    Use arrow format → and group by topic area.

    FOOTER WAVE — venom style matching the header:
    https://capsule-render.vercel.app/api?type=venom&color=gradient
    &customColorList=12,20,24&height=140&section=footer&animation=fadeIn

── URL RULES — follow exactly ────────────────────────────────────────────────────────

Never use herokuapp.com — all Heroku free-tier URLs are permanently dead.

  Typing SVG    → readme-typing-svg.demolab.com
  Streak        → streak-stats.demolab.com
  Stats / Langs → github-readme-stats.vercel.app
  Trophies      → github-profile-trophy.vercel.app
  Activity      → github-readme-activity-graph.vercel.app
  Banner/Footer → capsule-render.vercel.app
  View counter  → komarev.com/ghpvc
  Badges        → img.shields.io

── OUTPUT RULES ──────────────────────────────────────────────────────────────────────

- Replace every [u] and [username] with the actual GitHub username from the resume.
- bg_color=0a0a0a on ALL stats cards (not 0d1117 — this theme is darker).
- Theme: radical / high-contrast / dark throughout (NOT tokyonight — different design).
- Use for-the-badge style (NOT flat-square) for all tech and social badges.
- Output full raw README.md — no code fences wrapping the output, nothing omitted.

── MY RESUME ─────────────────────────────────────────────────────────────────────────

[PASTE YOUR FULL RESUME TEXT HERE]

── END OF PROMPT ─────────────────────────────────────────────────────────────────────
