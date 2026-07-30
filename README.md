# EvalZero Docs

Mintlify documentation for EvalZero LMS and its Sunbird services — one folder per service.

## Preview locally

```bash
cd /home/sdas/evalzero/evalzero-docs
npm i -g mint      # or: npx mint@latest dev
mint dev           # serves at http://localhost:3000
```

## Structure

- `index.mdx` — home
- `guide/` — quickstart, service map, ports, architecture
- one folder per service — `lms/`, `inquiry/`, `auth/`, `knowlg/`, `rc/`, `infra/`, `email/`
- `docs.json` — Mintlify navigation (Home / Guide / Services tabs)

Each service folder holds that service's overview + startup guide (and deps/config where relevant).
