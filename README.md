## OpenVPN-install
Secure OpenVPN installer for Debian, Ubuntu, CentOS and Arch Linux.

This script will let you setup your own secure VPN server in just a few minutes.

## Usage

**You have to enable the TUN module otherwise OpenVPN won't work.** Ask your host if you don't know how to do it. If the TUN module is not enabled, the script will warn you and exit.

First, get the script and make it executable :

```
wget https://github.com/waelisa/OpenVPN-Installer/raw/master/openvpn-installer.sh
chmod +x openvpn-installer.sh
```
Then run it :

`./openvpn-installer.sh`

The first time you run it, you'll have to follow the assistant and answer a few questions to setup your VPN server.

When OpenVPN is installed, you can run the script again, and you will get the choice to :

- Add a client
- Remove a client
- Uninstall OpenVPN

This script is based on the great work of [Nyr and its contributors](https://github.com/Nyr/openvpn-install)

Then add Secure DNS by me.

[Donate link – PayPal](https://www.paypal.me/WaelIsa)

## DNS list
1) Current system resolvers

2) Google

3) OpenDNS

4) NTT

5) Hurricane Electric

6) Verisign

7) AdGuard DNS (Can block ADS)

8) Comodo Secure DNS (malware, phishing sites and scam sites)

9) Norton ConnectSafe (malware, phishing sites and scam sites)
