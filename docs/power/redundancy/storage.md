---
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

n.b. - Most sailboats already come with separate house/starter battery banks,
and an accompanying giant switch. Typically you run on house bank, and then
when it's time to start the engine, you flip the house bank to "all," 
with the associated possible power blip. Your switch remains on "all," charging
all of your batteries until the motor is shut off, at which point you point the switch back to your house bank.

In this way, even if you drain your batteries in an unexpected way, you'll be able to
start the motor. Note that switching battery banks while running the motor is
inadvisable - you can fry your alternator diodes.
