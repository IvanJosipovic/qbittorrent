# qBittorrent with WebUI and OpenVPN
Container which runs the latest headless qBittorrent client with WebUI while connecting to OpenVPN with iptables killswitch to prevent IP leakage when the tunnel goes down.

## Features
* Base: Ubuntu 18.04
* Latest qBittorrent
* VPN Provider: PIA
* Port Forwarding Support behind VPN
* IP tables kill switch to prevent IP leaking when VPN connection fails