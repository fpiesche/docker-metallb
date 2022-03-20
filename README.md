# This repository is ARCHIVED as MetalLB has multi-architecture images avaialble from armv7 upwards at quay.io/metallb/controller and quay.io/metallb/speaker.

# Multi-arch builds for MetalLB

![build](https://github.com/fpiesche/docker-metallb/actions/workflows/build-release.yaml/badge.svg)

# Quick reference

- **Image Repositories**:
    - Docker Hub: [`florianpiesche/metallb-speaker`](https://hub.docker.com/r/florianpiesche/metallb-speaker)
        [`florianpiesche/metallb-controller`](https://hub.docker.com/r/florianpiesche/metallb-controller)
    - GitHub Packages: [`ghcr.io/fpiesche/metallb-speaker`](https://ghcr.io/fpiesche/metallb-speaker)
        [`ghcr.io/fpiesche/metallb-controller`](https://ghcr.io/fpiesche/metallb-controller)

- **Maintained by**:  
  	[Florian Piesche](https://github.com/fpiesche)

-	**Where to file issues**:  
    [https://github.com/fpiesche/docker-metallb/issues](https://github.com/fpiesche/docker-metallb/issues) (multi-arch Docker images only)
    [https://github.com/metallb/metallb/issues](https://github.com/metallb/metallb/issues) (upstream)

- **Dockerfile**:  
    [https://github.com/fpiesche/docker-metallb/blob/main/Dockerfile.controller](https://github.com/fpiesche/docker-metallb/blob/main/Dockerfile.controller)
    [https://github.com/fpiesche/docker-metallb/blob/main/Dockerfile.speaker](https://github.com/fpiesche/docker-metallb/blob/main/Dockerfile.speaker)

-	**Supported architectures**:  
    Each image is a multi-arch manifest for the following architectures:  
    `amd64`, `arm64`, `armv7`, `armv6`

- **Source of this description**:  
    [Github README](https://github.com/fpiesche/docker-metallb/tree/main/README.md) ([history](https://github.com/fpiesche/docker-metallb/commits/main/README.md))

# Supported tags

`latest` is the most recent tagged release in the [main metallb repository](https://github.com/metallb/metallb/releases).

Images are also tagged with the release tag.

# How to use this image

This is a drop-in replacement for the normal `metallb/speaker` and `metallb/controller` images. The only difference is that
the `florianpiesche/metallb-speaker` and `florianpiesche/metallb-controller` images are multi-arch manifests (as above)
