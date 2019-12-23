#!/bin/bash
version 1.0

clear
figlet INSTALLER4 | lolcat
echo "_______________________________________

# Name    : DoneX5
# Contact : xdone29@gmail.com
# Team    : Cyber Pembela Palestina

_______________________________________" | lolcat

sleep 2

echo "[1] Red Hawk
[2]. V Bug
[3]. SQL MAP
[4]. N Map
[5]. AirCrack-Ng
[&]. Exit" | lolcat
echo " [*]. Pilih Nomor :   " | lolcat
read nomor

if  [ $nomor  = 1  ]  || [ $nomor = 01 ]
then
clear
pkg install php
pkg install curl
git clone https://github.com/Tuhinshubhra/RED_HAWK
cd RED_HAWK
php rhawk.php
fi

if [ $nomor = 2 ] || [ $nomor = 02 ]
then 
clear
apt update && apt upgrade 
pkg install git
pkg install python2
git clone https://github.com/Junior60/vbug/
cd vbug
python2 vbug.py
fi

if [ $nomor = 3 ] || [ $nomor = 03 ]
then
clear
pkg update && pkg upgrade 
pkg install git && pkg install python2
git clone https://github.com/sqlmapproject/sqlmap
cd sqlmap
python2 sqlmap.py
fi

if [ $nomor = 4 ] || [ $nomor = 04 ]
then 
clear
apt update && apt upgrade
apt install nmap
fi

if [ $nomor = 5 ] || [ $nomor = 05 ]
then
clear
apt-get install git
apt-get install build-essential
git clone https://github.com/aircrack-ng/aircrack-ng.git
cd aircrack-ng
apt-get install libssl-dev libpcre3-dev libsqlite3-dev libnl-3-dev libnl-genl-3-dev pkg-config-y
make
make install
fi
