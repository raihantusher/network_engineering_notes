---
title: "EtherChannel"
date: 2023-10-26
author: Raihan Ahmed
id: 20231026125652
---

# EtherChannel

If you want to configure an Etherchannel there are two protocols you can choose from:
     	* PAgP (Cisco proprietary)
 		* LACP (IEEE standard)


   If you are going to create an etherchannel you need to make sure that all ports have the same configuration:
        a. Duplex has to be the same.
        b. Speed has to be there same.
        c. Same native AND allowed VLANs.
        d Same switchport mode (access or trunk).

[[20231026130113]] PAgP