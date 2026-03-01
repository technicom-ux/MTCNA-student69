### SET - 10 

  

1\. You start a scan for wireless networks on you access point. What will happen ?

a. All connected clients will disconnect

b. You'll see all connected clients

c. You'll see available frequencies

  

2\. Is action=masquerade allowed in chain=dstnat?

a. no

b. yes

c. yes, but it works only for incoming connections

d. yes, but only if dst-addr is specified

  

3\. Which route will be used to reach host 192.168.1.55?

  

/ip route

add disabled=no distance=1 dst-address=192.168.1.0/24 gateway=1.1.1.1

add disabled=no distance=1 dst-address=192.168.1.0/25 gateway=2.2.2.2

add disabled=no distance=1 dst-address=192.168.0.0/16 gateway=3.3.3.3

a. Route via gateway 2.2.2.2

b. Route via gateway 1.1.1.1

c. Route via gateway 3.3.3.3

  

4\. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?

a. No

b. Yes

  

5\. What is necessary for PPPoE client configuration?

a. ip firewall nat masquerade rule

b. Static IP address on PPPoE client interface

c. Interface (on which PPPoE client is going to work)

  

6\. Mark all correct answers

a. Wireless access-list could allow and deny access to your AP

b. Default-Forwarding could be enabled for a specific clients by wireless access-list

c. /ip firewall filter allows to deny authentication to AP

d. The only way to prevent wireless clients connections - disable wireless interface

  

7\. You want to limit bandwidth for your HotSpot users. HotSpot can create dynamic queues on user login to do the speed limitations.

a. Yes/ True

b. No/ False

  

8\. A routing table has following entries:

  

0 dst-address=10.0.0.0/24 gateway=10.1.5.126

1 dst-address=10.1.5.0/24 gateway=10.1.1.1

2 dst-address=10.1.0.0/24 gateway=25.1.1.1

3 dst-address=10.1.5.0/25 gateway=10.1.1.2

  

Which gateway will be used for a packet with destination address 10.1.5.126?

a. 25.1.1.1

b. 10.1.1.1

c. 10.1.1.2

d. 10.1.5.126

  

9\. Which is the default port of IP-Winbox?

a. TCP 8192

b. TCP 8291

c. TCP 80

d. UDP 8291

  

10\. In case when router login password is lost, it is necessary to reinstall RouterOS or use hardware reset funcion.

a. Yes/ True

b. No/ False

  

11\. On the advanced menu of the wireless setup there is a parameter called "Area", it works directly with:

a. Security Profile

b. Connect List

c. Access List

d. None of these

  

12\. Is it possible that the same IP address is included in multiple address lists and still be used by these multiple address lists?

  

a. Destination NAT rule is required to utilize transparent proxy facility

b. To deny access to a specific website, caching should be enabled

c. Controls domains or servers which are allowed to cache by Proxy

d. Can deny access to a specific domains or servers, but not specific web pages

  

13\. What protocol does ping use?

a. ICMP

b. ARP

c. TCP

d. UDP

  

14\. Which firewall chain should you use to filter clients HTTP traffic going through the router?

a. prerouting

b. output

c. input

d. forward

  

15\. Connection marks are stored in the connection tracking table.

a. Yes/ True

b. No/ False

  

16\. MikroTik RouterOS commands can be run once a day by:

a. /system watchdog

b. /system scheduler

c. /system cron

  

17\. What is term for the hardware coded address found on an interface?

a. FQDN Address

b. MAC Address

c. Interface Address

d. IP Address

  

18\. For user in local ppp secrets/ppp profiles database, it is possible to

a. Allow/deny use of more than one login by this user

b. Allow only pppoe login

c. Allow login by pppoe and pptp, but deny login by l2tp

d. Deny services (like telnet) only for this user or for one group of users

e. Set max values for total transferred bytes (up- and download)

  

19\. You have a DHCP server on your MikroTik router. The IP addresses 10.1.2.2-10.2.2.20 are distributed in the DHCP network. Additionally, 3 static IP address are defined for your servers: 10.1.2.31-10.1.2.33. After a while 20 more IP addresses need to be distributed in the network. Is it possible to distribute the extra IP address without adding another DHCP Server?

  

  

20\. You wish to secure your RouterOS system. You do not want the RouterOS to be discoverable using MNDP or CDP locally. You also want to deny management via the MAC addresses on all interfaces. Select the correct actions to accomplish this.

a. Remove/Disable all interfaces under mac-server telnet

b. Remove/Disable all discovery interfaces

c. Place a proper forward firewall rule to block mac discovery

d. Remove/Disable the Interfaces

e. Place a proper input firewall rule to block mac discovery

f. Remove/Disable all interfaces under mac-Server winbox

g. Add a Deny All input firewall rule

  

21\. What does this simple queue do (check the image)?

a. Queue guarantees download data rate of one megabit per second for host 192.168.1.10

b. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10

c. Queue limits host 192.168.1.10 download data rate to one megabit per second.

d. Queue limits host 192.168.1.10 upload data rate to one megabit per second.

  

22\. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

a. none

b. advanced-tools

c. routing

d. dhcp

  

23\. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.

a. kind=pcq pcq-limit=256000 pcq-classifier=src-address

b. kind=pcq pcq-limit=1256000 pcq-classifier=dst-address

c. kind=pcq pcq-limit=5000000 pcq-classifier=src-address

d. kind=pcq pcq-limit=5000000 pcq-classifier=dst-address

e. kind=pcq pcq-limit=256000 pcq-classifier=dst-address

  

24\. To avoid looping on this network, you need to:

a. Enable RSTP on AP1, AP2 and AP3

b. Enable RSTP on AP1

c. Enable RSTP on AP1 and AP3

  

25\. HotSpot server is installed on the router. All IP-phones are required to have access to outside networks without any HotSpot authentication. Select the configuration options you can use to achieve this setup.

a. /ip hotspot walled-garden ip

b. /ip hotspot service-ports

c. /ip hotspot ip-binding
