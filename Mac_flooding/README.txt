Trang: 889-890
Máy:
mục tiêu: Windows 8.1 ip: 192.168.3.116
tấn công: Kali linux 2021 ip: 192.168.3.113

Bước 1: cài đặt dniff trên kali
sudo apt install dsniff
chạy hai máy ảo

Bước 2:
khởi động wireshark trên máy mục tiêu Windows
quan sát
Bước 3:
Khởi động wireshark trên máy tấn công
quan sát
Bước 4:
tấn công 
hai cách
tấn công không chỉ định
macof -i eth0 -n 10

tấn công chỉ định
macof -i eth0 -d <địa_chỉ_IP_máy_mục_tiêu>

Quan sát giá trị Ethernet II tại các gói lọc theo protocol IPv4
