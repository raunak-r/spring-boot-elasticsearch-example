# spring-boot-elasticsearch-example

How to start SpringBoot ElasticSearch using Spring Data

## Setup

Development OS - Windows

### Java

```
- Configure path variable JAVA_HOME in properties.
    - https://mkyong.com/java/how-to-set-java_home-on-windows-10/
- Install intellij IDEA community free version
```

### Elastic Search

```
# ELK

# Readme - https://www.tutorialspoint.com/elasticsearch/index.htm
# Setup - https://www.tutorialspoint.com/elasticsearch/elasticsearch_installation.htm
Link - https://www.elastic.co/downloads/elasticsearch

# Run
> cd elasticsearch-2.1.0/bin
> elasticsearch

- You can check if the server is up and running by browsing http://localhost:9200
```

### Kibana

```
- Download and Unzip like ES - https://www.elastic.co/downloads/kibana
CD c:\kibana-7.0.0-windows-x86_64
.\bin\kibana.bat
```

```
Open Project in IDEA.
8080 is the port number for Spring.
```

## Notes

```
The web URL you can open is localhost:9200, 
but the node's port is 9300, 
so none of the configured nodes are available if you use the 9200 as the port.
```
