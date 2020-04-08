# TraefikUI
1.Download  the traefik in https://github.com/containous/traefik/releases

2.run traefik with  ./traefik --configFile=traefik.etcd.toml
  traefik link to etcd in traefik.etcd.toml entrypoint
  
3. run ./TraefikAdmin  
 TraefikAdmin will read the config in config.ini
 set the etcd_server int config.ini the same in traefik.etcd.toml
 
4. then open url http://ip:port/web/
   you can manage the service route in this webpage.
 

TraefikAdmin，
A web page manage Traefik KV ETCD ，
manage entrypoint route service middleware

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/8.PNG)
![ui](https://github.com/zzxap/TraefikUI/blob/master/images/1.PNG)
![ui](https://github.com/zzxap/TraefikUI/blob/master/images/2.PNG)
![ui](https://github.com/zzxap/TraefikUI/blob/master/images/3.PNG)
![ui](https://github.com/zzxap/TraefikUI/blob/master/images/4.PNG)
![ui](https://github.com/zzxap/TraefikUI/blob/master/images/5.PNG)
![ui](https://github.com/zzxap/TraefikUI/blob/master/images/6.PNG)
![ui](https://github.com/zzxap/TraefikUI/blob/master/images/7.PNG)





