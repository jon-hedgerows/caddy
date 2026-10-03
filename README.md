# caddy-cloudflare

Caddy, with the cloudflare DNS plugin.

image: `ghcr.io/jon-hedgerows/caddy-cloudflare:latest`

See also [https://caddyserver.com/docs/install#docker](https://caddyserver.com/docs/install#docker)

There's an example compose file in `example/compose.yaml`

To add additional caddy variants, just create Dockerfile.variant, and edit it to pull in the required plugins.

The build workflow creates a separate image for each Dockerfile, named {repo}-{Dockerfile extension}.
