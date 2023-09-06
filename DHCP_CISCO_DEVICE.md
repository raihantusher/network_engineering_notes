---
title: 'DHCP Configuration'
...

**Step 1: open Interface**
DHCP(config)#interface fastEthernet 0/0
DHCP(config-if)#no shutdown
DHCP(config-if)#ip address 192.168.12.254 255.255.255.0
DHCP(config-if)#exit

**Step 2: DHCP Server**
DHCP(config)#ip dhcp pool MYPOOL
DHCP(dhcp-config)#network 192.168.12.0
DHCP(dhcp-config)#default-router 192.168.12.254
DHCP(dhcp-config)#dns-server 8.8.8.8
DHCP(dhcp-config)#exit

**DHCP Excluded Address**
DHCP(config)#ip dhcp excluded-address 192.168.12.10 192.168.12.20

**Check if Client recieves IP from DHCP**
Client(config)#interface fastEthernet 0/0
Client(config-if)#ip address dhcp
Client(config-if)#no shutdown