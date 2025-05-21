# SqlPractice

## Build Docker

```bash
docker compose up -d
```

## Download Data

```bash
 uv run huggingface-cli download lyk/ArxivEmbedding --repo-type dataset --local-dir ./data
 ```