# ARF Risk Demo – Public Sandbox (Simulated)

This repository contains a **client‑side, simulated risk scoring demo** that illustrates the concepts of Bayesian inference, expected loss minimisation, and semantic memory.  
It is **not connected to the protected ARF core engine** – all calculations are performed locally in the browser using mock data.

> ⚠️ **Important** – This demo uses **simulated data only**. The real ARF core engine is **access‑controlled** and available only to qualified pilots under outcome‑based pricing.  
> 👉 [Request pilot access](https://arf-frontend-sandy.vercel.app/signup)

---

## What this demo shows

- Beta‑Binomial conjugate prior updates (online risk scoring)
- Hybrid risk blending with simulated HMC (offline component)
- Mock semantic memory retrieval (pre‑defined incidents)
- Deterministic policy thresholds (approve/escalate/deny)
- Metropolis‑Hastings MCMC trace and posterior visualisation

**All numbers are illustrative and do not reflect the actual Bayesian engine.**

---

## Public vs. Private

| Component | Status |
|-----------|--------|
| This risk demo (HTML/CSS/JS) | ✅ Public – Apache 2.0 |
| ARF core engine (`agentic_reliability_framework`) | 🔒 Private – pilot only |
| Production API (`arf-api`) | 🔒 Private – pilot only |

---

## Live Demo

The demo is hosted at:  
[https://arf-foundation.github.io/arf-risk-demo/](https://arf-foundation.github.io/arf-risk-demo/)

---

## License

This repository is licensed under **Apache 2.0**.  
The license applies **only** to the demo code in this repo – it does **not** cover the proprietary ARF core engine.

---

## Contact

For pilot access or questions about the real engine, email **petter2025us@outlook.com**.
