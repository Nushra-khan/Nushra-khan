<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 200" width="900" height="200">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a0f2e"/>
      <stop offset="40%" style="stop-color:#2d1b4e"/>
      <stop offset="100%" style="stop-color:#1e1535"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f4a7c3"/>
      <stop offset="50%" style="stop-color:#c9a7eb"/>
      <stop offset="100%" style="stop-color:#a0c4ff"/>
    </linearGradient>

    <!-- Flower symbol reusable -->
    <g id="fl">
      <!-- 5 petals -->
      <ellipse cx="0" cy="-4" rx="2.2" ry="4" fill="currentColor" opacity="0.9"/>
      <ellipse cx="0" cy="-4" rx="2.2" ry="4" fill="currentColor" opacity="0.9" transform="rotate(72)"/>
      <ellipse cx="0" cy="-4" rx="2.2" ry="4" fill="currentColor" opacity="0.9" transform="rotate(144)"/>
      <ellipse cx="0" cy="-4" rx="2.2" ry="4" fill="currentColor" opacity="0.9" transform="rotate(216)"/>
      <ellipse cx="0" cy="-4" rx="2.2" ry="4" fill="currentColor" opacity="0.9" transform="rotate(288)"/>
      <circle cx="0" cy="0" r="2" fill="#fff9" />
    </g>

    <!-- tiny flower -->
    <g id="fls">
      <ellipse cx="0" cy="-2.5" rx="1.4" ry="2.5" fill="currentColor" opacity="0.85"/>
      <ellipse cx="0" cy="-2.5" rx="1.4" ry="2.5" fill="currentColor" opacity="0.85" transform="rotate(72)"/>
      <ellipse cx="0" cy="-2.5" rx="1.4" ry="2.5" fill="currentColor" opacity="0.85" transform="rotate(144)"/>
      <ellipse cx="0" cy="-2.5" rx="1.4" ry="2.5" fill="currentColor" opacity="0.85" transform="rotate(216)"/>
      <ellipse cx="0" cy="-2.5" rx="1.4" ry="2.5" fill="currentColor" opacity="0.85" transform="rotate(288)"/>
      <circle cx="0" cy="0" r="1.3" fill="#fff8" />
    </g>
  </defs>

  <!-- Background -->
  <rect width="900" height="200" fill="url(#bg)"/>

  <!-- Subtle starry dots -->
  <circle cx="80" cy="30" r="0.8" fill="#c9a7eb" opacity="0.5"/>
  <circle cx="200" cy="15" r="0.6" fill="#f4a7c3" opacity="0.4"/>
  <circle cx="450" cy="10" r="0.9" fill="#a0c4ff" opacity="0.5"/>
  <circle cx="650" cy="25" r="0.7" fill="#c9a7eb" opacity="0.4"/>
  <circle cx="820" cy="18" r="0.8" fill="#f4a7c3" opacity="0.5"/>
  <circle cx="130" cy="170" r="0.7" fill="#a0c4ff" opacity="0.4"/>
  <circle cx="760" cy="180" r="0.6" fill="#c9a7eb" opacity="0.3"/>

  <!-- ======= FALLING FLOWERS ======= -->

  <!-- Row 1: scattered across top, staggered delays -->
  <g style="color:#f4a7c3"><use href="#fl" transform="translate(40,0) scale(1.1)"><animateTransform attributeName="transform" type="translate" values="40,-10; 55,210" dur="6s" repeatCount="indefinite" begin="0s"/><animate attributeName="opacity" values="0;1;1;0" dur="6s" repeatCount="indefinite" begin="0s"/></use></g>

  <g style="color:#c9a7eb"><use href="#fls" transform="translate(90,0)"><animateTransform attributeName="transform" type="translate" values="90,-8; 80,210" dur="5s" repeatCount="indefinite" begin="1.2s"/><animate attributeName="opacity" values="0;1;1;0" dur="5s" repeatCount="indefinite" begin="1.2s"/></use></g>

  <g style="color:#f7cfe8"><use href="#fl" transform="translate(160,0)"><animateTransform attributeName="transform" type="translate" values="160,-10; 175,210" dur="7s" repeatCount="indefinite" begin="0.5s"/><animate attributeName="opacity" values="0;1;1;0" dur="7s" repeatCount="indefinite" begin="0.5s"/></use></g>

  <g style="color:#a0c4ff"><use href="#fls" transform="translate(240,0)"><animateTransform attributeName="transform" type="translate" values="240,-8; 230,210" dur="4.5s" repeatCount="indefinite" begin="2s"/><animate attributeName="opacity" values="0;1;1;0" dur="4.5s" repeatCount="indefinite" begin="2s"/></use></g>

  <g style="color:#e8b4d8"><use href="#fl" transform="translate(310,0)"><animateTransform attributeName="transform" type="translate" values="310,-10; 320,210" dur="6.5s" repeatCount="indefinite" begin="0.8s"/><animate attributeName="opacity" values="0;1;1;0" dur="6.5s" repeatCount="indefinite" begin="0.8s"/></use></g>

  <g style="color:#c9a7eb"><use href="#fl" transform="translate(390,0)"><animateTransform attributeName="transform" type="translate" values="390,-12; 378,210" dur="5.8s" repeatCount="indefinite" begin="1.8s"/><animate attributeName="opacity" values="0;1;1;0" dur="5.8s" repeatCount="indefinite" begin="1.8s"/></use></g>

  <g style="color:#f4a7c3"><use href="#fls" transform="translate(460,0)"><animateTransform attributeName="transform" type="translate" values="460,-8; 472,210" dur="5s" repeatCount="indefinite" begin="3s"/><animate attributeName="opacity" values="0;1;1;0" dur="5s" repeatCount="indefinite" begin="3s"/></use></g>

  <g style="color:#b8d4ff"><use href="#fl" transform="translate(530,0)"><animateTransform attributeName="transform" type="translate" values="530,-10; 518,210" dur="6.2s" repeatCount="indefinite" begin="0.3s"/><animate attributeName="opacity" values="0;1;1;0" dur="6.2s" repeatCount="indefinite" begin="0.3s"/></use></g>

  <g style="color:#f4a7c3"><use href="#fl" transform="translate(600,0)"><animateTransform attributeName="transform" type="translate" values="600,-10; 612,210" dur="7.2s" repeatCount="indefinite" begin="1s"/><animate attributeName="opacity" values="0;1;1;0" dur="7.2s" repeatCount="indefinite" begin="1s"/></use></g>

  <g style="color:#d4b3f0"><use href="#fls" transform="translate(670,0)"><animateTransform attributeName="transform" type="translate" values="670,-8; 660,210" dur="4.8s" repeatCount="indefinite" begin="2.5s"/><animate attributeName="opacity" values="0;1;1;0" dur="4.8s" repeatCount="indefinite" begin="2.5s"/></use></g>

  <g style="color:#f9d5e8"><use href="#fl" transform="translate(740,0)"><animateTransform attributeName="transform" type="translate" values="740,-10; 753,210" dur="6s" repeatCount="indefinite" begin="0.7s"/><animate attributeName="opacity" values="0;1;1;0" dur="6s" repeatCount="indefinite" begin="0.7s"/></use></g>

  <g style="color:#a0c4ff"><use href="#fls" transform="translate(810,0)"><animateTransform attributeName="transform" type="translate" values="810,-8; 800,210" dur="5.5s" repeatCount="indefinite" begin="1.5s"/><animate attributeName="opacity" values="0;1;1;0" dur="5.5s" repeatCount="indefinite" begin="1.5s"/></use></g>

  <g style="color:#e8c4f0"><use href="#fl" transform="translate(870,0)"><animateTransform attributeName="transform" type="translate" values="870,-10; 858,210" dur="6.8s" repeatCount="indefinite" begin="2.2s"/><animate attributeName="opacity" values="0;1;1;0" dur="6.8s" repeatCount="indefinite" begin="2.2s"/></use></g>

  <!-- Extra mid-drift flowers for density -->
  <g style="color:#c9a7eb"><use href="#fls"><animateTransform attributeName="transform" type="translate" values="115,-8; 125,210" dur="5.3s" repeatCount="indefinite" begin="3.5s"/><animate attributeName="opacity" values="0;1;1;0" dur="5.3s" repeatCount="indefinite" begin="3.5s"/></use></g>

  <g style="color:#f4a7c3"><use href="#fls"><animateTransform attributeName="transform" type="translate" values="280,-8; 268,210" dur="4.7s" repeatCount="indefinite" begin="4s"/><animate attributeName="opacity" values="0;1;1;0" dur="4.7s" repeatCount="indefinite" begin="4s"/></use></g>

  <g style="color:#b8d4ff"><use href="#fls"><animateTransform attributeName="transform" type="translate" values="490,-8; 502,210" dur="5.1s" repeatCount="indefinite" begin="0.1s"/><animate attributeName="opacity" values="0;1;1;0" dur="5.1s" repeatCount="indefinite" begin="0.1s"/></use></g>

  <g style="color:#e8b4d8"><use href="#fls"><animateTransform attributeName="transform" type="translate" values="700,-8; 690,210" dur="6.3s" repeatCount="indefinite" begin="1.3s"/><animate attributeName="opacity" values="0;1;1;0" dur="6.3s" repeatCount="indefinite" begin="1.3s"/></use></g>

  <!-- ======= TEXT ======= -->

  <!-- Name -->
  <text x="450" y="95" text-anchor="middle"
    font-family="Georgia, 'Times New Roman', serif"
    font-size="42" font-style="italic" font-weight="bold"
    fill="url(#textGrad)" letter-spacing="2">
    hey, I'm [Nushra] ✦
  </text>

  <!-- Subtitle -->
  <text x="450" y="128" text-anchor="middle"
    font-family="'Courier New', monospace"
    font-size="13" fill="#c9a7eb" letter-spacing="4" opacity="0.85">
    building things that matter · one model at a time
  </text>

  <!-- Soft glow pulse under text -->
  <ellipse cx="450" cy="108" rx="280" ry="35" fill="#c9a7eb" opacity="0">
    <animate attributeName="opacity" values="0;0.04;0" dur="4s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Bottom fade -->
  <defs>
    <linearGradient id="fade" x1="0" y1="0" x2="0" y2="1">
      <stop offset="60%" stop-color="transparent"/>
      <stop offset="100%" stop-color="#1a0f2e"/>
    </linearGradient>
  </defs>
  <rect width="900" height="200" fill="url(#fade)" opacity="0.5"/>
</svg>

<div align="center">

<!-- ╔══════════════════════════════════════════╗ -->
<!--        PASTE THIS INTO YOUR PROFILE REPO    -->
<!--   Replace: yourusername · YourName · links  -->
<!-- ╚══════════════════════════════════════════╝ -->

<!-- ✦ BANNER ✦ -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=0,15,19,23&height=200&section=header&text=hey%2C%20I%27m%20YourName%20%E2%9C%A6&fontSize=42&fontAlignY=45&fontColor=f9d5e8&desc=building%20things%20that%20matter%20%C2%B7%20one%20model%20at%20a%20time&descAlignY=68&descSize=15&descColor=c9a7eb&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=DM+Serif+Display&size=20&pause=1000&color=C9A7EB&center=true&vCenter=true&width=600&lines=AI+%26+ML+Engineer+in+the+making+%E2%9C%A8;Mental+Health+Tech+Advocate+%F0%9F%A9B;Turning+data+into+decisions%2C+quietly.;Building+BEACON+%E2%80%94+one+prompt+at+a+time.)](https://git.io/typing-svg)

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## `✦ about me`

```python
class YourName:
    def __init__(self):
        self.role        = "CS Engineering Student"
        self.focus       = ["AI", "ML", "Mental Health Tech"]
        self.currently   = "Building BEACON — an AI wellness chatbot 🤍"
        self.learning    = ["MLOps", "LLM Fine-tuning", "Prompt Engineering"]
        self.loves       = ["impactful products", "clean code", "iced coffee ☕"]
        self.believe_in  = "Technology should care about people first."

    def say_hello(self):
        return "Let's build something meaningful ✦"
```

> *I believe the most powerful code is the kind that quietly changes someone's day for the better.*

<br/>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## `✦ tech stack`

<div align="center">

**✦ Languages**

![Python](https://img.shields.io/badge/Python-f2c6de?style=for-the-badge&logo=python&logoColor=7c5cbf)
![Java](https://img.shields.io/badge/Java-d4c1f9?style=for-the-badge&logo=openjdk&logoColor=5c4a8a)
![C++](https://img.shields.io/badge/C++-c5d8f7?style=for-the-badge&logo=cplusplus&logoColor=3a6fa8)

**✦ AI / ML**

![TensorFlow](https://img.shields.io/badge/TensorFlow-f2c6de?style=for-the-badge&logo=tensorflow&logoColor=7c5cbf)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-d4c1f9?style=for-the-badge&logo=scikit-learn&logoColor=5c4a8a)
![Pandas](https://img.shields.io/badge/Pandas-c5d8f7?style=for-the-badge&logo=pandas&logoColor=3a6fa8)
![NumPy](https://img.shields.io/badge/NumPy-fde8f5?style=for-the-badge&logo=numpy&logoColor=7c5cbf)
![HuggingFace](https://img.shields.io/badge/HuggingFace-f2c6de?style=for-the-badge&logo=huggingface&logoColor=7c5cbf)

**✦ Tools & Workflow**

![Git](https://img.shields.io/badge/Git-d4c1f9?style=for-the-badge&logo=git&logoColor=5c4a8a)
![GitHub](https://img.shields.io/badge/GitHub-c5d8f7?style=for-the-badge&logo=github&logoColor=3a6fa8)
![Jupyter](https://img.shields.io/badge/Jupyter-fde8f5?style=for-the-badge&logo=jupyter&logoColor=7c5cbf)
![VS Code](https://img.shields.io/badge/VSCode-f2c6de?style=for-the-badge&logo=visualstudiocode&logoColor=5c4a8a)

</div>

<br/>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## `✦ projects`

<div align="center">

### 🤍 &nbsp; BEACON &nbsp; — &nbsp; *flagship project*

</div>

```
┌─────────────────────────────────────────────────────────────────┐
│  ✦  BEACON  ·  AI-Powered Student Wellness Chatbot              │
│─────────────────────────────────────────────────────────────────│
│  Mental health support meets academic guidance, thoughtfully    │
│  designed for students navigating pressure, burnout & anxiety.  │
│                                                                 │
│  ◦ PHQ-9 based adaptive depression screening                    │
│  ◦ Personalized, empathetic conversational AI                   │
│  ◦ Academic support + wellness resources in one interface       │
│  ◦ Built with: Python · NLP · Prompt Engineering · ML          │
└─────────────────────────────────────────────────────────────────┘
```

<div align="center">

[![BEACON](https://img.shields.io/badge/✦%20View%20BEACON-d4c1f9?style=for-the-badge&logo=github&logoColor=5c4a8a)](https://github.com/yourusername/BEACON)

</div>

<br/>

| Project | Description | Tech |
|:---|:---|:---|
| 🚕 **Taxi Demand Predictor** | ML model forecasting urban cab demand patterns | `Python` `Scikit-learn` `Pandas` |
| 💬 **PHQ-9 Chatbot** | Adaptive chatbot for mental health self-screening | `Python` `NLP` `ML` |

<br/>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## `✦ github stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&bg_color=fdf0f8&title_color=c9a7eb&icon_color=f4a7c3&text_color=7c5cbf&border_color=e8d5f5&border_radius=16" height="165"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&bg_color=fdf0f8&title_color=c9a7eb&text_color=7c5cbf&border_color=e8d5f5&border_radius=16" height="165"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=yourusername&background=fdf0f8&stroke=e8d5f5&ring=c9a7eb&fire=f4a7c3&currStreakNum=7c5cbf&sideNums=7c5cbf&currStreakLabel=c9a7eb&sideLabels=c9a7eb&dates=b0a0cc&border_radius=16" />

</div>

<br/>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## `✦ fun facts`

```
  ✦  I debug by explaining the problem to my coffee mug first.
  ✦  My first ML model had 94% accuracy and 0% real-world sense.
  ✦  I name my models — BEACON was not my first idea, but it was the right one.
  ✦  I think DSA is like solving puzzles you didn't ask for but secretly enjoy.
  ✦  I believe AI should be empathetic, not just efficient.
```

<br/>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## `✦ a thought`

<div align="center">

<br/>

*"The world doesn't need more cold, clever systems.*
*It needs ones built with care — quietly, precisely, and with people at the center."*

<br/>

```
  — something I tell myself before every commit ✦
```

<br/>
</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## `✦ find me`

<div align="center">

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-d4c1f9?style=for-the-badge&logo=linkedin&logoColor=5c4a8a)](https://linkedin.com/in/yourprofile)
[![GitHub](https://img.shields.io/badge/GitHub-c5d8f7?style=for-the-badge&logo=github&logoColor=3a6fa8)](https://github.com/yourusername)
[![Email](https://img.shields.io/badge/Email-f2c6de?style=for-the-badge&logo=gmail&logoColor=7c5cbf)](mailto:youremail@example.com)

<br/>

```
  ✦  open to collaborations · internships · research  ✦
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,15,19,23&height=100&section=footer" width="100%"/>

</div>
