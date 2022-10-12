#### UNTUK BYPASS HOTSPOT DI LAPTOP UNTUK GUNA DATA SELAIN DARI HOTSPOT DI HANDPHONE SENDIRI 

1. Buka hotspot di handfon
2. Di laptop/pc, connect hotspot yang dibuka
3. Di laptop/pc, click start then type cmd, run as administrator 
   ![image](https://user-images.githubusercontent.com/92897556/195276075-75a42d09-301d-4b7e-9d8f-c5890fc4f0f8.png)
4. type "netsh int ipv4 set glob defaultcurhoplimit=65" di cmd 
5. tekan enter dan akan keluar ok
   ![image](https://user-images.githubusercontent.com/92897556/195275785-3a2f83fd-ce66-4e0b-a7c5-68780d3fc0d7.png)
6. dah bypass


-------------------------------------------------------------------------


#### INFORMATION


Using hotspot data from your mobile phone on your laptop/computer

1. netsh int ipv4 set glob defaultcurhoplimit=65
2. netsh int ipv6 set glob defaultcurhoplimit=65


Use your laptop as a Wi-Fi repeater:

1. netsh int ipv4 set glob defaultcurhoplimit=64
2. netsh int ipv6 set glob defaultcurhoplimit=64


Set it to default:

1. netsh int ipv4 set glob defaultcurhoplimit=128
2. netsh int ipv6 set glob defaultcurhoplimit=128


*defaultcurhoplimit - Default HopLimit of packets sent*

**************************************************************************



