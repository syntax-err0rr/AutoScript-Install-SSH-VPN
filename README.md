# AutoScript-Install-SSH-VPN

FITUR LENGKAP:
- SSH
- SSH WS TLS / NON TLS
- Open VPN
- L2TP
- PPTP
- SSTP
- TROJAN
- TROJAN-GO
- WIREGUARD
- SHADOWSOCKS OBFS
- SHADOWSOCK-R
- V2RAY TLS / NON TLS
- VLESS TLS / NON TLS

FOR USAGE:
- STEP 1: 
apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && reboot

- STEP 2: 
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget -O setup.sh 'http://lostserver.my.id:81/setup.sh' && chmod +x setup.sh && screen -S setup ./setup.sh

SUPPORT OS:
- DEBIAN 9 & 10
- UBUNTU 18 & 20

FOR MORE INFORMATION
- CONTACT: 081326854629

![Screenshot_20210814-175523_JuiceSSH](https://user-images.githubusercontent.com/83074099/129452598-44d12e5f-dbb4-4192-b47d-d0d9c12064ed.png)
