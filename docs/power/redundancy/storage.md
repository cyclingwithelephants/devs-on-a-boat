---
bibliography: ../bib.bib
layout: default
title: Storage 
grand_parent: Power
parent: Redundancy
nav_order: 3
---
### Storage

House and Motor power will be stored in a single, large battery bank. We
can achieve redundancy of power but not high availability, damage to or
loss of a battery *will* mean a temporary outage for the network but any
work in progress won't be affected due to laptops having an inbuilt UPS.

In the event of damage to or loss of a cell, the topology of the battery
bank means that restarting the system will be as simple as isolating the
battery from the bank and resetting the circuit breaker. In this way we
will lose 1/Nth maximum current draw, in an identical manner to the
discussion on solar panels.