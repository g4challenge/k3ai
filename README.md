---
description: >-
  K3Ai is a lightweight infrastructure-in-a-box ready to run on top of edge and
  IoT devices  filled in with a set of Artificial Intelligence platforms and
  solutions
---

# Quick Start Guide

## First things First

Start by installing K3Ai with this:

```text
curl -sfL https://raw.githubusercontent.com/kf5i/k3ai/master/install | sh -
```

wait for a minute and check the status of installation with:

```text
kubectl get pods -n kubeflow
```

when all pods are in status `running` you're good to go.

![K3ai installation process](.gitbook/assets/demo.gif)

## What do I find within K3Ai

K3ai supports a variety of artificial intelligence tools that can be installed as standalone or as a bundle from directly from the command-line. The actual list may be run adding the below options after `k3ai server` the command:

`-- pipelines` \(default\): Kubeflow pipelines are installed as default settings so there's no need to explicit the command. If one desires, anyway, to add to an existing k3ai custom installation the command will install and configure the Kubeflow pipelines automatically.

-- 

