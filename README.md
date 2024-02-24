# Rocket.Chat with Let's Encrypt Using Docker Compose



❗ Change variables in the `.env` to meet your requirements.

💡 Note that the `.env` file should be in the same directory as `rocketchat-traefik-letsencrypt-docker-compose.yml`.

Create networks for your services before deploying the configuration using the commands:

`docker network create traefik-network`

`docker network create rocketchat-network`

Deploy Rocket.Chat using Docker Compose:

`docker compose -f rocketchat-traefik-letsencrypt-docker-compose.yml -p rocketchat up -d`

