---
title: "Native Vlan"
date: 2023-10-22
author: Raihan Ahmed
id: 20231022091146
---

# Native Vlan


VLAN that goes across the trunk will be tagged using the 802.1Q protocol but there is one exception. The native VLAN is the only VLAN that will not be tagged. That‟s right it will be using regular Ethernet frames. So what do we use the native VLAN for?
	- Management protocols like CDP (Cisco Discovery Protocol) use the native VLAN.
	- Remote management to your Cisco switch uses the native VLAN.
 	- The default native VLAN is VLAN 1.

