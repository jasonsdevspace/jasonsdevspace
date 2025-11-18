# GitHub Profile Project Roadmap

This roadmap tracks the projects and structure I’m building out in this GitHub profile to showcase my experience and coding style.

---

## Phase 1 – Core Repos

### 1. `frontend-dashboard`
**Goal:** A clean React + Vite + TypeScript dashboard that demonstrates front-end architecture and testing.

- [ ] Initialize Vite React + TS project
- [ ] Configure ESLint + Prettier + TypeScript strict mode
- [ ] Set up basic routing (e.g., `/`, `/analytics`, `/settings`)
- [ ] Implement a small dashboard layout with responsive design
- [ ] Add example widgets (table, chart, stats cards)
- [ ] Integrate React Query (or similar) with mock API layer
- [ ] Add unit + integration tests (Vitest + Testing Library)
- [ ] Add GitHub Actions CI (lint, test, build)
- [ ] Write a clear README with screenshots

---

### 2. `fullstack-next-supabase`
**Goal:** Full-stack app with Next.js and Supabase demonstrating auth, database, and API routes.

- [ ] Initialize Next.js + TypeScript project (App Router)
- [ ] Connect to Supabase (env config, client setup)
- [ ] Implement email/password (or magic link) auth
- [ ] Create basic schema (e.g., `profiles`, `tasks`, or `notes`)
- [ ] Add protected routes + server components using Supabase
- [ ] Implement CRUD operations using API routes and/or server actions
- [ ] Add basic tests (unit + api route tests)
- [ ] Add Docker support for local dev (if needed)
- [ ] Add GitHub Actions CI
- [ ] Document architecture and decisions in README

---

### 3. `backend-api-fastify`
**Goal:** A robust REST API showing structure, validation, and observability.

- [ ] Initialize Node.js + TypeScript project
- [ ] Set up Fastify with healthcheck route
- [ ] Configure logging and request validation (Zod or similar)
- [ ] Implement sample resource (e.g., `/users` or `/todos`)
- [ ] Add error handling and consistent response shapes
- [ ] Integrate with Postgres (or in-memory + interface)
- [ ] Add tests (unit + integration)
- [ ] Add Dockerfile + docker-compose for local development
- [ ] Add GitHub Actions CI
- [ ] Document endpoints (OpenAPI or markdown) in README

---

### 4. `algorithms-sandbox`
**Goal:** A focused repo for data structures and algorithms in TypeScript.

- [ ] Initialize TypeScript project
- [ ] Set up testing (Vitest or Jest)
- [ ] Implement core data structures (linked list, stack, queue, tree, graph)
- [ ] Implement classic algorithms (binary search, BFS/DFS, sorting)
- [ ] Add performance notes and trade-off comments
- [ ] Organize by topic in folders
- [ ] Add GitHub Actions CI
- [ ] Write README with how to run tests and what’s included

---

### 5. `architecture-patterns`
**Goal:** Small, isolated examples of software architecture and design patterns.

- [ ] Initialize TypeScript project
- [ ] Create examples:
  - [ ] Layered architecture (API, service, repository)
  - [ ] Repository pattern with in-memory + DB implementation
  - [ ] Event-driven flow with simple event bus
  - [ ] Dependency injection example
- [ ] Write short explanations in each folder’s README
- [ ] Add basic tests where useful
- [ ] Add GitHub Actions CI

---

### 6. `simple-games-react`
**Goal:** Fun demos that show interactive UI and clean state management.

- [ ] Initialize React + TypeScript project (Vite)
- [ ] Implement Tic-Tac-Toe (with scalable board size)
- [ ] Implement at least one more game (e.g., counter-based, timing-based, or simple puzzle)
- [ ] Separate UI from game logic into pure functions
- [ ] Add tests for game logic
- [ ] Polish basic styling and responsiveness
- [ ] Add GitHub Actions CI

---

## Phase 2 – Extras and Polish

- [ ] Add screenshots / GIFs to each README
- [ ] Add a “How to Use This in Interviews” section in one repo
- [ ] Create a `resume-and-interview` repo with:
  - [ ] Resume PDF (or template)
  - [ ] Summary of tech stack
  - [ ] Example interview problem walkthroughs
- [ ] Create small reusable tooling repos (e.g., CLI, utilities)
- [ ] Update profile README to match final list of highlighted projects

---

## Phase 3 – Maintenance

- [ ] Keep dependencies reasonably up to date
- [ ] Add new patterns or algorithms periodically
- [ ] Add links to talks, blog posts, or gists if created
