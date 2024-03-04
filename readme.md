# Quick and easy nextcloud on tailscale

## TL;DR

1. Here is what you need to have:

- tailscale account (free is fine)
- a domain that uses cloudflare as a nameserver
- a PC to run docker compose on.

2. Here is what you need to configure:

Copy the `env.example` to `.env`, and fill in the enviroment variables.

3. Profit

`docker compose -f nextcloud.yaml up -d`


## Longer description
TODO