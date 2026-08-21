<div align="center">

# 🌐 Access-Hire

### An Adaptive Capability Twin for an Inclusive Workforce

*AI is rewriting who gets to work. We make sure it rewrites the rules fairly.*

[![SAP Hackfest](https://img.shields.io/badge/SAP%20Hackfest-Theme%202%3A%20Inclusive%20Workforce-0070F2?style=for-the-badge&logo=sap&logoColor=white)](https://github.com/Devengoyal885/Access-Hire)
[![Team](https://img.shields.io/badge/Team-StarCoders-F2A93B?style=for-the-badge)](#-team-starcoders)
[![License](https://img.shields.io/badge/License-MIT-1C7293?style=for-the-badge)](#-license)
[![Status](https://img.shields.io/badge/Status-Hackathon%20Build-2E9E6B?style=for-the-badge)](#)

[Problem](#-the-problem) · [Solution](#-our-solution) · [Architecture](#-system-architecture) · [Dashboards](#-product-walkthrough) · [Tech Stack](#-tech-stack) · [Team](#-team-starcoders)

</div>

---

## 📌 Table of Contents

- [The Problem](#-the-problem)
- [Our Solution](#-our-solution)
- [Core Concept — The Capability Twin](#-core-concept--the-capability-twin)
- [System Architecture](#-system-architecture)
- [Multi-Agent Ecosystem](#-multi-agent-ecosystem)
- [Evidence-to-Transition Loop](#-evidence-to-transition-loop)
- [Bias Audit & Inclusion Layer](#-bias-audit--inclusion-layer)
- [Product Walkthrough](#-product-walkthrough)
- [Competitive Landscape](#-competitive-landscape)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Our Track Record](#-our-track-record)
- [Team StarCoders](#-team-starcoders)
- [License](#-license)

---

## 🧩 The Problem

> **"The challenge is no longer *will AI take jobs* — it's *who will AI leave behind.*"**

AI is reshaping global employment and creating a **$5.5T global skills gap**. Traditional workforce systems still filter people by:

`Job Title` · `Resume Keywords` · `Degree` · `Certifications` · `Years of Experience`

This creates two blind spots:

| 👤 For Employees | 🏢 For Companies |
|---|---|
| Someone may already have the skills for a new role — but gets rejected because their job title, resume, or degree doesn't match. Real capability stays invisible. | Companies only ask *"what job does this person hold?"* instead of *"what can they do, what's missing, and what could they become?"* — so they hire externally instead of reskilling. |

---

## 💡 Our Solution

**Access-Hire** asks a better question:

> ### "What can this person actually do — and what could they become?"

We built an AI-powered workforce platform with two connected users:

- 👤 **Employee** — *"What can I do, what can I become, and how do I get there?"*
- 🏢 **Company / HR** — *"What capabilities do my employees have, what will we need, and who can I reskill instead of replacing?"*

```
Understand → Transfer → Forecast → Reskill → Verify → Opportunity
```

---

## 🧬 Core Concept — The Capability Twin

Instead of a static label like `Python = Expert`, every person gets a **living, evidence-backed Capability Twin**.

```mermaid
graph LR
    A["🧑 Employee"] --> B["Evidence Engine<br/>Projects · GitHub · Assessments · Work History"]
    B --> C{{"⚡ Capability Twin"}}
    C --> D["Proficiency: 87%"]
    C --> E["Confidence: 94%"]
    C --> F["Recency: High"]
    C --> G["Independent Capability: 81%"]
    C --> H["AI-Assisted Capability: 94%"]

    style C fill:#0B2E4F,stroke:#F2A93B,stroke-width:2px,color:#fff
    style A fill:#1C7293,color:#fff
    style B fill:#F4F7FA,stroke:#1C7293
```

The system knows **what someone can do + how well + where + the evidence proving it** — not just a resume keyword match.

---

## 🏗 System Architecture

The full pipeline — from raw evidence to a verified new opportunity — with governance built in at every high-stakes step.

```mermaid
flowchart TD
    EMP(["👤 Employee"]) --> EE["🔍 Evidence Engine"]
    EE --> CT{{"⚡ Capability Twin"}}
    CT --> CTG["🔗 Capability Transfer Graph"]
    CTG --> AIO["🌐 AI Ontology + Market Intelligence"]
    AIO --> FRF["📈 Future Role Forecast"]
    FRF --> SG["🎯 Skill Gap"]
    SG --> MT["⚡ Minimum Transition Path"]
    MT --> LT["🎓 Learning + Practical Task"]
    LT --> PT["🧪 Practical Test"]
    PT --> VC["✅ Verified Capability"]

    VC --> ED["👤 Employee Dashboard"]
    VC --> CD["🏢 Company Dashboard"]

    ED --> CG["🚀 Career Growth & Opportunities"]
    CD --> WP["📊 Workforce Planning & Reskilling"]

    CG --> HR(["🧑‍⚖️ Human Review"])
    WP --> HR

    style CT fill:#0B2E4F,stroke:#F2A93B,stroke-width:2px,color:#fff
    style VC fill:#2E9E6B,color:#fff
    style HR fill:#F2A93B,color:#0B2E4F,stroke-width:2px
    style ED fill:#1C7293,color:#fff
    style CD fill:#1C7293,color:#fff
```

---

## 🤖 Multi-Agent Ecosystem

Six specialized agents share one Capability Twin — built directly to the SAP Hackfest brief for a **fair, skills-first workforce platform**.

```mermaid
graph TD
    subgraph Agents["Multi-Agent System"]
        SD["🔍 Skills Discovery Agent<br/><i>Builds the Capability Twin<br/>from evidence</i>"]
        MI["📈 Market Intelligence Agent<br/><i>Tracks skills → tasks → jobs<br/>→ market demand</i>"]
        LP["🎓 Learning Pathway Agent<br/><i>Calculates the minimum<br/>reskilling path</i>"]
        IM["🤝 Inclusive Matching Agent<br/><i>Matches on capability,<br/>never pedigree</i>"]
        BA["⚖️ Bias Audit Agent<br/><i>Screens every recommendation<br/>for bias</i>"]
        HL["🧑 Human-in-the-Loop<br/><i>Final review on<br/>high-stakes calls</i>"]
    end

    SD --> CORE{{"⚡ Capability Twin<br/>Core Engine"}}
    MI --> CORE
    LP --> CORE
    IM --> CORE
    CORE --> BA
    BA --> HL
    HL --> OUT(["✅ Trusted Recommendation"])

    style CORE fill:#0B2E4F,stroke:#F2A93B,stroke-width:3px,color:#fff
    style BA fill:#F2A93B,color:#0B2E4F
    style HL fill:#1C7293,color:#fff
    style OUT fill:#2E9E6B,color:#fff
```

---

## 🔁 Evidence-to-Transition Loop

We don't just *recommend* learning — we **verify** whether someone actually became capable.

```mermaid
flowchart LR
    C1(["1️⃣ Current<br/>Capability"]) --> C2(["2️⃣ Transferability<br/>Score"])
    C2 --> C3(["3️⃣ Missing<br/>Capability"])
    C3 --> C4(["4️⃣ Minimum<br/>Learning"])
    C4 --> C5(["5️⃣ Practical<br/>Work"])
    C5 --> C6(["6️⃣ Verified<br/>Capability"])
    C6 --> C7(["7️⃣ New Role /<br/>Opportunity"])
    C7 -. "New evidence updates the Twin" .-> C1

    style C1 fill:#1C7293,color:#fff
    style C2 fill:#1C7293,color:#fff
    style C3 fill:#1C7293,color:#fff
    style C4 fill:#1C7293,color:#fff
    style C5 fill:#1C7293,color:#fff
    style C6 fill:#2E9E6B,color:#fff
    style C7 fill:#F2A93B,color:#0B2E4F
```

> 💬 *"Learning ≠ readiness. Performance on real, practical work is what unlocks the next opportunity."*

---

## ⚖️ Bias Audit & Inclusion Layer

Fairness is architecture, not a feature.

| ❌ We ignore | ✅ We weigh instead |
|---|---|
| College name | Demonstrated capability |
| Location | Transferable capability |
| Career gap | Verified evidence |
| Previous job title alone | Growth potential |
| Formal credential alone | Accessibility & flexibility needs |

```mermaid
flowchart LR
    R(["Recommendation"]) --> BA(["Bias Audit"])
    BA --> D{"Bias<br/>Detected?"}
    D -- Yes --> HR(["🧑‍⚖️ Human Review"])
    D -- No --> OUT(["✅ Approved"])

    style D fill:#F2A93B,color:#0B2E4F
    style HR fill:#0B2E4F,color:#fff
    style OUT fill:#2E9E6B,color:#fff
```

The AI recommends. **Humans make the final high-stakes decisions — always.**

---

## 📊 Product Walkthrough

<table>
<tr>
<td width="50%" valign="top">

### 👤 Employee Dashboard

```
MY CAPABILITY TWIN
────────────────────
Python              87%  ████████▋
Backend             81%  ████████
SQL                 82%  ████████
Cloud                64%  ██████▍
AI                    58%  █████▊

FUTURE OPPORTUNITIES
────────────────────
AI Operations        74%
AI Engineer            71%
Cloud Engineer     68%

RECOMMENDED GROWTH
────────────────────
▸ AI Evaluation
▸ Agent Orchestration
▸ Cloud AI Deployment
```

</td>
<td width="50%" valign="top">

### 🏢 Company Workforce Dashboard

```
COMPANY WORKFORCE — 10,000 EMPLOYEES
────────────────────
AI                    42%  ████▌
Cloud                58%  ██████
Data                  61%  ██████▎
Cybersecurity     37%  ████

WORKFORCE GAP
────────────────────
AI Engineering        1,240
AI Security                680
Cloud AI                     520

"We don't need to hire 1,240 people
— we can reskill from within."
```

</td>
</tr>
</table>

---

## 🥊 Competitive Landscape

| Platform | Their Strongest Point | Where Access-Hire Goes Further |
|---|---|---|
| **Eightfold AI** | Talent intelligence & trajectory prediction | Prove readiness through practical work, not just inference |
| **Workday Skills Cloud** | Deep HCM & employee data integration | Add a transition-readiness layer on top of the skills graph |
| **SAP Talent Intelligence Hub** | Native SAP HCM ecosystem | Complement SAP — extend skills into verified transitions |
| **Beamery** | Workforce digital twin & task intelligence | Make it employee-transition-centric with proof, not just data |
| **Gloat** | Opportunity marketplace matching | Be the readiness engine that runs *before* marketplace matching |
| **Phenom** | Skills ontology & career pathing | Make transitions measurable and experimentally verified |

---

## 🛠 Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

</div>

> ℹ️ Update the badges above to match the exact stack used in this repository (backend framework, database, ML/AI libraries, etc.) as the implementation evolves.

---

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/Devengoyal885/Access-Hire.git
cd Access-Hire

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env.local
# Fill in the required API keys / config values

# 4. Run the development server
npm run dev
```

The app should now be running at `http://localhost:3000` 🎉

---

## 🏆 Our Track Record

StarCoders doesn't just pitch — we ship. Access-Hire is our latest build.

| Project | Description | Link |
|---|---|---|
| **CodeXPath** | An AI-assisted platform for navigating and understanding code paths | [code-x-path.vercel.app](https://code-x-path.vercel.app/) |
| **Opportunity Radar AI** | Discovers and surfaces relevant opportunities through an AI-driven dashboard | [opportunity-radar-ai.netlify.app](https://opportunity-radar-ai.netlify.app/dashboard) |
| **Access-Hire** | Adaptive Capability Twin for an Inclusive Workforce *(this project)* | [github.com/Devengoyal885/Access-Hire](https://github.com/Devengoyal885/Access-Hire) |

---

## 👨‍💻 Team StarCoders

<div align="center">

| Avatar | Name | GitHub | LinkedIn |
|:---:|---|:---:|:---:|
| 🧑‍💻 | **Deven Goyal** | [@Devengoyal885](https://github.com/Devengoyal885) | [LinkedIn](https://www.linkedin.com/in/deven-goyal/) |
| 🧑‍💻 | **Gurleen Kaur Bedi** | [@Gurleen12star](https://github.com/Gurleen12star) | [LinkedIn](https://www.linkedin.com/in/gurleen-kaur-bedi-296305314/) |
| 🧑‍💻 | **Ridhi Bansal** | [@RidhiiBansal](https://github.com/RidhiiBansal) | [LinkedIn](https://www.linkedin.com/in/ridhi-bansal-42a700317/) |
| 🧑‍💻 | **Bani Kaur** | [@banikaur22](https://github.com/banikaur22) | [LinkedIn](https://www.linkedin.com/in/bani-kaur-3b7283217/) |
| 🧑‍💻 | **Aryan Yadav** | [@aryanrao](https://github.com/aryanrao) | [LinkedIn](https://www.linkedin.com/in/aryanyadav05/) |

*Full-stack builders — from AI product design to shipped, live applications.*

</div>

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### 🌟 Let's build the fair future of work — together.

**Team StarCoders** · SAP Hackfest 2026 · Theme 2: Inclusive Workforce

⭐ If you like this project, consider giving it a star on [GitHub](https://github.com/Devengoyal885/Access-Hire)!

</div>
