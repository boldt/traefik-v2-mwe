# README

MWE for the bug report https://github.com/containous/traefik/issues/5729

## Clone

```bash
git clone git@github.com:boldt/traefik-v2-mwe.git
cd traefik-v2-mwe/
```

## Start

```bash
docker-compose up -d
```

# Test

```bash
curl -H Host:whoami.docker.localhost http://127.0.0.1
curl --insecure -H Host:whoami.docker.localhost https://127.0.0.1
```