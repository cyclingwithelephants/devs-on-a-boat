---
layout: default
title: Charging
grand_parent: Power
parent: Redundancy
nav_order: 2
---
### Charging

Charge controllers are getting to a point today where one no longer
needs separate solar, wind and motor charge controllers, drastically
simplifying their implementation. Instead we can use a single, one size
fits all solution.

To achieve high availability at this level we will use two charge
controllers in parallel, where each is sufficiently sized to handle the
maximum possible charge in the case that the other were to fail.

And one will fail, at the most inconvenient time possible.