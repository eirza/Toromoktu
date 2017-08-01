# Toromoktu_Debian7

### Auto Install Script For VPS Debian7 - www.twitter.com/eirza

	wget https://github.com/eirza/Toromoktu/raw/master/debian7.sh
	bash debian7.sh

## Autoscript Include:

### Services

* OpenSSH : 22, 143
* Dropbear : 443, 110, 109
* Squid3 : 80, 8080 (limit to IP SSH)
* badvpn : badvpn-udpgw port 7300

### Tools

axel, bmon, htop, iftop, mtr, rkhunter, nethogs: nethogs venet0

### Script

	screenfetch
	./ps_mem.py (RAM Check)
	./speedtest_cli.py --share (VPS Speed Test)
	./bench-network.sh (VPS Performance Benchmark)
	./user-login.sh (User Login Monitor)
	./user-expired.sh (Auto Lock Expired Users every 0000 Hrs)
	./user-list.sh (View Registered Users)
	sh dropmon [port]

### Other Features

* Webmin : http://IPVPS:10000/
* vnstat : http://IPVPS:81/vnstat/ (Bandwith Check)
* MRTG : http://IPVPS:81/mrtg/
* Timezone : Asia/Singapore (GMT +8)
* Fail2Ban : [on]
* IPv6 : [off]

**_DAILY VPS AUTO REBOOT_**
