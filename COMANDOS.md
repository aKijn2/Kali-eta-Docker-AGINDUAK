# DOCKER COMANDOS

### PARA SABER EL NOMBRE DEL CONTENEDOR
`
docker ps
`

### PARA EJECUTAR ALGO DEL CONTENEDOR EN ESTE CASO
#### EJECUTAMOS EL BASH DEL CONTENEDOR.
`
docker exec -it [NOMBRE DLE CONTENEDOR] /bin/bash 
`

# KALI COMANDOS

### PARA MOSTRAR LOS DISPOSITIVOS QUE ESTAN EN UNA RED
`
apt install arp-scan
`

`
arp-scan -I eth0 --localnet
`

### DESCUBRIR VURNERABILIDADES EN PAGINAS WEB
`
whatweb [pagina]
`
### EJEMPLO WHAT WEB:
(root㉿efb46d340bc4)-[~/scan-output]

└─# whatweb https://miwifi.com

https://miwifi.com [200 OK] Country[UNITED STATES][US], Email[wf_miwifi@2x.png,wf_video01@2x.jpg,wf_video_mitu@2x.jpg,wf_video_trans@2x.jpg], Frame, HTML5, HTTPServer[Tengine], IP[18.185.134.188], JQuery[1.5.1], Script, Tengine-Web-Server, Title[MiWiFi – 小米路由器官网]

### 