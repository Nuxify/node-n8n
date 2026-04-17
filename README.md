# N8N Base

Self hosted n8n server using docker compose and traefik.

## Traefik Documentation

This template uses Traefik (<https://traefik.io/>), an edge router and reverse proxy written in Go.

To start, make sure to configure your Traefik instance or remove some Traefik-related configs in your docker compose file.

When using Traefik, you can easily deploy using <https://github.com/Nuxify/traefik-setup>.

## N8N Documentation

Refer to official N8N site: <https://docs.n8n.io/>

1. Clone <https://github.com/Nuxify/node-n8n>

2. Create .env file from .env.example

3. Up the n8n container

    ```bash
    make up
    ```

4. Access the n8n editor at - TODO

5. Create owner account

6. Create workflows

Made with ❤️ at [Nuxify](https://nuxify.tech)
