FROM logstash:7.14.1

# add custom config
COPY clickstream.conf /etc/logstash/conf.d/clickstream.conf

# add csv file
COPY weblog.csv /etc/logstash/data/weblog.csv

# add templates
COPY ./templates/ /config-dir/templates/