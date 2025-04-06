# 🤖 AutoPR Sentinel

AutoPR Sentinel is an AI-powered GitHub bot designed to streamline the pull request (PR) review process in open-source and team-based projects. It ensures every incoming PR adheres to the project’s code style, structure, and standards — before even touching the main branch.

---

## 📖 Story

Open-source maintainers and small dev teams often struggle with a flood of inconsistent pull requests that don’t follow established coding patterns, leading to burnout and slow development. AutoPR Sentinel solves this by acting as an automated reviewer — it scans your codebase, learns your style, and flags any mismatches in PRs. From naming conventions to architecture decisions, the bot ensures every PR aligns with your project’s DNA. Once a PR passes style and quality checks, it’s auto-tested in a sandbox — no human effort wasted on broken or misaligned contributions.

---

## Demo UI

![image](https://github.com/user-attachments/assets/127c7586-cf3c-425d-8d98-56b23fecce3f)
![image](https://github.com/user-attachments/assets/8fa8e1c9-872f-4cb7-89d8-b94657b7084a)
![image](https://github.com/user-attachments/assets/e4a3ca88-53d6-4a77-8e50-6d9c25e036a9)
![image](https://github.com/user-attachments/assets/7bd86c77-3a91-45fe-8f15-54efc3be1e7e)
![image](https://github.com/user-attachments/assets/ef951e34-77d1-420a-8029-5ed13e8a2792)


visit : [Landing Page](https://passionate-seat-044305.framer.app/)

---

## 🚀 Features

- 🔍 Scans entire codebase and builds a vector-based memory
- 🧠 Uses Gemini AI to review PRs against existing code style
- ✅ Flags PRs that match standards and auto-runs test cases
- 🧪 Executes test cases in a sandbox environment
- 💬 Summarizes result for maintainers with pass/fail verdict

---

## 🛠 Tech Stack

- **Frameworks & Libraries**: Next.js, Probot  
- **AI & Automation**: Gemini, Auto-GPT  
- **Languages**: Python, TypeScript, JavaScript  
- **Databases & Caching**: MongoDB, Redis  
- **DevOps & Runtime**: Docker, Sandbox Environments  
- **Integrations & APIs**: Webhooks, REST API  
- **Code Quality & Standards**: ESLint  

---

## 📈 Business Plan

**Target Market**  
- Open-source projects (with 5+ contributors)  
- Indie maintainers & small dev teams  
- Startups (1–10 engineers)  
- Enterprises with internal GitHub usage  

**Market Segments**  
- Free users (OSS visibility)  
- Paid SaaS (private repo automation)  
- Enterprise clients  

**Revenue Model**  
Hybrid model (Free + Premium)  
- 🟡 Free Plan – Public repos, basic PR tools  
- 🟢 Pro Plan – $19/mo, includes private repo support  
- 🔵 Team Plan – $99/mo, supports multiple repos  
- 🔷 Enterprise – Custom pricing with full control & support  

---

## 🔁 Workflow

```mermaid
graph TD;
    A[User] -->|Sign Up| B[GitHub App];
    B --> C[Select Repo];
    C --> D[Our Software Analyzes Codebase];
    D --> E[User Selects Issue Label];
    E --> F[Issue Created];
    F --> G[Bot Jumps to Oldest Issue Containing PR];
    G --> H[Bot Analyzes Issue & PR];
    H --> I[Reads issue, PR title, code changes];
    I --> J[Runs on Sandbox];
    J --> K[Tests PR in sandbox environment];
    K --> L[Runs Testcases];
    L --> M[Execute Testcases];
    M --> N[Summarizes];
```

---

## 📄 License

MIT © 2025
