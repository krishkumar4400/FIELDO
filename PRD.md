# FIELDO

## Complete Product Documentation v1.0

### AI-Powered Dispatch & Scheduling Intelligence for Skilled Trades

---

> **"Kaam sahi jagah, sahi waqt, sahi insaan."**
> *The right job, the right time, the right person.*

---

## Table of Contents

1. [Product Name & Brand Identity](#1-product-name--brand-identity)
2. [Executive Summary](#2-executive-summary)
3. [Problem Statement](#3-problem-statement)
4. [Solution Overview](#4-solution-overview)
5. [Target Market & User Personas](#5-target-market--user-personas)
6. [Core Features — Detailed Specification](#6-core-features--detailed-specification)
7. [User Flows & Journey Maps](#7-user-flows--journey-maps)
8. [Technical Architecture](#8-technical-architecture)
9. [Tech Stack](#9-tech-stack)
10. [Database Schema](#10-database-schema)
11. [API Design](#11-api-design)
12. [AI & ML Systems](#12-ai--ml-systems)
13. [Business Model & Pricing](#13-business-model--pricing)
14. [Go-to-Market Strategy](#14-go-to-market-strategy)
15. [Product Roadmap](#15-product-roadmap)
16. [Competitive Analysis](#16-competitive-analysis)
17. [KPIs & Success Metrics](#17-kpis--success-metrics)
18. [Security & Privacy](#18-security--privacy)
19. [Risks & Mitigations](#19-risks--mitigations)
20. [Appendix](#20-appendix)

---

# 1. Product Name & Brand Identity

## The Name: FIELDO

**Pronunciation:** Feel-doh
**Tagline:** *Smart dispatch. Faster jobs. Happy customers.*
**Hindi tagline:** *Ek tap mein sahi technician, har baar.*

### Why "Fieldo"

| Element | Meaning |
|---|---|
| **Field** | Where the work happens — the field, not the office |
| **-o** | A warm, approachable suffix used in successful Indian startups (Meesho, Swiggy, Zomato) |
| **Together** | "Field operations" compressed into something a trades owner can say and remember |

The name is short (6 letters), easy to spell in Hindi and English, works as a domain (`fieldo.in`, `fieldo.app`), and feels like a tool — not a corporate product. When an HVAC owner tells his friend "Use Fieldo bhai," it sounds natural.


### Brand Personality

- **Tone:** Direct, warm, no-nonsense — like a smart friend in the business
- **Color palette:** Deep navy (#1A1A3E) + electric amber (#F59E0B) + clean white
- **Typography:** Bold, readable, works on low-resolution screens (many trade owners have budget Android phones)
- **Logo concept:** A stylized location pin with a wrench inside — field + trade in one icon

---

# 2. Executive Summary

## What is Fieldo?

Fieldo is an AI-powered dispatch and job management platform built exclusively for small and medium-sized skilled trade businesses — HVAC, plumbing, and electrical service companies with 5 to 100 technicians.

Fieldo replaces the WhatsApp groups, phone calls, paper job cards, and gut-feel decisions that currently run these businesses. It gives owners a real-time view of all jobs and all technicians, suggests the optimal technician for each job using AI, and keeps customers informed automatically — all from a single screen.

## The One-Line Pitch

> **Fieldo tells you which technician to send to which job, so you stop wasting money, time, and customers.**

## The Opportunity

- 500,000+ skilled trade service companies in India alone
- Average company loses ₹3–8 lakh per year to dispatch inefficiency
- 90% of these companies run on WhatsApp + phone calls + intuition
- No Indian-built, affordable, AI-native dispatch tool exists
- Proven willingness to pay: ServiceTitan (US equivalent) charges $300–$600/month and companies pay it

## The Business

- SaaS subscription, ₹2,999–₹9,999/month per company
- Target: 100 paying customers in 18 months → ₹30L ARR
- Path to ₹10 crore ARR: 1,000 customers across 5 trades in 10 cities
- Long-term vision: The operating system for every skilled trade business in India

---

# 3. Problem Statement

## The World Inside a Small Trade Company

Meet Ramesh. He runs a 15-technician AC service company in Pune. His mornings look like this:

1. Phone rings at 8:15 AM — customer wants AC repair today
2. Ramesh looks at a whiteboard with technician names and some scribbled job locations
3. He calls Suresh to check where he is — Suresh doesn't pick up
4. He sends a WhatsApp message to the group — "Kaun free hai Kothrud area mein?"
5. Three people reply. Ramesh picks one based on memory
6. The chosen technician — Anil — gets sent. But Anil doesn't know how to fix inverter ACs
7. Anil goes, can't fix it, customer is angry, Ramesh has to send Suresh anyway
8. Two technicians wasted half a day. Customer leaves a 2-star Google review.

This is not an unusual day. This is every day.

## The Problems — Quantified

### Problem 1: Wrong technician dispatched

**What happens:** Customer needs inverter AC repair. Owner sends the technician nearest on the map — not the one with that skill. Technician arrives, can't fix it, has to call another tech.

**Cost per incident:**

- Wasted trip: 1.5 hours × ₹300/hour labour cost = ₹450
- Customer callback needed: second trip = ₹450 more
- Customer satisfaction: near-zero → potential churn
- **Estimated frequency:** 4–8 times per week for a 15-tech company
- **Annual cost:** ₹1.87L – ₹3.74L per year from this issue alone

### Problem 2: Dispatcher/owner time wasted on coordination

**What happens:** For each job, the owner or supervisor spends 10–20 minutes on calls and messages to find and assign a technician.

**Cost per incident:**

- Owner time: 15 min × 20 jobs/day = 5 hours/day on dispatch coordination
- Owner's opportunity cost: ₹500/hour = ₹2,500/day = ₹75,000/month
- That's time not spent on customer relationships, sales, or quality checks

### Problem 3: No visibility = no accountability

**What happens:** Owner doesn't know where technicians are, what job they're on, or when they'll be done. He finds out when a customer complains.

**Cost per incident:**

- Delayed jobs trigger customer escalation calls (30 min of owner time)
- Job status unknown = can't accept new bookings confidently
- Technician idle time invisible → paid but not working

### Problem 4: Customer communication is manual

**What happens:** Customer calls to ask "Technician kab aayega?" Owner has to call the technician, then call the customer back.

**Cost per incident:**

- 3 phone calls per job × 20 jobs/day = 60 extra calls/day
- Each call: 5 minutes = 5 hours/day on status update calls
- Customer frustration when no one picks up → negative reviews

### Problem 5: No historical data = no learning

**What happens:** Every dispatch decision starts from zero. Owner doesn't know which technician has the best first-call-fix rate, which area takes the most time, or which customer type is most profitable.

**Cost:** No optimization possible without data. Business grows only through experience, not insight.

## Total Annual Cost of These Problems

For a typical 15-technician HVAC company:

| Problem | Annual Cost |
|---|---|
| Wrong technician dispatched | ₹1,87,000 – ₹3,74,000 |
| Owner time on coordination | ₹9,00,000 |
| Customer churn from poor service | ₹2,00,000 – ₹5,00,000 |
| Customer communication waste | ₹3,00,000 |
| **Total estimated loss** | **₹15,87,000 – ₹20,74,000/year** |

Fieldo at ₹5,999/month = ₹71,988/year. The ROI pitch writes itself.

## Why Current Solutions Fail

| Solution | What They Do | Why They Fail |
|---|---|---|
| WhatsApp | Group messages | No structure, no history, no AI, creates chaos at scale |
| Phone calls | Verbal assignment | No record, no tracking, completely manual |
| Paper job cards | Written records | No real-time visibility, gets lost, not searchable |
| Jobber / Housecall Pro (US) | Basic scheduling | Built for US, expensive, no Hindi, no UPI, poor India UX |
| Zoho Field Service | Enterprise CRM | Complex, expensive, requires IT setup, not SME-friendly |
| Google Sheets | Manual tracking | No mobile, no automation, no AI, breaks at 10+ technicians |

**The gap:** No Indian-built, affordable, AI-native dispatch tool exists for trade SMEs. This is the white space Fieldo owns.

---

# 4. Solution Overview

## What Fieldo Does

Fieldo is a three-sided platform connecting:

1. **The Owner/Dispatcher** — gets a unified command center for all jobs and technicians
2. **The Technician** — gets a mobile app that replaces WhatsApp for job updates
3. **The Customer** — gets automatic WhatsApp updates so they never have to call

## The Core Workflow Fieldo Enables

```
Customer calls/books job
         ↓
Job created in Fieldo (owner or auto via call transcription)
         ↓
AI analyzes: skills needed, technician proximity, current workload, job history
         ↓
Fieldo suggests: "Send Raju — 2.1km away, AC inverter certified, currently free"
         ↓
Owner clicks "Assign" (one tap)
         ↓
Raju gets notification on his app: job address, customer name, job details
         ↓
Customer gets WhatsApp: "Raju is on his way. Expected arrival: 11:30 AM"
         ↓
Raju marks "Arrived" → customer gets notification
         ↓
Raju marks "Completed" → owner sees job done → invoice generated
         ↓
Data saved: job type, duration, technician, outcome → AI gets smarter
```

## What Makes Fieldo Different

| Feature | WhatsApp + Calls | Fieldo |
|---|---|---|
| Dispatch decision | Gut feel | AI suggestion with reasons |
| Technician location | Unknown | Live GPS on map |
| Job assignment | Manual call/message | One tap |
| Customer update | Manual call | Automatic WhatsApp |
| Job history | Memory / paper | Searchable database |
| Business insights | None | Weekly reports |
| Skill matching | Never considered | Always considered |
| Technician accountability | None | GPS + job status tracking |

---

# 5. Target Market & User Personas

## Market Sizing — India Focus

### Total Addressable Market (TAM)

- Skilled trade service companies in India: ~800,000
- Includes: HVAC, plumbing, electrical, pest control, carpentry, appliance repair
- At ₹5,999/month average: **TAM = ₹57,590 crore ($7B)**

### Serviceable Addressable Market (SAM)

- Companies with 5–50 technicians and smartphone usage: ~150,000
- At ₹5,999/month: **SAM = ₹10,798 crore ($1.3B)**

### Serviceable Obtainable Market (SOM) — 3-year target

- Penetrate 1% of SAM = 1,500 companies
- At blended ₹5,500/month: **SOM = ₹99 crore ARR ($12M)**

## Phase 1 ICP (Ideal Customer Profile)

**Company type:** AC service and repair company
**City:** Tier 1 or Tier 2 Indian city (Pune, Hyderabad, Jaipur, Lucknow initially)
**Team size:** 8–25 technicians
**Current dispatch method:** WhatsApp + phone calls
**Owner profile:** 30–50 years old, business owner (not tech-savvy, but has a smartphone)
**Revenue:** ₹30–₹150 lakh/year
**Pain frequency:** Dispatch chaos happens multiple times daily
**Decision maker:** The owner himself (no procurement process)
**Sales cycle:** 1–3 weeks
**Willingness to pay:** Has already paid for tools (accounting software, some basic apps)

---

## User Personas

### Persona 1: Ramesh — The Overwhelmed Owner

**Age:** 42
**Business:** Ramesh AC Services, Pune
**Team:** 18 technicians
**Revenue:** ₹80L/year

**A day in his life:**
Ramesh starts at 7:30 AM answering WhatsApp messages. By 9 AM he has 12 new job requests and is trying to figure out who is free and where. He spends 4 hours on calls and messages. By afternoon he is exhausted and has missed 3 customers who didn't get callbacks. He knows his business could be 30% bigger if he wasn't stuck doing dispatch all day.

**Goals:**

- Spend less time on dispatch coordination
- Never lose a customer due to slow response
- Grow from 18 to 30 technicians without chaos getting worse

**Frustrations:**

- "Technician nahi milta — phone karo, message karo, tab bhi pata nahi kahan hai"
- "Customer call karta hai, main busy hoon, call miss ho jaata hai"
- "Pata nahi kaun kitna kaam kar raha hai — salary same de raha hoon sab ko"

**What Fieldo means to him:** 2–3 hours freed every day. Confidence that every job is assigned to the right person. Data that shows who his best technicians are.

**Adoption trigger:** A friend/competitor shows him the live technician map on Fieldo. He immediately understands.

---

### Persona 2: Suresh — The Senior Technician (Field User)

**Age:** 28
**Role:** Senior HVAC technician, 6 years experience
**Education:** ITI diploma
**Phone:** Budget Android (4G, 32GB)
**App proficiency:** Uses WhatsApp, YouTube, PhonePe. Avoids complex apps.

**Current experience:**
Suresh gets jobs through WhatsApp messages or phone calls from Ramesh. Sometimes the job address is wrong. Sometimes he doesn't know the customer's contact number. He has to call Ramesh for every piece of information. He gets paid the same whether he does 4 jobs or 8 jobs.

**Goals:**

- Know exactly where he's going before he leaves
- Not get blamed for jobs that weren't his fault
- Earn more if he does more work (performance visibility)

**Frustrations:**

- "Address aata hai WhatsApp pe — usse Google Maps pe dhoondho — kabhi milta hai, kabhi nahi"
- "Customer ka number nahi hota, baat kaise karun?"
- "Boss lagta hai mujh par trust nahi karta — GPS track karta hai"

**What Fieldo means to him:** Clean job card with everything he needs. One-tap navigation. Customer auto-notified so he doesn't have to explain. Fair recognition if he does more jobs.

**Adoption requirement:** The app must be extremely simple. If there's any learning curve beyond 5 minutes, he won't use it.

---

### Persona 3: Priya — The Customer (End User, Indirect)

**Age:** 35
**Situation:** Works from home, AC is broken in June heat
**Expectation:** Someone fixes it today, arrives at the promised time, and doesn't make her call 3 times for an update

**Frustration today:**
She called the service company at 10 AM. They said "technician bhejte hain." It's now 2 PM. She has called twice. Each time she's put on hold. The technician finally arrives at 4 PM with no warning. She misses a work call to let him in.

**What Fieldo means to her:** She gets a WhatsApp when the technician leaves, when he's 10 minutes away, and when the job is done. She never has to call the company. She gives them 5 stars.

---

# 6. Core Features — Detailed Specification

## Feature Priority Matrix

| Feature | Phase | Priority | Build Time |
|---|---|---|---|
| Job creation & management | MVP | P0 | Week 1–2 |
| Technician list & profiles | MVP | P0 | Week 1 |
| Live technician map | MVP | P0 | Week 2 |
| AI dispatch suggestion | MVP | P0 | Week 3 |
| Technician mobile app | MVP | P0 | Week 4–5 |
| Customer WhatsApp notifications | MVP | P1 | Week 5 |
| Job history & search | MVP | P1 | Week 6 |
| Basic analytics dashboard | V1 | P1 | Month 3 |
| Invoice generation | V1 | P2 | Month 4 |
| Spare parts inventory | V1 | P2 | Month 5 |
| Customer portal | V2 | P3 | Month 7 |
| Multi-branch support | V2 | P3 | Month 8 |
| AMC (Annual Maintenance Contract) module | V2 | P3 | Month 9 |

---

## Feature 1: Smart Job Board (Owner Web App)

**What it is:** A real-time dashboard showing all jobs — open, assigned, in-progress, and completed — in a visual Kanban-style board.

**How it works:**

- Owner opens Fieldo on any browser (laptop, tablet, or phone)
- All jobs displayed as cards in columns: New → Assigned → En Route → In Progress → Done
- Each job card shows: customer name, address, job type, assigned tech, time created, urgency level
- Jobs can be created by typing, or via a WhatsApp Business API integration (customer messages automatically create draft jobs)
- Drag-and-drop to reassign jobs if needed

**Key data per job card:**

- Customer name + phone number (tap to call)
- Full address with one-tap Google Maps open
- Job type (AC repair / gas fill / plumbing leak / electrical short / etc.)
- Special notes (e.g., "customer has dog", "3rd floor, no lift")
- Assigned technician (photo + name)
- Time elapsed since job opened
- Status colour coding (red = overdue, amber = at risk, green = on track)

**Design principle:** An owner must be able to understand the full state of his business in under 10 seconds of looking at the screen. Like an air traffic control dashboard — clear, colour-coded, and scannable.

---

## Feature 2: Live Technician Map

**What it is:** A map showing real-time location of all technicians, overlaid with current job pins.

**How it works:**

- Technician app sends GPS ping every 60 seconds (battery-optimised)
- Owner sees each technician as a labelled marker: name + current status
- Job locations shown as separate pins: colour-coded by urgency
- Clicking a technician shows: current job, distance to next available job, estimated free time
- Clicking a job pin shows the job card with assign button

**Technician status indicators:**

- Green dot: Free / available
- Blue dot: En route to job
- Orange dot: On job
- Grey dot: App offline / break

**Privacy consideration:** Technicians are informed during onboarding that location is tracked only during working hours. Location sharing can be paused by technician and tracked by owner. Clear communication in onboarding.

---

## Feature 3: Fieldo AI Dispatch Engine

**What it is:** The core differentiator. When a new job is created, Fieldo's AI ranks available technicians and recommends the best one with a clear reason.

**How the AI decides:**

The dispatch score for each technician is calculated from:

```
Dispatch Score = 
  (Proximity Score × 0.35) +
  (Skill Match Score × 0.35) +
  (Current Workload Score × 0.20) +
  (Historical Performance Score × 0.10)
```

**Proximity Score:** Distance from technician's current location to job address. Closer = higher score. Accounts for traffic (Google Maps Distance Matrix API).

**Skill Match Score:** Does the technician have the required skill/certification for this job type? Binary for specialized skills (inverter AC, 3-phase electrical), weighted for general skills.

**Current Workload Score:** How many jobs does the technician already have assigned today? Is the current job nearly done? Estimates tech's availability time.

**Historical Performance Score:** Based on this technician's first-call-fix rate for this job type. A tech who has fixed inverter ACs successfully 9 out of 10 times gets a higher score than one who has 5 of 10.

**What the owner sees:**

```
 AI Recommendation
 ─────────────────────────────────────────
 ★  RAJU SHARMA           Score: 94/100
    2.1 km away · Free now · AC Inverter ✓
    Reason: Nearest available tech with
    inverter certification. 9/10 fix rate.
 
 2. AMIT PATEL            Score: 71/100
    4.8 km away · Free in ~25 min
    Reason: Has inverter cert but farther.
 
 3. SURESH KUMAR          Score: 58/100
    1.9 km away · On job · Free in ~1 hr
    Reason: Closer but currently busy.
 ─────────────────────────────────────────
 [Assign Raju]    [See All Technicians]
```

**Important design decision:** The AI always shows its reasoning in plain language. Owner can override at any time. Fieldo never dispatches without owner confirmation. This builds trust and ensures the AI is seen as a helper, not a boss.

**How the AI learns:**

- Every dispatch decision is logged (AI suggested X, owner chose Y)
- If owner consistently overrides AI for certain scenarios, the model updates weights
- After 90 days of data, the AI is highly calibrated to that specific company's patterns

---

## Feature 4: Technician Mobile App

**Platform:** React Native (Android-first, as 90%+ of field techs in India use Android)

**Design principles:**

- Works on 2GB RAM budget Android phones
- Works on 2G/3G connections (offline mode for job viewing)
- No English proficiency required (full Hindi UI option)
- Maximum 3 taps to complete any action

**Core screens:**

### Screen 1: My Jobs Today

- List of all jobs assigned to this technician today
- Each job: customer name, address, job type, time slot
- Tap to see full job details
- "Navigate" button opens Google Maps with address pre-loaded
- Status buttons: "On my way" → "Arrived" → "Job Done"

### Screen 2: Active Job View

- Customer name + phone (tap to call)
- Full address + one-tap navigation
- Job notes from dispatcher
- Photo upload (for before/after documentation)
- Status update buttons (large, easy to tap with work gloves on)

### Screen 3: My Performance (Gamification)

- Jobs completed this week / month
- Customer rating average
- "Top Technician" badge if ranked #1 this week
- Simple leaderboard: how they compare to team

**Offline capability:** Job list and customer details are cached locally. Technician can view job info even with no internet. Status updates sync when connection returns.

---

## Feature 5: Automatic Customer Notifications

**What it is:** Customers receive automated WhatsApp messages at key job milestones — without the owner lifting a finger.

**Notification triggers and templates:**

| Trigger | Message Sent to Customer |
|---|---|
| Technician assigned | "Aapki AC service ke liye Raju Sharma assign kiya gaya hai. Unka number: 98XXXXXX. Aaj aayenge. — Ramesh AC Services" |
| Technician on the way | "Raju aapki taraf aa rahe hain. Expected time: 11:30 AM. Live track: [link]" |
| Technician arrived | "Raju Sharma aapke door pe hain. — Ramesh AC Services" |
| Job completed | "Aapka kaam complete ho gaya. Koi bhi issue ho toh call karein. Rating dein: [link]" |

**Delivery method:** WhatsApp Business API (via Gupshup or Twilio — chosen for Indian number support and lower cost).

**Owner control:** Owner can customise the message templates with their company name and tone. Can turn off individual notification types. Can add/remove fields.

**Business impact:** This feature alone can be the selling point. Tell an owner: "Customer kabhi bhi aapko puchne ke liye call nahi karega — hum automatically update bhej denge." That eliminates 40% of inbound calls.

---

## Feature 6: Analytics Dashboard

**What it is:** A weekly/monthly report showing the owner key business metrics they never had before.

**Key metrics shown:**

**Operational metrics:**

- Jobs completed per day/week/month
- Average response time (job created → technician assigned)
- Average job duration by job type
- First-call fix rate (% of jobs that didn't need a callback)
- Callback rate per technician

**Technician metrics:**

- Jobs per technician this week (who's doing most work)
- Revenue generated per technician (if pricing is entered)
- Average rating per technician
- On-time arrival rate

**Business metrics:**

- Revenue trend (if prices entered per job)
- Most common job types
- Peak demand times and days
- Geographic heat map of jobs (which areas are busiest)

**Design principle:** All charts are simple bar/line charts. No complex visualizations. Owner needs to understand it in 30 seconds without explanation.

---

## Feature 7: Job History & Search

**What it is:** A searchable log of every job ever completed.

**Search filters:**

- Customer name or phone number
- Date range
- Job type
- Technician name
- Job status
- Area/locality

**Why this matters:**

- "Customer ka pehle ka kaam kya tha?" — owner can check history before new visit
- "Ye AC pehle kab service hua tha?" — service history at a glance
- "Suresh ne is mahine kitne kaam kiye?" — accountability data
- Handles warranty/callback disputes: "Bhai, aapke yahan 15 din pehle Raju gaya tha, dekhte hain"

---

# 7. User Flows & Journey Maps

## Flow 1: New Job Creation and Assignment (Core Flow)

```
OWNER receives customer call
     │
     ▼
Opens Fieldo → clicks "New Job" button
     │
     ▼
Enters: Customer name, phone, address (type or paste)
       Job type (dropdown: AC Repair / Gas Fill / Installation / etc.)
       Special notes (optional)
       Urgency (Normal / Urgent)
     │
     ▼
Clicks "Find Best Technician"
     │
     ▼
AI Engine runs (< 2 seconds):
  - Checks all technician locations
  - Scores each on: proximity + skill + availability + performance
     │
     ▼
Owner sees ranked recommendations with scores and reasons
     │
     ▼
Owner clicks "Assign [Technician Name]" (one tap)
     │
     ▼
TECHNICIAN receives push notification + WhatsApp:
  "New job: [Customer Name], [Address], [Job Type]"
     │
     ▼
CUSTOMER receives WhatsApp:
  "[Tech Name] will arrive by [time]. Contact: [number]"
     │
     ▼
Job card moves to "Assigned" column on owner dashboard
     │
     ▼
[Technician taps "On My Way"]
     │
     ▼
CUSTOMER receives WhatsApp:
  "Your technician is on the way. Estimated arrival: X"
     │
     ▼
[Technician taps "Arrived"]
     ↓
[Technician taps "Job Done" + uploads photo]
     │
     ▼
OWNER dashboard: Job moves to "Completed"
CUSTOMER receives: Completion message + rating link
     │
     ▼
Data saved to history. AI model updated with outcome.
```

**Total owner time for this flow: under 90 seconds.**
**Previously (WhatsApp/calls): 15–25 minutes.**

---

## Flow 2: Technician Morning Start

```
Technician wakes up → opens Fieldo app
     │
     ▼
Sees "My Jobs Today" screen — all pre-assigned jobs listed
     │
     ▼
First job: [Customer Name] — [Area] — [Job Type] — 9:00 AM
     │
     ▼
Taps "Navigate" → Google Maps opens with address
     │
     ▼
[Arrives] → taps "Arrived" → customer notified automatically
     │
     ▼
Completes job → taps "Job Done" → takes before/after photo (optional)
     │
     ▼
Sees next job automatically. Navigates. Repeats.
     │
     ▼
End of day: sees jobs completed, ratings received, daily summary
```

---

## Flow 3: Owner's Morning Overview

```
Owner wakes up → opens Fieldo (takes 10 seconds)
     │
     ▼
Dashboard shows:
  - 4 jobs pending from yesterday (red — overdue)
  - 12 jobs booked for today
  - 8 technicians active (green dots on map)
  - 3 technicians not yet started (grey)
     │
     ▼
Sees Raju hasn't started his first job (9 AM, now 9:25 AM)
     │
     ▼
Taps Raju's card → calls from app with one tap
     │
     ▼
Raju says he's stuck in traffic. Owner taps "Notify Customer" →
Customer gets: "Raju is delayed by 20 min. New ETA: 9:45 AM"
     │
     ▼
Owner has full visibility. No panic. No angry customer calls.
```

---

# 8. Technical Architecture

## High-Level Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                        CLIENT LAYER                              │
│  ┌─────────────────┐          ┌──────────────────────────────┐  │
│  │ Owner Web App   │          │  Technician Mobile App       │  │
│  │ (Next.js/React) │          │  (React Native — Android)    │  │
│  └────────┬────────┘          └──────────────┬───────────────┘  │
└───────────┼───────────────────────────────────┼─────────────────┘
            │  HTTPS/REST + WebSocket           │  HTTPS/REST
┌───────────┼───────────────────────────────────┼─────────────────┐
│           ▼           API GATEWAY             ▼                 │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │              Node.js / Express API Server                │    │
│  │     (Rate limiting · Auth middleware · Route handlers)   │    │
│  └────────┬────────────────────────────────────────────────┘    │
│           │                                                       │
│  ┌────────┴──────────────────────────────────────────────────┐  │
│  │                    SERVICES LAYER                          │  │
│  │ ┌──────────────┐ ┌──────────────┐ ┌──────────────────┐   │  │
│  │ │ Dispatch AI  │ │ Notification │ │ Location Service │   │  │
│  │ │ Service      │ │ Service      │ │ (GPS tracking)   │   │  │
│  │ └──────┬───────┘ └──────┬───────┘ └────────┬─────────┘   │  │
│  │        │                │                   │              │  │
│  └────────┼────────────────┼───────────────────┼─────────────┘  │
└───────────┼────────────────┼───────────────────┼────────────────┘
            │                │                   │
┌───────────┼────────────────┼───────────────────┼────────────────┐
│           ▼                ▼                   ▼                │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────────────┐  │
│  │  PostgreSQL  │  │  Redis       │  │  External Services   │  │
│  │  (Primary DB)│  │  (Cache +    │  │  - Google Maps API   │  │
│  │              │  │   Job Queue) │  │  - WhatsApp API      │  │
│  └──────────────┘  └──────────────┘  │  - Claude API (AI)   │  │
│                                       │  - Razorpay (billing)│  │
│                                       │  - FCM (push notifs) │  │
│                                       └──────────────────────┘  │
└─────────────────────────────────────────────────────────────────┘
```

## Key Architectural Decisions

### Decision 1: REST API with WebSocket for real-time

Jobs and technician status updates need real-time push (owner dashboard updates without refresh). Use WebSocket (Socket.IO) for dashboard live updates. REST for all other operations.

### Decision 2: PostgreSQL as primary database

ACID-compliant, excellent at relational queries (jobs × technicians × customers × history). PostGIS extension for geospatial queries (find all technicians within 10km radius). Supabase provides hosted PostgreSQL with built-in auth.

### Decision 3: Redis for job queue and caching

When a job is created, dispatch calculation is queued in Redis. This decouples the API response (fast) from the AI computation (slower). Redis also caches technician locations (updated every 60s — no need to hit PostgreSQL for every map refresh).

### Decision 4: Edge-hosted AI with API fallback

Dispatch scoring algorithm runs server-side (Python microservice). Calls Claude API only for natural language job classification (parsing customer description into structured job type). This keeps AI costs low — Claude API only called for NLP tasks, not for every dispatch calculation.

### Decision 5: Android-first mobile app

90% of trade technicians in India use Android. React Native allows code sharing between Android and future iOS. Offline-first design: all job data cached locally, sync when connected.

---

# 9. Tech Stack

## Complete Technology Decisions

### Frontend — Owner Web App

| Layer | Technology | Why |
|---|---|---|
| Framework | Next.js 14 | React-based, fast, great SEO for marketing site, API routes built in |
| Styling | Tailwind CSS | Fast to build, consistent design, no CSS files to manage |
| State management | Zustand | Lightweight, simpler than Redux for this app size |
| Maps | Google Maps JS API | Most reliable in India, familiar to users |
| Real-time | Socket.IO client | Live job and tech location updates |
| Charts | Recharts | Simple, React-native, good enough for analytics |
| Forms | React Hook Form | Validation without bloat |
| HTTP client | Axios | Standard, handles auth headers cleanly |

### Frontend — Technician Mobile App

| Layer | Technology | Why |
|---|---|---|
| Framework | React Native (Expo) | Code sharing with web logic, Expo simplifies build process |
| Navigation | React Navigation | Industry standard for RN |
| Maps | React Native Maps | Google Maps on Android, performance-optimized |
| Offline storage | MMKV (via react-native-mmkv) | 10x faster than AsyncStorage, critical for offline mode |
| Push notifications | Expo Notifications + FCM | Firebase Cloud Messaging for Android |
| Background location | react-native-background-geolocation | Handles Android Doze mode, battery-efficient |

### Backend — API Server

| Layer | Technology | Why |
|---|---|---|
| Runtime | Node.js 20 LTS | JavaScript everywhere, large ecosystem, your team knows it |
| Framework | Express.js | Simple, fast, huge community, easy to add middleware |
| Real-time | Socket.IO | Mature, handles reconnection gracefully |
| ORM | Prisma | Type-safe database queries, great developer experience |
| Validation | Zod | Runtime type validation for API inputs |
| Auth | JWT + Supabase Auth | Stateless tokens, phone OTP via Supabase |

### AI Microservice

| Layer | Technology | Why |
|---|---|---|
| Runtime | Python 3.11 | Superior ML library ecosystem |
| Framework | FastAPI | Async, fast, auto-generates API docs |
| Dispatch algorithm | scikit-learn + custom scoring | Interpretable, fast, doesn't need GPU |
| NLP / classification | Claude API (claude-sonnet-4-6) | Parse job descriptions into structured data |
| Job queue | Redis Queue (RQ) | Async dispatch calculations, prevents API blocking |

### Database & Infrastructure

| Layer | Technology | Why |
|---|---|---|
| Primary database | PostgreSQL 15 (via Supabase) | ACID, PostGIS for geo, free tier to start |
| Cache | Redis (Upstash) | Serverless Redis, pay-per-use, no idle cost |
| File storage | Supabase Storage | Job photos, technician profile pictures |
| Hosting (API) | Railway.app | Free tier, auto-deploy from GitHub, Indian latency ok |
| Hosting (web) | Vercel | Free for Next.js, global CDN |
| Monitoring | Sentry | Error tracking across web + mobile + API |
| Analytics | PostHog (self-hosted or free tier) | Product analytics, funnel tracking |

### Integrations

| Service | Provider | Cost |
|---|---|---|
| WhatsApp Business API | Gupshup | ~₹0.30–₹0.50 per message |
| SMS (backup) | MSG91 | ₹0.15 per SMS |
| Maps & Routing | Google Maps Platform | $200 free credit/month covers ~40K requests |
| Payments | Razorpay | 2% per transaction, no setup fee |
| Push notifications | Firebase (FCM) | Free up to 1M messages/month |
| Email | Resend | 100 emails/day free |

### Development & Operations

| Tool | Purpose |
|---|---|
| GitHub | Version control, CI/CD triggers |
| GitHub Actions | Auto-deploy on push to main |
| Postman / Bruno | API testing and documentation |
| Figma | UI/UX design (free tier sufficient) |
| Linear | Issue and sprint tracking (free for solo/small team) |
| Notion | Product docs, meeting notes, customer feedback |

---

# 10. Database Schema

## Core Tables

### companies

```sql
CREATE TABLE companies (
  id            UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  name          VARCHAR(255) NOT NULL,
  owner_name    VARCHAR(255) NOT NULL,
  phone         VARCHAR(20) UNIQUE NOT NULL,
  email         VARCHAR(255),
  trade_type    VARCHAR(50) NOT NULL,  -- 'HVAC', 'PLUMBING', 'ELECTRICAL', 'MULTI'
  city          VARCHAR(100) NOT NULL,
  address       TEXT,
  gstin         VARCHAR(20),
  plan          VARCHAR(20) DEFAULT 'starter',  -- starter | growth | pro
  plan_expires_at TIMESTAMPTZ,
  whatsapp_number VARCHAR(20),
  settings      JSONB DEFAULT '{}',   -- customizable notification templates, etc.
  created_at    TIMESTAMPTZ DEFAULT NOW(),
  updated_at    TIMESTAMPTZ DEFAULT NOW()
);
```

### technicians

```sql
CREATE TABLE technicians (
  id              UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  company_id      UUID REFERENCES companies(id) ON DELETE CASCADE,
  name            VARCHAR(255) NOT NULL,
  phone           VARCHAR(20) NOT NULL,
  photo_url       TEXT,
  skills          TEXT[] NOT NULL DEFAULT '{}',
  -- e.g. ['AC_REPAIR', 'GAS_FILL', 'INVERTER_AC', 'DUCT_CLEANING', 'INSTALLATION']
  certifications  TEXT[] DEFAULT '{}',
  experience_years INT DEFAULT 0,
  status          VARCHAR(20) DEFAULT 'active',  -- active | inactive | on_leave
  is_available    BOOLEAN DEFAULT TRUE,
  fcm_token       TEXT,  -- for push notifications
  created_at      TIMESTAMPTZ DEFAULT NOW(),
  updated_at      TIMESTAMPTZ DEFAULT NOW(),
  UNIQUE(company_id, phone)
);
```

### technician_locations

```sql
CREATE TABLE technician_locations (
  technician_id   UUID REFERENCES technicians(id) ON DELETE CASCADE,
  lat             DECIMAL(10, 7) NOT NULL,
  lng             DECIMAL(10, 7) NOT NULL,
  accuracy        FLOAT,
  updated_at      TIMESTAMPTZ DEFAULT NOW(),
  PRIMARY KEY (technician_id)
  -- Single row per tech, updated in place (not time-series, to keep it fast)
);

-- PostGIS extension for efficient geo queries
CREATE INDEX idx_tech_location_geo ON technician_locations 
  USING GIST (ST_MakePoint(lng, lat));
```

### customers

```sql
CREATE TABLE customers (
  id          UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  company_id  UUID REFERENCES companies(id) ON DELETE CASCADE,
  name        VARCHAR(255) NOT NULL,
  phone       VARCHAR(20) NOT NULL,
  address     TEXT,
  area        VARCHAR(100),
  lat         DECIMAL(10, 7),
  lng         DECIMAL(10, 7),
  notes       TEXT,  -- "has dog", "ground floor only", "prefers morning"
  created_at  TIMESTAMPTZ DEFAULT NOW(),
  UNIQUE(company_id, phone)
);
```

### jobs

```sql
CREATE TABLE jobs (
  id                UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  company_id        UUID REFERENCES companies(id) ON DELETE CASCADE,
  customer_id       UUID REFERENCES customers(id),
  technician_id     UUID REFERENCES technicians(id),
  
  -- Job details
  job_type          VARCHAR(100) NOT NULL,
  -- e.g. 'AC_REPAIR', 'GAS_FILL', 'AC_INSTALLATION', 'PLUMBING_LEAK', etc.
  description       TEXT,
  address           TEXT NOT NULL,
  area              VARCHAR(100),
  lat               DECIMAL(10, 7),
  lng               DECIMAL(10, 7),
  urgency           VARCHAR(20) DEFAULT 'normal',  -- normal | urgent | emergency
  
  -- Scheduling
  scheduled_at      TIMESTAMPTZ,
  
  -- Status tracking
  status            VARCHAR(30) DEFAULT 'pending',
  -- pending | assigned | en_route | arrived | in_progress | completed | cancelled
  
  -- Timestamps for each status change
  assigned_at       TIMESTAMPTZ,
  en_route_at       TIMESTAMPTZ,
  arrived_at        TIMESTAMPTZ,
  completed_at      TIMESTAMPTZ,
  
  -- Outcomes
  resolution_notes  TEXT,
  before_photos     TEXT[] DEFAULT '{}',
  after_photos      TEXT[] DEFAULT '{}',
  customer_rating   INT CHECK (customer_rating BETWEEN 1 AND 5),
  callback_required BOOLEAN DEFAULT FALSE,
  
  -- Billing
  amount            DECIMAL(10, 2),
  payment_status    VARCHAR(20) DEFAULT 'pending',  -- pending | paid | waived
  
  -- AI dispatch
  ai_recommendation JSONB,  -- stores the ranked suggestions at time of dispatch
  ai_accepted       BOOLEAN,  -- did owner accept or override AI suggestion?
  
  created_at        TIMESTAMPTZ DEFAULT NOW(),
  updated_at        TIMESTAMPTZ DEFAULT NOW()
);

CREATE INDEX idx_jobs_company_status ON jobs(company_id, status);
CREATE INDEX idx_jobs_technician ON jobs(technician_id, status);
CREATE INDEX idx_jobs_created ON jobs(company_id, created_at DESC);
```

### dispatch_scores (AI learning data)

```sql
CREATE TABLE dispatch_decisions (
  id                UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  job_id            UUID REFERENCES jobs(id),
  company_id        UUID REFERENCES companies(id),
  ai_top_pick_id    UUID REFERENCES technicians(id),
  owner_pick_id     UUID REFERENCES technicians(id),
  ai_scores         JSONB NOT NULL,  -- full ranking with scores
  override_reason   TEXT,  -- if owner overrode, optional note
  outcome_rating    INT,  -- job's final customer rating (for feedback loop)
  created_at        TIMESTAMPTZ DEFAULT NOW()
);
```

### notifications_log

```sql
CREATE TABLE notifications_log (
  id            UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  job_id        UUID REFERENCES jobs(id),
  company_id    UUID REFERENCES companies(id),
  recipient     VARCHAR(20) NOT NULL,  -- phone number
  channel       VARCHAR(20) NOT NULL,  -- 'whatsapp' | 'sms' | 'push'
  message_type  VARCHAR(50) NOT NULL,  -- 'tech_assigned' | 'en_route' | etc.
  message_body  TEXT NOT NULL,
  status        VARCHAR(20) DEFAULT 'sent',  -- sent | delivered | failed
  sent_at       TIMESTAMPTZ DEFAULT NOW()
);
```

---

# 11. API Design

## API Conventions

- **Base URL:** `https://api.fieldo.in/v1`
- **Authentication:** Bearer JWT token in Authorization header
- **Request format:** JSON
- **Response format:** JSON with `{ success, data, error }` envelope
- **Versioning:** URI-based (`/v1/`, `/v2/`)
- **Rate limiting:** 1,000 requests/hour per company, 100/min per endpoint

## Core Endpoints

### Authentication

```
POST   /auth/send-otp          Send OTP to phone number
POST   /auth/verify-otp        Verify OTP, return JWT
POST   /auth/refresh-token     Refresh expired JWT
POST   /auth/logout            Invalidate token
```

### Company Management

```
GET    /company                Get company profile
PATCH  /company                Update company settings
GET    /company/stats          Get dashboard stats summary
```

### Technicians

```
GET    /technicians            List all technicians (with current location)
POST   /technicians            Add a new technician
GET    /technicians/:id        Get technician details
PATCH  /technicians/:id        Update technician (skills, status, etc.)
DELETE /technicians/:id        Deactivate technician
GET    /technicians/:id/jobs   Get job history for technician
GET    /technicians/locations  Get all current locations (for map)
```

### Jobs

```
GET    /jobs                   List jobs (filter by status, date, tech, area)
POST   /jobs                   Create a new job
GET    /jobs/:id               Get job details
PATCH  /jobs/:id               Update job (status, notes, amount, etc.)
DELETE /jobs/:id               Cancel job
POST   /jobs/:id/assign        Assign technician to job
POST   /jobs/:id/photos        Upload job photos
GET    /jobs/history           Paginated job history with search
```

### AI Dispatch

```
POST   /dispatch/recommend     Get AI technician recommendations for a job
                               Body: { job_type, address, lat, lng, urgency, skills_required }
                               Returns: ranked list of technicians with scores and reasons
```

### Customers

```
GET    /customers              List customers (searchable)
POST   /customers              Add customer
GET    /customers/:id          Get customer with job history
PATCH  /customers/:id          Update customer
GET    /customers/search       Search by name or phone
```

### Analytics

```
GET    /analytics/summary      Jobs, revenue, techs summary for date range
GET    /analytics/technicians  Per-tech performance metrics
GET    /analytics/jobs         Job type breakdown, peak times
GET    /analytics/map          Geographic job distribution
```

### Notifications (Technician App)

```
POST   /technician/location    Update technician GPS location (60s interval)
GET    /technician/jobs        Get today's jobs for logged-in technician
PATCH  /technician/jobs/:id    Update job status (en_route, arrived, done)
POST   /technician/jobs/:id/complete  Mark complete with photos
```

### Webhooks (Incoming)

```
POST   /webhooks/whatsapp      Receive inbound WhatsApp messages (auto-create job drafts)
POST   /webhooks/razorpay      Payment confirmation events
```

## Sample API Response

**POST /dispatch/recommend** — response:

```json
{
  "success": true,
  "data": {
    "job_id": "job_abc123",
    "recommendations": [
      {
        "technician_id": "tech_xyz789",
        "name": "Raju Sharma",
        "photo_url": "https://...",
        "phone": "9800000001",
        "score": 94,
        "distance_km": 2.1,
        "eta_minutes": 8,
        "status": "free",
        "skill_match": true,
        "current_jobs_today": 3,
        "fix_rate_this_job_type": 0.9,
        "reason": "Nearest available technician with AC Inverter certification. 9/10 first-call-fix rate for this job type.",
        "score_breakdown": {
          "proximity": 92,
          "skill_match": 100,
          "workload": 88,
          "performance": 90
        }
      },
      {
        "technician_id": "tech_def456",
        "name": "Amit Patel",
        "score": 71,
        "distance_km": 4.8,
        "eta_minutes": 19,
        "status": "free",
        "reason": "Has required certification but farther away.",
        "score_breakdown": { "proximity": 62, "skill_match": 100, "workload": 95, "performance": 78 }
      }
    ],
    "calculated_at": "2025-06-01T09:14:22Z"
  }
}
```

---

# 12. AI & ML Systems

## The Dispatch Intelligence Engine

### Architecture Overview

```
Job Request
    │
    ▼
Job Classification (Claude API)
    │  "AC not cooling, inverter model" → job_type: "AC_REPAIR", skills: ["INVERTER_AC"]
    ▼
Candidate Filtering
    │  Filter: available technicians with required skills
    ▼
Scoring Engine (Python / scikit-learn)
    │  Score each candidate on 4 dimensions
    ▼
Ranking & Explanation Generator
    │  Produce ranked list with plain-language reasons
    ▼
Owner Receives Recommendation
    │
    ▼
Feedback Capture
    │  Did owner accept? What was the outcome?
    ▼
Model Update (weekly batch retraining)
```

### Component 1: Job Classification

**Problem:** Owners describe jobs in natural language. "AC ki thandi nahi aa rahi" needs to map to `job_type: AC_REPAIR`, `skills_required: ['COOLING_SYSTEMS']`.

**Solution:** Call Claude API with a structured prompt:

```python
CLASSIFICATION_PROMPT = """
You are a job classification system for a field service company.
Given a job description, extract structured data.

Job description: {description}

Return ONLY valid JSON (no other text):
{
  "job_type": "one of: AC_REPAIR | AC_INSTALLATION | GAS_FILL | DUCT_CLEANING | PLUMBING_LEAK | ELECTRICAL_FAULT | OTHER",
  "skills_required": ["list of skills from: INVERTER_AC | SPLIT_AC | WINDOW_AC | THREE_PHASE | GAS_WORK | etc."],
  "urgency_signal": "normal | urgent",
  "estimated_duration_hours": 1.5,
  "equipment_type": "split | window | cassette | duct | unknown"
}
"""
```

**Cost:** Claude API call for every job creation ≈ $0.001 per job. For 1,000 jobs/month across all customers = $1/month. Negligible.

**Fallback:** If Claude API fails, show a dropdown for owner to manually select job type. Never block the workflow.

### Component 2: Scoring Algorithm

```python
def calculate_dispatch_score(tech, job, company_weights):
    """
    Returns score 0-100 for a technician-job pairing.
    company_weights: learned per-company (how much this owner values proximity vs skill)
    """
    
    # Proximity Score (0-100)
    distance_km = get_road_distance(tech.location, job.location)
    proximity_score = max(0, 100 - (distance_km * 10))
    # 0km = 100, 10km = 0 (adjusted for city traffic)
    
    # Skill Match Score (0-100)
    required = set(job.skills_required)
    tech_skills = set(tech.skills)
    if required.issubset(tech_skills):
        skill_score = 100
    else:
        overlap = len(required & tech_skills) / len(required)
        skill_score = int(overlap * 70)  # Partial match max 70
    
    # Workload Score (0-100)
    jobs_remaining_today = get_remaining_jobs_today(tech.id)
    minutes_until_free = estimate_free_time(tech.id)
    workload_score = max(0, 100 - (jobs_remaining_today * 15) - (minutes_until_free * 0.5))
    
    # Performance Score (0-100)
    fix_rate = get_historical_fix_rate(tech.id, job.job_type)
    performance_score = int(fix_rate * 100) if fix_rate else 75  # Default 75 if no history
    
    # Composite Score
    weights = company_weights or DEFAULT_WEIGHTS
    total = (
        proximity_score    * weights['proximity']    +   # default 0.35
        skill_score        * weights['skill_match']  +   # default 0.35
        workload_score     * weights['workload']      +   # default 0.20
        performance_score  * weights['performance']       # default 0.10
    )
    
    return {
        'total': round(total),
        'proximity': proximity_score,
        'skill_match': skill_score,
        'workload': workload_score,
        'performance': performance_score
    }
```

### Component 3: Learning & Weight Calibration

Every time an owner overrides the AI recommendation:

- Record which tech was suggested vs chosen
- Record the outcome (job rating, callback required)

Weekly batch process:

- If owner consistently prefers proximity over skill → increase proximity weight for this company
- If owner's overrides lead to better outcomes → learn from those patterns
- If AI suggestions perform better on average → increase confidence threshold

**Data needed for meaningful calibration:** ~50 dispatch decisions per company. After 30 days of active use, the AI is significantly better calibrated.

### Component 4: Explanation Generation

Plain-language reasons are generated deterministically (no AI needed):

```python
def generate_reason(tech, scores, job):
    reasons = []
    
    if scores['proximity'] > 85:
        reasons.append(f"Nearest available ({tech.distance_km:.1f}km away)")
    
    if scores['skill_match'] == 100:
        reasons.append(f"{job.job_type} certified")
    
    if scores['performance'] > 85:
        fix_rate = int(scores['performance'])
        reasons.append(f"{fix_rate}% first-call-fix rate for this job type")
    
    if tech.status == 'free' and scores['workload'] > 80:
        reasons.append("Currently free")
    
    return ". ".join(reasons) + "."
    # e.g. "Nearest available (2.1km away). AC Inverter certified. 90% first-call-fix rate."
```

---

# 13. Business Model & Pricing

## Revenue Streams

### Primary: SaaS Subscription (95% of revenue initially)

| Plan | Price | Technician limit | Key features |
|---|---|---|---|
| **Starter** | ₹2,999/month | Up to 10 techs | Job board, AI dispatch, tech app, customer notifications |
| **Growth** | ₹5,999/month | Up to 30 techs | All Starter + Analytics dashboard, job history search, multi-user owner access |
| **Pro** | ₹9,999/month | Unlimited techs | All Growth + AMC module, invoice generation, priority support, custom notification templates |
| **Enterprise** | Custom (₹20,000+) | Unlimited | Multi-branch, API access, custom integrations, dedicated onboarding |

### Secondary: Usage-based Add-ons (introduced at V1.5)

| Add-on | Price | Description |
|---|---|---|
| Customer SMS notifications | ₹500/month | WhatsApp included free; SMS for non-WhatsApp customers |
| Extra WhatsApp messages | ₹0.40/message | Over 1,000 messages/month |
| Advanced analytics | ₹1,500/month | Revenue tracking, custom reports, CSV export |

### Future Revenue Streams (Year 2+)

| Stream | Description | Potential |
|---|---|---|
| Spare parts marketplace | Connect companies to wholesalers, take commission | 15–20% of GMV |
| Working capital / invoice financing | Small business loans against job history | Large |
| Insurance products | Group insurance for technicians via partners | ₹500/tech/month |
| Training marketplace | Certifications, skill upgrade courses | ₹5,000–₹20,000 per course |

## Unit Economics

**Customer Acquisition Cost (CAC) target:** ₹3,000–₹8,000 per customer (founder-led sales: primarily time cost, not cash)

**Average Revenue Per Account (ARPA):** ₹5,500/month (blended across plans)

**Monthly Churn Target:** < 3% (= ~36% annual retention → 64% retained = good for SME SaaS)

**Gross Margin:** ~85% (infrastructure costs are low at this scale)

**Payback period:** < 2 months (CAC ₹5,000 ÷ ARPA ₹5,500 = 0.9 months) — excellent

**LTV (24-month customer):** ₹5,500 × 24 × 0.97^24 = ~₹82,000

**LTV:CAC ratio:** ₹82,000 ÷ ₹5,000 = **16.4x** — well above the 3x minimum target

## Revenue Projections

| Month | Customers | MRR | ARR |
|---|---|---|---|
| 1 | 0 | ₹0 | – |
| 3 | 5 | ₹15,000 | – |
| 6 | 18 | ₹54,000 | ₹6.5L |
| 9 | 35 | ₹1,05,000 | ₹12.6L |
| 12 | 55 | ₹1,65,000 | ₹19.8L |
| 18 | 90 | ₹2,70,000 | ₹32.4L |
| 24 | 160 | ₹4,80,000 | ₹57.6L |
| 36 | 400 | ₹12,00,000 | ₹1.44 crore |

---

# 14. Go-to-Market Strategy

## Phase 1 — Nail It (Months 0–3)

**Objective:** 5 paying customers in one city, one trade

**Target:** AC service companies in your city with 8–25 technicians

**Channels:**

- Google Maps cold outreach (search "AC service [city]" → WhatsApp the owner)
- Local trade association meetings (electricians' association, HVAC dealer networks)
- Warm intros from friends/family who know trade business owners

**Sales motion:**

1. WhatsApp discovery message (no pitch, ask to learn)
2. 15-minute discovery call (understand their pain, don't sell)
3. Offer 30-day free pilot (zero friction, zero commitment)
4. In-person setup (visit their office, set it up together, train the owner)
5. Day 30: in-person review and conversion to paid

**Target conversion:** 1 in 5 discovery calls → pilot; 2 in 3 pilots → paid

**What not to do in Phase 1:**

- Don't build any feature not requested by a paying customer
- Don't pitch on the first call
- Don't try to scale before the product works for 5 companies perfectly

## Phase 2 — Scale It (Months 3–8)

**Objective:** 25–30 paying customers via referrals

**Primary channel:** Customer referrals (each owner knows 10+ others)

**Referral mechanics:**

- Ask every paying customer: "Aapke jaisa koi aur business owner hai jo yeh problem face karta ho?"
- Incentive: 1 month free for every paid referral
- Co-create a referral WhatsApp message they can forward

**Secondary channels:**

- YouTube content: "HVAC business ko kaise manage karein" (target: trade company owners)
- Facebook groups: HVAC India, electricians, plumbers (provide value, don't spam)
- Local trade expos and conferences

## Phase 3 — Expand It (Months 8–18)

**Objective:** 100 customers across 3 trades and 3 cities

**Expansion logic:**

- New trade: Add plumbing (similar operations, existing customers may refer)
- New city: Clone the Phase 1 playbook in a new city (start with 1 person on the ground)
- Inside sales: Hire 1 inside sales rep when MRR hits ₹1.5L/month

**Content marketing:**

- "Field Guide" blog: tips for running a trade service business
- WhatsApp broadcast for existing customers: monthly tips, product updates
- Google Ads targeting: "HVAC service software India", "dispatch app technician"

---

# 15. Product Roadmap

## MVP (Months 0–2) — Core Dispatch Engine

*Ship this. Get paying customers. Everything else waits.*

- [ ] Company onboarding and auth
- [ ] Technician management (add, edit, skills)
- [ ] Job creation (manual)
- [ ] Job board (Kanban view)
- [ ] Live technician map (GPS)
- [ ] AI dispatch recommendation
- [ ] Job assignment (one tap)
- [ ] Technician mobile app (jobs + status update)
- [ ] Customer WhatsApp notifications (assigned, en route, done)
- [ ] Basic job history log

## V1 (Months 2–5) — Retention Features

*Makes customers dependent on Fieldo. Reduces churn.*

- [ ] Analytics dashboard (per-tech performance, job trends)
- [ ] Customer database with search
- [ ] Job history search and filters
- [ ] Invoice generation (simple PDF)
- [ ] Razorpay payment collection link in invoice
- [ ] Owner reporting (weekly email summary)
- [ ] Bulk job import (from Excel)
- [ ] Multiple owner users (dispatcher role)

## V2 (Months 5–9) — Growth Features

*Expands revenue per customer and enables upselling.*

- [ ] AMC (Annual Maintenance Contract) module — track all active AMC customers, schedule auto-reminders
- [ ] Spare parts inventory tracker (basic)
- [ ] Customer app (view job status, book service)
- [ ] Multi-branch support
- [ ] WhatsApp bot integration (auto-create job from customer message)
- [ ] Custom notification templates
- [ ] Advanced analytics (revenue, profitability per job type)

## V3 (Months 9–18) — Platform Features

*Transforms Fieldo from a tool into a platform.*

- [ ] Marketplace: spare parts ordering with trade supplier integration
- [ ] Working capital: partner lending for equipment purchases
- [ ] Technician certification tracking and training marketplace
- [ ] API access for Enterprise customers
- [ ] Multi-language UI (Hindi, Tamil, Telugu)
- [ ] Offline-first mode for low-connectivity areas

---

# 16. Competitive Analysis

## Landscape Map

| Product | Target | Geography | Price | Dispatch AI | India-ready | Threat level |
|---|---|---|---|---|---|---|
| **ServiceTitan** | Enterprise | US | $300–600/mo | Yes | No | Low (too expensive, US-focused) |
| **Jobber** | SME | US/Canada | $49–199/mo | No | No | Low (no India ops, no Hindi) |
| **HouseCall Pro** | SME | US | $65–189/mo | No | No | Low |
| **Zoho FSM** | SME-Enterprise | India | ₹1,500+/mo/user | No | Partial | Medium (Zoho brand, but complex) |
| **FieldEZ** | Enterprise | India | Custom | No | Yes | Low (enterprise only, expensive) |
| **Srviz** | SME | India | Free–₹2,000/mo | No | Yes | Medium (direct but no AI) |
| **Goodservice** | SME | India | ₹1,000–₹3,000/mo | No | Yes | Medium (early, no AI) |

## Fieldo's Differentiation

| Dimension | Competitors | Fieldo |
|---|---|---|
| AI dispatch | None have it | Core feature |
| India-first UX | Poor or nonexistent | Hindi support, UPI payments, WhatsApp notifications |
| Price-to-value | High (especially US tools) | ₹2,999 starter |
| Setup time | Days to weeks | Under 30 minutes |
| Mobile app quality | Basic or missing | Offline-first, designed for Android budget phones |
| Skill matching | Manual | AI-powered |

## The Moat Fieldo Builds

1. **Data moat:** Every dispatch decision trains the AI on that company's preferences. After 90 days, the AI is calibrated to Ramesh's business specifically. A competitor offering a fresh AI model can't replicate this.

2. **Workflow moat:** After 3 months, the owner and all technicians depend on Fieldo daily. Switching means re-training everyone, losing 6 months of job history, and reconfiguring WhatsApp notifications. The pain of switching exceeds the pain of staying.

3. **Network effect (within company):** When 18 technicians all use the app and the owner uses the dashboard, the product becomes stickier for every additional user. Removing one person's access breaks everyone's workflow.

---

# 17. KPIs & Success Metrics

## North Star Metric

**Jobs dispatched through Fieldo per month** (across all customers)
This represents both platform usage and value delivered. If this grows, everything else follows.

## Business Metrics

| Metric | Target (Month 12) | Measurement |
|---|---|---|
| Monthly Recurring Revenue | ₹1,65,000 | Razorpay dashboard |
| Paying customers | 55 | CRM |
| Monthly churn rate | < 3% | Lost customers / total |
| Net Revenue Retention | > 105% | (MRR end - churned + expansion) / MRR start |
| CAC | < ₹8,000 | Time cost estimate + any ads spend |
| Trial-to-paid conversion | > 60% | Pilots → paid |

## Product Metrics

| Metric | Target | Why It Matters |
|---|---|---|
| AI dispatch acceptance rate | > 70% | If < 50%, AI is not trusted / not useful |
| Jobs dispatched per company per month | > 80 | Measures activation and real usage |
| Technician app DAU/MAU | > 0.8 | Technicians must use it daily |
| Customer notification delivery rate | > 95% | Core promise to owners |
| Average time to assign a job | < 90 seconds | vs. 15+ min manually |
| First-call-fix rate improvement | +10% vs. pre-Fieldo | Core value metric |
| Owner time saved per day | 2–3 hours | Ask owners in monthly survey |

## Customer Health Metrics

| Signal | Good | Warning | Action Required |
|---|---|---|---|
| Weekly jobs dispatched | > 15 | 5–15 | < 5 |
| Technician app logins | Daily | 3x/week | < 2x/week |
| Owner app logins | Daily | 3x/week | < 2x/week |
| Last job dispatched | < 3 days | 3–7 days | > 7 days |
| Support tickets | 0–1/month | 2–3/month | > 4/month |

Customers in "Action Required" get a personal call within 48 hours.

---

# 18. Security & Privacy

## Data Sensitivity Classification

| Data Type | Sensitivity | Protection |
|---|---|---|
| Customer phone numbers | High | Encrypted at rest, access logged |
| Technician GPS locations | High | Only shared with company's owner, not third parties |
| Job details | Medium | Tenant-isolated (company cannot see other companies' data) |
| Business revenue data | High | Encrypted, owner-only access |
| Authentication tokens | Critical | Short-lived JWTs, refresh token rotation |

## Security Measures

**Authentication:**

- Phone OTP-based login (no password to compromise)
- JWT tokens expire in 24 hours; refresh tokens in 30 days
- Rate limiting on OTP requests (prevent brute force)

**Multi-tenancy isolation:**

- Every database query includes `company_id` filter
- Row-level security (RLS) enforced at Supabase level
- A company can never access another company's data, even with a valid JWT

**API security:**

- HTTPS only (TLS 1.2+)
- Rate limiting: 100 requests/minute per company
- Input validation with Zod on all endpoints
- SQL injection prevention via Prisma ORM (parameterised queries)

**Technician location privacy:**

- GPS tracking only active during working hours (configurable per company)
- Technician can pause tracking (logged, owner notified)
- Locations not stored longer than 30 days
- Data never sold or shared with third parties

**Data residency:**

- All data hosted in India (AWS Mumbai / Supabase India region)
- Complies with Indian IT Act 2000 and PDPB (Personal Data Protection Bill)

---

# 19. Risks & Mitigations

| Risk | Probability | Impact | Mitigation |
|---|---|---|---|
| Technicians refuse to use the app | High | High | Keep app dead-simple; gamify with performance visibility; get owner buy-in first |
| Owner loses interest after free trial | Medium | High | Active onboarding: visit in person, set up together, check in on day 7 and 14 |
| Competitor copies the AI dispatch feature | Medium | Medium | Data moat — calibrated models per company cannot be copied. First-mover advantage in this niche. |
| WhatsApp API restrictions / cost increase | Low | Medium | Build SMS fallback. Use multiple WhatsApp API providers (Gupshup + Twilio). |
| Google Maps API cost spike | Low | Low | Switch to OpenStreetMap / MapBox (same integration) if Google raises prices. |
| Customer churn due to product complexity | Medium | High | Never add features that make the core workflow harder. Keep onboarding under 30 minutes. |
| Regulatory: GPS tracking privacy concerns | Low | Medium | Clear terms, consent during onboarding, data deletion on request. Comply with PDPB. |

---

# 20. Appendix

## Appendix A: Trade Skill Taxonomy

Skills used in technician profiles and job matching:

**HVAC / AC:**
`AC_REPAIR` `AC_INSTALLATION` `GAS_FILL` `INVERTER_AC` `SPLIT_AC` `WINDOW_AC` `CASSETTE_AC` `DUCT_AC` `DUCT_CLEANING` `PCB_REPAIR` `COMPRESSOR_REPLACEMENT`

**Plumbing:**
`PLUMBING_REPAIR` `PIPE_FITTING` `BATHROOM_FITTING` `WATER_HEATER` `BOREWELL` `TANK_CLEANING` `DRAINAGE_CLEANING` `KITCHEN_PLUMBING`

**Electrical:**
`ELECTRICAL_WIRING` `PANEL_WORK` `THREE_PHASE` `EARTHING` `INVERTER_INSTALLATION` `SOLAR_INSTALLATION` `CCTV_WIRING` `APPLIANCE_REPAIR`

## Appendix B: Notification Message Templates (Default)

**Tech assigned:**
> "Namaste [Customer Name]! Aapki [Job Type] service ke liye [Tech Name] ko assign kiya gaya hai. Unka number: [Tech Phone]. Estimated time: [Time Slot]. — [Company Name]"

**En route:**
> "[Tech Name] aapki taraf aa rahe hain. Expected arrival: [ETA]. Koi baat nahi — hum time pe pahunchenge. — [Company Name]"

**Arrived:**
> "[Tech Name] aapke door pe hain. Please door kholen. — [Company Name]"

**Completed:**
> "Kaam complete ho gaya! Koi bhi problem ho toh humein call karein: [Company Phone]. Rating dene ke liye: [Rating Link]. Shukriya! — [Company Name]"

## Appendix C: Glossary

| Term | Definition |
|---|---|
| Dispatch | The act of assigning a technician to a job |
| First-call-fix rate | % of jobs resolved without a callback or second visit |
| Callback | A return visit needed because the first visit didn't fix the problem |
| AMC | Annual Maintenance Contract — a customer pays annually for scheduled service |
| ARPA | Average Revenue Per Account |
| MRR | Monthly Recurring Revenue |
| CAC | Customer Acquisition Cost |
| LTV | Lifetime Value of a customer |
| ICP | Ideal Customer Profile |
| Churn | Customers who cancel their subscription |
| NRR | Net Revenue Retention — accounts for expansions and contractions |
| OTP | One-Time Password |
| JWT | JSON Web Token (authentication) |
| RLS | Row-Level Security (database access control) |
| FCM | Firebase Cloud Messaging (push notifications) |

---

*Document version: 1.0*
*Created: June 2025*
*Product: Fieldo — AI Dispatch Intelligence for Skilled Trades*
*Status: Pre-launch / MVP planning phase*

---

**© 2025 Fieldo. All rights reserved.**
