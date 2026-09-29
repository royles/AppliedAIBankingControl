# Agent and developer instructions — AppliedAIBankingControl

All work on the **Banking Control Solution** happens on **`main`**.

## Before editing

```bash
git fetch origin
git checkout main
git pull origin main
git branch --show-current   # must print main
```

Optional guard (recommended after clone):

```bash
git config core.hooksPath .githooks
```

## Commit and push

```bash
git add -A
git commit -m "Describe the change"
git push origin main
```

## Paths owned by this project

- `banking_control/`
- `4_application/`
- `1_session-install-dependencies/`
- `2_job-init-database/`
- `frontend/dist/`
- `data/schema.sql`
- `scripts/init_db.py`
- `.project-metadata.yaml`, `amp-catalog.yaml`, `docs/CAI_APPLICATION.md`
