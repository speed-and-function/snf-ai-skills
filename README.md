# SNF AI Skills

Umbrella repository for Speed & Function AI skill libraries.

This repo contains domain-specific skill repositories as Git submodules:

- `content-engine` — marketing, copywriting, social media skills
- `eboss` — E-BOSS meeting, RAS, and operating system skills
- `enterprise` — client delivery, proposals, estimation skills
- `internal` — HR, onboarding, admin skills

## Clone with all submodules

```bash
git clone --recurse-submodules git@github.com:speed-and-function/snf-ai-skills.git
```

## If already cloned without submodules

```bash
git submodule update --init --recursive
```

## Repository layout

- content-engine/
- eboss/
- enterprise/
- internal/

More domain repositories can be added later without changing the umbrella structure