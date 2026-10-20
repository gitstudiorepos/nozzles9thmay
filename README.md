# Nozzles

Managed with **[GitStud.io](https://gitstudio.web.app)** — Sovereign Media Vault & Git LFS Workspace for Film and Audio Creators.

## Quick Browser Access
Browse and stream audio/video directly in the browser:
- **GitStudio Web Player:** [Open in GitStud.io](https://gitstudio.web.app/browse?key=gs_ak8xlzjddqj8xo0l787jc5)

## Local Git + LFS Clone Setup
This repository is pre-configured with `.gitattributes` and `.lfsconfig` so large media files (`.wav`, `.mp4`, `.mov`, DAW/NLE sessions) are stored in your dedicated Google Cloud Storage vault instead of bloating Git history.

```bash
git lfs install
git clone https://github.com/gitstudiorepos/nozzles9thmay.git
cd nozzles9thmay
git lfs pull
```
