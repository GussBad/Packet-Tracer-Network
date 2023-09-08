
## Topology Overview

My network topology consists of:

- 20 computers.
- 5 Cisco 2950-24 switches.
- 4 Cisco 3550-24PS switches.
- 4 servers.
- 3 routers for interconnecting 3 sites.

![1](https://github.com/GussBad/Packet-Tracer-Network/assets/98527927/06e91700-39e4-4150-a16c-162614acc3dd)


## DNS Configuration

I've set up a DNS server to enable name resolution within my network, making it easier for devices to communicate using names instead of IP addresses.

![DNS](https://github.com/GussBad/Packet-Tracer-Network/assets/98527927/560148e9-84f0-44b1-939c-537686e1defe)



## DHCP Configuration

I've implemented a DHCP server to automatically assign IP addresses to devices on the network, simplifying scalability and network administration.

Key DHCP server settings:
- IP Address Range: 192.168.1.10 to 192.168.1.50
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.1.1
- DNS Servers: 192.168.5.2

  ![2](https://github.com/GussBad/Packet-Tracer-Network/assets/98527927/251facd4-ab0c-49f7-9fc6-39f4593303c8)


## IP Addressing Configuration

Each site in my network has its own IP address range, helping to organize and isolate traffic between sites.

Key IP addressing settings:
- Site 1: 192.168.1.1
- Site 2: 192.168.2.2
- Site 3: 192.168.3.1

## Other Configurations

Additionally, I've configured routing rules between routers to allow communication between sites and local networks.

![3](https://github.com/GussBad/Packet-Tracer-Network/assets/98527927/e3447970-e7d7-4317-95da-d472b96ef04f)


## Conclusion

This is just an overview of my network configuration in Packet Tracer. I'm excited to have completed this project and look forward to sharing more details and learning from other networking enthusiasts.

If you have any questions about the configuration or would like more details on any specific aspect, please don't hesitate to reach out.

Thank you for reading, and I hope this project proves to be informative and useful!
