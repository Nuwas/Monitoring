# Monitoring


Order of installation.

1. Create a kubernetes namespace  monitoring
2. Prometheus
3. Grafana
4. kube-state-metrics
5. node-exporter
6. Add 'micrometer-registry-prometheus' maven dependency to pom for jvm stats.

Once done import the respective grafana dashboards in the below sequence.

Node Exporter --> 1860
Java service dashboard --> https://medium.com/simform-engineering/revolutionize-monitoring-empowering-spring-boot-applications-with-prometheus-and-grafana-e99c5c7248cf
Kubernetes apiserver--> 12006 --> https://grafana.com/grafana/dashboards/12006-kubernetes-apiserver/




