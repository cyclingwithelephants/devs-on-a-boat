---
layout: default
title: Office Requirements
grand_parent: Power
parent: Out
---

# Office power

My work-from-home set up currently consists of a macbook driving two 4k
27-inch monitors, with an external mouse and keyboard with a standing
desk. I will be replicating this set up in the boat (I'm still figuring out the standing desk!). Not compromising on
a workstation is absolutely non-negotiable for me and I discuss my
workstation twice, here where I talk about the power requirements and
further in the logistics section.

## Monitors
Different resolution monitors differ greatly in power usage, it's up to you whether or not you want to take on the extra cost/electrical burden for 4k monitors.

### Notes:
- We assume a 10 hour work day, this tries to factor in time spent at the computer that isn't work related. If you're likely to spend less/more time then you should adjust accordingly.
- Power draw is taken directly from the manufacturer's spec sheet.
- information taken from [displayspecifications.com](https://www.displayspecifications.com/)
- the currently listed options would currently require to run an inverter with the associated loss of power due to inverter inefficiencies (10-40% - not included.

|           Model          | Typical draw <br />(Watts) | Peak draw <br />(Watts) | Daily typical usage <br />(Watt hours) | Daily maximum usage  <br />(Watt hours)                        |
|:------------------------:|:--------------------------:|:-----------------------:|:--------------------------------------:|:--------------------------------------------------------------:|
| BenQ GW2780 <br />(1080p, 27") |             18             |            32           |                   180                  |                               320                              |
|  BenQ P2700Q <br />(1440p, 27")   |             28             |            58           |                   280                  |                               580                              |
|  BenQ PD2700U <br />(4k, 27")  |             30             |            80           |                   300                  |                               800                              |

### Other options
Other options not yet discussed are:
- Using ipads as external monitors (these can double as navigation screens for onboard equipment and charge by conventional USBC Power Delivery i.e. DC)
- Monitors that run on 12v natively (these currently seem to only exist in 1080p and 1440p resolutions)
- Monitors that are designed to be run portably, these are typically quite small (up to 16 inches). e.g. [this](https://www.amazon.co.uk/Portable-Monitor-EVICIV-Upgraded-Raspberry/dp/B08CXQ8Z5F/ref=pd_sbs_6?pd_rd_w=q9fan&pf_rd_p=c1b0d6b0-0f46-4d06-b951-a1c184c4ce91&pf_rd_r=SGJV1GFGKJNF746M9X5E&pd_rd_r=e14402d1-611d-45cc-ae08-63cd39686e29&pd_rd_wg=yjuLI&pd_rd_i=B08CXQ8Z5F&psc=1)

## Laptop
Not everybody is lucky enough to be able to choose their own work laptop, as such I would suggest choosing an upper limit similar to that of the 16" MBP to ensure that you're covered. Below are some user supplied power usages for various machines. I haven't got any linux laptops to measure as of yet. If you _are_ a lucky individual, I'd recommend using a 13 inch laptop if you can due to energy usage and portability - this may not be appropriate for e.g. Rust/C++ devs however. I've been doing so since August and have no regrets.

### Notes:

- We assume a 10 hour work day, this tries to factor in time spent at the computer that isn't work related. If you're likely to spend less/more time then you should adjust accordingly.
- Peak power draw has been taken from the maximum power delivered by the manufacturer's power supply. Actual results might be higher or lower. For example the 16" MBP has reports of being able to 
discharge the battery faster than it can be charged when being used at 100% CPU and 100% GPU but this is quite exceptional.
- Typical draw values are user supplied.

|       Model       | Typical draw <br />(Watts) | Peak draw <br />(Watts) | Daily typical usage <br />(Watt hours) | Daily maximum usage  <br />(Watt hours) |
|:-----------------:|:--------------------------:|:-----------------------:|:--------------------------------------:|:--------------------------------------------------------------:|
| 13" i5 MBP (2019) |            12.5            |            60           |                   125                  |                               600                              |
| 13" i5 MBP (2020) |       To be measured       |            60           |             To be measured             |                               600                              |
| 16" i9 MBP (2020) |            15-20           |           100           |                   175                  |                               1000                             |


## Networking

## Total
