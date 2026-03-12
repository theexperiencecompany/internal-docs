# GAIA Internal Docs

Internal developer documentation for the GAIA platform, built with [Mintlify](https://mintlify.com).

Covers the main [GAIA monorepo](https://github.com/theexperiencecompany/gaia) — Next.js frontend, FastAPI/LangGraph backend, React Native mobile, Electron desktop, and Discord/Slack/Telegram bots.

## Contents

- **Getting started** — prerequisites, local setup
- **Production** — environment variables, Docker Compose, Grafana/observability, bot deployment

## Local preview

Install the Mintlify CLI and run:

```bash
npm install -g mintlify
mintlify dev
```

Docs will be available at `http://localhost:3000`.

## Structure

```
docs.json                        # Mintlify config
index.mdx
getting-started/
  prerequisites.mdx
  local-setup.mdx
production/
  overview.mdx
  environment-variables.mdx
  docker.mdx
  grafana.mdx
  bots.mdx
```

## Deployment

Connected to Mintlify — docs auto-deploy on every push to `main`.
