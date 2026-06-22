# Documentation source

Everything in this folder is the **documentation source** forwarded to the locked Redocly
GitHub repo on each push to `master`. The contents of this folder become the **root** of that
repo, so place your Redocly project / OpenAPI here (e.g. `openapi.yaml`, `redocly.yaml`,
guides, etc.).

Do not commit anything outside this folder expecting it to reach Redocly — only `docs/` is
forwarded. See [../README.md](../README.md).
