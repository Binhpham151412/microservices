## Microservices
Eureka-server, Config-server, Api-gateway, Load Balance, Multi-services

## Main functions
- .....
- .....
- .....

## System requirements
- Docker version >= 27.3.1
- java version >= 21

## Installation
- Clone repository:
```bash
   git clone https://github.com/Binhpham151412/microservices
```
- Setting JDK, maven
- Move to folder user-module/api
```bash
    cd eureka-server
    ./gradlew clean
    ./gradlew build
```
- Run all module
```bash
    docker-compose up --build (đang lỗi chưa fix được -> run local từng module (eureka-server, config-server, api-gateway,...))
```
- Run only module
```bash
    docker-compose up --build user-module
```
