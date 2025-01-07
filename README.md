# Stack Portainer
Note: <i>This stack uses Traefik.</i>

1. Change the values of `traefik.http.routers.portainer.rule` and `traefik.http.routers.portainer-http.rule` in docker-compose.yml


2. Deploy the stack using Docker Swarm:

```
docker stack deploy -c docker-compose.yml portainer
```

Access Portainer at: https://portainer.your-domain.com
