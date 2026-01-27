# Vite Lexical Build

BuildNinja configuration for Facebook's Lexical text editor framework.

## Source Repository

| Property | Value |
|----------|-------|
| **URL** | https://github.com/facebook/lexical |
| **Branch** | main |
| **Author** | Meta (Facebook) |
| **Stars** | 22,800+ |
| **License** | MIT |

## About Lexical

Lexical is an extensible JavaScript web text editor framework developed by Meta. It provides excellent reliability, accessibility, and performance for building rich text experiences.

**Key Features:**
- Framework Agnostic Core - Works with any UI framework
- Reliable & Accessible - Built-in WCAG compliance
- Extensible - Plugin-based architecture
- Immutable State Model - Time-travel with undo/redo
- Collaborative Editing - Real-time via Yjs integration
- Rich Content - Tables, lists, code blocks, images
- Cross-browser - Firefox 52+, Chrome 49+, Safari 11+, Edge 79+
- Type Safe - Written in TypeScript

**Browser Support:** Firefox 52+, Chrome 49+, Safari 11+, Edge 79+

## What This Demonstrates

- Meta/Facebook open-source build patterns
- Enterprise-scale TypeScript projects
- Complex npm monorepo builds
- Building popular text editor frameworks

## Agent Requirements

- Node.js 18+
- npm

## Build Steps

| Step | Command | Description |
|------|---------|-------------|
| 1 | `npm install` | Install dependencies |
| 2 | `npm run build` | Build all packages |

## Artifacts

- `packages/lexical/` - Core Lexical package
