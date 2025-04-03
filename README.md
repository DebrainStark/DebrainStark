<!-- HEADER -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320">
  <!-- Gradient Background -->
  <defs>
    <linearGradient id="headerGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1a2a6c" />
      <stop offset="33%" stop-color="#b21f1f" />
      <stop offset="67%" stop-color="#4B1248" />
      <stop offset="100%" stop-color="#0f0c29" />
    </linearGradient>
    
    <!-- Wave Pattern -->
    <clipPath id="waveClip">
      <path d="M0,160 
             C150,200 300,120 450,160 
             C600,200 750,120 900,160 
             C1050,200 1200,120 1350,160 
             L1350,320 L0,320 Z" />
    </clipPath>
    
    <!-- Animated dots pattern -->
    <pattern id="dotPattern" width="20" height="20" patternUnits="userSpaceOnUse">
      <circle cx="10" cy="10" r="1.5" fill="rgba(255,255,255,0.5)">
        <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3s" repeatCount="indefinite" />
      </circle>
    </pattern>
  </defs>
  
  <!-- Background Rectangle -->
  <rect width="1200" height="320" fill="url(#headerGradient)" />
  
  <!-- Dots overlay -->
  <rect width="1200" height="320" fill="url(#dotPattern)" opacity="0.3" />
  
  <!-- Wave Pattern -->
  <g clip-path="url(#waveClip)">
    <rect x="0" y="160" width="1200" height="160" fill="rgba(0,0,0,0.2)" />
    <path d="M0,200 
           C150,240 300,180 450,220 
           C600,260 750,180 900,220 
           C1050,260 1200,180 1350,220 
           L1350,320 L0,320 Z" 
          fill="rgba(255,255,255,0.1)" />
  </g>
  
  <!-- Main Title with animation -->
  <g>
    <text x="600" y="130" font-family="Arial, sans-serif" font-weight="900" font-size="80" text-anchor="middle" fill="white" letter-spacing="2">
      DEBRAIN STARK
      <animate attributeName="y" values="140;130;140" dur="5s" repeatCount="indefinite" />
    </text>
    <!-- Subtle shadow for depth -->
    <text x="603" y="133" font-family="Arial, sans-serif" font-weight="900" font-size="80" text-anchor="middle" fill="rgba(0,0,0,0.3)" letter-spacing="2">
      DEBRAIN STARK
      <animate attributeName="y" values="143;133;143" dur="5s" repeatCount="indefinite" />
    </text>
  </g>
  
  <!-- Tagline -->
  <g>
    <rect x="425" y="185" width="350" height="40" rx="20" fill="rgba(0,0,0,0.5)" />
    <text x="600" y="212" font-family="Consolas, monospace" font-size="20" text-anchor="middle" fill="white" letter-spacing="1.5">
      &lt; CODE / DESIGN / CREATE &gt;
    </text>
  </g>
  
  <!-- Decorative elements -->
  <!-- Left side code brackets -->
  <text x="190" y="130" font-family="Consolas, monospace" font-size="40" fill="rgba(255,255,255,0.2)" text-anchor="end">{</text>
  <text x="170" y="170" font-family="Consolas, monospace" font-size="40" fill="rgba(255,255,255,0.2)" text-anchor="end">}</text>
  <!-- Right side code brackets -->
  <text x="1010" y="130" font-family="Consolas, monospace" font-size="40" fill="rgba(255,255,255,0.2)">{</text>
  <text x="1030" y="170" font-family="Consolas, monospace" font-size="40" fill="rgba(255,255,255,0.2)">}</text>
  
  <!-- Decorative lines -->
  <line x1="300" y1="270" x2="900" y2="270" stroke="rgba(255,255,255,0.3)" stroke-width="1" stroke-dasharray="5,5" />
  <line x1="350" y1="280" x2="850" y2="280" stroke="rgba(255,255,255,0.2)" stroke-width="1" stroke-dasharray="3,3" />
</svg>

<!-- CONNECT BADGES -->
<div align="center">
  <a href="https://github.com/DebrainStark">
    <img src="https://img.shields.io/github/followers/DebrainStark?style=for-the-badge&logo=github&labelColor=191825&color=E384FF&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://twitter.com/DebrainStark">
    <img src="https://img.shields.io/badge/Twitter-follow-191825?style=for-the-badge&logo=twitter&labelColor=191825&color=E384FF&logoColor=white" alt="Twitter" />
  </a>
  <a href="https://www.linkedin.com/in/debrain-stark/">
    <img src="https://img.shields.io/badge/LinkedIn-connect-191825?style=for-the-badge&logo=linkedin&labelColor=191825&color=E384FF&logoColor=white" alt="LinkedIn" />
  </a>
</div>

<!-- ANIMATED GREETING -->
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=E384FF&center=true&vCenter=true&random=false&width=435&lines=Hello+There!+%F0%9F%91%8B;I'm+Debrain+Stark;AI+%26+Web+Developer;Problem+Solver;Open+Source+Enthusiast" alt="Typing SVG" />
</h1>

<!-- ABOUT ME SECTION -->
<div align="center">
  <h1>👨‍💻 About Me</h1>
  <table border="0">
    <tr>
      <td width="50%">
        <h3>Digital Problem Solver</h3>
        <p>
          I translate caffeine into code and turn complex problems into elegant solutions. With a background in AI and web development, I create tools that make a difference.
        </p>
        <p>
          When I'm not optimizing algorithms or designing interfaces, you'll find me exploring new technologies and contributing to open-source projects that push the boundaries of what's possible.
        </p>
      </td>
      <td width="50%" align="center">
        <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%" alt="Coding GIF" />
      </td>
    </tr>
  </table>
</div>

<!-- CODE BLOCK -->
```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-

class TechWizard:
    def __init__(self):
        self.name = "Debrain Stark"
        self.stack = {
            "frontend": ["React", "TypeScript", "Tailwind CSS"],
            "backend": ["Python", "Node.js", "Express"],
            "ai": ["TensorFlow", "PyTorch", "NLP"],
            "devops": ["Docker", "AWS", "CI/CD"],
        }
        self.current_focus = ["Building AI tools", "Web3 development"]
        self.coffee_level = 80  # percent
        
    def need_coffee(self):
        return self.coffee_level < 30
        
    def solve_problem(self, complexity):
        self.coffee_level -= complexity * 0.1
        
        if self.need_coffee():
            self.refill_coffee()
            
        return "Solution found! 🚀"
            
    def refill_coffee(self):
        self.coffee_level = 100
        print("Coffee refilled. Ready to code again!")

# Initialize me
me = TechWizard()
```

<!-- SKILLS SECTION -->
<div align="center">
  <h1>⚡ Technologies</h1>
  
  <h3>Languages</h3>
  <img src="https://skillicons.dev/icons?i=js,ts,python,java,cpp&perline=5" alt="Languages" />
  
  <h3>Frontend</h3>
  <img src="https://skillicons.dev/icons?i=react,vue,angular,html,css,tailwind,bootstrap&perline=7" alt="Frontend" />
  
  <h3>Backend & Database</h3>
  <img src="https://skillicons.dev/icons?i=nodejs,express,django,flask,graphql,mongodb,postgres,mysql&perline=8" alt="Backend" />
  
  <h3>AI & ML</h3>
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch&perline=5" alt="AI & ML" />
  <img src="https://img.shields.io/badge/NLP-E384FF?style=for-the-badge&labelColor=191825" alt="NLP" />
  <img src="https://img.shields.io/badge/Computer_Vision-E384FF?style=for-the-badge&labelColor=191825" alt="Computer Vision" />
  
  <h3>DevOps & Tools</h3>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,git,github,vscode,vim&perline=7" alt="DevOps & Tools" />
</div>

<!-- GITHUB STATS SECTION -->
<div align="center">
  <h1>📊 GitHub Stats</h1>
  
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DebrainStark&theme=midnight-purple&hide_border=true&background=0D1117&stroke=E384FF&fire=E384FF&currStreakLabel=E384FF&ring=E384FF&sideLabels=E384FF&dates=888888" width="49%" alt="GitHub Streak" />
  
  <img src="https://github-readme-stats.vercel.app/api?username=DebrainStark&show_icons=true&include_all_commits=true&hide_border=true&theme=transparent&title_color=E384FF&text_color=FFFFFF&icon_color=E384FF&hide=contribs" width="49%" alt="GitHub Stats" />
  
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DebrainStark&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=E384FF&text_color=FFFFFF" width="49%" alt="Top Languages" />
  
  <img src="https://github-profile-trophy.vercel.app/?username=DebrainStark&theme=discord&no-frame=true&no-bg=true&column=7" width="98%" alt="GitHub Trophy" />
</div>

<!-- CONTRIBUTION GRAPH -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=DebrainStark&bg_color=0D1117&color=E384FF&line=E384FF&point=FFFFFF&area=true&hide_border=true" width="100%" alt="Activity Graph" />

<!-- SNAKE CONTRIBUTION ANIMATION -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DebrainStark/DebrainStark/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DebrainStark/DebrainStark/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub Snake Animation" src="https://raw.githubusercontent.com/DebrainStark/DebrainStark/output/github-contribution-grid-snake-dark.svg" />
</picture>

<!-- PROJECTS SECTION -->
<div align="center">
  <h1>🚀 Featured Projects</h1>
  
  <a href="https://github.com/DebrainStark/ai-chatbot-framework">
    <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=DebrainStark&repo=ai-chatbot-framework&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=E384FF&icon_color=E384FF&text_color=FFFFFF" />
  </a>
  <a href="https://github.com/DebrainStark/nlp-toolkit">
    <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=DebrainStark&repo=nlp-toolkit&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=E384FF&icon_color=E384FF&text_color=FFFFFF" />
  </a>
  <a href="https://github.com/DebrainStark/web3-marketplace">
    <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=DebrainStark&repo=web3-marketplace&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=E384FF&icon_color=E384FF&text_color=FFFFFF" />
  </a>
  <a href="https://github.com/DebrainStark/react-component-library">
    <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=DebrainStark&repo=react-component-library&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=E384FF&icon_color=E384FF&text_color=FFFFFF" />
  </a>
</div>

<!-- CURRENT FOCUS -->
<div align="center">
  <h1>🔭 Current Focus</h1>
  
  <table border="0">
    <tr>
      <td width="50%" align="center">
        <h3>AI Systems</h3>
        <img src="https://img.icons8.com/fluency/96/000000/artificial-intelligence.png" alt="AI Systems" />
        <p>Developing conversational AI with human-like understanding</p>
      </td>
      <td width="50%" align="center">
        <h3>Web Applications</h3>
        <img src="https://img.icons8.com/fluency/96/000000/web-design.png" alt="Web Applications" />
        <p>Building responsive and intuitive interfaces with modern frameworks</p>
      </td>
    </tr>
    <tr>
      <td width="50%" align="center">
        <h3>NLP Research</h3>
        <img src="https://img.icons8.com/fluency/96/000000/mind-map.png" alt="NLP Research" />
        <p>Exploring cutting-edge natural language processing techniques</p>
      </td>
      <td width="50%" align="center">
        <h3>Open Source</h3>
        <img src="https://img.icons8.com/fluency/96/000000/open-source.png" alt="Open Source" />
        <p>Contributing to projects that drive innovation in the developer community</p>
      </td>
    </tr>
  </table>
</div>

<!-- BLOG POSTS SECTION -->
<div align="center">
  <h1>📝 Latest Blog Posts</h1>
  
  <!-- BLOG-POST-LIST:START -->
  <!-- This section will be automatically populated by a GitHub Action -->
  <!-- BLOG-POST-LIST:END -->
</div>

<!-- CONTACT SECTION -->
<div align="center">
  <h1>📫 Connect With Me</h1>
  
  <a href="https://twitter.com/DebrainStark">
    <img src="https://img.shields.io/badge/Twitter-191825?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
  </a>
  <a href="https://linkedin.com/in/debrain-stark">
    <img src="https://img.shields.io/badge/LinkedIn-191825?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:contact@debrainstark.dev">
    <img src="https://img.shields.io/badge/Email-191825?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://debrainstark.dev">
    <img src="https://img.shields.io/badge/Portfolio-191825?style=for-the-badge&logo=react&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://calendly.com/debrainstark">
    <img src="https://img.shields.io/badge/Schedule_Call-191825?style=for-the-badge&logo=google-calendar&logoColor=white" alt="Calendly" />
  </a>
  
  <br><br>
  <img src="https://komarev.com/ghpvc/?username=DebrainStark&style=for-the-badge&color=E384FF" alt="Profile Views" />
</div>

<!-- SUPPORT SECTION -->
<div align="center">
  <h1>☕ Support My Work</h1>
  
  <a href="https://www.buymeacoffee.com/debrainstark">
    <img src="https://img.shields.io/badge/Buy_Me_A_Coffee-191825?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" alt="Buy Me A Coffee" />
  </a>
  <a href="https://github.com/sponsors/DebrainStark">
    <img src="https://img.shields.io/badge/GitHub_Sponsors-191825?style=for-the-badge&logo=github-sponsors&logoColor=white" alt="GitHub Sponsors" />
  </a>
</div>

<!-- FOOTER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&customColorList=12,21,28,16,6&section=footer&reversal=true&textBg=false&fontColor=FFFFFF&fontSize=50&animation=fadeIn" />
