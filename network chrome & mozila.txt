@echo off
echo Membuka Chrome via Jaringan WiFi...
start "" forcebindip -i 172.20.200.101 "C:\Users\louis\AppData\Local\Google\Chrome\Application\chrome.exe"

echo Membuka Firefox via Jaringan Kabel LAN...
start "" forcebindip -i 192.168.2.12 "C:\Program Files\Mozilla Firefox\firefox.exe"

echo Selesai! Kedua browser siap digunakan dengan jaringan terpisah.
timeout /t 3
exit
