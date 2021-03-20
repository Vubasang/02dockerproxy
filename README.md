## Ссылка:
https://hub.docker.com/repository/docker/sangvuba/myproxy-vu
##
## Команды строки:
```
docker build -t myproxy-vu .
```
```
docker login -u sangvuba
```
```
docker tag myproxy-vu sangvuba/myproxy-vu
```
```
docker push sangvuba/myproxy-vu
```
```
docker run -dt -p 9000:8000 sangvuba/myproxy-vu
```
