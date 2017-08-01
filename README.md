Auto Install Script For VPS Debian7 - www.twitter.com/eirza

wget https://github.com/ForNesiaFreak/FNS_Debian7/raw/fornesia.com/debian7.sh
bash debian7.sh

===========================================
Autoscript Include:

Service

OpenSSH : 22, 143
Dropbear : 443, 110, 109
Squid3 : 80, 8080 (limit to IP SSH)
badvpn : badvpn-udpgw port 7300

Tools

axel, bmon, htop, iftop, mtr, rkhunter, nethogs: nethogs venet0

Script

screenfetch
./ps_mem.py (Cek RAM)
./speedtest_cli.py --share (VPS Speed Test)
./bench-network.sh (VPS Performance Benchmark)
./user-login.sh (User Login Monitor)
./user-expired.sh (Auto Lock Expired Users every 0000 Hrs)
./user-list.sh (View Registered Users)
sh dropmon [port] e.g: sh dropmon 443

Fitur lain

Webmin : http://IPVPS:10000/
vnstat : http://IPVPS:81/vnstat/ (Cek Bandwith)
MRTG : http://IPVPS:81/mrtg/
Timezone : Asia/Singapore (GMT +8)
Fail2Ban : [on]
IPv6 : [off]

===========================================

DAILY VPS AUTO REBOOT

===========================================
