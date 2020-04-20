 # Introduction
This repository is a fork of [Dick Chesterwood repo](https://github.com/bagcheap/istio-udemy) to extend and update with some more istio feature scenarios.

Thanks to Dick Chesterwood for an elaborative and extensive in-depth course on istio.

The aim of the repo is to demonstrate the Istio features using the minikube Kubernetes local cluster.

The repo contains all the course files in terms of Kubernetes yaml files and istio CRD files along with Fleetman Microservice application.

## Fleetman application Microservices

* **istio-fleetman-api-gateway**
 This is not intended to be a full production strength API Gateway. For now, it simply serves as a backend facade for the Angular front end to connect to.

* **istio-fleetman-photo-service**
A Micro service for suplying the driver profile photo.

* **istio-fleetman-position-simulator**
A microservice that generates fake streams of position data, representing trucks/lorries on a delivery route.
This code is not production standard - it is intended merely to generate some interesting test data.

* **istio-fleetman-position-tracker**
Consumes vehicle position reports from a queue. Stores them in-memory for testing.

* **istio-fleetman-staff-service**
A microservice that calculates the speed of the vehicle that is being tracked along with the list of vehicles data

* **istio-fleetman-vehicle-telemetry**
A microservice that traces/tracks the vehicle position.

* **istio-fleetman-webapp-angular**
A front end angular application rendering the list of vehicles in the left panel and the realtime tracking position tracked through map and driver details along with their profile picture. 

# Istio Installation

Istio is going to be installed using kubectl and minikube, the installation of Kubectl and Minikube is given below. 

## Kubectl Installation



## Minikube Installation

# The Course Architecture diagram
TODO


## Installing Istio using course files
TODO


# Kubectl commands
TODO
