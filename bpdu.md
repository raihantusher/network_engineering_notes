---
title: "Bpdu"
date: 2023-10-25
author: Raihan Ahmed
id: 20231025145516
---



# BPDU
Since spanning tree is enabled, all our switches will send a special frame to each other called a BPDU.

“Bridge Protocol Data Unit”


Bridge ID = MAC address + Priority



The ports on our root bridge are always designated which means they are in a forwarding state.

The shortest path to the root bridge is called the **root port.**



The old switch probably has a lower MAC address and will become the root bridge…not a
good idea right? I‟ll show you how to change the priority so the MAC address is no longer
the tie-breaker!

