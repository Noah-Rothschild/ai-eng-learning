# Week 0 — Environment & Account Setup

Got accounts, billing safety nets, and local tooling in place before starting.

## What I set up
- Fresh AWS account, $100 signup credit, budget alerts configured (zero-spend template)
- Anthropic Console API key with a small prepaid credit balance
- Local dev environment on Windows: Python 3.11+, Docker Desktop (WSL2 backend), AWS CLI v2
- This repo initialized, `.gitignore` confirmed to exclude `.env`

## Verification checklist
- [x] `python --version`
- [x] `aws sts get-caller-identity`
- [x] `docker run --rm hello-world`
- [ ] Anthropic API key makes a successful test call