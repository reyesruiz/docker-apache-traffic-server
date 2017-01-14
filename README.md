Apache Traffic Server for Docker
----------------------------------------
[reyesruiz/docker_traffic_server][1]

[Apache Trafic Server][0]

#### Build
 - Centos: 7
 - Apache Traffic Server: Latest Release 7.0.0

### Usage

 - Run
 `docker run -d --name traffic_server -p 8080:8080 reyesruiz/docker_traffic_server:7.0.x`
 `docker exec -i -t traffic_server /bin/bash`

### Configuration
 This build has standard configuration directories located under /opt/ts

[0]: http://trafficserver.apache.org/
[1]: https://hub.docker.com/r/reyesruiz/docker-apache-traffic-server/
