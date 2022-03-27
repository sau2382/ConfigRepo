# ConfigRepo
Repository to centrally maintain all the microservice configurations

Example shows repository with separate subdirectories for two microservices. 
1. microservice1  ->  config for app name : demo-service
2. microservice2  -> config for app name : someother-service

URLS and corresponding results fron the config server :
1.  http://localhost:8888/demo-service/prod  -> microservice1/demo-service-prod.yml
2.  http://localhost:8888/demo-service/dev  -> microservice1/demo-service-dev.yml
3.  http://localhost:8888/someother-service/dev  -> microservice2/someother-service-dev.yml
