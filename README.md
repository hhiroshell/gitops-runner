GitOps Runner for Wercker CI
=============================
This repository is for a Box of [Wercker](https://app.wercker.com/). "Box" is a concept of Wercker, environments for runnig continuous integration tasks made by Docker container.

The container is made for running GitOps CI operation. In other words, building applications, and creating PR to update the Single Source of Truth (git repositories these contains Kubernetes manifests) have to be performed in the box.
For this porpose, this box include the packages below:

    - Hub (CLI tool for GitHub)
    - Helm

This repository contains only a Dockerfile, and actual containers are built in Docker hub builds. See the actuial [repository](https://cloud.docker.com/repository/docker/hhayakaw/gitops-runner/).