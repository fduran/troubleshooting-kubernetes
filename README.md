# Troubleshooting Kubernetes


## Table of Contents

### Section One: Introduction

- Emergency Sheet
- [Introduction](#introduction)
	- Preparedness
	- Incident Response
	- [Troubleshooting Techniques](#troubleshooting-techniques) 
- Tooling
	- Command line foo
	- Dashboards
	- Pre-flight checkers
	- Debugging Containers
	- Service Meshes
	- Distributed Tracing
	- Inspecting Kubernetes Servers
	- Other Tools

### Section Two: Troubleshooting Kubernetes

- Logging
- Clusters
- Applications
- Kubernetes Objects
	- Services
	- Pods
	- Nodes
	- StatefulSets
	- ReplicationControllers
	- Deployments
	- IngressControllers
- Kubernetes Services
	- API Server
	- etcd
	- Metrics Server
	- Networking
- RBAC
- Linux
- Kubernetes Cloud Providers
	- GKE
	- AKS
	- EKS
		
### Section Three: Prevention

- Best Practices
	- Test Environments
	- Degraded Mode
- Monitoring and Alerting
- Operations
	- Rollbacks
	- Continuous Testing
	- Backups and Restores
	- Workload Upgrades
	- Kubernetes Upgrades
	- Game Days(#game-days)
	- Post-Incident Reviews

	
Licence is [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International	](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
Copyright Fernando Duran



## Introduction

The purpose of this guide is to help Kubernetes practitioners — in particular administrators of production environments —  prevent and deal with incidents in their clusters.  


The main topic will be **troubleshooting** (taken as a synonym of **debugging**) as in finding the root cause of an ongoing issue in a Kubernetes cluster.

Before getting into the particulars of troubleshooting in Section Two, in this first section we will briefly talk about incident response, general troubleshooting techniques and the set of tools that will help us with the actual debugging. Then in Section Three we will discuss ways to have a solid system so that we avoid having problems in the first place.


### Troubleshooting Techniques




