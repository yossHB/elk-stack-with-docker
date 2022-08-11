ARG ELASTIC_VERSION

FROM docker.elastic.co/beats/metricbeat:${ELASTIC_VERSION}

COPY --chown=root:metricbeat extensions/metricbeat.yml /usr/share/metricbeat/metricbeat.yml
