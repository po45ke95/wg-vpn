# WireGuard http version docker compose
---
### Please follow steps can build WireGuard VPN in docker compose

1. Please change `WG_HOST` and `PASSWORD` in first time.

2. `WG_DEFAULT_DN` default value is `1.1.1.1` , this is optional value.

3. Used `docker compose up -d` can run WireGuard in server.

4. Open in browser http://VM_IP_ADDR:51821 in this docker compose file.

Refernce by: https://github.com/wg-easy/wg-easy