Apache Traffic Server for Docker
----------------------------------------
[reyesruiz/docker_traffic_server][1]

[Apache Trafic Server][0]

#### Build
 - Centos: 7
 - TrafficServer: Latest from epel-release

### Usage

 - Run
 `docker run -d --privileged --name traffic_server -p 8080:8080 reyesruiz/docker_traffic_server`
 `docker exec -i -t traffic_server /bin/bash`

### Configuration
 This build has standard configuration directories located under /etc/trafficserver

[0]: http://trafficserver.apache.org/
[1]: https://hub.docker.com/r/reyesruiz/docker_traffic_server/
