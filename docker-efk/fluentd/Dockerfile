FROM fluent/fluentd
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri"]
# RUN rm -f fluent-bit/bin/fluent-bit.conf

#docker run -t -i -d --privileged --network=docker-efk_default -v /var/lib/docker/containers:/var/lib/docker/containers f117e38a63c0 /fluent-bit/bin/fluent-bit  -v -i tail -p 'path=/var/lib/docker/containers/*/*.log' \ -o es://elasticsearch:9200/container/containermetrics -m '*'\ -o stdout -m '*'



