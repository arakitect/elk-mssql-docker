ARG ELK_VERSION
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

RUN rm -rf /usr/share/logstash/pipeline
COPY pipeline /usr/share/logstash/pipeline
COPY mssql-jdbc-8.2.2.jre11.jar /usr/share/logstash/mssql-jdbc-8.2.2.jre11.jar