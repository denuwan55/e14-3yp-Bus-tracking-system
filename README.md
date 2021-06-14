---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e14-3yp-Bus-tracking-system
title: Bus tracking system
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Bus tracking system

---

## Team
-  E/14/181, KAVINDAT.B.D.H., [e14181@eng.pdn.ac.lk](mailto:e14181@eng.pdn.ac.lk)
-  E/14/178, KARUNASINGHE Y.K., [e14178@eng.pdn.ac.lk](mailto:e14178@eng.pdn.ac.lk)
-  E/14/298, RUWANTHAJ.M.D.J., [e14298@eng.pdn.ac.lk](mailto:e14298@eng.pdn.ac.lk)

## Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Hardware & Software Designs](#hardware-and-software-designs)
4. [Links](#links)

---

## Introduction

A lot of people do not like to travel in crowded buses. We would love to travel sitting, sleeping. It will be very useful if there is a system to know whether the next bus on our route is full or not, to know the location of that bus, to know whether there are any alternative buses on route and etc.

So we came up with a solution which is an embedded system and huge network of various devices. Real-time bus data, which comes from the bus tracking system, shows the expected time in minutes until the arrival of the relevant bus. Customers can view this anticipated arrival time at a location via an app, website or, where available on the public information display system at the bus stop.  

The main purpose in this idea is to check whether the buses are heavily loaded and late. So that if a person is willing to use another way of transportation, he can use that considering the information given by the system.

After all, the collected data will be very valuable also. They can be used to analyse and check which route has heavy load of people, whether the time differences among buses should be adjusted and should there be more buses in a route in a particular time and any more.


## Solution Architecture

CO321 – The relevant parameters will be measured using sensors such as IR, pressure sensors and GPS trackers and processed raw data using AVR controller.

CO322 – The data will be transferred to a centralized server via Wi-Fi or using a GSM module. Those processed data can be viewed by an app or through a web interface.

CO325 – The data will be sent encrypted not to have them seen by a third party before reaching the server.

## Hardware and Software Designs

- [Project Proposal](data/documents/1.pdf)  
- [Project Design](data/documents/2.pdf)

## Links

- <a href = "https://github.com/cepdnaclk/e14-3yp-Bus-tracking-system" target = "_blank">Project Repository</a>
- <a href = "https://cepdnaclk.github.io/e14-3yp-Bus-tracking-system/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://eng.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
