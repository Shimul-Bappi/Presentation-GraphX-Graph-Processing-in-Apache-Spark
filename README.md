# ⚡ GraphX: Distributed Graph Processing in Apache Spark

[![GitHub Pages](https://img.shields.io/badge/Live_Presentation-GitHub_Pages-2563EB?style=for-the-badge&logo=github)](https://shimul-bappi.github.io/Presentation-GraphX-Graph-Processing-in-Apache-Spark/)
[![Apache Spark](https://img.shields.io/badge/Apache_Spark-3.5+-EA580C?style=for-the-badge&logo=apachespark)](https://spark.apache.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-10B981?style=for-the-badge)](LICENSE)

An interactive, responsive presentation slide deck and comprehensive technical guide on **Apache Spark GraphX** — covering graph-parallel computation, the Property Graph model, functional graph operators, the Pregel message-passing API, and production graph algorithms.

---

## 👥 Group Members & Presenters

| Sl | Member Name | Student ID | Role |
|:---|:---|:---|:---|
| **01** | **MD. Shimul Ahmed Bappi** | `837` | Presenter |
| **02** | **Tasnim Islam Bristi** | `837` | Presenter |
| **03** | **Sarmin Akter** | `00` | Presenter |

---

## 🖥️ Launch the Live Presentation

The slide deck is built with standalone modern HTML5/CSS3/JavaScript (no external runtime dependencies) and is hosted via **GitHub Pages**:

👉 **[Launch Interactive Slides Online](https://shimul-bappi.github.io/Presentation-GraphX-Graph-Processing-in-Apache-Spark/)**

### 🎮 Keyboard & Touch Shortcuts
* **Next Slide:** `→` (Right Arrow), `Spacebar`, `PageDown`, or swipe left on mobile.
* **Previous Slide:** `←` (Left Arrow), `PageUp`, or swipe right on mobile.
* **Jump Menu:** Press `M` or click **☰ Menu**.
* **Toggle Fullscreen:** Press `F` or click **⛶ Fullscreen**.
* **First / Last Slide:** `Home` / `End`.
* **Export PDF:** Press `Ctrl + P` / `Cmd + P` (Landscape print enabled).

---

## 📂 Repository Contents

| File | Description |
|:---|:---|
| `index.html` | Fully responsive, fluid typography, interactive presentation deck with SVG diagrams. |
| `presentation.tex` | LaTeX Beamer 16:9 widescreen presentation deck using TikZ drawings. |
| `generate_pptx.py` | Standalone Python script to generate the PowerPoint `.pptx` file. |
| `requirements.txt` | Python dependencies for PPTX generation (`python-pptx`). |

---

## 🚀 Local Setup & Execution

### 1. View HTML Slides Locally
```bash
git clone https://github.com/Shimul-Bappi/Presentation-GraphX-Graph-Processing-in-Apache-Spark.git
cd Presentation-GraphX-Graph-Processing-in-Apache-Spark

# Open index.html directly in your browser or run a simple server:
python -m http.server 8000
