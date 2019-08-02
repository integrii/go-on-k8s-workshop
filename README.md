## Developing and Deploying a Go Web Server on Kubernetes

### Overview

We will start by learning some of the fundamentals of Go and Docker before using them to build our own containerized Go web server on our own locally hosted Kubernetes clusters.  We will look closely at Kubernetes specs while reviewing the best practices for highly-available production deployments.  At the end of this workshop you should be able to build and deploy production-ready applications on top of a Kubernetes cluster.


### Materials Required

- Laptop (and charger) preferably running MacOS
- Docker Desktop (https://www.docker.com/products/docker-desktop)
- [`kubectl`](https://kubernetes.io/docs/tasks/tools/install-kubectl/) (`brew install kubectl`) 
- [`go`](https://golang.org/dl/) (`brew install go`)


### Chapters

- Overview of Workshop
- Go
- Writing a Go application
- Building a Go application
- Multi-stage builds with Docker
- Pushing to an image host
- Using Kubernetes with Docker Desktop
- Writing a Kubernetes Deployment
- Deploying new versions with rolling updates
- Using a Horizontal Pod Autoscaler
- Using a Pod Disruption Budget
- Configuring pod anti-ffinity
- Review
