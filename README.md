# 👋 Hi, I'm Noella — I build things that work

💡 *From data pipelines to web apps, from embedded hardware to playful games — I like turning ideas into projects you can actually run.*

<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Hey%20There!%20I'm%20Noella%20%E2%9C%A8&animation=fadeIn&type=waving&color=gradient&height=120&fontColor=ffffff" alt="wavy header"/>
</p>

---

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=F75C7E&center=false&vCenter=false&width=600&lines=Data+Scientist+%F0%9F%93%8A;Software+Engineer+%F0%9F%92%BB;Game+Builder+%F0%9F%8E%AE;Always+Learning+%F0%9F%92%A1)

---

## ✨ About this Profile
- Organized in **three tracks** (Data, Software/Hardware, Games).
- Uses **badges, emojis, visuals, and dynamic widgets** for both tech & non-tech audiences.
- Repos are being rebuilt with clear READMEs, demos, and graphics.

<p>
  <a href="https://www.linkedin.com/in/noellabuti/"><img height="28" src="https://img.shields.io/badge/LinkedIn-Noella%20Buti-F75C7E?logo=linkedin&logoColor=white" /></a>
  <a href="mailto:noellabuti@gmail.com"><img height="28" src="https://img.shields.io/badge/Email-noellabuti%40gmail.com-1ABC9C?logo=gmail&logoColor=white" /></a>
</p>

![Profile Views](https://komarev.com/ghpvc/?username=NoellaButi&style=flat-square&color=1ABC9C)

---

# 📊 DATA SCIENCE & AI
```ansi
██╗  ██╗███████╗ █████╗ ███╗   ███╗███████╗
██║  ██║██╔════╝██╔══██╗████╗ ████║██╔════╝
███████║█████╗  ███████║██╔████╔██║█████╗  
██╔══██║██╔══╝  ██╔══██║██║╚██╔╝██║██╔══╝  
██║  ██║███████╗██║  ██║██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝
Project	What it Does	Tools	Demo
Laptop Price Prediction	Predict laptop prices with RF/GB (R² ≈ 0.84)	Python, Pandas, scikit-learn	
Census Income (ID3)	Decision tree from scratch (entropy/info gain, pruning)	Python	
Anime Story Generation	Prompt→Synopsis with LSTM/GPT-2	Python, TensorFlow, Hugging Face	

💻 SOFTWARE & HARDWARE
```ansi
Copy code
███████╗ ██████╗  ██████╗ ██████╗ ██╗    ██╗███████╗██████╗ 
██╔════╝██╔═══██╗██╔════╝██╔═══██╗██║    ██║██╔════╝██╔══██╗
███████╗██║   ██║██║     ██║   ██║██║ █╗ ██║█████╗  ██████╔╝
╚════██║██║   ██║██║     ██║   ██║██║███╗██║██╔══╝  ██╔══██╗
███████║╚██████╔╝╚██████╗╚██████╔╝╚███╔███╔╝███████╗██║  ██║
╚══════╝ ╚═════╝  ╚═════╝ ╚═════╝  ╚══╝╚══╝ ╚══════╝╚═╝  ╚═╝
Project	What it Does	Tools	Demo
Lisanga Web App	Flask demo tying UI to ML logic	Python, Flask, HTML/CSS	
Arduino LCD Game	Inputs + LCD display + loop logic	Arduino, C++	
Assembly Menu Program	Interactive menu system at low-level	Assembly (NASM)	

🎮 GAMES & GRAPHICS
ansi
Copy code
 ██████╗  █████╗ ███╗   ███╗███████╗    ██████╗  █████╗ ███╗   ███╗███████╗
██╔════╝ ██╔══██╗████╗ ████║██╔════╝    ██╔══██╗██╔══██╗████╗ ████║██╔════╝
██║  ███╗███████║██╔████╔██║█████╗      ██████╔╝███████║██╔████╔██║█████╗  
██║   ██║██╔══██║██║╚██╔╝██║██╔══╝      ██╔═══╝ ██╔══██║██║╚██╔╝██║██╔══╝  
╚██████╔╝██║  ██║██║ ╚═╝ ██║███████╗    ██║     ██║  ██║██║ ╚═╝ ██║███████╗
 ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝    ╚═╝     ╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝
Project	What it Does	Tools	Demo
Unity 2D Mini Game	Movement, physics, enemy AI, scene loading	Unity (C#)	
LED Patterns	Fun interactive hardware with patterns & timing	Arduino	

🔧 How I Build
Simple first. Baselines before fancy; tight loops.

Reproducible. Lockfiles, seeds, versioned configs.

Metric-driven. Accuracy, FPS, latency, memory use.

Readable. Docs + comments where it matters.

Tested. Unit tests, lightweight CI.

Responsible. Clear about limits & assumptions.

🛠️ Tech I Use

🌈 Dynamic & Fun
⏳ Typing banner (above) shows rotating roles.

🏆 GitHub Trophy


📈 GitHub Stats + Streaks



🐍 Contribution Snake (auto-updates)



<details> <summary><strong>Enable the Snake + Activity Feed (optional)</strong></summary>
Create a file at .github/workflows/profile.yml in your profile repo with:

yaml
Copy code
name: Profile Automations
on:
  schedule:
    - cron: "0 */12 * * *"  # every 12 hours
  workflow_dispatch:

jobs:
  snake:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        with:
          github_user_name: NoellaButi
          outputs: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  activity:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: Readme-Workflows/recent-activity@v2
        with:
          GH_USERNAME: NoellaButi
          MAX_LINES: 5
Then add this line to your README where you want the snake to appear (already placed above):

md
Copy code
![Snake animation](https://github.com/NoellaButi/NoellaButi/blob/output/github-contribution-grid-snake.svg)
</details>
🎶 Now Playing on Spotify (optional)

<sub>Set up a tiny Vercel serverless function and embed the card. We can wire this later.</sub>

🔮 Next Builds Roadmap → Anime recommender, Unity multiplayer prototype, Energy viz dashboard.

🚀 Explore
For ML: open notebooks/ or run python -m src.models.train.

For web apps: see /api docs + docker-compose up.

For games: open Unity project and press Play.

For hardware: wiring diagrams + demo GIFs in repo.

📬 Contact
LinkedIn: linkedin.com/in/noellabuti

Email: noellabuti@gmail.com
