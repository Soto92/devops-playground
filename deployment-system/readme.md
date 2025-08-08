## Building a Local Kubernetes Deployment System

This guide provides a step-by-step walkthrough for creating a robust, local Kubernetes-based deployment system. Was set up two Minikube clusters: one for our CI/CD tools (Jenkins) and another for deploying our applications.

Used the following tools:

- Minikube: To create and manage our local Kubernetes clusters.

- OpenTofu: To define and provision our clusters as code.

- Helm: To package and deploy our applications to Kubernetes.

- Jenkins: As our CI/CD automation server.

- Prometheus: To collect metrics from our application cluster.

- Grafana: To visualize the metrics collected by Prometheus.
