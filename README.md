# worm
auto script debian 7

wget https://raw.githubusercontent.com/anggasa/worm/master/debian7.sh
bash debian7.sh

Autoscript Include:
-------



Service
-------
OpenSSH : 22, 143  
Dropbear : 443, 110,2017  
Squid3 : 80, 8080 (limit to IP SSH)  
badvpn : badvpn-udpgw port 7300  
nginx : 82  

Tools
-----
axel, bmon, htop, iftop, mtr, rkhunter, nethogs: nethogs venet0

Script
------
screenfetch  
./ps_mem.py (Cek RAM)  
./speedtest_cli.py --share (Speed Test VPS)  
./bench-network.sh (Cek Kualitas VPS)  
./user-login.sh (Monitoring User Login)  
./user-expired.sh (Auto Lock User Expire tiap jam 00:00)  
./user-list.sh (Melihat Daftar User)  
./userlimit.sh 1 (max login 1 akun ssh)
./userlimit.sh 2 (max login 2 akun ssh)
sh dropmon [port] contoh: sh dropmon 443  

Fitur lain
----------
Webmin : http://IPVPS:10000/  
vnstat : http://IPVPS:81/vnstat/ (Cek Bandwith)  
MRTG : http://IPVPS:81/mrtg/  
Timezone : Asia/Jakarta (GMT +7)  
Fail2Ban : [on]  
IPv6 : [off]  

===========================================

VPS AUTO REBOOT TIAP 1 HARI

===========================================
Join Group:https://www.facebook.com/groups/1863177667292579/
