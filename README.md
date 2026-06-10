# Django ToDo List – Kubernetes Monitoring & Observability

## Project Overview

Enhanced a Django-based ToDo application by implementing a complete monitoring and observability stack in Kubernetes. The project focused on exposing application metrics, configuring Prometheus scraping, and building Grafana dashboards to monitor application traffic in a cloud-native environment.

## My Contributions

### Application Monitoring

* Implemented a custom `/metrics` endpoint in Django.
* Integrated **Prometheus Client** to expose application metrics in Prometheus-compatible format.
* Created custom metrics to track HTTP GET and POST requests.
* Exposed request statistics for real-time monitoring and analysis.

### Containerization & Deployment

* Updated application dependencies and Docker build process to include monitoring libraries.
* Deployed the application as a containerized workload in Kubernetes.
* Managed application configuration through Helm charts.

### Kubernetes & Helm

* Provisioned a local Kubernetes environment using **Kind**.
* Configured and deployed the application using **Helm**.
* Created and customized Kubernetes manifests for application deployment and service exposure.
* Implemented **ServiceMonitor** resources for automatic Prometheus target discovery.
* Configured Kubernetes Services and labels required for Prometheus scraping.

### Observability Stack

* Installed and configured the **kube-prometheus-stack** using Helm.
* Integrated the application with **Prometheus Operator**.
* Verified metric collection and target discovery through Prometheus.
* Enabled automated monitoring of application endpoints.

### Grafana Dashboards

* Designed Grafana dashboards to visualize application metrics.
* Created panels displaying:

  * HTTP request rates by method (GET/POST)
  * Request metric creation timestamps
  * Application activity trends
* Configured PromQL queries for real-time monitoring and analysis.

## Technologies

**Backend**

* Python
* Django
* Django REST Framework
* Prometheus Client

**DevOps & Cloud Native**

* Docker
* Kubernetes
* Kind
* Helm
* Prometheus
* Prometheus Operator
* ServiceMonitor
* Grafana

## Key DevOps Skills Demonstrated

* Kubernetes Deployment & Management
* Helm Chart Development
* Monitoring & Observability
* Prometheus Metrics Collection
* Grafana Dashboard Creation
* Service Discovery Configuration
* Containerization with Docker
* Infrastructure as Code
* Cloud-Native Application Operations
* Application Performance Monitoring (APM)
