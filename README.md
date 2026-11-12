# Workout Logger on Kubernetes

Kubernetes deployment of the [Workout Logger](https://github.com/helgaszebenyi/workout-logger) app,
using the container images its CI pipeline publishes to GitHub Container Registry.

> 🚧 Work in progress

## Planned

- Local cluster with kind
- Deployments, Services and Ingress for the web and API containers
- Liveness and readiness probes using the app's health endpoints
- Secrets kept out of the repo
- Kustomize overlays for dev and prod
- Autoscaling (HPA)
- GitHub Actions pipeline that tests the deployment on a temporary cluster