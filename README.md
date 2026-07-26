# Aakash R

**Automation & data engineering for consultancies and service businesses.**

I build the operational layer that companies run on — client intake, payments, scheduling, document handling, follow-up — and the data infrastructure underneath it. Most automation looks fine in a demo and falls apart by week three. I build for the edge cases first: the retry that never fires, the record that silently duplicates, the booking made against hours already spent.

Currently available for freelance work.

<a href="https://www.linkedin.com/in/aakash-r-3238bb376/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://www.upwork.com/freelancers/aakash0r">
  <img src="https://img.shields.io/badge/Upwork-14A800?style=flat-square&logo=upwork&logoColor=white" alt="Upwork" />
</a>
<a href="https://aakashr.com">
  <img src="https://img.shields.io/badge/Portfolio-1F2328?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" />
</a>
<a href="mailto:aakash13011990@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
</a>

---

## What I build

**Workflow & CRM automation** — Multi-stage pipelines with automated progression, payment-linked entitlements, conditional follow-up sequences, and exit logic that stops messaging people the moment they reply.

**Data pipelines & extraction** — Large-scale scrapers with rotating proxies and rate-limit handling, plus the cleaning and validation layer that makes the output actually usable.

**Backend systems** — Real-time services in Go and Python, backed by PostgreSQL and Redis.

**LLM-powered tools** — Agents and internal tools built on model APIs, wired into existing business systems rather than sitting beside them.

---

## Selected work

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **ANTIBOT** | Real-time bot-detection engine. Behavioural and request-level signals scored against a live decision path, built to hold latency under load. | `Go` `PostgreSQL` `Redis` |
| **Catalogue Extraction Engine** | Reconstructed a hidden category tree on a large e-commerce site and pulled 33,000+ product records in ~20 minutes. Rotating proxies, adaptive rate limiting, resumable state. | `Python` `Proxies` |
| **GovCon Client Intake System** | For a US government-contracting consultancy: an 11-stage pipeline with automated progression, Stripe checkout with split-payment plans, and document collection that matches every upload to the right client record. | `GoHighLevel` `Stripe` `Webhooks` |
| **Expert-Time Booking & Credit System** | Sells consulting time as tiered products, credits a minutes-balance on payment, and deducts it on booking through single-use links across shared-availability calendars. | `GoHighLevel` `Stripe` `Custom Values` |
| **Quote Generation Agent** | Automated quote drafting from inbound enquiries — parses the request, pulls pricing context, produces a reviewable draft. | `n8n` `LLM APIs` |

> Client engagements are private repositories. Happy to walk through architecture and implementation on request.

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

Also: GoHighLevel, REST & webhook integrations, SPF/DKIM/DMARC email infrastructure, BeautifulSoup / Playwright, pandas.

---

## How I work

**Map first, build second.** I write down the process before touching a tool. Most automation failures are process failures wearing a technical costume.

**Documented handoff.** Every build ships with a written walkthrough so the team can run and modify the system without me.

**Designed to fail loudly.** Silent failure is worse than no automation. Retries, duplicate guards, and exit conditions get built in from the start, not patched in after something breaks.

---

## Recognition

- **PitchOff 2026** — Alliance University, Bangalore
- **Code2Create** — ACM, VIT
- **e-Yantra 2024** — IIT Bombay

---

## Get in touch

Building something that needs to work on real, messy data? I'd like to hear about it.

**aakash13011990@gmail.com** · [aakashr.com](https://aakashr.com) · [LinkedIn](https://www.linkedin.com/in/aakash-r-3238bb376/)
