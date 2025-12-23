# Project Mobile App
Ionic + Capacitor mobile application (Android/iOS)

## Tech Stack
- Ionic
- Capacitor
- Angular

## Git Workflow
- Feature branches are created from `develop`
- PRs are merged into `develop`
- `main` is updated only via release PRs

## Environment Variables
- Backend secrets are stored in `.env` (not committed)
- CI/CD secrets are stored in GitHub Actions Secrets
- Mobile environment configs are stored in Angular environment files