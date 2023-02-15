# Kong API Gateway with ELK

This project demonstrates running the API Gateway [Kong](https://konghq.com/kong/) with [Konga](https://github.com/pantsel/konga) for the Kong GUI and the ELK: [Elasticsearch](https://www.elastic.co/pt/elasticsearch/), [logstash](https://www.elastic.co/pt/logstash) and [kibana](https://www.elastic.co/pt/kibana).

---

#### Prerequisites

To make use of this project the only prerequisites are to have the [docker](https://docs.docker.com/get-docker/) and [docker-compose](https://docs.docker.com/compose/install/) installed.

#### First Steps

To do this, simply run the following command on your terminal:

`$ docker-compose up -d`

![Docker compose up](docker-compose-up.png?raw=true "Docker compose up")

#### Checking if everything is fine

After performing the previous step you should check that all containers are in UP status. To do this, use the following command on your terminal:

`$ docker-compose ps`

---

### Accessing Kong through the Konga GUI

**Kong**: The worlds most popular open source API gateway. Built for multi-cloud and hybrid, optimized for microservices and distributed architectures.

**Konga**: Konga is a fully featured open source, multi-user GUI, that makes the hard task of managing multiple Kong installations a breeze.

To access the Konga interface open your browser and type in the address bar http://localhost:1337
