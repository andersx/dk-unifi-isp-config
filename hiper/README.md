# Hiper setup

These are the steps to set up a a Unifi Network Controller to run your Ubiquiti router with IPv6 support. 
The Ubiquiti router should be plugged directly into the fiber ONT box (unfortunately, there is no way to get around this).

For this guide I am using the UCG-Ultra and running UniFi OS version 4.1.13 with Network version 9.0.114.

### Setup internet connection

These steps are necessary to reach the internet and set up IPv6 on the WAN side.

Go to Settings (gear icon) -> Internet and fill out the following:

Hiper (and most other Nuuday ISP) use VLAN tagging on the WAN interface.
The VLAN ID is 101. So check the box and put in this tag.

Next, make sure IPv4 and IPv6 are set to DHCP.
For IPv6, the option "Prefix Delegation Size" should be set to 48

See screenshot below for reference:

![Alt text](screenshots/internet.png)
# 




