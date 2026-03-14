# PM Toolkit

## Project Overview

A free, open-access collection of 18 product management templates. Single-page HTML app — no build step, no backend.

## Architecture

- **Single file**: Everything lives in `pm-toolkit.html` — React components, template content, and styles
- **CDN dependencies**: React 18, Tailwind CSS, Babel (JSX transform), Marked.js (Markdown rendering)
- **No build step**: Open the HTML file directly in a browser

## Template Categories

- Strategy & Planning (PRD, Roadmap, Competitive Analysis, OKRs)
- Feature Development (Feature Spec, User Story Map, Technical Brief)
- Agile & Sprints (Sprint Planning, Retro, Backlog Prioritization)
- Research & Discovery (Research Plan, Interview Guide, Survey)
- Communication (Stakeholder Brief, Meeting Notes, Status Update)
- Launch & Operations (Launch Checklist, GTM Plan, Post-Mortem)

## Working With This Codebase

- All template content is defined as Markdown strings inside `pm-toolkit.html`
- To add a new template: add a template object to the templates array with `title`, `category`, `content` (Markdown string), and `icon`
- To modify an existing template: find its entry in the templates array and edit the `content` field
- Categories are color-coded — follow existing category naming to match colors

## Branches

- `main` — production/published branch
- `source` — development branch
