# Mateos Xhukellari

**Full Stack Developer · DevOps · QA Automation Engineer**
Computer Science student at FSHN (Fakulteti i Shkencave të Natyrës), building and testing production software end to end.

## Overview

I design, build, and ship full stack applications — from data modelling and API design through to a deployed frontend backed by an automated CI/CD pipeline. My background in QA automation means I approach every system from two angles: how to build it correctly, and how to break it before it reaches production.

Currently, I own the backend and infrastructure for [Red Team Albania](https://rtacorp.co), a cybersecurity company — running a hardened, GitOps-managed production Kubernetes deployment with self-hosted Keycloak identity across multiple applications.

## Technologies

**Frontend**
React · TypeScript · TanStack · Zustand · Zod · Tailwind CSS · Vite · Electron

**Backend**
Java · Spring Boot · Spring Security · NestJS · C# / .NET · Rust · Node.js · Python · PostgreSQL · JWT · OAuth2 / OIDC · gRPC

**DevOps & Infrastructure**
Docker · Kubernetes (k3s) · Argo Rollouts · ArgoCD (GitOps) · GitHub Actions · Traefik · Redis · Maven · Ubuntu / Debian Linux

**Security**
Keycloak · Trivy · Gitleaks · Semgrep · Checkov · Cloudflare

**QA & Testing**
Playwright · Selenium · Cucumber · Postman

## Areas of Focus

**Backend Development**
REST API design with Java / Spring Boot and NestJS, secured with Spring Security, JWT, and — in production — self-hosted Keycloak with real OIDC across multiple isolated clients, including host-based multi-tenant authentication (separate `SecurityFilterChain`s for distinct subdomains within one application). Backed by PostgreSQL. Additional experience with C# / .NET modular monoliths, Python microservices for AI-driven features, Rust for systems-level work, and payment integration via Stripe Connect.

**Infrastructure & DevOps**
Production Kubernetes (k3s) with Argo Rollouts for canary deployments and ArgoCD for GitOps — proven working end to end, including automated sync and clean recovery from real merge conflicts. Containerisation with Docker and Docker Compose, CI/CD pipelines through GitHub Actions hardened with Trivy, Gitleaks, Semgrep, and Checkov (Kubernetes manifest scanning), with all third-party Actions pinned to verified commit SHAs. Multi-cloud deployment (Hetzner, Oracle Cloud) fronted by Traefik and Cloudflare.

**Production Operations**
Diagnosed and recovered a live memory-exhaustion incident — cascading pod failures and an unresponsive Kubernetes API server — down to its real root cause (a newly-added GitOps controller exceeding available node capacity), stabilizing the cluster via direct process management when the orchestration layer itself was unresponsive, then implementing lasting safeguards (swap, corrected autoscaling limits) rather than a one-time patch.

**Frontend Development**
Modern React and TypeScript single-page applications built on the TanStack ecosystem (Router and Query), with Zustand for state management, Zod for schema validation, and Tailwind CSS with shadcn/ui for the interface. Desktop applications delivered with Electron.

**QA Automation**
End-to-end and API test automation for enterprise systems:
- Playwright with Cucumber (BDD) — Page Object Model, Gherkin feature files, soft assertions
- Selenium with Cucumber — Java-based POM frameworks, WebDriver waits, data-driven testing
- API testing with Postman and REST endpoint validation
- Test pipelines integrated into GitHub Actions

## Selected Projects

**Red Team Albania — Cybersecurity Platform**
Backend and infrastructure for a live cybersecurity company: bug bounty aggregation, CTF hosting, penetration testing services, and a hands-on security training platform. Self-hosted Keycloak in production with per-application client isolation (including a dedicated, host-based admin authentication flow), canary deployments via Argo Rollouts, a GitOps pipeline via ArgoCD, and a CI/CD pipeline hardened with Trivy, Gitleaks, Semgrep, and Checkov.
`Java · Spring Boot · Rust · Kubernetes · Keycloak · ArgoCD · PostgreSQL · Redis`
Status: **Live**

**DocuMind AI — Document Intelligence Platform**
Production-ready backend with JWT authentication and a complete CI/CD pipeline.
`Java 17 · Spring Boot · PostgreSQL · Spring Security · Docker · GitHub Actions · React · TanStack · Zustand · Zod`
Status: In development

**Tiketa.al — Event Booking Platform**
An Eventbrite-style ticketing platform built for the Albanian market, with multi-role access, payment splitting, and QR-code tickets.
`React · TypeScript · Spring Boot · PostgreSQL · Stripe Connect`
Status: In development

**CVCraft — AI-Powered Resume Builder**
A desktop application that tailors CVs to individual job descriptions, with an application tracker and Kanban board.
`React · TypeScript · Spring Boot · Python (AI microservice) · Electron`
Status: In development

**HealthCare+ — Medical Appointment Booking**
Appointment scheduling with built-in chat and video calling.
`React · TypeScript · NestJS`
Status: Completed

## GitHub Statistics

![GitHub stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact)

## Contact

[LinkedIn](#) · [GitHub](#)

![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME)
