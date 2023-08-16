# tekton-pipelines

## Overview
This repo is used for capturing CI/CD pipelines for different languages.

This mostly uses the following stack for achieving full CI/CD deployment to a dev environment:

* `yq` for updating image versions
* `argocd` for deployment
* `kustomize` for templating