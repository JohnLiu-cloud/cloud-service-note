Creator MQTT Services.(I use Raspberry pi )
  Down: https://ubuntu.com/download/iot
  
Install Mosquitto and Creator
  sudo add-apt-repository ppa:mosquitto-dev/mosquitto-ppa
  sudo apt-get update
  sudo apt-get install mosquitto-clients
  sudo apt-get install mosquitto
  [
    Window Test:
    Install mosquitto and OpenSSL.
    Cmd:
    mosquitto_sub -h 113.116.179.xx -t tp1/test
    mosquitto_pub -h 113.116.179.xx -t tp1/test -m Hello
  ]

Open public network 

View public IP
  Mode A:
  https://www.cman.jp/network/support/go_access.cgi
  Mode B:
  Access the router to find public IP.

Get service IP(I use Raspberry pi )

DMZ
  Access the router to find DMZ.
  Enter service IP(I use Raspberry pi) to DMZ.