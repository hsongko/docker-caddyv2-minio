Starts 4 docker containers running minio server instances (cluster),
using Caddy v2 reverse proxy, load balancing, 

Caddy acces log path: caddy_log/access.log


For single/standalone minio instance, check "single" folder.



source:

MinIO
https://docs.min.io/docs/deploy-minio-on-docker-compose.html

Caddy v2:
https://caddyserver.com/docs/caddyfile/directives/reverse_proxy


this docs doesn't work in Caddy v2:
https://docs.min.io/docs/setup-caddy-proxy-with-minio.html
