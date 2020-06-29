# Assign Task Example

![](https://github.com/Bonitasoft-Community/assign-task-example/workflows/Build/badge.svg)
[![GitHub version](https://badge.fury.io/gh/Bonitasoft-Community%2Fassign-task-example.svg)](https://badge.fury.io/gh/Bonitasoft-Community%2Fassign-task-example)
![bonita version](https://img.shields.io/badge/bonita-7.10.5-red)


This repository contains an Bonita project example that highlight how to implement task assignment in a workflow.

## Build 

Run `./mvnw` in a terminal. The result of the build is a BOS Archive in the `target` folder.

## Project content

* An example organization with the `manager` role
* The `Assign Task Example` diagram
* The `AssignTaskForm`

## How to install

### Prerequisites

* Bonita Studio Community 7.10.5 and above
* [task-candidates-rest-api](https://github.com/Bonitasoft-Community/task-candidates-rest-api/releases/) Rest API Extension must be installed (Adminstrator Portal > Resources > Add )

### Usage

* Download the latest [release](https://github.com/Bonitasoft-Community/assign-task-example/releases) of the BOS Archive
* Import it in your Studio ( File > Import > BOS Archive...)
* Deploy the project (Right-click on the porject > Deploy...)
* Open the Portal, logout/login as `helen.kelly` to perform a task assignement
