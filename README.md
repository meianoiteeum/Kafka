# Formação Alura - Kafka

## Install Kafka on Windows
### Site
- Site: [Kafka](https://kafka.apache.org)
- Binary downloads: [Scala *"lastest_version"*](https://kafka.apache.org/downloads)

### Run Zookeeper
- walk to directory Kafka in C:\
- execute command line
```bash
  bin\windows\zookeeper-server-start.bat config\zookeeper.properties
```

### Run Kafka
- in directory Kafka
- execute command line
```bash
  bin\windows\kafka-server-start.bat config\server.properties
```

### Install Zookeeper outside Kafka download for Windows
- Review link: [DZone](https://dzone.com/articles/running-apache-kafka-on-windows-os)

## Install Kafka on Linux
### Run Zookeeper
- walk to directory Kafka
- execute command line
```bash
  bin/zookeeper-server-start.sh config/zookeeper.properties
```

### Run Kafka
- in directory Kafka
- execute command line
```bash
  bin/kafka-server-start.sh config/server.properties
```