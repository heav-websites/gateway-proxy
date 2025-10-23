FROM prom/prometheus:v3.7.2

COPY . /etc/prometheus/

CMD [ "--storage.tsdb.path=/prometheus", "--config.file=/etc/prometheus/prometheus.yml" ]
