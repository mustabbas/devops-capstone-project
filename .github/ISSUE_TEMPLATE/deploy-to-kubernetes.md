---
name: Deploy to Kubernetes
about: Deploy the Docker image to a Kubernetes cluster for scalability.
title: 'User Story: Deploy to Kubernetes'
labels: user-story
---

**As a** Cloud Architect
**I need** to deploy the image to a Kubernetes cluster
**So that** the application is scalable

### Details and Assumptions
* Kubernetes manifests (Deployment, Service) are defined
* The Docker image is available in a container registry
* The cluster is already provisioned and accessible

### Acceptance Criteria
```gherkin
Given the Kubernetes manifests are correctly configured
When I apply the manifests to the cluster
Then the pods move to a 'Running' state
```
