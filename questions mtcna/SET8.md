 SET - 8 

1\. log messages are stored on disk by default

  

  

2\. Router OS can set vlan-id value from - to :

a. 1-2048

b. 1-2049

c. 1-4096

d. 1-4095

  

3\. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?

a. Yes

b. No

  

4\. Which of the following is true for connection tracking

a. Enabling connection tracking reduces CPU usage in RouterOS

b. Disable connection tracking for mangle to work

c. Connection tracking must be enable for NAT'ed network

d. Connection tracking must be enabled for firewall to be effective

  

5\. What letters appear next to a route, which is automatically created by RouterOS when user adds a valid address to an active interface?

a. I

b. S

c. C

d. D

e. A

  

6\. Which is the default port of IP-Winbox?

a. TCP 8192

b. UDP 8291

c. TCP 8291

d. TCP 80

  

7\. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.

a. kind=pcqpcq-limit=5000000 pcq-classifier=dst-address

b. kind=pcqpcq-limit=256000 pcq-classifier=src-address

c. kind=pcqpcq-limit=256000 pcq-classifier=dst-address

d. kind=pcqpcq-limit=5000000 pcq-classifier=src-address

e. kind=pcqpcq-limit=1256000 pcq-classifier=dst-address

  

8\. To limit wireless access for your HotSpot users

a. Create MAC Address restriction on PPP user login

b. Create IP Address restriction in the Wireless Access List

c. Create MAC Address restriction on HotSpot user login

d. Create MAC Address restriction in the Wireless Access List

  

9\. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

a. routing

b. advanced-tools

c. none

d. dhcp

  

10\. To avoid looping on this network, you need to:

a. Enable RSTP on AP1 and AP3

b. Enable RSTP on AP1

c. Enable RSTP on AP1, AP2 and AP3

  

11\. To make the masquerading of the network 192.168.0.0/24, configured on the interface Ether1, you should add rule

a. /ip firewall nat add chain=dstnat in-interface=ether1 src-address=192.168.0.0/24 action=masquerade

b. /ip firewall nat add chain=srcnatsrc-address=192.168.0.0/24 action=masquerade

c. /ip firewall nat add chain=dstnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade

d. /ip firewall nat add chain=srcnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade

  

12\. On the advanced menu of the wireless setup there is a parameter called "Area", it works directly with:

a. None of these

b. Connect List

c. Access List

d. Security Profile

  

13\. The basic unit of a physical network (OSI Layer 1) is the:

a. Header

b. Bit

c. Byte

d. Frame

  

14\. It is impossible to disable user "admin" at the menu "/user"

  

True

False

  

15.HotSpot is required on the interfaces ether2, ether3, wlan1 (in ap-bridge mode).

These interfaces are bridged in the bridge1 interface.

Which interface should the HotSpot server be configured on?

a. On ether2 interface

b. On ether3 interface

c. On wlan1 interface

d. On bridge1 interface

  

16\. The highest queue priority is

a. 256

b. 1

c. 16

d. 8

  

17\. What is necessary for PPPoE client configuration?

a. Static IP address on PPPoE client interface

b. ip firewall nat masquerade rule

c. Interface (on which PPPoE client is going to work)

  

18\. To be able to do NAT the connection tracking does not need to be enabled.

a. True

b. False

  

19\. Check the allowed input formats for wireless scan-list.

a. 5500,5700

b. 5500-5700

c. 5500/5700

d. 5500 - 5700

e. 5500 5700

  

20\. To connect your MikroTik router to a wireless access point, you have to:

a. Use the same Radio Name

b. Use the same SSID as on accesspoint

c. Use the same Band (5 GHz, 2.4 GHz, ...)

  

21\. Which default route will be active?

/ip route

add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1

add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2

a. Route via gateway 1.1.1.1

b. Route via gateway 2.2.2.2

  

22\. An IP address pool can contain addresses from more than one subnet.

a. True

b. False

  

23\. Is it possible to use the serial port of MikroTik to communicate with an external device connected by null-modem cable?

a. Yes, if port is not being used

b. Yes, when other is a MikroTik router.

c. Yes, it is always possible by /system serial-terminal command.

  

24\. It is required to make a web server on a private LAN visible on the Public Internet. Only the web server port should be visible to the public. Which of the following configuration steps must be met. (select all that apply)

  

a. A route between the NAT Router and the webserver must exist

b. LAN address of the webserver should be routable on the internet

c. in ip firewall NAT there should be a dst-nat between the public ip of the router and the private ip of the webserver

d. Connection Tracking must be enabled on NAT router

e. Public IP address of the webserver must be installed on the NAT Router

  

25\. Collisions are possible in full-duplex Ethernet networks

  

True

False
