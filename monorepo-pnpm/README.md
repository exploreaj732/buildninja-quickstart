# Monorepo pnpm Build

BuildNinja configuration for Reactive Resume - a privacy-focused resume builder.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/AmruthPillai/Reactive-Resume |
| **Branch** | main |
| **Author** | [Amruth Pillai](https://github.com/AmruthPillai) |
| **Users** | 970,000+ |
| **Resumes Created** | 1.3 million+ |
| **License** | MIT |

## About Reactive Resume

A one-of-a-kind resume builder that keeps your privacy in mind. Completely secure, customizable, portable, open-source and free forever.

**Key Features:**
- Built with privacy as a core principle
- No tracking, no ads, no hidden costs
- Complete ownership of your data
- Self-hostable with Docker

**Tech Stack:**
- Frontend: React with TypeScript
- Backend: NestJS
- Database: PostgreSQL
- PDF Generation: Gotenberg (headless Chrome)
- Storage: SeaweedFS (S3-compatible)
- Package Manager: pnpm

## What This Demonstrates

- pnpm package manager for monorepos
- Complex multi-package builds
- Enterprise-scale JavaScript/TypeScript projects
- Frontend + Backend build pipelines

## Agent Requirements

- Node.js 18+
- pnpm (`npm install -g pnpm`)

## Build Steps

| Step | Command | Description |
|------|---------|-------------|
| 1 | `pnpm install` | Install all dependencies |
| 2 | `pnpm build` | Build all packages |

## Artifacts

- `dist/` - Built application
- `libs/utils/src/namespaces/tests` - Test utilities
