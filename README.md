# vimvie
Microservices project including Spring Config Server + Zuul + Consul+ Oauth2 + Zipkin + Sleuth on Gradle

## Consul
docker run     -d     -p 8500:8500     -p 8600:8600/udp     --name=badger     consul agent -server -ui -node=server-1 -bootstrap-expect=1 -client=0.0.0.0 -bind=0.0.0.0

## Zipkin
docker run -d -p 9411:9411 openzipkin/zipkin

## Start Services
Launch Spring Boot services with JVM ARGUMENT -DCONFIG_SERVICE_PASSWORD=user

## Launch URL
Launch URL: http://gatewayhost:4000/
