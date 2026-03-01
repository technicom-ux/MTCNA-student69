 SET - 4 

  

1\. You have a router with configuration

\- Public IP :202.168.125.45/24

\- Default gateway:202.168.125.1

\- DNS server: 248.115.148.136, 248.115.148.137

\- Local IP: 192.168.2.1/24

Mark the correct configuration on client PC to access to the Internet

a. IP:192.168.0.1/24 gateway:192.168.2.1

b. IP:192.168.2.253/24 gateway:202.168.0.1

c. IP:192.168.1.223/24 gateway:248.115.148.136

d. IP:192.168.2.115/24 gateway: 192.168.2.1

e. IP:192.168.2.2/24 gateway:202.168.125.45

  

2\. On the advanced menu of the wireless setup there is a parameter called “Area”, it works directly with:

a. Connect List

b. Access List

c. None of these

d. Security Profile

  

3\. What menus should be used to allow certain websites to be accessed from behind a hotspot interface, without client authentication

a. ip hotspot ip-binding

b. ip hotspot profile

c. ip hotspot walled-garden

d. ip hotspot walled-garden ip

  

4\. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.

a. kind=pcq pcq-limit=1256000 pcq-classifier=dst-address

b. kind=pcq pcq-limit=256000 pcq-classifier=dst-address

c. kind=pcq pcq-limit=5000000 pcq-classifier=src-address

d. kind=pcq pcq-limit=256000 pcq-classifier=src-address

e. kind=pcq pcq-limit=5000000 pcq-classifier=dst-address

  

5\. Which of the following is true for connection tracking

a. Enabling connection tracking reduces CPU usage in RouterOS

b. Connection tracking must be enabled for firewall to be effective

c. Connection tracking must be enable for NAT’ed network

d. Disable connection tracking for mangle to work

  

6\. Which of these are possible solutions to bridge two networks over a wireless link:

a. Both devices in AP mode and enable WDS mode

b. One device in AP mode, another one in station-pseudobridge-clone

c. One device in AP mode, another one in station-pseudobridge

d. One device in AP mode, another one in station

  

7\. When backing up your router by using the ‘Export’ command, the following happens:

a. Winbox usernames and passwords are backed up

b. The Export file can be edited with a standard text editor after its creation

c. You are requested to give the export file a name

  

8\. You need to reboot a RouterBoard after importing a previously exported rsc file to activate the new configuration.

True

False

  

9\. It is impossible to disable user “admin” at the menu “/user”

True

False

  

10\. If a packet comes to a router and starts a new, previously unseen connection, which connection state would be applied to it?

a. no connection state would be applied to such packet

b. new

c. unknown

d. invalid

e. established

  

11\. We have two radio cards in a point-to-point link with settings:

Card Nr 1.: mode=ap-bridge ssid=”office”

frequency=2447 band=2.4ghz-b/g default-authentication=yes default-forwarding=yes security-profile=wpa

Card Nr 2.: mode=station ssid=”office”

frequency=2412 band=2.4ghz-b/g default-authentication=yes default-forwarding=yes security-profile=wpa2

Is Card Nr2. able to connect to Card Nr 1.?

a. Yes, if Nstreme is enabled or disabled on both

b. Yes, when security profile settings are compatible with each other and Nstreme is enabled or disabled on both

c. No, because of the different frequencies

d. No, because of the different security profiles

  

12\. If you need to make sure that one computer in your HotSpot network can access the Internet without HotSpot authentication, which menu allows you to do this?

a. Walled-garden IP

b. Walled-garden

c. Users

d. IP bindings

  

13\. Consider the following network diagram. In R1, you have the following configuration:

/ip route

add dst-address=192.168.1.0/24 gateway=192.168.99.2

/ip firewall nat

add chain=srcnat out-interface=Ether1 action=masquerade

  

On R2, if you wish to prevent all access to a server located at 192.168.1.10 from LAN1 devices, which of the following rules would be needed?

a. /ip firewall filter add chain=forward src-address=192.168.99.1 dst-address=192.168.1.10 action=drop

b. /ip firewall filter add chain=input src-address=192.168.99.1 dst-address=192.168.1.10 action=drop

c. /ip firewall nat add chain=dstnat src-address=192.168.99.1 dst-address=192.168.1.10 action=drop

d. /ip firewall filter add chain=forward src-address=192.168.0.0/24 dst-address=192.168.1.10 action=drop

  

14\. What is the default protocol/port of (secure) winbox?

a. UDP/5678

b. TCP/8291

c. TCP/22

d. TCP/8080

  

15\. Mark the queue types that are available in RouterOS

a. SFQ – Stochastic Fairness Queuing

b. DRR – Deficit Round Robin

c. FIFO – First In First Out (for Bytes or for Packets)

d. LIFO – Last In First Out

e. PCQ – Per Connection Queuing

f. RED – Random Early Detect (or Drop)

  

16\. A network ready device is directly connected to a MikroTik RouterBOARD 750 with a correct U.T.P. RJ45 functioning cable. The device is configured with an IPv4 address of 192.168.100.70 using a subnet mask of 255.255.255.252. What will be a valid IPv4 address for the RouterBOARD 750 for a successful connection to the device?

a. 192.168.100.70/255.255.255.252

b. 192.168.100.69/255.255.255.252

c. 192.168.100.71/255.255.255.252

d. 192.168.100.68/255.255.255.252

  

17\. How many usable IP addresses are there in a 23-bit (255.255.254.0) subnet?

a. 512

b. 510

c. 508

d. 254

  

18\. Is ARP used in the IPv6 protocol ?

True

False

  

19\. Which of the following protocols / port s are used for SNMP. (Simple Network Managemnt Protocol)

a. TCP 162

b. UDP 162

c. UDP 161

d. TCP 25

e. TCP 123

f. TCP 161

  

20\. Select which of the following are ‘Public IP addresses’:

a. 192.168.0.1

b. 172.168.254.2

c. 172.28.73.21

d. 10.110.50.37

e. 11.63.72.21

  

21\. If ARP=reply-only is enabled on one router interface, router can add dynamic ARP entries for the particular interface.

False

True

  

22\. MAC layer by OSI model is also known as

a. Layer 3

b. Layer 7

c. Layer 1

d. Layer 2

e. Layer 6

  

23\. Select valid MAC-address

a. G2:60:CF:21:99:H0

b. 00:00:5E:80:EE:B0

c. AEC8:21F1:AA44:54FF:1111:DDAE:0212:1201

d. 192.168.0.0/16

  

24\. Which computers would be able to communicate directly (without any routers involved)

a. 192.168.17.15/29 and 192.168.17.20/28

b. 192.168.0.5/26 and 192.168.0.100

c. 10.5.5.1/24 and 10.5.5.100/25

d. 10.10.0.17/22 and 10.10.1.30/2
