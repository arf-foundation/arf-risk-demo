# ARF Risk Demo – Public Sandbox (Simulated)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen)](https://arf-foundation.github.io/arf-risk-demo/)

This repository contains a **client‑side, simulated risk scoring demo** that illustrates the concepts of Bayesian inference, expected loss minimisation, semantic memory, and MCMC.  
**It is not connected to the protected ARF core engine** – all calculations are performed locally in your browser using mock data.

> ⚠️ **Important** – This demo uses **simulated data only**. The real ARF core engine is **access‑controlled** and available only to qualified pilots under outcome‑based pricing.  
> 👉 [Request pilot access](https://arf-frontend-sandy.vercel.app/signup)

---

## ✨ What this demo shows

- **Beta‑Binomial conjugate prior updates** – online risk scoring with adjustable priors and observations.
- **Hybrid risk blending** – combines conjugate online updates with a simulated HMC (offline) component.
- **Mock semantic memory retrieval** – pre‑defined similar incidents to illustrate FAISS‑based retrieval.
- **Deterministic policy thresholds** – approve / escalate / deny based on configurable risk thresholds.
- **Metropolis‑Hastings MCMC** – trace and posterior visualisation to illustrate Bayesian inference.
- **Loss‑aversion messaging** – shows estimated monthly savings or costs based on the decision.
- **Fully responsive layout** – works seamlessly on desktop, tablet, and mobile devices.

**All numbers are illustrative and do not reflect the actual Bayesian engine.**

---

## 🧪 Live Demo

The demo is hosted at:  
[https://arf-foundation.github.io/arf-risk-demo/](https://arf-foundation.github.io/arf-risk-demo/)

---

## 📦 Public vs. Private

| Component | Status |
|-----------|--------|
| This risk demo (HTML/CSS/JS) | ✅ Public – Apache 2.0 |
| ARF core engine (`agentic_reliability_framework`) | 🔒 Private – pilot only |
| Production API (`arf-api`) | 🔒 Private – pilot only |
| Enterprise extensions | 🔒 Private – enterprise only |

---

## 🚀 Local Development

To run the demo locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/arf-foundation/arf-risk-demo.git
   cd arf-risk-demo
   ```
   
   Open `index.html` in your browser (no build step required).

All JavaScript and Plotly dependencies are loaded from CDNs – the demo works offline once cached.

## 🛠️ Technical Notes

- **No backend** – everything runs in the browser.
- **Simulated HMC** – the hybrid risk engine uses a slider to mimic offline HMC predictions; real HMC uses `pymc` and is not included here.
- **Mock semantic memory** – the memory store is a static array; real FAISS retrieval is part of the protected engine.
- **MCMC** – a simple Metropolis‑Hastings sampler illustrates posterior sampling; real HMC uses NUTS.

## 📄 License

This repository is licensed under **Apache 2.0**.  
The license applies **only** to the demo code in this repo – it does **not** cover the proprietary ARF core engine.

## 🤝 Contributing

We accept limited contributions (bug fixes, documentation, demo improvements).  
**We do not accept pull requests that attempt to connect this demo to a real backend.**

1. Open an issue describing your proposed change.
2. Wait for maintainer approval.
3. Submit a pull request.

For questions about the real engine or pilot access, **do not open issues** – email us directly.

## 📬 Contact

- Email: [petter2025us@outlook.com](mailto:petter2025us@outlook.com)
- Pilot access form: [Request Pilot Access](https://arf-frontend-sandy.vercel.app/signup)

---

*Stewarded by the founder – pilot‑first, outcome‑based pricing.*
