### SET - 11 

  

1\. DHCP server is configured on a routerโ€s ether1 interface. IP address 192.168.0.100/24 is assigned to the interface. Possible IP pools, that can be used by this DHCP server, are:

a. 192.168.0.1-192.168.0.255

b. 192.169.0.1-192.169.0.254

c. 192.168.0.1-192.168.0.14

d. 192.168.0.1-192.168.0.99,192.168.0.101-192.168.0.254

2\. Collisions are possible in full-duplex Ethernet networksTrue

False 

  

3\. What is possible with Netinstall?

a. MikroTikRouterOS reinstall

b. MikroTikRouterOS configuration reset

c. MikroTikRouterOS password reset with saving router's configuration

4\. Action=redirect allows you to make

a. Transparent DNS Cache

b. Enable Local Service

c. Forward DNS to another device IP address

d. Transparent HTTP Proxy

5\. Which software version can be installed onto the following RouterBoard types?

a. routeros-mipsle-x.xx.npk on RB133

b. routeros-x86-x.xx.npk on a RB1100

c. routeros-mipsbe-x.xx.npk on a RB433

d. routeros-powerpc-x.xx.npk on a RB333

e. routeros-mipsbe-x.xx.npk on a RB133

6\. What does the firewall action "Redirect" do? Select all true statements.  

a. Redirects a packet to a specified IP

b. Redirects a packet to a specified port on a host in the network

c. Redirects a packet to a specified port on the router

d. Redirects a packet to the router

7\. What does this simple queue do (check the image)?

a. Queue limits host 192.168.1.10 download data rate to one megabit per second.

b. Queue guarantees download data rate of one megabit per second for host 192.168.1.10

c. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10

d. Queue limits host 192.168.1.10 upload data rate to one megabit per second.

8\. What wireless modes can be used in a WDS setup?

a. bridge

b. nstreme-dual-slave

c. station-wds

d. ap-bridge

e. station

9\. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.

a. kind=pcqpcq-limit=256000 pcq-classifier=src-address

b. kind=pcqpcq-limit=1256000 pcq-classifier=dst-address

c. kind=pcqpcq-limit=5000000 pcq-classifier=dst-address

d. kind=pcqpcq-limit=256000 pcq-classifier=dst-address

e. kind=pcqpcq-limit=5000000 pcq-classifier=src-address

10\. Firewall NAT rules process only the first packet of each connection.

11\. Select all the RouterOS software packages required for configuring a wireless AP

a. wireless

b. advanced-tools

c. dhcp

d. routing

e. system

12\. Router OS can set vlan-id value from - to : 

a. 1-2048

b. 1-4096

c. 1-2049

d. 1-4095

13\. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package: 

a. none

b. advanced-tools

c. dhcp

d. routing

14\. Please select valid scan-list values in interface wireless configuration:

a. 5540,5560,5620+5700

b. 5640~5680

c. 5560,5620-5700

d. default,5560,5600,5660-5700

15\. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?

a. Yes

b. No

16\. What configuration is added by /ip hotspot setup command? (select all that apply)

a. /queue tree

b. /ip hotspot walled-garden

c. /ipdhcp-server

d. /ip hotspot user

e. /ip service

17\. Mark all correct answers: destination NAT will take place...

a. after ip firewall filter, chain forward

b. before ip firewall filter, chain forward

c. before routing decision

d. after routing decision

18\. It is possible to access MikroTik Graphs on a different port than HTTP port 80.

a. Yes

b. No

19\. HotSpot is required on the interfaces ether2, ether3, wlan1 (in ap-bridge mode).

These interfaces are bridged in the bridge1 interface.

Which interface should the HotSpot server be configured on?

a. On wlan1 interface

b. On ether3 interface

c. On bridge1 interface

d. On ether2 interface

20\. Using wireless connect-list itโ€s possible to prioritize connection to one Access Point over another Access Point by changing the order of the entries.

  

a.False

b. True

  

21\. MikroTik proxy features are:

a. HTTP caching

b. POP3 caching

c. SMTP caching

d. FTP caching

e. DNS name filtering

22\. Which computers would be able to communicate directly (without any routers involved)

a. 192.168.0.5/26 and 192.168.0.100

b. 192.168.17.15/29 and 192.168.17.20/28

c. 10.10.0.17/22 and 10.10.1.30/23

d. 10.5.5.1/24 and 10.5.5.100/25

23\. Is it possible to have PPTP Client and PPTP server on one MikroTik router at the same time?

a. Yes/ True

b. No/ False

24\. Which default route will be active?

  

/ip route

add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1

add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2  

a. Route via gateway 1.1.1.1

b. Route via gateway 2.2.2.2

25\. You can not use OSPF and RIP routing protocols simultaneously on the RouterOS.

  

a. Yes/ True

b. No/ False
