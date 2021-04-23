# keycloak-nginx-lets-encrypt

Docker configuration for Nginx Reverse Proxy with Let's Encrypt auto renew support.

Easily setup to proxy for a standalone http server (e.g. [Keycloak](http://www.keycloak.org), Wordpress, or Backend API).

## Overview
```code
keycloak-nignx-lets-encrypt        keycloak
           |                    (or HTTP server)
           |                           |
           V                           V
   HTTP   ___                         ___
 -- 80  -|   |                 HTTP  |   |
         |   | --------------> 8080 -|   |
 -- 443 -|___|                       |___|
   HTTPS 
```

## License

MIT License.
