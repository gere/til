# Discover IPs in a LAN

An easy, albeit partial, solution to discover most of the connected peripherals in a network is to ping the broadcast address of the network and then display the arp cache. It works both on Linux and Windows. Assuming 192.168.1.255 as broadcast address, the sequence is:

```bash
$ ping [-b] 192.168.1.255
$ arp -a
```

The -b switch may be neccessary on a Linux machine.