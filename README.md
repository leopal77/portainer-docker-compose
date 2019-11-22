## Portainer

A simple `docker-compose` file used to start [Portainer service](https://www.portainer.io/).

### Volume
Mounts host's `/var/run/docker.sock` to container's same path.

### Ports
Binded ports(HOST:CONTAINER):
- 8000:8000
- 9000:9000

### Start/Stop instructions

#### Start
`docker-compose up -d`

Then application would be available at `http://localhost:9000`

#### Stop
`docker-compose down`
