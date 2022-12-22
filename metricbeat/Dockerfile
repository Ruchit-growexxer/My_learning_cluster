ARG STACK_VERSION

FROM docker.elastic.co/beats/metricbeat:8.1.1

COPY metricbeat.yml /usr/share/metricbeat/metricbeat.yml

USER root
RUN chown root /usr/share/metricbeat/metricbeat.yml
#RUN chmod go-w /usr/share/metricbeat/metricbeat.yml
