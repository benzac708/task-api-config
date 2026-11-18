# task-api-config

Kustomize base and Argo CD application for task-api. Argo CD watches this repo.

- `base/` — Deployment, Service, Kustomization
- `app.yaml` — Argo CD Application pointing at `base/`

Image tag updates come from CI in the task-api repo.