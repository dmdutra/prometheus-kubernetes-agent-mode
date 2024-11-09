## Helm Chat for Prometheus

Prometheus is an open-source systems monitoring and alerting toolkit.

## Introduction

This chart bootstraps a Prometheus deployment running in agent mode.

## Prerequisites

* Kubernetes 1.23+
* Helm 3.15+

## Installing the chart

```sh
# Clone the repository

git clone https://github.com/dmdutra/prometheus-kubernetes-agent-mode.git

# Installing helm chart

helm install prometheus-agent --set prometheus.endpoint=https://prometheus.example.com .
```
