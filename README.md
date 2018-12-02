Kube Router
============

[![](https://images.microbadger.com/badges/version/runningman84/node_exporter.svg)](https://hub.docker.com/r/runningman84/node_exporter "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/runningman84/node_exporter.svg)](https://hub.docker.com/r/runningman84/node_exporter "CGet your own image badge on microbadger.com")
[![](https://img.shields.io/docker/stars/runningman84/node_exporter.svg)](https://hub.docker.com/r/runningman84/node_exporter "Click to view the image on Docker Hub")
[![](https://img.shields.io/docker/pulls/runningman84/node_exporter.svg)](https://hub.docker.com/r/runningman84/node_exporter "Click to view the image on Docker Hub")
[![Anchore Image Overview](https://anchore.io/service/badges/image/67c25bcc9388574461b256b9ace3e04011ab4fa3ff8fe4ce20a5ffe621c8a582)](https://anchore.io/image/dockerhub/runningman84%2Fnode_exporter%3Alatest)

Introduction
----
This docker image provides a multi arch node_exporter image. The offical image does not provide arm64 support yet:
https://github.com/prometheus/promu/issues/89
This image uses the docker multi-stage build feature in order to reduce the image size.

Install
----

In order to use this image instead of the offical image change the image setting in kubeadm-kuberouter-all-features.yaml from cloudnativelabs/node_exporter to runningman84/node_exporter

