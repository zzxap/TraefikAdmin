

# TraefikUI
1.Download  the traefik in https://github.com/containous/traefik/releases

  tar zxvf traefik_v2.2.0_linux_amd64.tar.gz 
  
  chmod 771 traefik
 2.Install ETCD and set ETCD's IP in  config.ini
 
3.run traefik with  ./traefik --configFile=traefik.toml

  traefik link to etcd in traefik.etcd.toml entrypoint
  
  then check http://127.0.0.1:8090/dashboard/#/ open traefik's dashboard 
  port 8090 is set in traefik.toml
  
  if open success ,countinue
  
4. chmod 771 TraefikAdmin     run  ./TraefikAdmin   

 TraefikAdmin will read the config in config.ini
 
 set the etcd_server int config.ini the same in traefik.toml
 
5. then open url http://ip:port/web/

  the port is set in config.ini http_port default is 8093  url must end with /web/

   you can manage the service route in this webpage.
 

TraefikAdmin，

A web page manage Traefik KV ETCD ，

manage entrypoint route service middleware


![ui](https://github.com/zzxap/TraefikUI/blob/master/images/8.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/9.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/1.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/2.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/3.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/4.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/5.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/6.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/7.PNG?raw=true)

![ui](https://github.com/zzxap/TraefikUI/blob/master/images/wechat.jpg?raw=true)



