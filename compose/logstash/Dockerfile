FROM docker.elastic.co/logstash/logstash:7.5.1

#安装input插件
RUN logstash-plugin install logstash-input-jdbc

#安装output插件
RUN logstash-plugin install logstash-output-elasticsearch