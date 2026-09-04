<div align="center">

<img src="https://img.shields.io/badge/PSYCH--INTEL-v2.4-e0122f?style=for-the-badge&labelColor=0f1420" alt="version"/>
<img src="https://img.shields.io/badge/STATUS-LIVE-27ae60?style=for-the-badge&labelColor=0f1420" alt="status"/>
<img src="https://img.shields.io/badge/ENGINE-ONLINE-0891b2?style=for-the-badge&labelColor=0f1420" alt="engine"/>

<br/>

# 🛡️ PSY`INTEL`

### Cyber Psychological Intelligence Platform

**Decoding the psychology of digital deception.**

*An AI-assisted behavioral analysis engine that detects psychological manipulation, social engineering, and scam intent inside SMS, email, WhatsApp, phishing content, and call transcripts — in real time.*

<br/>

[![Live Demo](https://img.shields.io/badge/🔴_LIVE_DEMO-karndeepbaror.github.io%2Fpsyintel-e0122f?style=for-the-badge&labelColor=0f1420)](https://karndeepbaror.github.io/psyintel)

<br/>

![HTML5](https://img.shields.io/badge/HTML5-0f1420?style=flat-square&logo=html5&logoColor=e0122f)
![CSS3](https://img.shields.io/badge/CSS3-0f1420?style=flat-square&logo=css3&logoColor=0891b2)
![JavaScript](https://img.shields.io/badge/JavaScript-0f1420?style=flat-square&logo=javascript&logoColor=f7df1e)
![Chart.js](https://img.shields.io/badge/Chart.js-0f1420?style=flat-square&logo=chartdotjs&logoColor=ff6384)
![jsPDF](https://img.shields.io/badge/jsPDF-0f1420?style=flat-square&logo=adobeacrobatreader&logoColor=e0122f)
![License](https://img.shields.io/badge/License-MIT-0f1420?style=flat-square)

</div>

<br/>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Why PsyIntel Exists](#-why-psyintel-exists)
- [Core Features](#-core-features)
- [How the Analysis Engine Works](#-how-the-analysis-engine-works)
- [Screenshots](#-screenshots)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Documentation](#-documentation)
- [Design Philosophy](#-design-philosophy)
- [Roadmap](#-roadmap)
- [Disclaimer](#-disclaimer)
- [Author](#-author)
- [License](#-license)

<br/>

---

## 🧠 Overview

**PsyIntel** is a browser-based **Cyber Psychological Intelligence Platform** built to help everyday users, investigators, and cybercrime analysts understand *why* a scam message works — not just *that* it's a scam.

Instead of a simple spam/not-spam classifier, PsyIntel breaks down a suspicious communication into its **psychological attack surface**: the fear triggers, urgency cues, authority impersonation signals, greed hooks, and pressure tactics that are engineered to override a victim's rational judgement.

Every analysis is treated like a piece of **digital forensic evidence** — complete with a case reference ID, a SHA-256 evidence hash, a timestamped chain of custody, and exportable investigation reports.

> **In short:** paste a message → PsyIntel tells you *what manipulation techniques were used, how confident it is, what the attacker's likely playbook is, and what to do next.*

<br/>

---

## 🎯 Why PsyIntel Exists

Scam and fraud campaigns — fake KYC alerts, OTP fraud, CBI/police impersonation calls, lottery scams, sextortion, fake investment schemes — all rely on the **same underlying psychological formula**: create fear, apply urgency, borrow authority, and remove the target's time to think.

PsyIntel exists to make that formula **visible**. By surfacing the manipulation mechanics in plain sight, it helps:

- 🧓 **Everyday users** recognize manipulation before they act on it
- 🕵️ **Investigators & cybercrime cells** build a documented, exportable case file
- 🏦 **Support & trust-safety teams** triage and categorize incoming threats fast
- 🎓 **Researchers & educators** study scam psychology with real linguistic evidence

<br/>

---

## ✨ Core Features

### 1. 🎯 Real-Time Psychological Threat Scoring
A composite **0–100 Threat Score** derived from weighted indicator density across six psychological dimensions — **Fear, Urgency, Authority, Greed, Pressure,** and **Trust Exploitation** — visualized on an animated circular gauge with a live CRITICAL / HIGH / MEDIUM / LOW verdict badge.

### 2. 🧬 Multi-Format Intelligence Input Module
Analyze content from **7 communication formats**: SMS/Text, Email, WhatsApp, Scam Scripts, Phishing content, Social Media DMs, and Call Transcripts — with drag-and-drop file upload, OCR-based text extraction from screenshots, and multi-language support (**English, Hindi, Hinglish, Auto-Detect**).

### 3. 🕸️ Scam Category Intelligence
Automatically classifies the message against known fraud categories (KYC Scam, OTP Fraud, Impersonation, Phishing, Banking Scam, and more) with individual confidence percentages, so you know exactly which playbook is in play.

### 4. 🎭 Known Campaign Signature Matching
Cross-references the message against a local library of **recurring, previously reported Indian scam-campaign scripts** — flagging when a message follows a known fraud template versus a novel one.

### 5. 🔍 Threat Language Detection (Inline Highlighting)
Renders the original message with **color-coded inline highlighting** over every phrase that triggers Fear, Urgency, Authority, Greed, or Pressure signals — turning invisible manipulation into a visible, annotated document.

### 6. 🧩 Behavioral Fingerprinting
Profiles the *attacker*, not just the message — surfacing sentence structure style, repetition patterns, manipulation style (e.g. *fear-urgency escalation cycle*), persuasion structure (e.g. *Cialdini authority + scarcity principles*), likely attacker profile, and communication register.

### 7. 🏷️ Entity Extraction Engine
Pulls out every actionable artifact from the text automatically: **phone numbers, URLs, email addresses, organization names, financial amounts, UPI IDs, IFSC codes, crypto wallet addresses,** and **bank account numbers.**

### 8. 🌐 URL & Domain Intelligence
Inspects every extracted link for spoofed-domain patterns and suspicious hosting signatures commonly used in phishing infrastructure.

### 9. 📊 Emotional Pressure Radar Chart
A live **Chart.js-powered radar visualization** plotting the six psychological indicators simultaneously — giving investigators an instant "shape" of the emotional attack.

### 10. 🗺️ Investigation Timeline & Relationship Map
Auto-generates a phase-by-phase attack timeline (*Contact → Pressure → Extraction*) alongside a node-based relationship map connecting the target to each manipulation vector (Fear, Authority, Greed, Urgency, Pressure).

### 11. 🔥 Suspicious Wording Density Heatmap
A grid-based heatmap (Clean / Moderate / High / Critical) visualizing the concentration of manipulative language across the message.

### 12. 🤖 AI Recommendations & Intel Report
Generates concrete, actionable next steps — reporting channels, evidence preservation guidance, and pattern-specific advice — written like a real investigator's notes.

### 13. 🔐 Forensic Evidence Chain
Every case is issued a unique **Case ID** (`CA-PSY-YYYYMMDD-XXXXX`), a **SHA-256 evidence hash** of the input, and a fully timestamped **Chain of Custody log** recording every action taken on the evidence.

### 14. 📤 Multi-Format Evidence Export System
One-click export as a **formatted PDF report** (via jsPDF, complete with letterhead, sectioned findings, and page footers), **JSON**, **CSV**, plain-text **Intel Report**, browser print, or a copyable evidence hash.

### 15. 💬 AI Investigator Chat Assistant
An embedded conversational panel that responds with investigator-level psychological insight on demand.

### 16. 📡 Live Scam Feed & Session Intelligence
A real-time simulated feed of trending scam phrases, plus a persistent **session stats panel** (analyses run, threats found, dominant scam type, detected language) and a **local case history** so investigators can revisit prior analyses.

<br/>

---

## ⚙️ How the Analysis Engine Works

PsyIntel's engine runs entirely **client-side** — no message content ever leaves the browser. The pipeline follows five deliberate stages:

```
① INPUT NORMALIZATION
   → Text is cleaned, language-tagged (EN/HI/Hinglish), and prepared for scanning

② LINGUISTIC PATTERN MATCHING
   → Scans for known fear, urgency, authority, greed & pressure trigger-word clusters

③ ENTITY & INFRASTRUCTURE EXTRACTION
   → Phone numbers, UPI IDs, IFSC codes, wallets, and URLs pulled via pattern recognition

④ CAMPAIGN CROSS-REFERENCING
   → Content is matched against a local library of known Indian scam-campaign scripts

⑤ COMPOSITE THREAT SCORING
   → A weighted 0–100 threat score is derived from indicator density,
     rendering the final verdict + full behavioral & forensic report
```

> ⚖️ **Methodology note:** PsyIntel is a **decision-support tool**, not a legal determination engine. Its output is designed to *assist* investigators and equip everyday users with clarity — always corroborate findings with independent evidence before acting on them formally.

<br/>

---

## 📸 Screenshots

> Full desktop views of the live platform — dashboard, analysis engine, and forensic tooling in action.

| | |
|---|---|
| **Homepage & Hero** | **Threat Score Dashboard** |
| Landing experience with live stats bar | Real-time 0–100 threat gauge + indicators |
| **Threat Language Detection** | **Entity Extraction** |
| Inline highlighted manipulation phrases | Auto-extracted phones, URLs, UPI IDs & more |
| **Emotional Pressure Radar + Timeline** | **Suspicious Wording Heatmap** |
| 6-axis psychological radar + attack phases | Density-mapped manipulation hotspots |
| **Chain of Custody + Methodology** | **Evidence Export System** |
| Forensic audit trail | PDF / JSON / CSV / Print / Hash export |

*(See `/documentation/screenshots` for the full high-resolution gallery.)*

<br/>

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| **Markup & Structure** | Semantic HTML5 |
| **Styling** | Hand-crafted CSS3 — custom design tokens, CSS variables, glassmorphism, radial-gradient ambient backgrounds |
| **Typography** | `Space Grotesk` (display), `Inter` (body), `JetBrains Mono` (data/technical) via Google Fonts |
| **Logic Engine** | Vanilla JavaScript (ES6+) — zero framework overhead |
| **Data Visualization** | [Chart.js](https://www.chartjs.org/) — radar chart rendering |
| **PDF Generation** | [jsPDF](https://github.com/parallax/jsPDF) — client-side forensic report export |
| **Cryptographic Hashing** | Web Crypto API (`crypto.subtle.digest`, SHA-256) |
| **Persistence** | `localStorage` — session case history |
| **Hosting** | GitHub Pages / Netlify (static SSR-free deployment) |

<br/>

---

## 🚀 Getting Started

### Live Version
Simply visit the hosted platform — no installation required:

**🔗 [karndeepbaror.github.io/psyintel](https://karndeepbaror.github.io/psyintel)**

No build step, no dependencies to install, no backend required — PsyIntel is **100% static and self-contained.**

<br/>

---

## 📁 Project Structure

```
psyintel/
├── index.html                  # Core application — UI + engine logic
├── js/
│   ├── chart.umd.js            # Chart.js — radar visualization
│   └── jspdf.umd.min.js        # jsPDF — PDF report generation
├── documentation/              # 📚 Full software documentation (see below)
│   ├── features/               # Deep-dive per-feature explainers
│   ├── architecture/           # System design & data-flow docs
│   └── screenshots/            # Full-resolution UI gallery
└── README.md                   # You are here
```

<br/>

---

## 📚 Documentation

A full software-grade documentation set lives inside [`/documentation`](./documentation), covering:

- 📄 Per-feature technical breakdowns — what each module does and why it was designed that way
- 🏗️ System architecture & data-flow diagrams
- 🧮 Scoring methodology & indicator weighting logic
- 🖼️ Complete high-resolution screenshot gallery
- 🔐 Forensic/evidentiary design rationale

> *(This section is actively being expanded — check back for the full documentation release.)*

<br/>

---

## 🎨 Design Philosophy

PsyIntel's interface is deliberately styled as a **forensic command console** rather than a consumer app:

- **Clinical, high-contrast light theme** — evidence should be legible, not decorative
- **Signal-red accent system** (`#e0122f`) reserved exclusively for threat/critical states
- **Monospace data typography** (`JetBrains Mono`) for anything resembling evidence — case IDs, hashes, timestamps
- **Glass-panel cards + subtle grain texture** for a premium, layered "intelligence dashboard" feel
- **Micro-interactions** — pulsing live indicators, animated score rings, typewriter hero text — to reinforce a sense of an *always-on, live engine*

<br/>

---

## 🗺️ Roadmap

- [ ] Expanded multilingual scam-pattern library (regional Indian languages)
- [ ] Browser extension for inline message scanning
- [ ] Shareable, anonymized case reports for community threat intelligence
- [ ] API layer for programmatic threat scoring
- [ ] Dark mode command-console theme

<br/>

---

## ⚠️ Disclaimer

PsyIntel is an **educational and decision-support tool**. Its threat scores and pattern matches are generated via automated linguistic heuristics and are **not legal proof of criminal intent**. Always corroborate findings with independent evidence and report suspected fraud through official channels:

📞 **National Cyber Crime Helpline: 1930** &nbsp;|&nbsp; 🌐 **[cybercrime.gov.in](https://cybercrime.gov.in)**

<br/>

---

## 🙌 Developer & Credits

<div align="center">


### 👤 Karndeep Baror

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-karndeepbaror-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karndeepbaror)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/cryptonicarea)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/cryptonicarea)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@CryptonicArea)
[![Telegram](https://img.shields.io/badge/Telegram-Join-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/cryptonicarea)
[![X](https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/cryptonicarea)

<br/>

---

<br/>

![Stars](https://img.shields.io/badge/⭐-Star%20this%20repo%20if%20WRAITH%20helped%20you-FFD60A?style=for-the-badge&labelColor=0b0e14)

<br/>

## 📜 License

Released under the **MIT License** — free to use, modify, and distribute.

<br/>

<div align="center">

**PSY`INTEL` — Understanding the psychology behind the scam.**

[![Live Demo](https://img.shields.io/badge/🔴_Launch_PsyIntel-e0122f?style=for-the-badge&labelColor=0f1420)](https://karndeepbaror.github.io/psyintel)

</div>
