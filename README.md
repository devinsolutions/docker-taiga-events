# Taiga Events Docker Image

Taiga-events on the official Node image (Alpine variant).

## Image discontinued

**This image is discontinued and will not receive any further updates at all.**
If the image becomes inactive on Docker Hub, it will be removed as per Docker
Hub [image retention policy](
https://www.docker.com/pricing/resource-consumption-updates).

There is now the official fork maintained by Taiga developers themselves and
can be used as a drop-in replacement. You can find the sources on
[their GitHub](https://github.com/taigaio/docker-taiga-events-5) and the image
on [their Docker Hub](https://hub.docker.com/r/taigaio/taiga-events5).

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
