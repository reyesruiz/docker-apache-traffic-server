Apache Traffic Server for Docker
----------------------------------------
[reyesruiz/docker-apache-traffic-server][1]

[Apache Trafic Server][0]

#### Build
 - Centos: 7
 - Apache Traffic Server: Latest Release  4.2.3, 5.3.2, 6.2.3, 7.0.0


### Tags
 - latest	(7.0.0)
 - 4.2.x	(4.2.3)
 - 5.3.x	(5.3.2)
 - 6.2.x	(6.2.0)
 - 7.0.x	(7.0.0)

### Usage

 - For latest release run:
 `docker run -d --name traffic_server -p 8080:8080 reyesruiz/docker-apache-traffic-server`
 `docker exec -i -t traffic_server /bin/bash`

 - For previous versions from add tag:
 `docker run -d --name traffic_server -p 8080:8080 reyesruiz/docker-apache-traffic-server:6.2.x`
 `docker exec -i -t traffic_server /bin/bash`

### Configuration
 This build has standard configuration directories located under /opt/ts

[0]: http://trafficserver.apache.org/
[1]: https://hub.docker.com/r/reyesruiz/docker-apache-traffic-server/
