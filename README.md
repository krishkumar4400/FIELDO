# FIELDO

> AI-powered dispatch intelligence platform for HVAC, plumbing, electrical, and field service businesses.

FIELDO helps service companies automatically assign the right technician to the right job using operational intelligence, realtime routing, AI predictions, and workflow automation.

Instead of relying on:

* phone calls
* dispatcher intuition
* WhatsApp chaos
* spreadsheets
* whiteboards

FIELDO creates an intelligent operational layer for field workforce coordination.

---

# Vision

Field service industries still operate with fragmented systems and manual coordination.

FIELDO aims to become:

> The operating system for field operations.

Our mission is to reduce:

* wrong technician dispatches
* excessive drive time
* callbacks
* scheduling chaos
* dispatcher overload
* operational inefficiency

using AI-powered decision systems.

---

# Problem

Most HVAC, plumbing, and electrical companies still rely on:

* dispatch managers
* manual scheduling
* spreadsheets
* WhatsApp groups
* paper job cards
* phone calls

This creates:

* delayed assignments
* poor technician utilization
* customer frustration
* repeat visits
* fuel waste
* operational stress

A 20-technician service company can lose:

* ₹20L–₹50L yearly
  from inefficient dispatching alone.

---

# Solution

FIELDO automatically:

* recommends the best technician
* optimizes routes
* predicts job duration
* estimates callback risk
* balances technician workload
* tracks field operations in realtime

The platform combines:

* operational workflows
* location intelligence
* predictive AI
* workforce analytics
* dispatch automation

into a single command center.

---

# Core Features

## AI Dispatch Recommendation Engine

Automatically recommends:

* best technician
* best route
* estimated arrival time
* workload-balanced assignment

based on:

* technician skill
* location
* historical performance
* callback history
* job complexity
* traffic conditions

---

## Smart Scheduling

* Dynamic scheduling
* Real-time rescheduling
* Route optimization
* Emergency prioritization
* Shift balancing

---

## Callback Risk Prediction

Predicts:

* jobs likely to fail
* technicians likely to require repeat visits
* complex repairs needing senior technicians

This reduces:

* repeat visits
* customer complaints
* revenue leakage

---

## Technician Mobile App

Technicians can:

* receive jobs
* navigate to customers
* upload photos
* update status
* submit service reports
* log parts used

Supports:

* offline mode
* realtime sync
* push notifications

---

## Realtime Operations Dashboard

Operations teams can monitor:

* active jobs
* delayed technicians
* live technician locations
* SLA performance
* job queues
* dispatch efficiency

---

## Customer Communication Layer

Automatic:

* WhatsApp notifications
* ETA updates
* job completion messages
* service confirmations

---

## AI Forecasting

Predict:

* demand spikes
* seasonal service surges
* technician shortages
* staffing requirements

---

# Product Architecture

FIELDO is built as a distributed, event-driven SaaS platform.

## Frontend

* Next.js
* React
* TailwindCSS
* Zustand
* React Query

---

## Mobile

* React Native

---

## Backend

* Node.js
* NestJS
* FastAPI (AI services)

---

## Databases

* PostgreSQL
* Redis
* ClickHouse (analytics)
* Vector DB (AI retrieval)

---

## AI Stack

* Python
* PyTorch
* XGBoost
* LightGBM
* MLflow

---

## Infrastructure

* Docker
* Kubernetes
* Terraform
* AWS

---

## Observability

* Prometheus
* Grafana
* OpenTelemetry
* Loki

---

# System Architecture

```text
Client Apps
    ↓
API Gateway
    ↓
Core Services
    ↓
Event Bus
    ↓
AI + Analytics Layer
```

---

# Microservices

## Core Services

### Dispatch Service

Handles:

* job assignments
* scheduling
* optimization
* workload balancing

### AI Service

Handles:

* prediction models
* technician matching
* demand forecasting
* callback prediction

### Realtime Service

Handles:

* websocket streams
* technician tracking
* live dashboards

### Notification Service

Handles:

* WhatsApp
* SMS
* email
* push notifications

### Analytics Service

Handles:

* reporting
* KPIs
* operational metrics
* historical analysis

---

# Database Design

## Core Tables

* companies
* users
* technicians
* technician_skills
* customers
* service_requests
* job_assignments
* job_events
* ai_recommendations
* technician_location_history
* callbacks
* notifications

---

# AI Models

## Technician Matching Model

Predicts:

* best technician for job

Inputs:

* skills
* historical performance
* distance
* job complexity

---

## Callback Prediction Model

Predicts:

* probability of repeat visit

---

## ETA Prediction Model

Uses:

* traffic
* technician behavior
* historical travel data

---

## Demand Forecasting

Predicts:

* service demand
* seasonal spikes
* staffing requirements

---

# Event-Driven Architecture

Every operational action becomes an event.

Examples:

* job.created
* technician.assigned
* technician.arrived
* repair.completed

Benefits:

* auditability
* analytics
* AI training
* realtime processing

---

# Security

* JWT authentication
* RBAC authorization
* tenant isolation
* encrypted secrets
* audit logging
* API rate limiting

---

# Multi-Tenant SaaS

FIELDO supports:

* multiple companies
* branch isolation
* role-based access
* subscription billing

Each company operates in isolated logical tenancy.

---

# Folder Structure

```text
apps/
services/
packages/
infrastructure/
databases/
event-bus/
observability/
security/
docs/
```

---

# AI Moat

FIELDO compounds operational intelligence over time.

The system learns:

* which technician solves which issue fastest
* which jobs cause callbacks
* which routes create delays
* seasonal demand patterns
* technician reliability trends

This creates:

* workflow moat
* operational moat
* data moat

---

# Why This Market Matters

Field service industries represent:

* hundreds of billions in economic activity
* low software penetration
* massive operational inefficiency
* fragmented legacy tooling

Most SMEs still operate manually.

FIELDO modernizes field operations with intelligent infrastructure.

---

# Ideal Customers

## Primary ICP

Field service businesses with:

* 5–200 technicians
* high dispatch volume
* manual scheduling workflows

Industries:

* HVAC
* plumbing
* electrical
* appliance repair
* telecom installation
* pest control
* solar maintenance

---

# Pricing Strategy

## SaaS Pricing

### Starter

Small teams

### Growth

Advanced dispatch intelligence

### Enterprise

Custom workflows + analytics + integrations

Potential future monetization:

* usage pricing
* AI pricing
* embedded financing
* payments
* insurance
* inventory intelligence

---

# MVP Scope

## Initial Features

* Job management
* Technician management
* AI technician recommendation
* Dispatch board
* Realtime tracking
* Mobile technician app
* WhatsApp notifications

---

# What NOT To Build Initially

* payroll systems
* full ERP
* inventory suite
* advanced accounting
* massive analytics dashboards

Focus:

* dispatch intelligence
* operational efficiency
* workflow automation

---

# Go-To-Market

## Initial Customer Acquisition

* Google Maps outreach
* founder-led sales
* WhatsApp demos
* local HVAC contractors
* free pilot deployments

Target:

* 5–30 technician businesses

---

# Long-Term Vision

FIELDO evolves from:

* dispatch software

into:

* operational intelligence platform
* AI coordination layer
* field workforce infrastructure

Future expansion:

* predictive maintenance
* inventory forecasting
* AI voice dispatch
* embedded fintech
* IoT integrations
* autonomous scheduling

---

# Development Setup

## Install Dependencies

```bash
pnpm install
```

---

## Run Frontend

```bash
cd apps/web
pnpm dev
```

---

## Run Backend

```bash
cd services/api-gateway
pnpm dev
```

---

## Run AI Service

```bash
cd services/ai-service
python main.py
```

---

## Run Docker Stack

```bash
docker-compose up
```

---

# Environment Variables

```env
DATABASE_URL=
REDIS_URL=
JWT_SECRET=
GOOGLE_MAPS_API_KEY=
OPENAI_API_KEY=
TWILIO_API_KEY=
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
```

---

# Engineering Principles

* event-driven systems
* operational reliability
* scalability-first architecture
* AI-assisted workflows
* observability-first engineering
* multi-tenant isolation
* realtime coordination

---

# Philosophy

FIELDO is not:

* another AI wrapper
* another CRUD dashboard
* another scheduling tool

FIELDO is:

* operational infrastructure
* workforce intelligence
* AI-powered coordination system

---

# Future

The future of field operations is:

* autonomous dispatch
* predictive coordination
* realtime operational intelligence
* AI-assisted workforce management

FIELDO aims to power that future.

## Project Structure

FIELDO/
│
├── apps/
│   │
│   ├── web/                         # Dispatcher dashboard (Next.js)
│   │   ├── src/
│   │   │   ├── app/
│   │   │   ├── components/
│   │   │   ├── modules/
│   │   │   ├── hooks/
│   │   │   ├── services/
│   │   │   ├── store/
│   │   │   ├── lib/
│   │   │   ├── utils/
│   │   │   ├── styles/
│   │   │   ├── providers/
│   │   │   ├── config/
│   │   │   └── types/
│   │   │
│   │   ├── public/
│   │   ├── tests/
│   │   ├── package.json
│   │   └── next.config.js
│   │
│   ├── mobile/                      # Technician mobile app
│   │   ├── src/
│   │   │   ├── screens/
│   │   │   ├── components/
│   │   │   ├── services/
│   │   │   ├── hooks/
│   │   │   ├── navigation/
│   │   │   ├── store/
│   │   │   ├── utils/
│   │   │   ├── config/
│   │   │   └── types/
│   │   │
│   │   ├── android/
│   │   ├── ios/
│   │   ├── package.json
│   │   └── app.json
│   │
│   └── admin/                       # Internal admin panel
│       ├── src/
│       └── package.json
│
├── services/
│   │
│   ├── api-gateway/                 # Main gateway
│   │   ├── src/
│   │   │   ├── routes/
│   │   │   ├── middleware/
│   │   │   ├── auth/
│   │   │   ├── validators/
│   │   │   ├── controllers/
│   │   │   ├── services/
│   │   │   ├── dto/
│   │   │   ├── utils/
│   │   │   ├── config/
│   │   │   └── index.ts
│   │   │
│   │   ├── tests/
│   │   └── package.json
│   │
│   ├── auth-service/
│   │   ├── src/
│   │   │   ├── jwt/
│   │   │   ├── oauth/
│   │   │   ├── permissions/
│   │   │   ├── sessions/
│   │   │   └── controllers/
│   │   └── package.json
│   │
│   ├── dispatch-service/            # CORE BUSINESS LOGIC
│   │   ├── src/
│   │   │   ├── engine/
│   │   │   │   ├── assignment/
│   │   │   │   ├── scheduling/
│   │   │   │   ├── routing/
│   │   │   │   ├── scoring/
│   │   │   │   └── optimization/
│   │   │   │
│   │   │   ├── jobs/
│   │   │   ├── technicians/
│   │   │   ├── customers/
│   │   │   ├── events/
│   │   │   ├── repositories/
│   │   │   ├── queues/
│   │   │   ├── workers/
│   │   │   ├── websocket/
│   │   │   ├── metrics/
│   │   │   ├── utils/
│   │   │   └── config/
│   │   │
│   │   └── package.json
│   │
│   ├── ai-service/
│   │   ├── src/
│   │   │   ├── models/
│   │   │   │   ├── duration_prediction/
│   │   │   │   ├── callback_prediction/
│   │   │   │   ├── skill_matching/
│   │   │   │   ├── demand_forecasting/
│   │   │   │   └── route_eta/
│   │   │   │
│   │   │   ├── training/
│   │   │   ├── inference/
│   │   │   ├── pipelines/
│   │   │   ├── feature_store/
│   │   │   ├── embeddings/
│   │   │   ├── vector_search/
│   │   │   ├── prompts/
│   │   │   ├── llm/
│   │   │   ├── evaluation/
│   │   │   ├── datasets/
│   │   │   ├── notebooks/
│   │   │   └── utils/
│   │   │
│   │   ├── models/
│   │   └── requirements.txt
│   │
│   ├── notification-service/
│   │   ├── src/
│   │   │   ├── whatsapp/
│   │   │   ├── sms/
│   │   │   ├── email/
│   │   │   ├── push/
│   │   │   ├── templates/
│   │   │   └── workers/
│   │   └── package.json
│   │
│   ├── realtime-service/
│   │   ├── src/
│   │   │   ├── sockets/
│   │   │   ├── streams/
│   │   │   ├── tracking/
│   │   │   ├── redis/
│   │   │   └── presence/
│   │   └── package.json
│   │
│   ├── billing-service/
│   │   ├── src/
│   │   │   ├── subscriptions/
│   │   │   ├── invoices/
│   │   │   ├── payments/
│   │   │   ├── usage/
│   │   │   └── webhooks/
│   │   └── package.json
│   │
│   ├── analytics-service/
│   │   ├── src/
│   │   │   ├── dashboards/
│   │   │   ├── warehouse/
│   │   │   ├── reports/
│   │   │   ├── aggregations/
│   │   │   ├── event-processing/
│   │   │   └── metrics/
│   │   └── package.json
│   │
│   └── integration-service/
│       ├── src/
│       │   ├── quickbooks/
│       │   ├── google_maps/
│       │   ├── whatsapp/
│       │   ├── stripe/
│       │   ├── twilio/
│       │   └── webhooks/
│       └── package.json
│
├── packages/
│   │
│   ├── ui/                          # Shared UI components
│   ├── types/                       # Shared TS types
│   ├── eslint-config/
│   ├── tsconfig/
│   ├── logger/
│   ├── event-sdk/
│   ├── auth-sdk/
│   ├── api-client/
│   ├── constants/
│   └── utils/
│
├── infrastructure/
│   │
│   ├── docker/
│   │   ├── api/
│   │   ├── ai/
│   │   ├── postgres/
│   │   ├── redis/
│   │   ├── nginx/
│   │   └── monitoring/
│   │
│   ├── kubernetes/
│   │   ├── staging/
│   │   ├── production/
│   │   ├── ingress/
│   │   ├── secrets/
│   │   └── autoscaling/
│   │
│   ├── terraform/
│   │   ├── aws/
│   │   ├── networking/
│   │   ├── databases/
│   │   ├── queues/
│   │   ├── storage/
│   │   └── monitoring/
│   │
│   ├── nginx/
│   └── scripts/
│
├── databases/
│   │
│   ├── postgres/
│   │   ├── migrations/
│   │   ├── seeds/
│   │   ├── schemas/
│   │   ├── functions/
│   │   └── triggers/
│   │
│   ├── redis/
│   ├── clickhouse/
│   └── vector-db/
│
├── event-bus/
│   │
│   ├── kafka/
│   ├── topics/
│   ├── consumers/
│   ├── producers/
│   └── schemas/
│
├── observability/
│   │
│   ├── prometheus/
│   ├── grafana/
│   ├── loki/
│   ├── opentelemetry/
│   ├── alerts/
│   └── dashboards/
│
├── security/
│   │
│   ├── policies/
│   ├── encryption/
│   ├── audit/
│   ├── secrets/
│   └── compliance/
│
├── docs/
│   │
│   ├── architecture/
│   ├── api/
│   ├── product/
│   ├── ai/
│   ├── workflows/
│   ├── onboarding/
│   └── runbooks/
│
├── .github/
│   │
│   ├── workflows/
│   │   ├── ci.yml
│   │   ├── cd.yml
│   │   ├── tests.yml
│   │   ├── security.yml
│   │   └── deploy.yml
│   │
│   └── ISSUE_TEMPLATE/
│
├── tools/
│   ├── scripts/
│   ├── generators/
│   └── migrations/
│
├── .env
├── .env.production
├── docker-compose.yml
├── turbo.json
├── pnpm-workspace.yaml
├── package.json
├── README.md
└── Makefile
