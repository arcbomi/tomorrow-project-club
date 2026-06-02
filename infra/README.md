# Infra Rules

This file sets the club's technical boundaries.

## Allowed Project Stack

- Frontend: React or Next.js
- Styling: Tailwind CSS is allowed
- Styling: SCSS is not allowed
- Package manager: pnpm
- Backend services: Go or Node.js with Fastify
- Data: PostgreSQL
- Cache: Redis
- Eventing / queues: Kafka
- Containerization: Docker
- CI: GitHub Actions
- Language: TypeScript only
- API style: REST/JSON only, no GraphQL

Plain JavaScript is not allowed for project code.


## Repository Rules

- Every project repo must be public
- PR review is required before merge
- Weekly releases are expected
- MIT is the default license

## Privacy Rules

- Do not publish student names, photos, emails, phone numbers, or private school data in public repos
- Keep sensitive internal notes out of the public project repository
- Ask before publishing anything that could identify a student in a risky way

## Tooling Rules

- Prefer Node.js, pnpm, and TypeScript-based tooling for automation
- Keep helper scripts small and documented
- Do not introduce another major runtime language just for convenience

## Third-Party Assets

- Check the license before importing code, fonts, icons, or other assets
- Keep attribution notes in the repo when needed
- Do not copy code from an unknown source
