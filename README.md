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


Prometheus
![prometheus-screenshot](https://github.com/Nuwas/Monitoring/assets/32307939/70bed845-68a9-4c68-a6c1-da5db111db2b)

Grafana
![springboot-screenshot](https://github.com/Nuwas/Monitoring/assets/32307939/74558fdd-96a8-4d71-82b8-ef04052fd37c)


![node_exporter_screenshot](https://github.com/Nuwas/Monitoring/assets/32307939/378debe6-f04e-43bd-a60b-c9321ebd4746)


![deployment_and_others_screenshot](https://github.com/Nuwas/Monitoring/assets/32307939/5a62709c-9558-4b2e-aebb-0a3ba00bb420)


