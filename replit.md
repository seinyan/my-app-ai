# Nuxt + NestJS Full-Stack Application

## Overview
This is a full-stack application with a Nuxt 4 (Vue 3) frontend and a NestJS backend API.

## Project Structure
```
/
├── front/           # Nuxt 4 frontend (Vue 3)
│   ├── nuxt.config.ts
│   └── package.json
├── api/             # NestJS backend API
│   ├── src/
│   │   ├── main.ts
│   │   ├── app.module.ts
│   │   ├── app.controller.ts
│   │   └── app.service.ts
│   └── package.json
└── replit.md        # This file
```

## Development

### Frontend (Nuxt 4)
- Runs on port 5000 (bound to 0.0.0.0)
- Start with: `cd front && npm run dev`
- Configured to trust all hosts for Replit proxy compatibility

### Backend (NestJS)
- Runs on port 3001 (bound to localhost)
- Start with: `cd api && npm run start:dev`

## Recent Changes
- 2026-01-20: Configured Nuxt frontend for Replit environment (port 5000, allowedHosts)
- 2026-01-20: Updated NestJS backend to use port 3001 on localhost
