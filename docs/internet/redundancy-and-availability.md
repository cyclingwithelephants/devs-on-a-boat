---
layout: default
title: Redundancy + Availability
parent: Internet
nav_order: 1
---
## redundancy and availability

The solution is built to be redundant at multiple levels, achieving a
highly available internet connection which I describe below.

I discuss power availability in its own section.

### Connection types

Whenever possible I would take advantage of long range wifi, this
extends up to 7 miles off-shore in perfect conditions but can more
reasonably be expected to be around half this distance under poor
conditions [@long-range-wifi]. This will of course provide sufficient
internet access, it's an otherwise standard WiFi connection. When this
is not available I would fallback automatically to a load-balanced 4G
connection (5G if available).

### Hardware

By virtue of using multiple, independent pieces of hardware to handle
each connection type I am insulated from any single piece of hardware
failing from causing an outage.

Additionally, 4G load-balancing will be dealt with by two independent
pieces of hardware rather than a single unit with multiple sim slots.
This is necessary for hardware level redundancy, ensuring high
availability of the 4G connection.
