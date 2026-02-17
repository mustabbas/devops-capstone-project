---
name: Containerize Microservice
about: Package the microservice into a Docker image for consistent deployment.
title: 'User Story: Containerize Your Microservice'
labels: user-story
---

**As a** DevOps Engineer
**I need** to package the service into a Docker image
**So that** it runs identically everywhere

### Details and Assumptions
* A Dockerfile is used to define the image
* The image should be lightweight and production-ready
* The container exposes the correct service port

### Acceptance Criteria
```gherkin
Given the Dockerfile is correctly configured
When I run docker build
Then a functional Docker image is created successfully
```
