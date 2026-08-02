- sudo nmap $IP -sCV -vv -p- --min-rate=300
- nmap -sV -sC -p 443,8090 <host>
- curl -i http://<host>:8090

- X-Powered-By: Express
- fix : app.disable("x-powered-by");

- curl -X OPTIONS -i http://<host>:8090
- Access-Control-Allow-Methods: GET,HEAD,PUT,PATCH,POST,DELETE

- Disable Yarn repo
- sudo mv /etc/apt/sources.list.d/yarn.list /etc/apt/sources.list.d/yarn.list.disabled

- cat /etc/os-release
