chmod 771 TraefikAdmin
# TraefikUI
Download the traefik in https://github.com/containous/traefik/releases 

1.run traefik with  ./traefik --configFile=traefik.etcd.toml
  traefik link to etcd in traefik.etcd.toml entrypoint
  
2. run ./TraefikAdmin  
 TraefikAdmin will read the config in config.ini
 set the etcd_server int config.ini the same in traefik.etcd.toml
 
 3. then open url http://ip:port/web/
   you can manage the service route in this webpage.
