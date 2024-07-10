[![ci](https://github.com/okdp/charts/actions/workflows/ci.yml/badge.svg)](https://github.com/okdp/superset/actions/workflows/ci.yml)
[![release-please](https://github.com/okdp/charts/actions/workflows/release-please.yml/badge.svg)](https://github.com/okdp/superset/actions/workflows/release-please.yml)
[![License Apache2](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)

<p align="center">
    <img width="400px" height=auto src="https://okdp.io/logos/okdp-inverted.png" />
</p>


This repo contains:

- A Dockerfile and associated scripts to build the `superset` docker image with additional python librairies.
- A corresponding helm chart whitch wraps the original official [superset chart](https://github.com/apache/superset/tree/master/helm/superset).

## Installation

Refer to [README](helm/superset/README.md) for the customization and installation guide.

## Requirements

- Kubernetes cluster
- [Helm](https://helm.sh/) installed

> [!NOTE]
> An OKDP sandbox, with all these helm charts installed, is under development and you can use it once released.
> 