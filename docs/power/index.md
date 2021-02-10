---
bibliography: ../bib.bib
layout: default
title: Power
has_children: true
nav_order: 4
---

# Power

In this section I'm going to outline the design of and choices involved
in creating a resilient electrical system with no single point of
failure that is capable of enabling someone to work indefinitely.

Power will be standardised at 12v as well as the USB-C Power Delivery
standard for use with laptops.

It's very fortunate that it's now practical to entirely forgo 220v AC
when powering an office; there is one fewer point of failure and
efficiency is increased hugely. This efficiency saving can be anywhere
from 10 to 40 % depending on operating conditions, this is a big win.


## A note on peak power use

In all honesty, it's a stroke of luck that unlike a conventional power
grid utilising solar power, which has peak supply in the middle of the
day and peak use in the evening, this grid will have overlapping peak
supply (solar power during the day) and draw (office equipment).

This has the implication that the external monitors (identified as being
the most power hungry item on the boat after the desalination machine)
don't require that their power budget is calculated in the same way as
most other items since we can safely assume that they will be running
directly off of the solar during the vast majority of their use. This is
a big win, essentially allowing me to half the size of the battery bank.

Similarly the desalination machine can be used whenever needed, so with
minimal planning one can utilise what would otherwise be over-charge
(i.e. electricity that would be generated but cannot be stored since the
batteries are full) for producing water.



# Wiring diagram

Much like a distributed system, the power system must have
