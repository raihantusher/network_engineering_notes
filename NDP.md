---
title: "NDP"
date: 2023-10-16
author: Raihan Ahmed
keywords:
    - ndp
    - IPv6
id: 20231016123412
---

# NDP

**Router Discovery:** NDP is used to learn about all available IPv6 routers in the subnet.
 **MAC Address Discovery:** Once a host has done the DAD check and is using anIPv6 address it will have to discover the MAC addresses of hosts it wants to communicate with.
 
**DAD (Duplicate Address Detection):**  Each IPv6 host will wait to use its address unless it knows that no other device is using the same address. This process is called DAD and NDP does this for us.
 
 **SLAAC (Stateless Address Autoconfiguration):** We‟ll cover SLAAC in a bit inmore detail, but NDP is used to learn what address and prefix length the host should use.
