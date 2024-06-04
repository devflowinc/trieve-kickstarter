# Quick Trieve Starter template

This is a quick starter template for Trieve. It is a simple example of how to use Trieve to create a fast search demo with local development.

## Getting Started

1. Clone this repository
```
git clone https://github.com/devflowinc/quick-start.git
```

Start the server
```
docker compose up -d
```

The following things have been created:
| Service           | Description      |
|-------------------|------------------|
| qdrant-database   | Database hosted @ localhost:6333             |
| search            | Search UI hosted @ localhost:5174            |
| s3                | S3 compatible minio hosted @ localhost:9000 |
| keycloak-db       | Keycloak database hosted @ localhost:5434    |
| dashboard         | Trieve Dashboard hosted @ localhost:5173     |
| db                | Postgres database hosted @ localhost:5432   |
| redis             | Redis hosted @ localhost:6379               |
| chat              | Chat hosted @ localhost:5175                |
| tika              | Tika hosted @ localhost:9998                |
| s3-client         | Client to bootstrap s3 with ACCESS/SECRET key | 
| keycloak          | Keycloak hosted @ localhost:8080             |
| ingestion-worker  | Worker to ingest data into qdrant and postgres|
| server            | Server hosted @ localhost:8090               |
| file-worker       | Worker to ingest files into s3 and perform OCR w/TIKA |
