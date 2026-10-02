<p align="center">
  <img src="./assets/header.svg" alt="Anmol Dhiman — Software engineer: AI, automation, secure systems" width="100%">
</p>

<p align="center">
  <img alt="Open to full-time" src="https://img.shields.io/badge/Open%20to-Full--time%20%2F%20New--grad-00e5ff?style=flat-square&labelColor=1a0b2e">
  <img alt="Location" src="https://img.shields.io/badge/Based%20in-Toronto%2C%20ON-ff2bd6?style=flat-square&labelColor=1a0b2e">
  <img alt="Education" src="https://img.shields.io/badge/Humber-Information%20Systems%20Engineering-7c3aed?style=flat-square&labelColor=1a0b2e">
</p>

<p align="center">
  <a href="https://anmold.dev"><b>Portfolio</b></a> ·
  <a href="https://linkedin.com/in/anmoldhimann">LinkedIn</a> ·
  <a href="mailto:contact@anmold.dev">Email</a>
</p>

## ⚡ Impact at a glance

<p align="center">
  <img src="./assets/stats.svg" alt="5x faster DEM processing; 60 GB processed in 3 hours instead of 15; 70 percent of faculty reporting automated; 1,300+ contributions in 12 months" width="100%">
</p>

<p align="center"><img src="./assets/divider.svg" alt="" width="100%"></p>

## 👋 About

I take an idea past the prototype: trace the failure, automate the repeatable work, and ship the next version. I like problems where performance, correctness, and trust all matter at once, whether that is a C++ pipeline chewing through tens of gigabytes of elevation data or a reporting system that faculty rely on for accreditation.

I study Information Systems Engineering at Humber Polytechnic with a focus on cybersecurity, and my work spans applied machine learning, data pipelines, performance-oriented systems, and practical automation.

## 🧭 Leadership

> **Technical Lead · GACI Online** — *Private Humber internal platform*
>
> Leading an internal admin platform for CLO mapping, workbook imports, and graduate-attribute analytics.

<p align="center"><img src="./assets/divider.svg" alt="" width="100%"></p>

## 🚀 Featured projects

### Terrain Builder — high-performance geospatial pipeline
[**Repository →**](https://github.com/Anmol-STRS/TerrainBuilderI-0) *(documentation-only public release)*

A C++ preprocessing pipeline that merges large Digital Elevation Model (DEM) datasets into unified terrain grids for hydraulic modelling workflows such as HEC-RAS.

| Metric | HEC-RAS baseline | Terrain Builder |
|---|---|---|
| Processing time (360 files, 60 GB) | 15 hours | **3 hours** |
| Throughput | 1.1 MB/s | **6.3 MB/s** |
| Memory footprint | Variable | **Constant, 622 MB** |

- **Four-phase pipeline:** parallel discovery, R-tree spatial indexing, chunk planning (9,604 chunks per run), cached windowed I/O, compressed tiled GeoTIFF output.
- **Performance engineering:** LRU block cache with a 40–60% hit rate and AVX2 SIMD kernels for a 2.5× processing speedup.

`C++` · `GDAL` · `PROJ` · `AVX2` · `CMake`

---

### Humber Workbook Insights — accreditation reporting automation
[**Repository →**](https://github.com/Anmol-STRS/Humber-Workbook-Insights) *(portfolio showcase; source is private under NDA)*

A Python system that parses Excel assessment results, automates CLO → Indicator binning, and exports polished Excel and PDF reports. Used across **4+ engineering programs** and automates **70%+ of manual faculty reporting**.

- Tkinter desktop app with multithreaded Excel processing, plus CLI and Streamlit interfaces.
- Indicator-, CLO-, and Level-I/D/A summaries, with step-by-step logging for traceability and audit.
- Private code walkthrough or demo available on request.

`Python` · `Pandas` · `OpenPyXL` · `Streamlit` · `SQLite`

---

### AI Trading Arena — ML + LLM market research platform
[**Repository →**](https://github.com/Anmol-STRS/AITraderBotMLProject)

A full-stack research project for TSX stock-price prediction and agent-assisted market analysis. It combines symbol-specific **XGBoost** models built from **40+ technical indicators** (optional CUDA acceleration) with LLM agents from Claude, GPT, and DeepSeek, served through a Flask API with WebSockets and a React/TypeScript dashboard.

- Compare model metrics, feature importance, and predictions in one dashboard.
- LLM agents interpret technical analysis, score sentiment, and flag risk factors, with cost tracking.
- Educational and research use only; not financial advice.

`Python` · `XGBoost` · `Flask` · `React` · `TypeScript` · `SQLite`

---

### Arduino Car — embedded control
[**Repository →**](https://github.com/Anmol-STRS/Arduino-Car-w-Obstacle-Detection) · [**Live demo →**](https://youtu.be/_BBaOZrlC_I)

An Arduino UNO robot combining IR line-following, ultrasonic obstacle avoidance, and Bluetooth remote control, with sensor inputs processed at 100 Hz.

- **17/18 laps** completed on a 2 m test track (94.4%).
- **48 ms** average full stop on obstacle detection.
- **~45 minutes** runtime on a single 7.4 V LiPo pack.

`Arduino C/C++` · `HC-SR04` · `HC-05` · `L298N`

---

### Project README Generator — developer tooling
[**Repository →**](https://github.com/Anmol-STRS/projectreadmegenerator)

A Python script that turns answers about a project into structured Markdown READMEs, with selectable sections such as installation, usage, contributing, and license.

`Python` · `Markdown`

<p align="center"><img src="./assets/divider.svg" alt="" width="100%"></p>

## 🛠 Skills

<p align="center">
  <b>Languages</b><br>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=1a0b2e" alt="Python">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&labelColor=1a0b2e" alt="C++">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white&labelColor=1a0b2e" alt="TypeScript">
  <img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white&labelColor=1a0b2e" alt="Arduino"><br><br>
  <b>AI & data</b><br>
  <img src="https://img.shields.io/badge/XGBoost-EB5A00?style=for-the-badge&logo=xgboost&logoColor=white&labelColor=1a0b2e" alt="XGBoost">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white&labelColor=1a0b2e" alt="Pandas">
  <img src="https://img.shields.io/badge/LLM_Agents-7c3aed?style=for-the-badge&logo=anthropic&logoColor=white&labelColor=1a0b2e" alt="LLM Agents">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white&labelColor=1a0b2e" alt="SQLite"><br><br>
  <b>Backend & web</b><br>
  <img src="https://img.shields.io/badge/Flask-444444?style=for-the-badge&logo=flask&logoColor=white&labelColor=1a0b2e" alt="Flask">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=1a0b2e" alt="React">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white&labelColor=1a0b2e" alt="Streamlit">
  <img src="https://img.shields.io/badge/WebSockets-333333?style=for-the-badge&logo=socketdotio&logoColor=white&labelColor=1a0b2e" alt="WebSockets"><br><br>
  <b>Systems & tooling</b><br>
  <img src="https://img.shields.io/badge/GDAL-589632?style=for-the-badge&logo=osgeo&logoColor=white&labelColor=1a0b2e" alt="GDAL">
  <img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white&labelColor=1a0b2e" alt="CMake">
  <img src="https://img.shields.io/badge/AVX2_SIMD-0071C5?style=for-the-badge&logo=intel&logoColor=white&labelColor=1a0b2e" alt="AVX2 SIMD">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=1a0b2e" alt="Git"><br><br>
</p>

<p align="center"><sub>Also: Excel/PDF report automation · feature engineering · memory-mapped I/O · cybersecurity focus at Humber Polytechnic</sub></p>

<p align="center"><img src="./assets/divider.svg" alt="" width="100%"></p>

## 📈 Contribution snapshot

<p align="center">
  <img src="./assets/contribution-heatmap.svg" alt="Static 53-week GitHub contribution heatmap showing 1,300+ contributions from August 11, 2025 through August 11, 2026." width="1120">
</p>

**1,300+ contributions · August 11, 2025 – August 11, 2026 · 53 weeks**

Dated GraphQL snapshot of contribution activity. This includes public and private work; private repository details remain private.

<p align="center"><img src="./assets/divider.svg" alt="" width="100%"></p>

## 📬 Let's talk

I'm looking for full-time and new-grad software roles. If you're hiring, collaborating, or want to talk through a project:

- 🌐 [anmold.dev](https://anmold.dev)
- 💼 [linkedin.com/in/anmoldhimann](https://linkedin.com/in/anmoldhimann)
- ✉️ [contact@anmold.dev](mailto:contact@anmold.dev)
