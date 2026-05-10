# ECSA Program Dashboard

**Education to Career Sovereignty Access** — NJ Pilot Program 2026

A live program monitoring dashboard and participant ecosystem built for the ECSA capstone presentation.

## What This Is

A full-stack web application hosted on Netlify that demonstrates ECSA's technology-enabled program infrastructure — including participant journey tracking, mentor engagement, employer partnerships, career resources with daily job alerts, and a live AI Resume Agent powered by Aria Thompson.

## Sections

- Participant Journey — 24-week program phases
- Outcome Metrics — Four benchmarks tracked through 24 months
- Mentor Engagement — AI-matched relationships with weekly tracking
- Employer Partnerships — Commitment pipeline for all three tracks
- Scale to 5 Million — Five-stage growth pathway to 2035
- Career Resources — Daily job alerts with Aria's coaching
- Participant Profile — Individual profile with credentials and wealth-building
- Message Mentor — Direct secure messaging interface
- Resource Library — Learning, career, and wealth-building materials
- Resume Agent (Aria) — Live AI resume generation

## Setup

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/ecsa-dashboard.git
cd ecsa-dashboard
```

### 2. Connect to Netlify
- Go to netlify.com
- Add new site → Import from Git
- Select this repo
- Build settings are automatic via netlify.toml

### 3. Add your API key
In Netlify → Project configuration → Environment variables:
```
ANTHROPIC_API_KEY = your-key-here
```

### 4. Deploy
Push any change to main branch and Netlify deploys automatically.

## Security

The Anthropic API key is stored securely as a Netlify environment variable. It never appears in the browser or the source code. All Claude API calls are routed through `netlify/functions/resume.js` which runs server-side.

## Built With

- Vanilla HTML/CSS/JS — no frameworks, no build step
- Netlify Functions (Node.js) — secure API proxy
- Claude claude-sonnet-4-20250514 — powers Aria Thompson, the ECSA Resume Agent
- Netlify — hosting and serverless functions

---

*DLJames Consulting · ECSA Capstone · June 6, 2026*
