# ARF Risk Demo – Governance Layer for Autonomous AI

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen)](https://arf-foundation.github.io/arf-risk-demo/)

This repository contains a **client‑side demo** that illustrates how **ARF (Agentic Reliability Framework)** acts as a **governance layer between autonomous AI agents and production execution.**

It showcases two real‑world AI governance incidents:
- **Air Canada (2023)** – AI chatbot generated a customer policy that conflicted with official policy.
- **PocketOS (2026)** – AI coding agent attempted to delete the production database and all backups.

The demo demonstrates how ARF intercepts autonomous actions, evaluates them against governance policies, and returns one of three decisions: **APPROVE, ESCALATE, or DENY.**

> ⚠️ **Important** – This demo uses **simulated data only**. The real ARF core engine is **access‑controlled** and available only to qualified pilots under outcome‑based pricing.  
> 👉 [Request pilot access](https://www.arf-ai.com/signup)

---

## ✨ What this demo shows

- **Two real‑world AI governance incidents** – Air Canada chatbot liability, PocketOS database deletion.
- **Incoming action interception** – ARF sits between the AI agent and production execution.
- **Governance decision engine** – APPROVE, ESCALATE, or DENY based on policy evaluation.
- **Audit trail with latency metrics** – complete governance timeline with decision latency.
- **Counterfactual comparison** – see what happens with and without ARF governance.
- **Technical analysis** – Bayesian risk scoring, credible intervals, and posterior distribution (collapsible).
- **Fully responsive layout** – works seamlessly on desktop, tablet, and mobile.
- **Complex visual animations** – data pulse flow, quantum burst decision reveal, typewriter audit trail, and more.

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

---

## 🛠️ Technical Notes

- **No backend** – everything runs in the browser.
- **Simulated Bayesian engine** – risk scores are computed using Beta‑Binomial conjugate priors; real ARF uses a proprietary Bayesian governance engine.
- **Mock incident data** – scenario details are sourced from public incident reports (Air Canada tribunal ruling, PocketOS outage report).
- **Governance decisions** – APPROVE (risk < 0.2), ESCALATE (0.2–0.8), DENY (risk > 0.8).
- **Audit trail** – simulated governance timeline with configurable latency.

---

## 📸 Screenshots

### Hero Section – AI Agent → ARF Governance → Production
*The hero immediately communicates ARF's position as a governance checkpoint.*

### Decision Panel – ESCALATE Example
*ARF intercepts the action, evaluates risk, and returns a governance decision with a complete audit trail.*

### Counterfactual Comparison
*Toggle between "Without ARF Governance" and "With ARF Governance" to see the value of the governance layer.*

---

## 📄 License

This repository is licensed under **Apache 2.0**.  
The license applies **only** to the demo code in this repo – it does **not** cover the proprietary ARF core engine.

---

## 🤝 Contributing

We accept limited contributions (bug fixes, documentation, demo improvements).  
**We do not accept pull requests that attempt to connect this demo to a real backend.**

1. Open an issue describing your proposed change.
2. Wait for maintainer approval.
3. Submit a pull request.

For questions about the real engine or pilot access, **do not open issues** – email us directly.

---

## 📬 Contact

- Email: [juan@arf-ai.com](mailto:juan@arf-ai.com)
- Website: [https://www.arf-ai.com](https://www.arf-ai.com)
- Pilot access form: [Request Pilot Access](https://www.arf-ai.com/signup)

---

## 🔗 Related Repositories

| Repository | Description |
|------------|-------------|
| [pitch-deck](https://github.com/arf-foundation/pitch-deck) | Public overview and investor materials |
| [arf-spec](https://github.com/arf-foundation/arf-spec) | Public specification and API contracts |

