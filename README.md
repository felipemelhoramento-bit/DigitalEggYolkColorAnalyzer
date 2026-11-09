# Digital Egg Yolk Color Analyzer

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5 / JS](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20JavaScript-orange)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

An open-source, mobile-first browser application designed for objective and automated classification of egg yolk color using computer vision. Built with pure HTML5, WebRTC, and modern JavaScript, the application performs real-time sampling and dual-statistic evaluation (RGB & HSV) directly in the mobile or desktop browser without requiring external server processing.

---

## ⚠️ Disclaimer

This is an independent, open-source scientific tool created strictly for academic research, biometrics, and agricultural data science. It is not affiliated with, endorsed by, or sponsored by DSM-Firmenich or any of its subsidiaries. Any references to standard 1–16 color fan scales (such as YolkFan™) are used solely for comparative and educational calibration purposes. "YolkFan" is a registered trademark of its respective owner.

---

## 🌟 Key Features

* **Fixed Circular Region of Interest (ROI):** Precision crosshair positioning targeting the yolk surface with dynamic ROI size adjustment.
* **Dual Statistical Engine (Mean & Median):** Computes both Mean and Median metrics simultaneously for RGB and HSV color channels to ensure statistical robustness against local noise.
* **HSV & RGB Hybrid Color Matching:** Combines **HSV Hue (Matiz)** distance (70% weight) with **normalized RGB chromaticity ($r, g$)** (30% weight) to eliminate bias caused by variable lighting, shadows, and low-cost camera sensors.
* **Gating & Adaptive Noise Reduction:** Automatically filters out specular highlights (glare) and deep shadow pixels before statistical calculation.
* **Single-Line Dashboard UX:** Compact, responsive interface displaying real-time RGB/HSV stats alongside dual Mean-based and Median-based color classification results.
* **Header Mobile Controls:** Quick-action buttons for `Copy` (report generator), `Flip` (camera toggle), and `Freeze` (frame sampler).

---

## 🚀 Live Application

Access the live web application on any device via GitHub Pages:

👉 **[https://your-username.github.io/your-repository-name/](https://your-username.github.io/your-repository-name/)** *(Replace with your actual GitHub Pages URL)*

---

## 💻 Tech Stack

* **Frontend:** HTML5, CSS3, [Tailwind CSS](https://tailwindcss.com/)
* **Icons:** [FontAwesome 6](https://fontawesome.com/)
* **Processing:** HTML5 Canvas API & WebRTC (`navigator.mediaDevices.getUserMedia`)
* **Deployment:** GitHub Pages

---

## 📖 How to Cite / Como Citar

If you use this software, its underlying algorithm, or code in your research, academic publications, or commercial benchmarks, please cite the foundational repository as follows:

### APA Format
> Ferreira, F., & Silva, F. G. (2026). *YolkFan Real-Time Analyzer: An HTML5/JavaScript application for egg yolk color classification*. GitHub Repository. [https://github.com/your-username/yolkfan-analyzer](https://github.com/your-username/yolkfan-analyzer)

### BibTeX Format
```bibtex
@software{Digital Egg Yolk Color Analyzer,
  author    = {Costa, Maria Letícia Martins; Silva, Wallace Gomes da; Ferreira, Fabiana and Silva, Felipe Gomes da},
  title     = {Digital Egg Yolk Color Analyzer,
  year      = {2026},
  publisher = {GitHub},
  journal   = {GitHub repository},
  url       = {[https://github.com/your-username/yolkfan-analyzer](https://github.com/your-username/yolkfan-analyzer)}
}
