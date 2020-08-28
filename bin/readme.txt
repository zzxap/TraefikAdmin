# TraefikUI
1.Download  the traefik in https://github.com/containous/traefik/releases

  tar zxvf traefik_v2.2.0_linux_amd64.tar.gz 
  
  chmod 771 traefik
 2.Install ETCD and set ETCD's IP in  config.ini
 
3.run traefik with  ./traefik --configFile=traefik.etcd.toml

  traefik link to etcd in traefik.etcd.toml entrypoint
  
4. chmod 771 TraefikAdmin     run  ./TraefikAdmin   

 TraefikAdmin will read the config in config.ini
 
 set the etcd_server int config.ini the same in traefik.etcd.toml
 
5. then open url http://ip:port/web/

   you can manage the service route in this webpage.
 

TraefikAdmin，

A web page manage Traefik KV ETCD ，

manage entrypoint route service middleware
