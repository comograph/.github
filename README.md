<p align="center">
  <img src="profile/lockup-dark.svg" alt="Comograph" width="480" />
</p>

<p align="center">
  <strong>Hire Engineers Who Prove It</strong>
</p>

<p align="center">
  Proof-of-work hiring for engineering teams — post real challenges, review GitHub repos and Loom walkthroughs, and get scored shortlists instead of another resume pile.
</p>

<p align="center">
  <a href="https://comograph.com">Website</a> ·
  <a href="https://www.linkedin.com/company/comograph/">LinkedIn</a> ·
  <a href="https://www.facebook.com/comograph/">Facebook</a>
</p>

---

## How it works

1. **Post a challenge** — Employers define real engineering problems from their stack: backend APIs, fullstack features, or DevOps pipelines.
2. **Engineers submit proof** — Candidates ship a public GitHub repo and a Loom walkthrough. Comograph scores submissions within 72 hours.
3. **Review ranked talent** — Browse leaderboards, reputation profiles, and five-dimension score breakdowns. Shortlist engineers who already proved they can deliver.

## Repositories

| Repository | Description | Dev port |
| --- | --- | --- |
| [comograph-backend](https://github.com/comograph/comograph-backend) | NestJS API — auth, challenges, submissions, scoring, reputation | 3000 |
| [comograph-engineer-portal](https://github.com/comograph/comograph-engineer-portal) | Engineer app — challenges, submissions, profile | 5173 |
| [comograph-employer-portal](https://github.com/comograph/comograph-employer-portal) | Employer app — post challenges, leaderboards, candidates | 5174 |
| [comograph-admin-portal](https://github.com/comograph/comograph-admin-portal) | Internal ops — scoring queue, approvals | 5175 |
| [comograph-landing](https://github.com/comograph/comograph-landing) | Public marketing site | — |

## Tech stack

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-11-E0234E?logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-5-2D3748?logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-BullMQ-DC382D?logo=redis&logoColor=white)

**Frontends**

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-5-FF4154?logo=reactquery&logoColor=white)

## Scoring rubric

Submissions are scored across five dimensions:

**Technical 40%** · **Problem Solving 20%** · **Documentation 15%** · **Architecture 15%** · **Communication 10%**

## Getting started

Clone the backend and run the local stack:

```bash
git clone https://github.com/comograph/comograph-backend.git
cd comograph-backend
cp .env.example .env
docker compose up postgres -d
npm run db:push
npm run prisma:seed
npm run start:dev
```

API: `http://localhost:3000/api/v1` · Swagger: `http://localhost:3000/api/docs`

Seed credentials (password `Admin123!`): `admin@comograph.dev`, `employer@comograph.dev`, `david@comograph.dev`

Portal repos run alongside the API on ports 5173–5175. See each repo's README for setup.

---

<p align="center">
  <em>Early-career engineers build real proof instead of relying on pedigree alone — and employers hire globally with evidence, not geographic guesswork.</em>
</p>
