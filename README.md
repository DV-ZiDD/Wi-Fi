# Wi-Fi_-
WiFi suspension bridge (සංගිලි පාලම) using NodeMcu ( no need separate wifi router )
use "DOS" command to uload this bin file to NodeMcu : 

C:\(FolderXXX)/esptool.exe -vv -cd nodemcu -cb 115200 -cp COM12 -ca 0x00000 -cf PIPE_ALGOBEL.bin 


#example : 
C:\Users\esptool.exe -vv -cd nodemcu -cb 115200 -cp COM12 -ca 0x00000 -cf C:\Users\PIPIE_ALGOBEL.bin 

SSID : PIPE_ALGOBEL
* Please contact info@algobel.com for password 

Authmode : AUTH_WPA_WPA2_PSK
Soft-AP IP address = 192.168.4.1
Subnet mask in bites: 24
Subnet details :
Usable IP addresses:  192.168.4.2 - 192.168.4.254
Subnet (255.255.255.0)
Gateway/Broadcast (192.168.4.255)
