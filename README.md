# Seafile

A self-hosted seafile application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/seafile/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/seafile" ~/.local/srv/docker/seafile
cd ~/.local/srv/docker/seafile
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install seafile
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
