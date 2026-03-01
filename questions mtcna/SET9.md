### SET - 9

1\. Is it possible to have PPTP Client and PPTP server on one MikroTik router at the same time?

a. Yes/ True

b. No/ False

  

2\. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

a. dhcp

b. none

c. advanced-tools

d. routing

  

3\. What could be monitored by Torch?

a. Dst. Address

b. Dst. Port

c. None of the above is correct

d. Src. Address

e. Vlan ID

f. Protocol

  

4\. The highest queue priority is

a. 16

b. 8

c. 1

d. 256

  

5\. Wireless clients (mode=station) will work properly if bridged to ethernet

  

  

6\. Which of the following Routes statuses are possible?

a. S = Static

b. C = Connected

c. D = Drop

d. A = Active

  

7\. You have to connect to a RouterBOARD without any previous configuration. Select all possibilities to connect and do some basic configuration

a. Telnet

b. Attach monitor/keyboard

c. MAC-Winbox

d. Serial Connection

  

8\. A network ready device is directly connected to a MikroTik RouterBOARD 750 with a correct U.T.P. RJ45 functioning cable. The device is configured with an IPv4 address of 192.168.100.70 using a subnet mask of 255.255.255.252. What will be a valid IPv4 address for the RouterBOARD 750 for a successful connection to the device?

a. 192.168.100.70/255.255.255.252

b. 192.168.100.68/255.255.255.252

c. 192.168.100.69/255.255.255.252

d. 192.168.100.71/255.255.255.252

  

9\. Netinstall can be used to

a. Install package for different hardware architecture

b. Reinstall software without losing licence

c. Keep configuration, but reset a lost admin password

d. Install different software version (upgrade or downgrade)

  

10\. Consider the following network diagram. In R1, you have the following configuration:

/ip route

add dst-address=192.168.1.0/24 gateway=192.168.99.2

  

/ip firewall nat

add chain=srcnat out-interface=Ether1 action=masquerade

  

On R2, if you wish to prevent all access to a server located at 192.168.1.10 from LAN1 devices, which of the following rules would be needed?

a. /ip firewall nat add chain=dstnat src-address=192.168.99.1 dst-address=192.168.1.10 action=drop

b. /ip firewall filter add chain=input src-address=192.168.99.1 dst-address=192.168.1.10 action=drop

c. /ip firewall filter add chain=forward src-address=192.168.0.0/24 dst-address=192.168.1.10 action=drop

d. /ip firewall filter add chain=forward src-address=192.168.99.1 dst-address=192.168.1.10 action=drop

  

11\. /interface wireless access-list is used for

a. Contains the security profiles settings

b. Handles a list of Client's MAC Address to permit/deny connection to AP

c. Shows a list of Client's MAC Address that are already registered at AP

d. Authenticate Hotspot users

  

12\. To make the masquerading of the network 192.168.0.0/24, configured on the interface Ether1, you should add rule

a. /ip firewall nat add chain=srcnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade

b. /ip firewall nat add chain=dstnat in-interface=ether1 src-address=192.168.0.0/24 action=masquerade

c. /ip firewall nat add chain=dstnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade

d. /ip firewall nat add chain=srcnat src-address=192.168.0.0/24 action=masquerade

  

13\. RouterOS DHCP server is able to send any DHCP options (specified in RFCs) to DHCP clients

a. Yes

b. No

  

14\. You would like to allow multiple logins with one user name on a HotSpot server. How should this be configured?

a. Set "only-one=no' at /ip hotspot

b. Set "Shared Users" option at /ip hotspot user profile

c. It's not possible

d. Set "Shared Users" option at /ip hotspot

  

15\. You are planning a migration from a wireless link using 802.11a on 5GHz (with no nstreme) to one using Nv2 on 5GHz. When you change the AP from 802.11a to Nv2, you do not wish a client to disconnect for more than a few seconds during the upgrade.

  

Assuming the client is capable of operating with Nv2 (correct hardware, correct encryption key and ROS version), which setting(s) for 'wireless-protocol' should be enabled on the client so that the client can auto-detect the protocol used by the AP and still make connection with 802.11a or Nv2 : (select all that apply)

a. unspecified

b. any

c. Nv2

d. nv2-nstreme-802.11

  

16\. Using wireless connect-list itโ€s possible to prioritize connection to one Access Point over another Access Point by changing the order of the entries.

  

a.False

b. True

  

  

17\. The total-max-limit under Simple Queues will limit the combined upload and download of the target-address of your simple queue.

  

a. Yes

b. No

  

18\. Two mangle rules defining different mangle marks for the same traffic type, will make it have both mangle marks.

a. Yes

b. No

  

19\. Where are HotSpot authorized clients shown?

a. /ip hotspot host

b. /ip hotspot active

c. /ip hotspot

d. /ip hotspot user

  

20\. A PC with IP 192.168.1.2 can access internet, and static ARP has been set for that IP address on gateway. When the PC Ethernet card failed, the user change it with a new card and set the same IP for it.

  

  

What else should be done?

a. Old static ARP entry on gateway has to be updated for the new card

b. MAC-address of the new card has to be changed to MAC address of old card

c. Another IP has to be added for Internet access

d. Nothing - it will work as before

  

21\. Is it possible for a client to get an IP address but no gateway after a successful DHCP request?

  

a. False

b. True

  

  

22\. Which RouterOS packages should be installed on router for SSH server support?

a. advanced-tools

b. system

c. ssh

d. security

  

23\. There is an HTTP server 10.0.0.1 in your private network. You have made a DST-NAT rule that sends all HTTP traffic received on your router's address 80.232.50.100 to this server. If you make a firewall rule on the router to disallow address 159.148.20.30 to communicate with the server, how would you identify this communication in this rule?

a. src-address=159.148.20.30 dst-address=80.232.50.100

b. src-address=159.148.20.30 dst-address=10.0.0.1

c. src-address=80.232.50.100 dst-address=10.0.0.1

d. src-address=80.232.50.100 dst-address=159.148.20.30

  

24\. Router A and B are both running as PPPoE servers on different broadcast domains of your network. It is possible to set Router A to use "/ppp secret" accounts from Router B to authenticate PPPoE customers.a. False

b. True

  

  

25\. Define a routing loop (choose the most precise description)

a. situation where the packet is routed through the same sequence of routers until the TTL expires

b. Situation where the packet does not reach it\\'s destination

c. situation where the TTL of the packet expires

d. situation where the packet is routed through the same router twice
