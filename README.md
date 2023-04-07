   * Public URL's: forward to an external host running Kubernetes/Ingress https://github.com/rogeriomm/labtools-k8s
      * https://world-zeppelin.duckdns.org
      * https://world-jupyter.duckdns.org/jupyter

   * Public URL's: forward to a local Docker container
      * https://world-dashboard.duckdns.org/whoami
         * https://github.com/traefik/whoami
      * https://world-dashboard.duckdns.org/traefik
      * https://world-pihole.duckdns.org
         * [Docker container management yacht](https://yacht.sh)
         * ![alt text](docs/yacht-dashboard.png "YACHT dashboard")
      * https://world-dashboard.duckdns.org/pihole/admin/
         * https://pi-hole.net/
      
   * TODO
      * mTLS + Traefik to improve security
         * [Traefik services TLS autentication](https://doc.traefik.io/traefik/routing/services/#certificates)
         * [TLS mutual authentication](https://en.wikipedia.org/wiki/Mutual_authentication#mTLS)

![alt text](docs/traefik-http-routers.png "Traefik HTTP Services screenshot")
