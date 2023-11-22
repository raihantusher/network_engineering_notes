---
title: "DR and BDR"
date: 2023-10-26
author: Raihan Ahmed
id: 20231026092549
---

# DR and BDR

All router sends their LSA packet to multicast address 224.0.0.6. DR router listen from this IP address. 
Then DR send this data to all router through 224.0.0.5 multicast address.

## How to determine Designated Router
    *  max router id
    * max interface ip

    