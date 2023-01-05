# Monitoring-with-Prometheus
Monitoring with Prometheus to monitor sample servers simulated with node exporter and a Python Flask application.
In this repo is prepared for become familiar with using Prometheus to monitor sample servers simulated with node exporter. You will use Prometheus to monitor the target node_exporter application that is configured by scraping metrics endpoints of the node_exporter and learning how to instrument a Python Flask application to emit metrics and deploy that application so that Prometheus can monitor it.
# Objectives
Configure the targets for Prometheus to monitor
Create queries to get the metrics about the target
Determine the status of the targets
Identify information about the targets and visualize it with graphs
Instrument a Python Flask application to be monitored by Prometheus
# Prerequisites
In this sample we use Docker to run both Prometheus, and special Node Exporters, which will behave like servers that you can monitor. As a prerequisite, you will pull down the bitnami/prometheus:latest image and the bitnami/node-exporter image from Docker Hub. You will use these images to run Prometheus and create three instances of node exporters to be monitored.
