# Free5gc Stage3 for Kubernetes
The free5GC is an open-source project for 5th generation (5G) mobile core networks. The ultimate goal of this project is to implement the 3GPP Release 15 (R15) and Release 16 (R16) 5G core network (5GC).

This repository aims to install dockerized free5gc stage3 and ride on kubernetes.

NOTE: Can work at version `5.0.0-23-generic` to run UPF(GTP5G Module.)

## Note
Modified from [sumichaaan/free5gc-k8s](https://github.com/sumichaaan/free5gc-k8s):
- remove gnb-sim
- upgrade to free5gc v3.0.6