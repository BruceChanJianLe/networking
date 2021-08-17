# Networking

This repository is some notes on networking.

## IP Address

IP addresses can be treated as phone number. For one device to find another device within a LAN (local area network) or WLAN (wide area network), it has to know the other devices IP address to find. Once the connection is established, both device can send data to one another, as though it is a phone call. Both parties can talk and listen.

## Switch

A switch is a device to allow multiple devices to find one another on a LAN. A switch should be as transparent as possible, meaning the devices on the LAN does not need to know its existance. You do not talk `to` your network switch, but you talk `through` your network switch.

## Router

A router acts as a bridge to connect a devices to WAN, meaning by connecting to a router, a device can now connect to or find another device is on WAN. The router connect LAN through gateway to WAN. Please refer to subnet mask and gateway.

## Gateway

The gateway is the IP address of the router, one on the LAN and another on the WAN. The question is when do you search for IP on the LAN and when do you search on WAN? We shall discuss this more on subnet.

## Subnet Mask

A subnet mask is not an IP address. It indicates the parts of your own IP address that form out LAN range.

255 is 11111111 and 0 is 00000000.

IP Address | 192.168.10.11
---|---
Subnet Mask | 255.255.255.0
LAN Range | 192.168.10.xxx

## Reference

- [yamaha_video_link](https://www.youtube.com/watch?v=udE60TJG0Qg)
