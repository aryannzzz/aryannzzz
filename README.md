<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Aryan%20Jain&fontSize=52&fontColor=fff&animation=twinkling&fontAlignY=36&desc=Research%20%7C%20Robotics%20%7C%20AI%2FML%20%7C%20IIT%20Madras&descAlignY=58&descSize=20" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=1200&color=00D9FF&center=true&vCenter=true&width=720&lines=Robotics+Researcher+%40+IISc+Stochastic+Lab+%F0%9F%A4%96;NeurIPS+%7C+ACL+Author+%7C+Provisional+IP+Holder+%F0%9F%93%84;Mechanistic+Interpretability+%7C+Quadruped+Locomotion+%F0%9F%A6%BE;Quant+Systems+%7C+RL+%7C+LLM+Orchestration+%F0%9F%9A%80;Chemical+Engineer+who+went+rogue+into+AI+%F0%9F%A7%AA" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aryan-jain-iitm)
[![Kaggle](https://img.shields.io/badge/Kaggle-%2320BEFF.svg?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/aryannzzz)
[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=for-the-badge&logo=leetcode&logoColor=white)](https://www.leetcode.com/aryan12012)
[![Codeforces](https://img.shields.io/badge/Codeforces-%231F8ACB.svg?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/aryannzzz)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ch24b040@smail.iitm.ac.in)

</div>

---

## 🧬 About Me

```python
class AryanJain:
    def __init__(self):
        self.name        = "Aryan Jain"
        self.institution = "IIT Madras — BTech Chemical Engineering (2024–2028)"
        self.cgpa        = 8.84
        self.jee_rank    = "99.87 %ile in JEE Mains 2024 (15L+ candidates)"
        self.research    = [
            "Stochastic Robotics Lab, IISc  (Advisor: Shishir Kolathaya)",
            "ValenceAI — LLM × CFD Research (Advisor: S. Abhinav Raman)",
        ]
        self.papers      = [
            "NeurIPS 2026 (under review) — RL Environment for ML Integrity Auditing",
            "SurgeLLM @ ACL 2026 — When LLMs Orchestrate but Do Not Compute",
        ]
        self.ip          = "Provisional patent: streaming multi-agent treasury orchestration"
        self.interests   = ["Robotics", "Mechanistic Interpretability", "Quantitative Systems", "RL"]

    def say_hi(self):
        print("Let's build something that matters. 🚀")

me = AryanJain()
me.say_hi()
```

---

## 🔬 Research Experience

<table>
<tr>
<td width="50%" valign="top">

### 🦾 Stochastic Robotics Lab, IISc
**Research Intern — Robotics × AI** `May 2026 – Present`
*Advisor: Prof. Shishir Kolathaya*

- Trained PPO-based quadruped locomotion policies in **IsaacLab** for rough terrain traversal
- Co-trained **DreamerV3-style RSSM** world model, generating 5-step CoM & joint-state predictions
- Derived first-principles thermal model for 12 DC motors, eliminating primary motor failure
- Stress-tested **50+ policies** on real hardware; validated zero-shot sim-to-real on an **80 kg quadruped** — 27° inclines & 14 cm stairs

</td>
<td width="50%" valign="top">

### 🌊 ValenceAI — LLM × CFD Research
**Undergraduate Research Project** `Jan 2026 – Present`
*Advisor: S. Abhinav Raman*

- Led **LLM-to-CFD pipeline** achieving 100% benchmark success (11/11) with SHA-256 caching & fallback
- Enforced physics correctness via **4 constraint matrices** (12 solvers × 9 regimes)
- Designed 37-pattern security layer against command injection & path traversal
- **0.88% L∞ velocity error** across 14 benchmarks; Re up to 1 lakh, laminar through turbulent, 4 geometry classes

</td>
</tr>
</table>

---

## 📄 Publications & Intellectual Property

| Type | Work | Venue |
|------|------|-------|
| 📝 Paper | *"An Interactive RL Environment on ML Experiment Integrity Auditing"* — **First Author** | NeurIPS 2026 *(under review)* |
| 📝 Paper | *"When LLMs Orchestrate but Do Not Compute"* — **First Author** | SurgeLLM @ ACL 2026 |
| 🔒 IP | Provisional patent: streaming-native multi-agent treasury orchestration for asset allocation & cashflow forecasting | Filed |

---

## 🏆 Achievements

| Achievement | Details |
|------------|---------|
| 🥇 **Inter IIT Tech Meet 14** | Built a production-grade streaming treasury system; Sharpe ratio 7.78, ~92% RMSE reduction, 85% drawdown reduction |
| 🚀 **OpenEnv Hackathon** (Meta × PyTorch × HuggingFace) | Selected in top teams for offline Grand Finale, Bangalore, from **70,000+ registered developers** |
| 📐 **JEE Mains 2024** | **99.87 percentile** out of 15+ lakh candidates |
| ✅ **JEE Advanced 2024** | Qualified out of ~2.5 lakh candidates |

---

## 🛠️ Featured Projects

<details>
<summary><b>🔍 CLIPSCOPE — Mechanistic Interpretability for Foundation Models</b></summary>
<br>

Built a mechanistic interpretability pipeline for Vision-Language Models, discovering latent concepts in CLIP via sparse feature learning.

- Trained a **6.3M-parameter Sparse Autoencoder** on 160K CLIP ViT-B/16 activations → **89% explained variance**
- Demonstrated feature steering: interventions on learned latent directions produced up to **24.9% probability shifts**
- Implemented Anthropic-inspired SAE: Top-K sparsity, ghost-gradient feature recovery & decoder normalization

`PyTorch` `Transformers` `Sparse Autoencoders` `CLIP` `Mechanistic Interpretability`
</details>

<details>
<summary><b>📈 Options Pricing Engine</b></summary>
<br>

Full derivatives pricing library spanning closed-form, stochastic, simulation, and numerical PDE methods.

- Heston pricing via **Albrecher little-trap & Laguerre-quadrature Fourier inversion** using live market data
- Implied volatility via Newton-Raphson/Brent; synthetic Heston parameters recovered within **10% error**
- Constructed live **SPY vol surfaces** from 859 contracts across 5 expiries; analyzed term-structure dynamics

`Python` `NumPy` `SciPy` `Black-Scholes` `Heston` `Monte Carlo` `Finite Differences`
</details>

<details>
<summary><b>📊 Limit Order Book Simulator & RL Market Maker</b></summary>
<br>

Event-driven LOB simulator with price-time-priority matching and a learned market-making agent.

- **PPO agent from scratch** (GAE + clipped objective) inside a custom OpenAI Gym environment
- Implemented **Avellaneda-Stoikov** framework from stochastic-control theory with inventory-aware quoting
- Microstructure analytics: adverse-selection cost, fill-rate, inventory utilization & **Kyle Lambda**
- Order-flow generation via **Hawkes process**

`Python` `PPO` `Reinforcement Learning` `Market Microstructure` `Gym`
</details>

<details>
<summary><b>📉 Statistical Arbitrage Research Platform</b></summary>
<br>

Pairs-trading research platform with rigorous statistical methodology and realistic execution.

- Engle-Granger & Johansen cointegration with **Kalman-filter dynamic hedge ratios**
- Walk-forward pipeline with zero-lookahead, block-bootstrap Sharpe intervals & transaction-cost-aware execution
- Evaluated on **992 NSE trading days**: 60 trades, OOS Sharpe **0.226**, avg holding period **2.1 days**
- LOB adapter for realistic fill simulation and adverse-selection analysis

`Python` `Kalman Filter` `Cointegration` `Pairs Trading` `NSE`
</details>

<details>
<summary><b>🤖 Project GRASP — Intelligent Robotic Arm (iBot Club, IITM)</b></summary>
<br>

Deploying an intelligent robotic arm to autonomously operate via visual scene understanding and natural language.

- Conditioned ACT's CVAE encoder on ResNet18 visual obs → **+40% task success** over baseline
- In-context learning for real-robot control: formatted teleoperation demos as LLM few-shot prompts
- Fixed gradient collapse in VLA models via cross-attention pooling → **85% reduction in cross-instruction correlation**
- Open-vocabulary detection + geometric grasp planning with OpenCV & SayCAN → **90% success in sim**

`PyTorch` `ACT` `ResNet18` `SayCAN` `OpenCV` `LLM` `Robotics`
</details>

<details>
<summary><b>🧠 Project NEUROSPIKE — Spiking Neural Networks (BT Club × Prof. Gopalakrishnan)</b></summary>
<br>

Biologically plausible alternative to backpropagation using Predictive Coding networks.

- 2-layer hierarchical Predictive Coding network in **Brian2** modelling Free Energy Principle update dynamics
- **96.9% test accuracy**, 0.9999 cosine similarity vs. standard backprop
- On 5-task split-MNIST: PC-native update rule forgot **68% less** than naive backprop fine-tuning
- Demonstrated generative inference ("dreaming") in **< 300 steps** by clamping output neurons to MNIST targets

`Brian2` `Spiking Neural Networks` `Predictive Coding` `Neuromorphic AI`
</details>

<details>
<summary><b>🏦 Inter IIT Tech Meet 14 — Streaming Treasury System (Pathway)</b></summary>
<br>

Production-grade real-time treasury orchestration system for banks.

- Autoregressive CashFlow forecasting with **Gaussian HMM regime detection** → **~92% RMSE reduction**
- Fundamental Analysis Agent → overall **Sharpe ratio of 7.78** with **85% drawdown reduction**
- Real-time yield forecasting via **Nelson-Siegel** yield-curve modeling on NSE G-Sec data over Kafka
- Bond pricing from first principles: YTM, duration, convexity & dirty-price
- **18 custom Pathway operators** across bonds, equities, and forex feeds

`Python` `Kafka` `Pathway` `HMM` `Nelson-Siegel` `RL` `LLM`
</details>

<details>
<summary><b>🎮 OpenEnv Hackathon — RL Environment for LLM Project Managers (Meta × PyTorch × HuggingFace)</b></summary>
<br>

First-of-its-kind RL environment training LLM project managers under deception and long-horizon software crises.

- Trained **LoRA-GRPO** policies on Qwen-1.5B evaluating strategic cross-verification under falsified observations
- Adaptive multi-agent dynamics: deceptive LLM teammates, social testimony graphs & crisis escalation

`RL` `LoRA` `GRPO` `Qwen` `Multi-Agent` `LLM`
</details>

---

## 🎓 Club & Community Work

| Role | Org | Highlights |
|------|-----|-----------|
| **Coordinator, Head of CV & RL** | iBot Club, IITM | Mentored **500+ students**; led 4-week CV bootcamp; designed RL locomotion project with 45-member team |
| **Open-Source Contributor** | Neural-LAM | Probabilistic forecasting — Graph-EFM integration; ensemble calibration diagnostics |
| **Teaching Assistant** | GN1002, IITM | Mentored 15-20 freshmen on personal development & time management |
| **Saathi Peer Mentor** | IITM | Guided freshmen through academics and institute life |

---

## 💻 Tech Stack

<div align="center">

### 🧠 AI / ML & Research
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### 🤖 Robotics & Simulation
![IsaacLab](https://img.shields.io/badge/IsaacLab-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![ROS](https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)

### 💻 Languages
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

### 🛠️ Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=aryannzzz&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=C9D1D9&rank_icon=github" height="170" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aryannzzz&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9&langs_count=8" height="170" alt="Top Languages" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=aryannzzz&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF&sideLabels=C9D1D9&dates=C9D1D9" alt="GitHub Streak" />

</div>

---

## 🐍 Contribution Graph

<div align="center">

![Snake animation](https://github.com/aryannzzz/aryannzzz/blob/output/github-contribution-grid-snake-dark.svg)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=aryannzzz&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&row=1&column=7" alt="GitHub Trophies" />

</div>

---

## 📬 Let's Connect

<div align="center">

I'm always open to collaborating on research in robotics, interpretability, RL, or quant systems — feel free to reach out!

<a href="mailto:ch24b040@smail.iitm.ac.in">
  <img src="https://img.shields.io/badge/Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://www.linkedin.com/in/aryan-jain-iitm/">
  <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

</div>

---

<div align="center">

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

<br/>

<img src="https://komarev.com/ghpvc/?username=aryannzzz&label=Profile+Views&color=00D9FF&style=for-the-badge" alt="Profile Views" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />

</div>
