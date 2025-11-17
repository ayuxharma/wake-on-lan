# wake-on-lan
A lightweight tool that sends a Wake-on-LAN Magic Packet to remotely power on computers over a local network. It constructs the required packet format (FF:FF:FF:FF:FF:FF + repeated MAC address) and broadcasts it over UDP, allowing machines with WOL enabled to turn on instantly.
