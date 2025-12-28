# Portal

"a very long ethernet cable"

The original inspiration for portal was encountering Wi-Fi in various locales that blocked common VPN protocols or otherwise restricted traffic to DNS and HTTP(S).

If you can't beat them, join them.


## What is portal?

**Portal** is a modular networking toolkit for securely extending and bridging devices across untrusted or restricted networks.

While not required, Portal is designed for and tested on Raspberry Pi devices.

---

## Audience & Use Cases

portal is intended for:
- Security engineers and researchers
- Infrastructure and network practitioners
- Edge and lab environments
- Privacy-conscious operators working across hostile or constrained networks

---

## Purpose

The purpose of portal is to reliably establish and maintain secure network communications for connected clents in environments where:
- Connectivity may be filtered, rate-limited, or degraded
- Isolation from the client-side LAN and ISP is desireable
- Reliance on a single provider, protocol, or algorithm is undesirable

---

## Functional Objectives

- Establish and maintain communications though restrictive egress firewalls
- Enable safe, reliable network "teleportation" ( Layer 2 adjacency ) for connected devices
- Isolate client traffic from the local network
- Provide end-to-end encryption for client traffic 

---

## Core Components

- L2TP
- Wireguard
- WebSocket Tunnels
- 

