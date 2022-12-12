   * Public URL's: forward to an external host running Kubernetes/Ingress https://github.com/rogeriomm/labtools-k8s
      * https://world-zeppelin.duckdns.org
      * https://world-jupyter.duckdns.org/jupyter

   * Public URL's: forward to a local Docker container
      * https://world-dashboard.duckdns.org/whoami
      
   * TODO
      * mTLS + Traefik to improve security
         * https://doc.traefik.io/traefik/routing/services/#certificates
         * https://en.wikipedia.org/wiki/Mutual_authentication
      * Upgrade from Raspberry PI 4 to [Orange Pi 5](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-5.html)
         * ARM V7->V8 64 bits

![alt text](docs/traefik-http-routers.png "Traefik HTTP Services screenshot")
