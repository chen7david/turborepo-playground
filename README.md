# Turborepo Playground — Setup Plan

## To-Do

- [ ] Setup barebones frontend
  - [ ] Install Vite (`npm create vite@latest`)
  - [ ] Configure base project structure
  - [ ] Setup Cloudflare CI/CD for frontend (staging + production)

- [ ] Setup barebones backend
  - [ ] Create basic Express app
  - [ ] Configure routes + health check endpoint
  - [ ] Setup basic CI/CD for Express app through Jenkins (both frontend + backend)

## Notes

- This project will be structured as a Turborepo monorepo.
- Keep all configs (TS, ESLint, Prettier) in a shared `packages/config` package.
