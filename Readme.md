# Prometheus

## Base Install

TODO

## IoT Prometheus DB

A Sample Prometheus DB for storing Metrics from IoT Devices, which can be visualized by Grafana.
Storage is in this cas Longhorn to persist the data.

Deployment with ArgoCD, if you doint have ArgoCD, just use Kustomize

    kubectl apply -k overlays/iot