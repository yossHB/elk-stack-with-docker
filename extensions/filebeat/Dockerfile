ARG ELASTIC_VERSION

FROM docker.elastic.co/beats/filebeat:${ELASTIC_VERSION}

COPY --chown=root:filebeat extensions/filebeat.yml /usr/share/filebeat/filebeat.yml
