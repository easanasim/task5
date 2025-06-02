# task5
when I captured my network traffic I found different types of protocols are used.


 1.ARP (Address resolution protocol)
 
   It is used to find MAC address of an IP address in a LAN.
   ARP request look like
   "Who has 192.168.43.23? Tell 192.168.43.1"
   In data link layer, devices are communicating using MAC addresses.
   Before sending packets our system checks its arp cache. if mac missing , system broadcasts arp request.
   Then the device with the ip address sents arp response with the mac address.

2. TCP (Transmission control protocol)
   
   TCP is used for reliable data transfer.
   SYN,SYN-ACK,ACK flags are used to create three way handshake.

3. TLSv1.3 (Transport layer security)
   
   This protocol encrypt the data after handshakes.
   "TLSv1.3	1372	Application Data, Application Data" is an example.
   
4. HTTP(Hypertext tranfer protocol)
   
   It is used for tranfering webdata over the internet.
   GET, POST, PUT are the requsets used in http.
   for example:GET /success.txt?ipv4 HTTP/1.1 
   
