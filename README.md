<img width="100%" src="https://capsule-render.vercel.app/api?type=slice&color=0F2D5E&height=150&section=header" />

<div align="center">

# Akshay Gautam

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1000&color=0F2D5E&center=true&vCenter=true&width=700&lines=AI+%26+Machine+Learning+%7C+Computer+Vision+%7C+Deep+Learning;500%2B+CP+%26+DSA+Problems+Solved;LeetCode+Knight+1886+%7C+Codeforces+Pupil+1314" />

<br/>

<a href="https://linkedin.com/in/akshaygautam4451"><img src="https://img.shields.io/badge/LinkedIn-0F2D5E?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/77RedX"><img src="https://img.shields.io/badge/GitHub-0F2D5E?style=flat-square&logo=github&logoColor=white" /></a>
<a href="https://leetcode.com/u/redx_was_taken"><img src="https://img.shields.io/badge/LeetCode-0F2D5E?style=flat-square&logo=leetcode&logoColor=white" /></a>
<a href="https://codeforces.com/profile/redx_was_taken"><img src="https://img.shields.io/badge/Codeforces-0F2D5E?style=flat-square&logo=codeforces&logoColor=white" /></a>
<a href="mailto:akshaygautam4451@gmail.com"><img src="https://img.shields.io/badge/Email-0F2D5E?style=flat-square&logo=gmail&logoColor=white" /></a>



</div>

---

AIML undergraduate at **Birla Institute of Technology, Mesra** (CGPA **8.81**). I work on things that are genuinely hard to benchmark simply — video frame synthesis at measurable PSNR/SSIM targets, audio emotion modelling with continuous valence-arousal prediction, and quantitative portfolio allocation under real constraints. The through-line is building systems that are precise, measurable, and fast.

Currently directing the technical division of BIT Mesra's Aerospace Society — applying computer vision and control theory to autonomous drone hardware.

---

## Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,cpp,c,java&theme=dark" />

**ML & AI**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" />

**Engineering & Tools**

<img src="https://skillicons.dev/icons?i=docker,git,github,linux,flask&theme=dark" />

</div>

---

## Projects

### Theia — Video Frame Interpolation

Hardware-accelerated Windows application that doubles video frame rates with no CUDA dependency. Built around a multi-scale optical flow estimator with feature pyramids, coarse-to-fine flow refinement, residual U-Net structures, and deep supervision. Inference runs on ONNX Runtime DirectML. Trained on the Vimeo-90K dataset with PyTorch and Automatic Mixed Precision.

```
PSNR   34.06 dB
SSIM    0.9679
```

`PyTorch` `ONNX Runtime DirectML` `Optical Flow` `Vimeo-90K` `AMP`

---

### KaiROS — Emotion-Aware Music Engine

Production Discord bot that reads emotional content from audio and adapts music recommendations in real time. Core model: a 12.0M-parameter CNN-BiLSTM predicting valence and arousal from 140-dimensional Mel + Chroma features. Trained on the DEAM dataset. Recommendation uses Squared Euclidean Distance with probabilistic exploration-exploitation to avoid deterministic loops. FFmpeg-backed voice stream with automatic fault recovery and persistent SQLite embeddings.

```
Mean CCC    0.6541
Parameters  12.0M
```

`PyTorch` `CNN-BiLSTM` `Librosa` `FFmpeg` `SQLite` `Discord API`

---

### Algorithmic Portfolio Optimizer — Deep Learning × MPT

Full-stack financial engine combining temporal deep learning with Modern Portfolio Theory across 174 S&amp;P 500 assets. Residual Temporal CNN predicting 21-day forward returns from 20 technical indicators over a 63-day lookback window (150 epochs, AdamW, early stopping). Allocation via Sharpe Ratio maximisation — SciPy SLSQP with Ledoit-Wolf covariance shrinkage and a strict 35% per-asset cap. Dockerized with GitHub Actions CI/CD for daily model retraining.

```
Assets         174 S&P 500
Lookback       63 days → 21-day forward return
Optimiser      SciPy SLSQP + Ledoit-Wolf
Position cap   35% per asset
```

`PyTorch` `Temporal CNN` `SciPy SLSQP` `Flask` `Docker` `GitHub Actions`

---

## Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=77RedX&show_icons=true&hide_border=true&title_color=4A90E2&icon_color=1D4ED8&text_color=c9d1d9&bg_color=0d1117" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=77RedX&hide_border=true&background=0d1117&ring=1D4ED8&fire=4A90E2&currStreakLabel=4A90E2&sideLabels=c9d1d9&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9&stroke=4A90E2" />

<br/>

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=77RedX&layout=compact&hide_border=true&title_color=4A90E2&text_color=c9d1d9&bg_color=0d1117" />
<img width="49%" src="https://leetcard.jacoblin.cool/redx_was_taken?theme=dark&font=JetBrains%20Mono&ext=heatmap" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=77RedX&theme=onedark&no-frame=true&no-bg=true&column=7&margin-w=4&margin-h=4" />

</div>

---

## Recognition

| | |
|:---|:---|
| LeetCode | Knight · 1886 rating · 400+ problems solved |
| Codeforces | Pupil · 1314 peak rating |
| Pantheon 2024 — Capture The Flag | 3rd place (largest technical festival in Jharkhand) |
| Stanford ML Specialization | Completed — Andrew Ng, Coursera |

---

## Leadership

**Tech Lead, Aerospace Society — BIT Mesra** *(Aug 2024 – Present)*  
Managing a 10-person engineering team. Scope covers computer vision pipelines and control theory for transitioning autonomous drone concepts into physical prototypes.

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=77RedX&bg_color=0d1117&color=4A90E2&line=1D4ED8&point=FFFFFF&area=true&area_color=1D4ED8&hide_border=true&custom_title=Contribution+Graph" />
