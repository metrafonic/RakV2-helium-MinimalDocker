# Minimal Helium setup for RAK v2 / MNTD Miners

This is a barebones helium mining config for the Raspberry Pi based miners provided by RAK.

No bluetooth control etc. That can be done via the cli

## Installation
```
git clone https://github.com/metrafonic/RakV2-helium-MinimalDocker
```
Edit the region in `docker-compose.yml` to match yours

```
docker compose up -d
```
