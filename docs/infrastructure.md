---
layout: default
title: Infrastructure
nav_order: 6
---

# Infrastructure

I personally think it would be a crime to *not* have a kubernetes
cluster on board. Jokes aside, it's also the perfect solution for a
durable, resilient system which I've been professionally trained to use.

-   can operate as a local development environment

-   provides Workstation redundancy and durability; in the event of
    machine failure a new workstation is simply a virtual machine based
    on an incremental backup away.

-   Is a home-server. I do this stuff for fun, I need a playground too!

-   provides various services to me such as incremental backups, GPS
    services, and various others outside of the scope of this paper.

-   integrates with onboard marine sensors, e.g. with [CANBOAT](https://github.com/canboat/canboat)

## Limitations

There would be a single switch at the heart of any network I would
build, I'm not currently aware of a way around this without using 3
switches simultaneously and my current proposed solution is to keep a
cold spare available.

It would be wise to procure onboard networking equipment specifically for
this purpose, as the marine environment is hell on electronics.
