# Webserver
Setting up a Webserver using Hetzner as a hosting provider.

## Instruction

1. Create webserver
 - Use cloud-config.yml and set <strong>username</strong> and <strong>ssh key</strong>

2. Clone this repository on the server

3. Set environment variables in `.env` file

4. Generate .htpasswd file: `htpasswd -c $ABSOLUTE_PATH/data/traefik/.htpasswd $TRAEFIK_USERNAME`

5. Start all docker container
