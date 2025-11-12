# Ubuntu-Network-Scripts
Ubuntu Network Scripts

A series of scripts (2) to be able to type in the commands IP or DHCP to be able to switch between a static IP or a DHCP assigned IP address. Be sure to change the IP address in 00-installer-config.IP to the static IP address you plan on assigning, otherwise it will assign 10.10.10.10 as it is set now.

Setup:

Copy scripts to /etc/netplan

Usage:

Execute ./IP.sh to assign the assigned static IP.

Execure ./DHCP to assign a network assigned IP address.

