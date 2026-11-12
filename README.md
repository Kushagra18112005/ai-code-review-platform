# AI Code Review Platform

Rule-based code review API for JavaScript and TypeScript snippets. This first iteration does not call an LLM or GitHub API.

## Setup

Requires Node.js 20+. Run `npm install`, `npm run dev`, `npm run typecheck`, and `npm test`.

## Routes

`GET /health`, `POST /api/reviews`, `GET /api/reviews`, `GET /api/reviews/:id`.

Reviews are in memory. Add persistent storage and authentication before production use.
