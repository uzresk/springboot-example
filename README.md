# springboot-example

This is a sample of SpringBoot.

http://qiita.com/uzresk/items/31a4585f7828c4a9334f

---

## Description

* Account of registration , login , and offers a search function using itunes search API.

---

## Requires

* Java8
* PostgreSQL8.5 later

---

## Usage

### DataBaseSettings

* change application.yml
* apply specify the DDL（account.sql)

### Packaging

`mvn clean package`

### To Start Springboot Example Application

` ${JAVA_HOME}/bin/java -Dlogging.config=logback.xml -jar sbex-0.0.1-SNAPSHOT.jar &`

### Open Browser

`http://localhost:8080/app/`

