<div align="center">

# Leandro Jessé

**Full Stack Developer building product-driven applications with React, TypeScript, FastAPI, PostgreSQL and Supabase.**

I develop practical software products with structured architecture, secure data access, tested business rules and production-oriented workflows.

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=111827" alt="React 19" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/pgvector-Vector_Search-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=111827" alt="Supabase" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

</div>

---

## About

I build full stack applications around real operational and commercial workflows.

My projects combine frontend development, database modeling, authentication, authorization, business rules, automated testing and deployment. I am especially focused on transforming practical business problems into structured software products.

My current areas of development include:

* Multi-tenant SaaS applications
* Business and operational management systems
* E-commerce platforms
* Retrieval-Augmented Generation systems
* Secure Supabase applications with Row Level Security
* API development with FastAPI
* Automated tests, CI and production validation

---

## Featured Projects

### Job e Comissões

Multi-tenant SaaS for barbershop operations, covering appointment scheduling, public booking, barber management, commissions, financial reporting and tenant-scoped access.

The project started as a local commission management tool and evolved into a React and Supabase application with separate workflows for owners, barbers and clients.

**Current status**

```text
Technical MVP: completed
Pilot baseline: completed
Controlled pilot: ready
Scalable commercial SaaS: in development
```

**Stack**

React 19, TypeScript, Vite, Tailwind CSS, Framer Motion, Supabase, PostgreSQL, RLS, Vitest, Playwright, jsPDF and GitHub Actions.

**Product capabilities**

* Multi-tenant architecture using `barbershop_id`
* Public booking through `/book/:slug`
* Guided owner onboarding
* Operational readiness checklist
* Tenant-scoped barber and service catalogs
* Configurable business hours and appointment intervals
* Public branding for each barbershop
* Barber account linking through a database RPC
* Role-based access for owners and barbers
* Barber dashboard restricted to the authenticated professional
* Internal appointment creation and status management
* Duplicate active-slot protection
* Gross revenue, calculated commission and estimated balance reporting
* Voucher and financial record management
* PDF and CSV report export
* Human-readable operational error messages
* Contextualized and sanitized diagnostic logs
* Fail-closed behavior when Supabase is unavailable in production
* Unit, integration and browser tests
* Initial bundle and rendering performance improvements
* Responsive onboarding tour

**Architecture and security**

* Supabase Authentication
* PostgreSQL persistence
* Row Level Security
* Tenant-aware repositories
* Role-based application flows
* Local fallback restricted to development and demonstration
* GitHub Actions validation pipeline
* Vercel deployment

**Repository**

https://github.com/leorecoa/Job-e-Comiss-es

**Application**

https://job-e-comiss-es.vercel.app

**Public booking**

https://job-e-comiss-es.vercel.app/book

---

### RagResover

Local-first Retrieval-Augmented Generation platform for indexing private documents, retrieving semantically relevant content and answering questions with cited sources.

The project combines a FastAPI backend, vector search, object storage and a React interface to provide a complete document ingestion and retrieval workflow.

**Stack**

FastAPI, Python, PostgreSQL, pgvector, Redis, MinIO, Docker, React, TypeScript, Vite, Ollama and OpenAI.

**Product capabilities**

* Private document upload
* TXT, Markdown, JSON, PDF and DOCX extraction
* Document processing and chunking pipeline
* Embedding generation
* PostgreSQL vector storage with pgvector
* Semantic document search
* RAG chat with retrieved source references
* Tenant-scoped access
* API token support
* React dashboard for upload, search and chat
* Local object storage using MinIO
* Local model execution using Ollama
* OpenAI provider support for production environments
* Database migrations with Alembic
* Automated backend tests
* Docker Compose development environment

**Architecture**

```text
React frontend
      |
FastAPI API
      |
Retrieval and ingestion services
      |
PostgreSQL + pgvector
      |
MinIO / Ollama / OpenAI
```

**Repository**

https://github.com/leorecoa/RagResover

**Frontend**

https://ragresover-frontend.vercel.app

---

### Mansão Maromba

Full stack e-commerce application focused on product discovery, protected checkout, order processing, stock control and administrative operations.

**Stack**

React 19, TypeScript, Vite, Tailwind CSS, Zustand, TanStack Query, Supabase, PostgreSQL, Vitest, Playwright and Vercel.

**Product capabilities**

* Product and category catalog
* Product details
* Persistent shopping cart
* Protected checkout
* Google OAuth authentication
* Customer profile and order history
* Transactional order creation through SQL RPC
* Stock validation and decrement during order creation
* Order item snapshots
* Administrative product management
* Administrative order management
* Product image upload with validation
* Role-based administrative access
* Supabase Row Level Security
* Unit, integration and end-to-end test structure
* Vercel deployment

**Application**

https://projeto-site-mansao-maromba.vercel.app

**Repository**

https://github.com/leorecoa/Projeto-Site-Mansao-Maromba

---

## Engineering Scope

<table>
  <tr>
    <td><strong>Frontend</strong></td>
    <td>React, TypeScript, Vite, Tailwind CSS, Zustand, TanStack Query and Framer Motion</td>
  </tr>
  <tr>
    <td><strong>Backend</strong></td>
    <td>FastAPI, Supabase, PostgreSQL and SQL functions</td>
  </tr>
  <tr>
    <td><strong>Authentication</strong></td>
    <td>Supabase Auth, Google OAuth and API tokens</td>
  </tr>
  <tr>
    <td><strong>Security</strong></td>
    <td>Row Level Security, RBAC, tenant isolation and protected routes</td>
  </tr>
  <tr>
    <td><strong>AI and RAG</strong></td>
    <td>Embeddings, semantic search, pgvector, retrieval pipelines, Ollama and OpenAI</td>
  </tr>
  <tr>
    <td><strong>Testing</strong></td>
    <td>Vitest, Pytest, Playwright, integration tests and business-rule tests</td>
  </tr>
  <tr>
    <td><strong>Infrastructure</strong></td>
    <td>Docker, Docker Compose, MinIO, GitHub Actions and Vercel</td>
  </tr>
</table>

---

## Development Principles

* Model the business rules before building the interface
* Keep UI, domain logic and persistence responsibilities separated
* Treat authentication and authorization as different concerns
* Apply tenant isolation at the database level
* Preserve historical financial data
* Validate inputs at application and database boundaries
* Protect production workflows with fail-closed behavior
* Use automated tests for critical operational rules
* Document the actual product state without inflating unfinished features
* Deliver changes through isolated branches and reviewed pull requests

---

## Current Focus

* Validating Job e Comissões in a controlled real-world pilot
* Improving multi-tenant architecture and Supabase RLS
* Expanding automated browser and integration testing
* Strengthening application observability and production diagnostics
* Developing private-document RAG pipelines
* Improving checkout, order and inventory consistency
* Converting practical workflows into maintainable SaaS products

---

## Selected Product Areas

```text
Barbershop SaaS
├── Public booking
├── Internal scheduling
├── Commission reporting
├── Owner onboarding
├── Barber access
└── Multi-tenant security

Private-document RAG
├── Document ingestion
├── Chunking
├── Embeddings
├── Vector search
├── Source retrieval
└── RAG responses

E-commerce
├── Authentication
├── Product catalog
├── Persistent cart
├── Protected checkout
├── Order processing
└── Inventory control
```

---

## Contact

* **GitHub:** https://github.com/leorecoa
* **LinkedIn:** https://www.linkedin.com/in/leandro-jess%C3%A9-7b575539a/

---
