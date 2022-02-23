# docker-Tomcat_and_MySQL
  * Launch Tomcat and MySQL.
  * Dockerのテスト。
  * webapps/warファイルを差し替えるだけ。

## How to Use
```
docker-compose up -d
```

```
docker exec -it docker-mysql-1 bash -p
docker exec -it tomcat bash -p
```