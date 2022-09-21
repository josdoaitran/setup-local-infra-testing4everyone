# setup-local-infra-testing4everyone
Local-Infra-Tutorial-Testing4Everyone

- Install docker

- Run this command to install and setup `Kafka, Mysql and Phpmyadmin`
```
docker compose -f local-infra-mysql-kafka.yml up -d
```

- Run this command to install and setup `Mysql and Phpmyadmin`
```
docker compose -f local-infra-mysql.yml up -d
```