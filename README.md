<!-- Header -->
<p align="center">
  <img src="assets/header.svg" alt="Omar Faruk · Computer Science & Engineering · BRAC University" width="100%">
</p>

<p align="center">
  <a href="https://github.com/Omar136796">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=22D3EE&center=true&vCenter=true&width=720&lines=Final-year+CSE+student+%40+BRAC+University;CGPA+3.98+%2F+4.00+%C2%B7+Student+Tutor+for+Discrete+Maths;Thesis%3A+attacking+and+defending+LLMs;Full-stack+%C2%B7+AI%2FML+%C2%B7+Systems+%C2%B7+Embedded;Currently+learning+Data+Analysis" alt="Typing intro">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Dhaka,_Bangladesh-0E7490?style=flat-square&logo=googlemaps&logoColor=white" alt="Location">
  <a href="mailto:omar136796@gmail.com"><img src="https://img.shields.io/badge/omar136796@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://omar136796.github.io"><img src="https://img.shields.io/badge/Portfolio-omar136796.github.io-0E7490?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.facebook.com/Omar136796"><img src="https://img.shields.io/badge/Facebook-Omar136796-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="Facebook"></a>
  <img src="https://img.shields.io/badge/Graduating-January_2027-22D3EE?style=flat-square&logo=bookstack&logoColor=white" alt="Graduating January 2027">
  <img src="https://komarev.com/ghpvc/?username=Omar136796&style=flat-square&color=0E7490&label=Profile+views" alt="Profile views">
</p>

---

## 👋 About me

```python
class OmarFaruk:
    university   = "BRAC University, Dhaka"
    degree       = "B.Sc. in Computer Science and Engineering"
    status       = "12th (final) semester, graduating January 2027"
    cgpa         = 3.98                       # out of 4.00
    teaching     = "Student Tutor, CSE230: Discrete Mathematics (Fall 2026)"
    research     = "LLM security: copyright extraction attacks and machine unlearning"
    builds_with  = ["Python", "C", "C++", "Java", "JavaScript", "PHP", "SQL", "Verilog", "8086 Assembly"]
    explores     = ["AI/ML and LLMs", "Full-stack web", "Systems programming", "Embedded and robotics", "Networks"]
    learning_now = ["Excel", "Power BI", "MySQL", "Python for data analysis"]
    off_screen   = ["🎬 movies", "🍥 anime", "🏏 cricket", "⚽ football", "🧳 travelling"]
```

- 🔬 **Researching** how large language models leak memorised, copyrighted text, and how to make them *forget* it reliably
- 🧑‍🏫 **Teaching** Discrete Mathematics to juniors as a Student Tutor. Explaining things simply is my favourite part of learning
- 🛠️ **Building** across the stack: from AI web platforms and 3D games down to shells, file systems, assembly, VLSI and robots
- 📊 **Learning** data analysis with Excel, Power BI, SQL and Python

---

## 🔬 Current research: undergraduate thesis

> ### ATTACK ON LLMS: Mitigating LLM Vulnerabilities in Intellectual Property Applications
> 🏅 **5th place, CSE Thesis Poster Exhibition, Fall 2026**, BRAC University (a curated final exhibition of the best posters from the last two semesters)

LLMs trained on web-scale data can memorise copyrighted text word for word, and clever prompts (role-play, prefilling, multi-turn and more) can make them reproduce it. *Machine unlearning* is meant to remove that knowledge, but it is usually tested only with polite, ordinary questions.

We propose **Adversarial Forget-Set Augmentation (AFSA)**. It takes the jailbreak prompts that actually succeed in extracting text, pairs them with refusals, and adds them to the unlearning objective (OBLIVIATE). The goal is a model that forgets *both* the protected text *and* the attack paths to it, without losing general ability.

- 🧪 A deliberately memorising **Llama-3.1-8B-Instruct + QLoRA** model, attacked with **2,110 frozen prompts across 17 jailbreak templates**
- 📈 Pre-thesis results: the model recalls 95% of passages from the start of a chapter. About **1 in 5 attack prompts extract 50+ verbatim tokens**, and only 3% of attacks are refused.
- 👥 Team of 4 · Supervisor: Dr. Farig Yousuf Sadeque · Co-supervisor: Ariyan Hossain

<details>
<summary><b>🖼️ View the award-winning poster</b></summary>
<br>
<img src="assets/thesis_poster.jpg" alt="Thesis poster: ATTACK ON LLMS" width="100%">
</details>

---

## 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Mahidad/chhaya"><img src="assets/chhaya.jpg" alt="Chhaya"></a>
      <h3><a href="https://github.com/Mahidad/chhaya">🎙️ Chhaya: learn in your favourite teacher's style</a></h3>
      AI learning platform that pulls a teacher's <i>teaching style</i> out of YouTube lectures and uses it to teach new topics. <b>I built</b> exam-paper OCR, AI prediction of likely exam questions, and study groups with group chat. Deployed on Vercel and Render.<br><br>
      <code>FastAPI</code> <code>React</code> <code>PostgreSQL</code> <code>Gemini</code> <code>OCR.Space</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/amiyo-bhowmik/ThesisConnect"><img src="assets/thesisconnect.jpg" alt="ThesisConnect"></a>
      <h3><a href="https://github.com/amiyo-bhowmik/ThesisConnect">🎓 ThesisConnect: find your thesis team</a></h3>
      A platform where students discover thesis partners, form groups, share versioned documents and chat. <b>I built</b> profile management, thesis group creation, group and member views, and message pinning.<br><br>
      <code>Java</code> <code>Spring Boot</code> <code>Spring Security + JWT</code> <code>MySQL</code> <code>React</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Omar136796/CSE440-QA-Text-Classification"><img src="assets/text_classification.jpg" alt="Text classification results"></a>
      <h3><a href="https://github.com/Omar136796/CSE440-QA-Text-Classification">🧠 Q&amp;A Text Classification</a></h3>
      Classifying 150k Q&amp;A posts into 10 topics. Compares TF-IDF with Skip-gram Word2Vec across 9 models, from Random Forest to BiLSTM. <b>BiGRU wins with 69.3% accuracy.</b><br><br>
      <code>TensorFlow/Keras</code> <code>scikit-learn</code> <code>Gensim</code> <code>NLTK</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Omar136796/CSE461-FocusPal"><img src="assets/focuspal.jpg" alt="FocusPal robot"></a>
      <h3><a href="https://github.com/Omar136796/CSE461-FocusPal">🤖 FocusPal: study companion robot</a></h3>
      Arduino desk robot with a Pomodoro timer, a <b>servo-locked phone compartment</b>, an animated OLED face (custom memory-light driver), posture, noise and climate monitoring, and voice alerts.<br><br>
      <code>Arduino C++</code> <code>I2C</code> <code>UART</code> <code>Servos</code> <code>Sensors</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Omar136796/CSE421-BoardNet-Network-Design"><img src="assets/boardnet.jpg" alt="BoardNet topology"></a>
      <h3><a href="https://github.com/Omar136796/CSE421-BoardNet-Network-Design">🌐 BoardNet: six-site enterprise network</a></h3>
      A network for six education boards: VLSM addressing, RIPv2, <b>floating static routes for automatic failover</b>, central and local DHCP, DNS, web and cross-site email.<br><br>
      <code>Cisco Packet Tracer</code> <code>VLSM</code> <code>RIPv2</code> <code>DHCP/DNS</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Omar136796/CSE423-Vehicle-Combat"><img src="assets/vehicle_combat.jpg" alt="Vehicle Combat game"></a>
      <h3><a href="https://github.com/Omar136796/CSE423-Vehicle-Combat">🎮 Vehicle Combat: 3D battle game</a></h3>
      A 3D game built from scratch in OpenGL. Drive a tank, jeep or sports car through 3 levels, fighting AI enemies with day/night, rain, snow and three camera views.<br><br>
      <code>Python</code> <code>PyOpenGL</code> <code>GLUT</code> <code>3D graphics</code>
    </td>
  </tr>
</table>

### 🗂️ More of my work

| Area | Projects |
|---|---|
| 🤖 **AI and ML** | [T20 Score Predictor](https://github.com/Omar136796/CSE422-T20-Score-Predictor) (regression and clustering) · [AI labs](https://github.com/Omar136796/CSE422-Artificial-Intelligence) (search, genetic algorithms, ML) · [NLP labs](https://github.com/Omar136796/CSE440-Natural-Language-Processing-II) (NLTK, embeddings, text classification) |
| ⚙️ **Systems** | [Unix Shell in C](https://github.com/Omar136796/CSE321-Unix-Shell) (pipes, redirection, signals) · [VSFS file-system checker](https://github.com/Omar136796/CSE321-VSFS-Consistency-Checker) · [Movie Watchlist in 8086 Assembly](https://github.com/Omar136796/CSE341-Movie-Watchlist-8086-Assembly) · [Microprocessor labs](https://github.com/Omar136796/CSE341-Microprocessors) |
| 🔌 **Hardware, embedded and VLSI** | [Pomodoro Bot](https://github.com/Omar136796/CSE360-Pomodoro-Bot) (Arduino) · [Digital Voltmeter (ICL7107 ADC)](https://github.com/Omar136796/CSE350-Digital-Voltmeter-ICL7107) · [Four 3-bit Number Adder](https://github.com/Omar136796/CSE260-Four-3-Bit-Number-Adder) · [VLSI labs](https://github.com/Omar136796/CSE460-VLSI-Design) (CMOS, Verilog, FSMs) |
| 🌐 **Web and databases** | [Football Tournament Management System](https://github.com/Omar136796/CSE370-Football-Tournament-Management-System) (PHP, MySQL) · [Database labs](https://github.com/Omar136796/CSE370-Database-Systems) (SQL) |
| 🎨 **Graphics and networks** | [Computer graphics labs](https://github.com/Omar136796/CSE423-Computer-Graphics) (2D/3D PyOpenGL) · [Networks labs](https://github.com/Omar136796/CSE421-Computer-Networks) (sockets, Wireshark, ns-3, routing) |
| 📐 **Foundations** | [Programming I](https://github.com/Omar136796/CSE110-Programming-Language-I) · [OOP](https://github.com/Omar136796/CSE111-Programming-Language-II) · [Data Structures](https://github.com/Omar136796/CSE220-Data-Structures) · [Algorithms](https://github.com/Omar136796/CSE221-Algorithms) · [Numerical Methods](https://github.com/Omar136796/CSE330-Numerical-Methods) · [Calculus and ODEs](https://github.com/Omar136796/MAT120-Integral-Calculus-and-Differential-Equations) |

---

## 🛠️ Tech stack

**Languages**<br>
<img src="https://skillicons.dev/icons?i=py,c,cpp,java,js,php,html,css,bash,verilog&theme=dark" alt="Languages"><br>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL"> <img src="https://img.shields.io/badge/8086_Assembly-555555?style=flat-square&logo=intel&logoColor=white" alt="8086 Assembly"> <img src="https://img.shields.io/badge/Arduino_C++-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino C++">

**Frameworks, AI and ML**<br>
<img src="https://skillicons.dev/icons?i=fastapi,spring,react,vite,tensorflow,sklearn&theme=dark" alt="Frameworks"><br>
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras"> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"> <img src="https://img.shields.io/badge/NLTK-2C7A7B?style=flat-square" alt="NLTK"> <img src="https://img.shields.io/badge/Gensim-4B5563?style=flat-square" alt="Gensim"> <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API"> <img src="https://img.shields.io/badge/PyOpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="PyOpenGL">

**Databases**<br>
<img src="https://skillicons.dev/icons?i=mysql,postgres&theme=dark" alt="Databases">

**Hardware, networks and design tools**<br>
<img src="https://skillicons.dev/icons?i=arduino,figma,postman&theme=dark" alt="Hardware and design"><br>
<img src="https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="Cisco Packet Tracer"> <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" alt="Wireshark"> <img src="https://img.shields.io/badge/Proteus-1F5F8B?style=flat-square" alt="Proteus"> <img src="https://img.shields.io/badge/Intel_Quartus-0071C5?style=flat-square&logo=intel&logoColor=white" alt="Intel Quartus"> <img src="https://img.shields.io/badge/DSCH_%2F_Microwind-6B7280?style=flat-square" alt="DSCH"> <img src="https://img.shields.io/badge/EMU8086-374151?style=flat-square" alt="EMU8086">

**Dev tools and deployment**<br>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode,idea,linux,apple,vercel&theme=dark" alt="Tools"><br>
<img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white" alt="Google Colab"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"> <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" alt="Render">

**📊 Currently learning: data analysis**<br>
<img src="https://img.shields.io/badge/Excel-217346?style=flat-square" alt="Excel"> <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square" alt="Power BI"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">

---

## 🏆 Achievements and roles

| | |
|---|---|
| 🏅 | **5th place, CSE Thesis Poster Exhibition (Fall 2026)**, BRAC University, for *ATTACK ON LLMS* |
| 🎓 | **CGPA 3.98 / 4.00**, B.Sc. in CSE, BRAC University |
| 🧑‍🏫 | **Student Tutor (ST), CSE230: Discrete Mathematics**, Fall 2026 |
| 💰 | **Children of Freedom Fighter Scholarship**: 100% tuition waiver for the entire undergraduate program |
| 💰 | **BRACU Merit Scholarship** for academic results: 75% waiver (8 semesters) and 50% waiver (2 semesters) |
| 📜 | **Grameenphone Academy** certificates: *Ace the Aptitude Test* and *Build an ATS-Winning CV* (2026) |
| 🏫 | GPA 5.00 in both SSC (2019) and HSC (2021) |

---

## 📈 GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Omar136796&theme=tokyonight&hide_border=true&background=0D1117&ring=22D3EE&fire=22D3EE&currStreakLabel=22D3EE">
    <img src="https://streak-stats.demolab.com?user=Omar136796&hide_border=true&ring=0E7490&fire=0E7490&currStreakLabel=0E7490" alt="GitHub streak">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Omar136796&theme=tokyo-night&hide_border=true&area=true&bg_color=0D1117&color=22D3EE&line=0E7490&point=FFFFFF">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Omar136796&theme=github-compact&hide_border=true&area=true&bg_color=FFFFFF&color=0E7490&line=22D3EE&point=0F172A" alt="Contribution activity graph" width="100%">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Omar136796/Omar136796/output/github-snake-dark.svg">
    <img src="https://raw.githubusercontent.com/Omar136796/Omar136796/output/github-snake.svg" alt="Snake eating my contribution graph" width="100%">
  </picture>
</p>

---

## 🎬 When I'm not coding…

You'll find me watching a movie or the latest anime, following **cricket** 🏏 and **football** ⚽, or planning my next **trip** 🧳.

## 📫 Let's connect

<p align="center">
  <a href="mailto:omar136796@gmail.com"><img src="https://img.shields.io/badge/Email-omar136796%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.facebook.com/Omar136796"><img src="https://img.shields.io/badge/Facebook-Omar136796-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"></a>
  <a href="https://github.com/Omar136796"><img src="https://img.shields.io/badge/GitHub-Omar136796-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<p align="center">
  <a href="https://omar136796.github.io"><img src="https://img.shields.io/badge/Portfolio-omar136796.github.io-0E7490?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio website"></a>
  <a href="https://omar136796.github.io/cv.html"><img src="https://img.shields.io/badge/CV-View_%26_download-22D3EE?style=for-the-badge&logo=readthedocs&logoColor=white" alt="CV"></a>
</p>

<p align="center"><i>🌐 Explore my projects, research and journey on my <a href="https://omar136796.github.io">portfolio website</a>, or grab my <a href="https://omar136796.github.io/cv.html">CV</a>.</i></p>

<p align="center">
  <img src="assets/footer.svg" alt="" width="100%">
</p>
