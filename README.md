<h1 align="center"> DevOps </h1> <br>

## Table of Contents

- [Introduction](#introduction)
- [Platzi&nbsp;Course](#platzicourse)

## Introduction

#### DevOps (Developer Operations)
It is a way to connect operators with software developers in an efficient way, since they follow:
- Aligned goals
- Greater communication
- Greater speed and results
Devops is a culture of collaboration, characterized by the automation of workflows, process metrics and the sharing of tools between different teams. One of the benefits of Devops is the increase in deployments for the same time and the reduction of errors.
#### Homogeneous Environments for Applications
"It works in my machine" is the situation that arises when there are discrepancies transferring the code from one environment to another, to ensure that it runs in the same way, it is necessary to establish the same configuration together with the dependencies in each of the environments. One way to avoid this problem is use containers, for example, Docker. The dockers are reproducible, programmable and the documentation is the same code that is contained in the Dockersfiles. The definition of a docker can be used for different environments, allowing them to be completely homogeneous. Another option is virtual machines, however they are much less portable than containers.
#### Homogeneous Environments for Infrastructure
There are options to have the equivalent of docker in infrastructure; one of them is Terraform that allows the generation of resources with the same configuration for different regions. In Terraform you can write code that can mount resources for cloud services such as AWS, in which you only have to define the parameters and with this allows you to scale yours functions.
#### Testing
It is important that the tests can be replicated in the different environments to ensure that the code is working properly. These tests must be carried out in an automated way, in which at least unit and integration tests are executed, although it is recommended that the acceptance test be included.
#### Continuous integration (CI)
It is a workflow used by teams that makes it easy to add functionality to products. A flow could be the following:
- Git: Keeps a history of code changes.
- Jenkis: Automates the tests of the changes made, preventing errors from transferring to the main branch.
- Code analysis: It is the part in which it’s possible to re-factor the code and modify the style of the program.

#### Artifact
It is the unit that is transferred to the environments, it is something immutable that allows homogenization in the different environments. These should be stored in case it is necessary to make a rollback in the future.

#### Continuous Delivery
It is a CI extension that automates the entire process of adding code to the main branch, so that it can be deployed to production at any time manually and safely.

#### Site Reliability Engineering
It is the way in which the company internally measures the level of quality of the products. Service Level Indicators (SLI) can get error, measure latency. Service Level Objectives (SLO) obtains the metrics of what is offered to the client and what they receive.



## Platzi&nbsp;Course

Check out [Platzi's DevOps course]( https://platzi.com/clases/devops/).
