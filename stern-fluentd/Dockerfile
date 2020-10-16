FROM fluentd:latest

USER root
RUN cd /usr/bin && wget https://github.com/wercker/stern/releases/download/1.11.0/stern_linux_amd64 && chmod 755 stern_linux_amd64
RUN fluent-gem install fluent-plugin-elasticsearch

USER fluent


