# Hi, I'm Vishesh Vandan 👋

BCA student and AI/ML-focused full-stack developer building applied AI tools, security-analysis prototypes, and event platforms used in live college events.

![Skills](https://skillicons.dev/icons?i=py,js,ts,php,react,vite,tailwind,fastapi,nodejs,express,supabase,postgres,firebase,prisma,git,jest,threejs)

**AI Platforms and Tools**

![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-412991?style=flat&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logo=groq&logoColor=white)
![Copilot CLI](https://img.shields.io/badge/GitHub_Copilot_CLI-000000?style=flat&logo=githubcopilot&logoColor=white)

**AI / ML:** OpenCV · scikit-learn · Random Forest · custom k-NN SMOTE  
**Full-stack / backend:** React · TypeScript · FastAPI · Supabase/PostgreSQL · JWT · Pillow · Brevo API  
**Developer tools:** Git · Railway · Rich · Framer Motion · Recharts

---

## 🚀 Featured Projects

### 🔎 [DarkLens — AI-Powered Dark Pattern Forensics](https://github.com/princevshetty-ui/DarkLens)
Built at **Hack4Future 2025** with a four-person team. Analyzes **1–3 checkout/UI screenshots**, maps visible evidence against **13 CCPA dark-pattern categories**, and returns a **0–100 manipulation-intensity score** with confidence levels and legal references. Includes cross-screen comparison for price escalation, new fees, and repeated patterns. Team received positive judge feedback.  
**Stack:** React 19 · FastAPI · Gemini 2.0 Flash Vision · Tailwind · Recharts

### 🏢 IZee Job Fair 2026 — Event Registration & QR Pass Platform *(private repo)*
Full-stack platform for the **8 May 2026** placement drive, supporting pre-registration and walk-ins, admin/volunteer roles, digital QR passes, pass delivery, entry validation, and CSV/Excel reporting. **Live-event outcomes reported by the team: 650+ registrations, 500+ attendees, 50+ volunteers, and 80+ recruiting companies.**  
**Implementation highlights:** React 19/Vite frontend; FastAPI backend; Supabase/PostgreSQL; JWT role-based access; Pillow-based QR passes; Brevo email API; Railway deployment.  
**Stack:** React · FastAPI · Supabase · JWT · Pillow · Brevo · Railway

### 🎭 IZee Got Talent — Cultural Fest Registration & Approval *(private repo)*
Registration system for audience and competitors, with a **two-event selection limit**, pending-to-approved faculty workflow, QR pass generation only after approval, status checking, QR entry validation, faculty dashboard, and CSV export. **Supported 350+ attendees during the live event.**  
**Stack:** React · FastAPI · Supabase/PostgreSQL · QR generation · CSV export

### 💻 [College Code Arena — Live Web App](https://dev-duels-foundation.lovable.app/)
Multi-round debugging competition platform built for a BCA event at IZee Business School. **Round 1:** 30 debugging MCQs in 30 minutes with randomized question/option order and save/resume support. **Round 2:** 10 predefined-answer coding/debugging challenges across easy, medium, and hard levels. Includes server-authoritative timing/scoring, server-side answer validation, one-attempt enforcement, qualification thresholds, registration, results, and admin workflows. These are implemented competition controls, not a formal security audit.  
**Stack:** TypeScript · PostgreSQL · Lovable · server-side validation

### 📈 Zerve-Pulse — Behavioral Power-User Prediction *(hosted on Zerve)*
Random Forest model to identify likely long-term power users from behavioral telemetry rather than relying only on credits or sign-ups. Includes a custom k-NN SMOTE approach for class imbalance and a live REST API. **The project description reports 100% recall and 99.09% precision on 5,410 users; treat these as reported evaluation results until the train/test split, resampling pipeline, and threshold-selection method are documented and reproducible.**  
**Stack:** Python · scikit-learn · Random Forest · custom k-NN SMOTE · REST API

---

## 🛡️ Cybersecurity Projects

### 🛡️ SecureMailScope — Passive Email & TLS Security Analysis
Collaborative SIH 2026 project (SIH 26159). Parses PCAP captures, reconstructs TCP streams and observable SMTP/IMAP/POP3 sessions, examines STARTTLS/STLS behavior and TLS/X.509 certificate evidence, applies deterministic rules and risk scoring, and produces evidence-backed JSON/HTML/PDF reports. The Isolation Forest layer provides advisory anomaly signals; **deterministic rules determine the reported security posture**.

**Verified engineering metrics:** **1,735 automated tests passed**, 35 PCAP fixtures, 29 certificate fixtures, 10 deterministic rules, and 3 report formats. These are engineering/test-suite metrics, not real-world detection-accuracy claims.

**My contribution (team project):** Backend analysis-pipeline work, deterministic security-rule engine and ML advisory integration, risk-scoring/report validation, demo-PCAP scenarios, and judge-facing explanations/demo workflows. This is not a claim of sole authorship.  
**Stack:** Python · Scapy · cryptography · scikit-learn · HTML/CSS/JavaScript

### 🔎 [ThreatDetection AI-Based Detection of Cyber Threats in Unidirectional IP Traffic](https://github.com/princevshetty-ui/threatdetection) *(completed prototype; private repo)*
Passive, read-only analyzer for PCAP and PCAPNG captures. Focuses on offline capture ingestion, unidirectional IP-flow reconstruction, evidence tracking, validation, and documented findings; does not probe monitored hosts or send traffic back into the network. No verified accuracy, throughput, or false-positive-rate benchmark is currently claimed.

**My contribution (team project):** Helped translate the SIH problem statement into technical requirements, shape the passive-ingestion/flow-reconstruction workflow, and review testing, evidence provenance, limitations, and documentation. Not a claim of sole authorship.  
**Stack:** Python · PCAP/PCAPNG · network traffic analysis · cybersecurity

---

## ⚡ Developer Tools & Other Work

### [AURA CLI — Agentic Developer Shield](https://github.com/princevshetty-ui/aura-cli)
A **1,700+ line Python CLI** built for the GitHub Copilot CLI Hackathon. Five modules cover secret/environment-file checks with AI remediation guidance, developer wellness and activity visualization, AI-generated development journals, codebase/complexity and carbon-efficiency audits, and interactive project scaffolding. Uses Copilot CLI as the AI integration and Rich for terminal UI.  
**Stack:** Python · argparse · Rich · GitHub Copilot CLI

**Also building:** PayzonHub (payroll/attendance, private/in progress) · AI Skill Gap Analyzer (in progress) · Roadmap App (AI/ML preparation tracker, live on Vercel)  
**Experimenting with:** Arcane (PDF knowledge graphs) · Nexus Campus OS (multi-tenant RBAC/RLS) · Smart Pitch Validator · StudyMind (RAG)

---

## 🏅 Hackathons & Wins

- **1st Prize — College Codeathon**
- **Special Mention — Debugging Competition**
- Built DarkLens at **Hack4Future 2025**; team received positive judge feedback
- Participated in GitHub Copilot CLI Hackathon and Zerve × HackerEarth

---

## 📌 Academic Details

**BCA — IZee Business School / Bangalore University**  
CGPA: *8.2*

---

*Building at the intersection of applied AI, cybersecurity, and real-world full-stack systems.*
