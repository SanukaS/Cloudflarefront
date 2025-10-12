### Command Install

```
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/SanukaS/Cloudflarefront/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

### Feature Script

• SSH & OpenVPN

• SSH Websocket TLS & No TLS ( CloudFlare & CloudFront )

• OHP SSH & OHP Dropbear & OHP OpenVPN

• Backup Data ALL Service

• Restore Data ALL Service

### Os Supported

• Debian 10 & 11

• Ubuntu 18.04 & 20.04 (Recommended)

# Service & Port

• OpenSSH                 : 443, 22

• OpenVPN                 : TCP 1194, UDP 2200, SSL 990

• Stunnel5                : 443, 445, 777

• Dropbear                : 443, 109, 143

• Squid Proxy             : 3128, 8080 (OFF)

• Badvpn                  : 7100, 7200, 7300

• Nginx                   : 89

• Websocket TLS           : 443

• Websocket None TLS      : 8880

• Websocket Ovpn          : 2086

• OHP SSH                 : 8181

• OHP Dropbear            : 8282

• OHP OpenVPN             : 8383

 ### Server Information & Other Features

• Timezone                : Asia/Colombo (GMT +5.30)

• Fail2Ban                : [ON]

• Dflate                  : [ON]

• IPtables                : [ON]

• Auto-Reboot             : [ON]

• IPv6                    : [OFF]

• Autoreboot On 03.30 GMT +5.30

• Auto Delete Expired Account






------------
**Telegram**
------------
[Sanuka](https://hells_BAD_KING)
