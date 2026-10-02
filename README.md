# Quantum 101 (qm)

> A minimalist, interactive quantum mechanics puzzle designed to test physical intuition and intelligence.

🌐 **Live Demo:** [https://qm.sam7.xyz](https://qm.sam7.xyz)

---

## 💡 Overview

An electron is confined within a 1D infinite potential well of randomly generated width $L$ (in nm). 

Can you determine:
1. **The ground-state energy $E_1$ (in eV)**
2. **The coordinate $x$ with the maximum probability density in the ground state**

Features interactive client-side answer validation, dynamic HTML5 canvas renderings of both the potential well $U(x)$ and stationary probability distributions $|\psi_n(x)|^2$, complete step-by-step mathematical derivations, and seamless **Bilingual (English / 中文)** switching.

---

## 🛠️ Tech Stack & Design Philosophy

- **Zero Frameworks / Pure Vanilla**: Single-file HTML5, lightweight modern CSS, and plain JavaScript.
- **MathJax 3**: Clean, responsive client-side LaTeX typesetting.
- **HTML5 Canvas**: Native 2D canvas plotting for physical boundaries and quantum wavefunctions.
- **Static Hosting**: Served via GitHub Pages with custom domain DNS mapping.

---

## 🚀 Local Preview

Simply open `index.html` in any web browser, or serve it locally:

```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```
