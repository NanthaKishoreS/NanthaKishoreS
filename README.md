<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2200&pause=700&color=39D353&center=true&vCenter=true&width=600&lines=booting+profile...;user%3A+nantha-kishore-s;role%3A+backend+%2B+systems+%2B+linux;status%3A+building" alt="Typing SVG" />

<br>

# NANTHA KISHORE S

`software engineering` · `backend` · `systems` · `linux` · `machine learning`

<a href="https://www.linkedin.com/in/nanthakishore06"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="https://leetcode.com/u/NanthaKishoreS/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white"/></a>
<a href="mailto:nanthakishore06@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=NanthaKishoreS&label=visitors&color=39D353&style=flat-square"/>

</div>

<br>

```text
$ whoami
```

```
nantha-kishore-s
└── computer science undergraduate, SVCE, Chennai
    ├── backend systems
    ├── linux / operating-system internals
    ├── software engineering
    └── machine learning (exploring)

Third-year B.E. Computer Science and Engineering student.

I tend to work from the bottom up — understanding how something works
before trying to optimize or build on top of it. That's what pulled me
from "using Linux" to configuring i3, tuning swap behaviour, and reading
about OS layers for a research project.

Daily driver: Arch Linux. Most of my week happens in a terminal.
```

<br>

```text
$ cat /proc/current-interests
```

```
SYSTEMS
  linux · process management · resource management
  CLI environments · operating-system architecture

BACKEND
  FastAPI · REST APIs · service communication · microservices · Docker

MACHINE LEARNING
  Python · TensorFlow · lightweight models · AI/ML systems research

CURRENTLY READING UP ON
  distributed systems · kernel behaviour · scheduling & memory management
```

<br>

```text
$ cat skills.yaml
```

```yaml
languages:      Java, Python, C++, Bash
backend:        FastAPI, Node.js (basic), REST APIs
systems:        Linux, Arch Linux, Ubuntu, i3, CLI,
                Process Management, ZRAM, ZSWAP, TLP
machine_learning: TensorFlow, Neural Networks, Lightweight ML Models
tools:          Git, GitHub, Docker, VS Code
also_used_in_projects: React.js, Flutter, Firebase, Unity
```

<br>

## `$ ls ~/projects`

<details open>
<summary><b>01 · efficient-linux-environment</b> — daily-driver tuning, solo project</summary>
<br>

A personal experiment in making a 4GB DDR3 laptop usable as a daily development machine.

| | |
|---|---|
| **Hardware** | Intel Core i3-6100U · 4GB DDR3 |
| **Environment** | Arch Linux · i3 window manager |
| **Tools** | Bash · ZRAM · ZSWAP · TLP |

- Started on Ubuntu for ~8 months, then moved to Arch Linux and adopted a terminal-centric workflow
- Replaced GNOME with the **i3** tiling window manager to cut overhead
- Built Bash shortcuts for application launching and switching system modes
- Configured separate **performance** and **battery-saver** profiles
- Added manual control over background processes
- **Reduced steady-state RAM usage from ~3GB to under 1GB**
- Noticeably faster boot time; used the machine for daily dev work and hackathons

> What started as a necessity became a genuine interest in how Linux manages system resources.

</details>

<details>
<summary><b>02 · ai-enabled-operating-systems</b> — research contributor, C-DAC-sponsored, team of 6</summary>
<br>

A feasibility study on integrating AI/ML into critical layers of an operating system, undertaken by the CSE department in connection with **C-DAC** (Centre for Development of Advanced Computing).

| | |
|---|---|
| **Team** | 6 |
| **Funding** | ₹9.5 lakh |
| **Status** | Ongoing |
| **Scope** | Mobile · HPC · Server · Embedded · Desktop |

My research focus:

```
Physical Infrastructure & Environment
                ↓
        Operating System Core
                ↓
  Middleware & Core System Services
```

- Researched the layers above and studied physical-infrastructure / environmental considerations
- Identified gaps and possible innovation opportunities within each layer
- Studied AI/ML integration possibilities specific to those layers
- Consolidated individual and team research into the overall AI/ML architecture mapping
- Presented findings across C-DAC-arranged review meetings

</details>

<details>
<summary><b>03 · JalGarbha</b> — Smart India Hackathon 2025, Top 4 / 76, team of 6</summary>
<br>

Smart Rooftop Rainwater Harvesting Ecosystem — a location-aware rainwater recharge recommendation platform.

| | |
|---|---|
| **Result** | Top 4 of 76 teams — SIH Internal Selection |
| **Backend** | FastAPI |
| **ML** | TensorFlow + additional models |
| **Other** | React.js, Flutter, Firebase, Unity (teammate) |

- Personally implemented the **FastAPI backend** and the connections between application components
- Team used multiple ML models to assess environmental conditions: rooftop area/material, soil condition, and geographic coordinates
- Explored prediction of water-collection efficiency and flow from rooftop to recharge pit
- A teammate built the 3D representation of the recharge pit in Unity

</details>

<details>
<summary><b>04 · supply-chain-intelligence</b> — YAH'26 (ACM), team of 4</summary>
<br>

A distributed prototype built around six containerized microservices for shipment tracking and warehouse logic.

| | |
|---|---|
| **Services** | 6, containerized with Docker |
| **Focus** | APIs · shipment tracking · warehouse logic |
| **Team** | 4 |

- Defined communication protocols between the six services
- Worked on shipment-tracking and warehouse workflow logic
- Containerized all services with Docker
- Demonstrated live API communication between services

</details>

<details>
<summary><b>05 · developer-telemetry</b> — Blueprints'26, team of 6</summary>
<br>

A prototype exploring developer activity and code-efficiency telemetry, shipped as a downloadable VS Code extension.

| | |
|---|---|
| **Extension** | TypeScript |
| **Processing** | Python |
| **Environment** | VS Code |

The extension explores code-change capture, developer-activity detection, JSON-based telemetry, and lightweight Python-side processing to link activity with task requirements and generate an efficiency/contribution score.

My contribution was the extension's structure, monitoring flow, and the real-time connections for developer activity — not the full implementation, which was built together with Antigravity.

</details>

<br>

## `$ ./root-access`

**Root Access — Technical Hunt**
Association of Computer Engineers (ACE), SVCE · Department Symposium: INTERRUPT
**Role:** Lead Organizer · **Participants:** 90+

A terminal-oriented technical competition:

```
terminal-based programming
        ↓
generate access keys
        ↓
navigate hidden directories
        ↓
solve system-level challenges
```

**Code Validation System** — a two-step approach:

```
Dummy Input → Original Input → Algorithm / Implementation Validation
```

**Technical operations:** configured 45+ offline development environments, managed the progressive release of system-level problem statements, and coordinated the technical execution of the event.

<br>

## `$ git log --oneline --achievements`

```
2026   NPTEL — Elite + Gold
       Neural Networks for Computer Vision & Natural Language Processing
       Score: 95/100 · IIT Guwahati

2026   C-DAC-sponsored OS research
       AI/ML integration feasibility study · ₹9.5 lakh project funding

2026   Root Access — Technical Hunt
       Lead Organizer · 90+ participants · 45+ offline dev environments

2025   Smart India Hackathon — Internal Selection
       JalGarbha · Top 4 of 76 teams
```

<br>

## `$ cat leadership.log`

**Association of Computer Engineers — ACE, SVCE**
Current: **Design Team Lead** (previously Design Executive)

- Coordinating junior and peer members
- Managing design outputs for department technical events
- Reviewing and coordinating creative deliverables

<br>

## `$ ./leetcode --stats`

<a href="https://leetcode.com/u/NanthaKishoreS/"><img src="https://img.shields.io/badge/LeetCode-NanthaKishoreS-FFA116?style=flat-square&logo=leetcode&logoColor=white"/></a>

```
80+ problems solved · 4 contests attended · 50-day streak badge
current focus: arrays · strings · algorithmic efficiency
```

<br>

## `$ git status`

```
On branch: building

✓ Backend
✓ Linux
✓ Systems
→ Distributed Systems
→ Machine Learning
→ AI + Operating Systems
```

Currently trying to move beyond simply *using* systems toward understanding what happens underneath them:

```
processes → memory → scheduling → I/O → resource management → kernel behaviour
```

<br>

## `$ cat education.yaml && cat certification.yaml`

```yaml
education:
  degree:  B.E. Computer Science & Engineering
  college: Sri Venkateswara College of Engineering (SVCE), Chennai
  years:   2024 – 2028
  cgpa:    8.23 / 10

certification:
  name:    Neural Networks for Computer Vision & Natural Language Processing
  issuer:  NPTEL · IIT Guwahati
  length:  12-week course (Jan – Apr 2026)
  score:   95 / 100
  award:   Elite + Gold
```

<br>

## `$ git log --stat`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NanthaKishoreS&show_icons=true&hide_border=true&theme=dark&bg_color=0D1117&title_color=39D353&icon_color=39D353&text_color=E6EDF3" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NanthaKishoreS&layout=compact&hide_border=true&theme=dark&bg_color=0D1117&title_color=39D353&text_color=E6EDF3" height="165"/>
</div>

<br>

<div align="center">

```
┌──────────────────────────────────────────┐
│                                          │
│   currently: learning how systems work   │
│                                          │
│   Chennai, India · Arch Linux            │
│                                          │
└──────────────────────────────────────────┘

   build it · break it · understand it · improve it
```

</div>
