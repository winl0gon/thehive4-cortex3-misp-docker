The default setting do not recommanded on product environment.
If you want use this template on product enviroment, Please modify configuration refer to below links.
 - https://github.com/TheHive-Project/Docker-Templates
 - https://github.com/MISP/misp-docker
---
You can run below command on local.
```
$ docker compose up
```



| Service   |      Address      |  User |  Password |
|----------|:-------------:|:------:|------:|
| The Hive |  http://localhost:9000 | admin@thehive.local | secret
| Cortex |    http://localhost:9001  |    |
| Elasticsearch | http://localhost:9200 |     |
| Kibana |  http://localhost:5601 |  |
| MISP |    https://localhost:443   |  admin@admin.test | admin
| Shuffle | http://localhost:3001 |    |
