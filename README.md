# Hi, I'm Shannon 👋

I'm a Customer Success leader with 15+ years building and scaling CS teams at SaaS companies. I'm currently on parental leave and using the time to build real AI skills — not just talk about them.

---

## What I'm Building

### 🤖 Job Search Agent
I built an AI agent to help with my own job search. It autonomously finds relevant roles across multiple job titles, scores them against my background, flags red flags, generates tailored cover letters and resume rewrites, and logs strong matches to a tracker — running every morning without me touching it.

**What it actually does:**
- Searches Google Jobs via SerpAPI across multiple job titles simultaneously
- Scores each role against my resume using the Claude API
- Deep-dives on strong matches by fetching the full job posting
- Checks for duplicates before logging — it has memory across runs
- Generates a tailored cover letter and rewrites resume bullets (with reasoning) for every strong match
- Logs everything to Google Sheets automatically
- Runs daily via GitHub Actions — no manual trigger needed

→ [View the overview](https://github.com/slacy77/job-search-agent-overview)

---

### 🚨 Churn Risk Monitor
A prototype AI agent that analyzes customer account data and produces a prioritized churn risk report — the kind of synthesis that normally requires checking 3-4 different CS tools.

**What it actually does:**
- Reads account health data — health scores, support tickets, NPS, renewal timelines, exec sponsor status, CSM notes
- Scores churn risk High/Medium/Low with Claude, grounded in the specific account data
- Identifies the 2 most important risk factors and 2 targeted next steps per account — no generic advice
- Logs everything to Google Sheets, organized by risk level
- Calculates total ARR at risk across the portfolio

Built using mock data (no real customer data involved), with a clear map of how each piece would connect to real CS tools — Salesforce, Gainsight, Gong, Zendesk.

→ [View the overview](https://github.com/slacy77/churn-risk-monitor-overview)

---

## Why I'm Building These

I wanted to understand AI agents from the inside — not just use them. Both projects follow the same core pattern: read data → analyze with Claude → make a decision → log a structured, actionable output. Once you understand that pattern, it applies to almost any CS workflow — onboarding tracking, QBR prep, voice-of-customer analysis, and more.

Neither project fabricates information. The cover letter and resume rewriter surface and reframe my real experience; the churn monitor's recommendations are grounded in the actual account data. AI here is doing synthesis and pattern-matching at scale — the judgment calls stay with me.

---

## My Background

- **15+ years** in Customer Success at SaaS companies
- Led CS teams of up to 15 CSMs across SMB and Mid-Market segments
- Experience owning GRR/NRR outcomes, building CS playbooks from scratch, and implementing CS platforms
- Currently building hands-on AI skills to complement CS leadership experience

---

## Skills I'm Building
`Claude API` `Python` `AI Agent Development` `Prompt Engineering` `GitHub Actions` `Google Sheets API` `Web Scraping` `Workflow Automation` `End-to-End System Design`

---

*Open to Customer Success leadership roles. Building in public while I search.*
