# Rocket.Chat with Let's Encrypt in a Docker Swarm

Configure Traefik before applying the configuration.

Traefik configuration: https://github.com/heyValdemar/traefik-letsencrypt-docker-swarm

Deploy Rocket.Chat in a Docker Swarm using the command:

`docker stack deploy -c rocketchat-traefik-letsencrypt-docker-swarm.yml rocketchat`
