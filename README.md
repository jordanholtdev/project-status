# Project Status

### Dev

1. Create a `env` file with the following enviornment variables:

```
AWS_ACCESS_KEY=
AWS_SECRET_KEY=
AWS_REGION=
AWS_PROFILES=
GITHUB_TOKEN=
```

2. Create local volume to persist Grafana data

```
docker volume create --name=grafana-data
```

3. Build container with `docker-compose`

```
docker-compose up
```
