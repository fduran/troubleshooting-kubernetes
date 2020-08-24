# Troubleshooting Kubernetes

The purpose of this guide is to help Kubernetes practicioners — in particular administrators of production environments —  prevent and deal with incidents in their clusters.

## Table of Contents

- [Preface](#preface)
- [Emergency Sheet](#emergency-sheet)
- [Introduction](#introduction)
	* [Preparedness](#preparedness)
	* [Incidence Response](#incidence-response)
	* [Troubleshooting Techniques](#troubleshooting-techniques) 
- [Tooling](#tooling)
	* [Command line foo](#command-line-fu)
	* [Dashboards](#dashboards)
	* [Pre-flight checkers](#pre-flight-checkers)
	* [Service Meshes](#service-meshes)
	* [Distributed Tracing](#distributed-tracing)
	* [Inspecting Kubernetes Servers](#inspecting-kubernetes-servers)
	* [Other Tools](#other-tools)
- [Troubleshooting Kubernetes](#troubleshooting-kubernetes)
	* [Logging](#logging)
	* [Clusters](#clusters)
	* [Applications](#applications)
	* [Kubernetes Objects](#kubernetes-objects)
		+ [Services](#services)
		+ [Pods](#pods)
		+ [Nodes](#nodes)
		+ [StatefulSets](#statefulsets)
		+ [ReplicationControllers](#replicationcontrollers)
		+ [Deployments](#deployments)
		+ [IngressControllers](#ingresscontrollers)
	* [Kubernetes Services](#kubernetes-services)
		+ [API Server](#api-server)
		+ [etcd](#etcd)
		+ [Metrics Server](#metrics-server)
		+ [Networking](#networking)
	* [RBAC](#rbac)
	* [Linux](#linux)
	* [Kubernetes Cloud Providers](#troubleshooting-kubernetes-cloud-providers)
		+ [GKE](#gke)
		+ [AKS](#aks)
		+ [EKS](#eks)
- [Prevention](#prevention)
	* [Best Practices](#best-practices)
		+ [Test Environments](#test-environments)
		+ [Degraded Mode](#degraded-mode) 
	* [Monitoring and Alerting](#monitoring-and-alerting)
	* [Operations](#operations)
		+ [Rollbacks](#rollbacks)
		+ [Continous Testing](#continous-testing)
		+ [Backups and Restores](#backups-and-restores)
		+ [Workload Upgrades](#workload-upgrades)
		+ [Kubernetes Upgrades](#kubernetes-upgrades)
		+ [Game Days](#game-days)
		+ [Post-Incident Reviews](#post-incident-reviews)

	
	
	
	
## Preface
Audience is pratitioners, objective, breakdown

## Emergency
Emergency Sheet

## Introduction
Intro

### Preparedness
Preparedness

Know your system. 
Maintenance: purge deleted objects


### Incidence Response
Incidence Response

### Troubleshooting Techniques
Troubleshooting Techniques



## Tooling
Tooling

### Command line foo
Command line foo

### Dashboards
Dashboards

### Pre-flight checkers
Pre-flight checkers

### Service Meshes
Service Meshes

### Distributed Tracing
Distributed Tracing

### Inspecting Kubernetes Servers
Inspecting Kubernetes Servers

### Other Tools
Other Tools


## Troubleshooting Kubernetes Objects
Troubleshooting Kubernetes Objects

### Logging
Audit policy defines rules about what events should be recorded and what data they should include.

### Services
Services

## Troubleshooting Kubernetes Servers
Troubleshooting Kubernetes Servers

### API Server
API Server

### etcd
etcd

### Metrics Server
Metrics Server

### Networking
Debugging CNI, DNS 

## Troubleshooting Kubernetes Cloud Providers
Troubleshooting Kubernetes Cloud Providers

### GKE
GKE

### AKS
AKS

### EKS
EKS

## Prevention
Prevention

### Best Practices
Best Practices

#### Test Environments
Test Environments

#### Degraded Mode
Degraded Mode

### Monitoring and Alerting
Monitoring and Alerting

### Operations
Operations

#### Rollbacks
Rollbacks

#### Continous Testing
Continous Testing

#### Backups and Restores
Backups and Restores

#### Workload Upgrades
Workload Upgrades

#### Kubernetes Upgrades
Kubernetes Upgrades

#### Game Days
Game Days

#### Post-Incident Reviews
Post-Incident Reviews






