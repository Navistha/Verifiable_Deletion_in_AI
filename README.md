# verifiable-deletion

Setup commands only. See docs/run-guide.md for the full guide and docs/architecture/ for diagrams.

## One-time setup

```bash
git clone <repo-url> verifiable-deletion && cd verifiable-deletion
cp infra/.env.example .env            # set your id, project name and port block
```

## Start local services (use your own role id: java1, java2, ml1, ml2, ml3)

```bash
docker compose -p <id> -f infra/base.yml up -d                       # shared services
docker compose -p <id> -f infra/base.yml --profile <id> up -d        # plus your own services
```

## Java (java1, java2)

```bash
cd platform && mvn -q verify
```

## Python (ml1, ml2, ml3): one environment per folder

```bash
cd ml/<folder>
python3.11 -m venv .venv && source .venv/bin/activate
pip install -e .[dev] && pytest
```
