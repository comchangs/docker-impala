# **docker-impala**
___

### Description
___

This image runs [*Cloudera Impala*](https://www.cloudera.com/products/open-source/apache-hadoop/impala.html) distribution on HDFS.

You can pull it with:

    docker pull comchangs/impala


You can also find other images based on different Apache Impala releases, using a different tag in the following form:

    docker pull comchangs/impala:[impala-release]-[cdh-release]


Stop with Docker Compose:

    docker-compose -p parrot

Setting the project name to *parrot* with the **-p** option is useful to share the network created with the containers coming from other Parrot docker-compose.yml configurations.

Once started you'll be able to access to the following UIs:

| **Impala Web UIs**           |**URL**                    |
|:----------------------------|:--------------------------|
| *Impala State Store Server* | http://localhost:25010    |
| *Impala Catalog Server*     | http://localhost:25020    |
| *Impala Server Daemon*      | http://localhost:25000    |

### Available tags:

- Apache Impala 3.0.0-cdh6.0.0 ([latest](https://github.com/comchangs/docker-impala/blob/latest/Dockerfile), [3.0.0-cdh6.0.0](https://github.com/comchangs/docker-impala/blob/3.0.0-cdh6.0.0/Dockerfile))
- Apache Impala 2.8.0-cdh5.15.1 ([2.12.0-cdh5.15.1](https://github.com/comchangs/docker-impala/blob/2.12.0-cdh5.15.1/Dockerfile))
- Apache Impala 2.8.0-cdh5.11.1 ([2.8.0-cdh5.11.1](https://github.com/comchangs/docker-impala/blob/2.8.0-cdh5.11.1/Dockerfile))
