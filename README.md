# cloud
Useful docker compose deployments I use for my cloud.

## Disable Docker iptables configuration
Edit `/etc/docker/daemon.json`:
```json
{
  "iptables": false
}
```

## Ports
- Proxy Manager
  - HTTP: 80
  - HTTPS: 443
  - Management: 81
- Authentik
  - HTTP: 9000
  - HTTPS: 9443
- Headscale
  - HTTP: 8010
  - Metrics: 8011
