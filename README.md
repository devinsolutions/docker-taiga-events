# Taiga Events Docker Image

Taiga-events on the official Node image (Alpine variant).

## Deployment

See [Taiga: Setup production environment](
https://taigaio.github.io/taiga-doc/dist/setup-production.html) and
[docker-compose.advanced.yml](
https://github.com/devinsolutions/docker-taiga/blob/master/docker-compose.advanced.yml)
to find out more about the deployment procedures.

### Configuration

`/etc/opt/taiga-events/config.json` is used by default as the configuration
file. See [config.example.json](
https://github.com/taigaio/taiga-events/blob/master/config.example.json).

### Logs

Stdout and stderr are copied to `/var/log/taiga-events.log`.