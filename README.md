# Wireguard docker compose

just `docker-compose up -d`

but dont forget to fix `- PEERS=10` from 10 to your value.

After running server just use client for phones or copy configs from `config/peer{0-N}` to your machine to `/etc/wireguard/wg0.conf` and then run `sudo wg-quick up wg0`
