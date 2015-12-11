# Lab 5 - IP Addressing

## 2 connected networks

* open [this topology](http://ocw.cs.pub.ro/courses/_media/rl/labs/03/contents/rl_lab-03_config_ip_simple.pkt)
* in the network on the left side, subnet it using the `192.168.0.0/24` address space
* in the network on the right side, subnet it using the `10.0.0.0/24` address space
* make sure the PCs can ping each other

## VLSM

* open [this topology](http://ocw.cs.pub.ro/courses/_media/rl/labs/03/contents/rl_lab-03_config_vlsm.pkt)
* learn more about VLSM from [this lab](http://ocw.cs.pub.ro/courses/rl/labs/03)
* subnet the 3 networks as follows from the address space `172.16.10.0/23`
  * the network on the right should support 200 hosts
  * the network on the top should support 100 hosts
  * the network on the left should support 10 hosts
* each PC should receive the first and last available IP addresses
* make sure at the end that all PCs can ping each other
