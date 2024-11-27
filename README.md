# springboot_observability

Test resources replicating the example for spring boot observability defined in: 

https://github.com/marcingrzejszczak/observability-boot-blog-post/

- Loki version: 3.2.1
- Prometheus version: 2.55.1
  - Prometheus execution parameters: --config.file=/etc/prometheus/prometheus.yml --storage.tsdb.path=/etc/prometheus/data --enable-feature=exemplar-storage --enable-feature=otlp-write-receiver --web.enable-remote-write-receiver
- Tempo version: 2.6.1
- OS: Debian 12
