# Лаборатоная №7
Apache jUDDI необходимо установить **самостоятельно**!

Для проверки работоспособности работы лабораторной необходимо:

```bash
    mvn clean package #для сборки проекта
    docker-compose up --build standalone 
    java -jar client/target/client-1.0-jar-with-dependencies.jar
```
