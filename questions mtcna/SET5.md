
------------------------------------------------------------------------------------- SET - 5 -------------------------------------------------------------------------------------


1. What kind of users are listed in the Secrets window of the PPP menu?

a. hotspot users
b. wireless users
c. l2tp users
d. pptp users
e. pppoe users
f. winbox users


2. What configuration is added by /ip hotspot setup command? (select all that apply)
a. /ip service
b. /ip hotspot user
c. /ip hotspot walled-garden
d. /ip dhcp-server
e. /queue tree 


3. Using wireless connect-list it’s possible to prioritize connection to one Access Point over another Access Point by changing the order of the entries. 

a.False
b. True


4. If ARP=reply-only is configured on an interface, what will this interface do
a. Add new MAC addresses in /ip arp list
b. Accept all MAC-addresses listed in /ip arp as static entries
c. Add new IP addresses in /ip arp list
d. Accept all IP addresses listed in /ip arp as static entries
e. Accept all IP/MAC combinations listed in /ip arp as static entries


5. Router A and B are both running as PPPoE servers on different broadcast domains of your network. It is possible to set Router A to use "/ppp secret" accounts from Router B to authenticate PPPoE customers.
a. False
b. True


6. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?

a. Yes

b. No


7. What can be used as ’target-address’ in the simple queue?
a. client’s address
b. client’s MAC address
c. server’s address
d. address list name


8. Which is the default port of IP-Winbox?
a. TCP 8291
b. TCP 80
c. UDP 8291
d. TCP 8192


9. MikroTik RouterOS is sending logs to an external syslog server. Which protocol and port is used by RouterOS for sending logs (by default)?
a. UDP 514
b. UDP 21
c. UDP 113
d. TCP 110


10. Which route will be used to reach host 192.168.1.55?

/ip route
add disabled=no distance=1 dst-address=192.168.1.0/24 gateway=1.1.1.1
add disabled=no distance=1 dst-address=192.168.1.0/25 gateway=2.2.2.2
add disabled=no distance=1 dst-address=192.168.0.0/16 gateway=3.3.3.3
 

a. Route via gateway 1.1.1.1

b. Route via gateway 3.3.3.3 

c. Route via gateway 2.2.2.2


11. In which situations can Netinstall NOT be used to install a RouterBOARD?
a. The router does not have an operating system
b. The router is connected only to a wireless network
c. You do not know the password of the router
d. The router is connected only to a secondary Ethernet port


12. To use masquerade, you need to specify
a. action=accept, out-interface, chain=src-nat
b. action=masquerade, out-interface, chain=src-nat
c. action=masquerade, in-interface, chain=src-nat
d. action=masquerade, out-interface, chain=dst-nat


13. Please select valid scan-list values in interface wireless configuration:
a. 5560,5620-5700
b. 5640~5680
c. default,5560,5600,5660-5700
d. 5540,5560,5620+5700


14. When adding a static route, you must always ensure that you add both the gateway and the interface.
False
True


15. You would like to allow multiple logins with one user name on a HotSpot server. How should this be configured?
a. Set "Shared Users" option at /ip hotspot user profile
b. It's not possible
c. Set "Shared Users" option at /ip hotspot
d. Set "only-one=no' at /ip hotspot


16. In which order are the entries in Access List and Connect List processed?
a. In sequence order
b. In a random order
c. By Signal Strength Range
d. By interface name


17. What protocol does ping use?
a. TCP
b. ICMP
c. UDP
d. ARP


18. Is it possible for a client to get an IP address but no gateway after a successful DHCP request?
a. False
b. True


19. Firewall configuration is the following:
1) /ip firewall filter add chain=input protocol=icmp action=jump jump-target=ICMP
2) /ip firewall filter add chain=input protocol=icmp action=log log-prefix=ICMP-DENY
3) /ip firewall filter add chain=input protocol=icmp action=drop
4) /ip firewall filter add chain=ICMP protocol=icmp action=log log-prefix=JUMP-ICMP-DENY
5) /ip firewall filter add chain=ICMP protocol=icmp action=drop

Client sends "ping" to router. What will the router do?

a. Router will drop the packet at ICMP (jump) chain drop rule (5th rule)
b. Router will log it with prefix: ICMP-DENY
c. Router will drop the packet at the Input drop rule (3rd rule)
d. Router will log it with prefix: JUMP-ICMP-DENY

20. /ip firewall nat
add chain=dstnat in-interface=ether1 protocol=tcp dst-port=3389 action=dst-nat to-address=192.168.1.2 to-ports=81

The command shown above:
a. Adds IP address 192.168.1.2 to the interface ether1
b. Forwards any TCP traffic incoming through ether1 port 3389 to the port 81 of the internal host 192.168.1.2
c. Forwards all TCP traffic from 192.168.1.2 to port 81 of the interface ether1
d. Forwards any TCP traffic incoming through ether1 port 81 to the port 3389 of the internal host 192.168.1.2


21. While troubleshooting a network from inside the network, you discover that you can ping the gateway reliably, but you cannot browse the Internet. Skype, however, works flawlessly. What is the most likely issue?
a. DNS is not available
b. The computer did not get an IP address
c. Network card and/or cable is not working
d. Masquerading rule is not applied

22. What is marked by connection-state=established matcher?
a. Packet begins a new TCP connection
b. Packet does not correspond to any known connection
c. Packet belongs to an existing connection,for example a reply packet or a packet which belongs to already replied connection
d. Packet is related to, but not part of an existing connection


23. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

a. routing
b. none
c. dhcp
d. advanced-tools


24. You are planning a migration from a wireless link using 802.11a on 5GHz (with no nstreme) to one using Nv2 on 5GHz. When you change the AP from 802.11a to Nv2, you do not wish a client to disconnect for more than a few seconds during the upgrade.

Assuming the client is capable of operating with Nv2 (correct hardware, correct encryption key and ROS version), which setting(s) for 'wireless-protocol' should be enabled on the client so that the client can auto-detect the protocol used by the AP and still make connection with 802.11a or Nv2 : (select all that apply)
a. Nv2
b. nv2-nstreme-802.11
c. any
d. unspecified

25. What does this simple queue do (check the image)?
a. Queue limits host 192.168.1.10 upload data rate to one megabit per second.
b. Queue guarantees download data rate of one megabit per second for host 192.168.1.10
c. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10
d. Queue limits host 192.168.1.10 download data rate to one megabit per second.
