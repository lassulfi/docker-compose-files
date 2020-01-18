# Docker-Compose Files

Docker-compose files that I use for developments (examples: databases, apps..).

### Prerequisites

In order to use build and run these files both docker and docker-compose are required.

To install docker plase visit https://docs.docker.com/install/.

To install docker-compose please visit https://docs.docker.com/compose/install/

### Building and running an image

To build and run an image download the yaml file and run the following command:

```
docker-compose docker-filename.yml run -d --build
```