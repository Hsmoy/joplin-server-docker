# joplin-server-docker
Docker quickly builds joplin server

```
git clone https://github.com/Hsmoy/joplin-server
cd  joplin-server
docker-compose up -d 

http://localhost:9090
default accout:
username: admin@localhost
password: admin
```

You can modify the database account configuration, but this has no effect. Docker does not map the access port. By default, it accesses localhost:9090 or the 9090 port of the current ip. If you want to change the access port, you can modify the ngnix access port.


It takes time for the joplin server to run. If the access shows 502, please wait a few minutes and re-access

