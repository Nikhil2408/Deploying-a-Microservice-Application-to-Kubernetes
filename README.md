# Deploying a Microservice Application to Kubernetes

In this repository, I have deployed a sample microservice application called Stan's Robot Shop. This is an open-source sample microservice app made by <a href="https://www.instana.com/">Instana.</a>

![](images/Scaling-Microservices-with-Kubernetes.jpg)

<h2> Attribution </h2>

Hello everyone, you are welcome to make use of this repository and learn from it but please do not copy without giving attribution to the author.

<h2> Microservices </h2>

Microservices are small and independent services that work together to form a whole application. Traditionally, apps use a monolithic architecture. In monolithic architecture, all features and services are part of one layer application but a microservice architecture breaks an application up into a collection of small loosely-coupled service.

Microservices are small - each microservice implements only a small piece of an application's overall functionality. Microservices interact with each other using stable and well defined APIs. As each of the service has its own codebase and a separate running process therefore <b> they can be scaled separately </b>.

<p align="center">
  <img src="https://github.com/Nikhil2408/Deploying-a-Microservice-Application-to-Kubernetes/blob/master/images/microservice-architecture.png" width="700">
</p>

<h4> 1. Cloning the robot-shop git repo </h4>
