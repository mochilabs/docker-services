<h1 align="center">
Docker Services (docker-compose, docker-swarm)
</h1>

Want to use your bot rather than host it? [Invite to your guild!](https://discordapp.com/api/oauth2/authorize?client_id=426722888293548032&permissions=277062404416&scope=bot+applications.commands)

```
docker swarm networks

traefik-reverse-proxy
  - portainer (9000 -> 443) [portainer.example.com]
      - portainer_agents_network
  - traefik dashboard (80 -> 443) [traefik.example.com]
  
portainer_agents_network
  - portainer-agent (9001) <-> poratainer
```
