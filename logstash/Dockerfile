FROM docker.elastic.co/logstash/logstash-oss:7.9.2
RUN logstash-plugin install logstash-input-beats
USER root
RUN mkdir -p /home/logstash/logfile
RUN chown -R logstash:logstash /home/logstash/logfile/
