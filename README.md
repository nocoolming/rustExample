#简介：
##部署由三个容器组成：
scrm
nginx-scrm
supervisor

依赖：
- mongodb
- mysql
- redis

启动顺序：1. scrm 2. nginx-scrm 3. supervisor

- scrm :
```sh
 ./run.sh
```
- 这个服务有pv的依赖

- nignx-scrm:
```sh
 ./run.sh
```
- supervisor:
```
 ./run.sh
```