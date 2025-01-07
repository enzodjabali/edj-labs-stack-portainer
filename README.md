# Stack Portainer
> This stack uses Traefik.


1. Change the values of `traefik.http.routers.portainer.rule` and `traefik.http.routers.portainer-http.rule` in docker-compose.yml
<br>
2. Deploy the stack using Docker Swarm:
```
docker stack deploy -c docker-compose.yml portainer
```

Access Portainer at: https://portainer.your-domain.com
