---
title: Install a Pod network add-on
description: A pod network add-on is neccessary for pod communication
date: 2025-03-22
weight: 5
---

## Add pod network add-on

This is a part of Kubernetes that doesn't come directly with kubeadm.  

You can choose from the list of pod networks listed on the [kubeadm website](https://kubernetes.io/docs/concepts/cluster-administration/addons/#networking-and-network-policy)

One option is weave... which can be installed with kubectl:

`kubectl apply -f https://github.com/weaveworks/weave/releases/download/v2.8.1/weave-daemonset-k8s.yaml`

