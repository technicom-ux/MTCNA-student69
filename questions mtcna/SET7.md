
 SET - 7 


1. Choose correct statements for MikroTik proxy.
a. Destination NAT rule is required to utilize transparent proxy facility
b. To deny access to a specific website, caching should be enabled
c. Controls domains or servers which are allowed to cache by Proxy
d. Can deny access to a specific domains or servers, but not specific web pages

2. Collisions are possible in full-duplex Ethernet networks

True
False

 
3. Which of the following is NOT a valid MAC Address?
a. 13:16:86:53:89:43
b. 80:GF:AA:67:13:5D
c. 88:0C:00:99:5F:EF
d. EA:BA:AA:EE:FF:CB
e. 95:B5:DD:EE:78:8A

4. The default value of 'target-scope' for a static route is:
a. 30
b. 1
c. 10
d. 255

5. Which firewall chain would be used to block a client's MSN traffic on a router?
a. output
b. static
c. input
d. forward

6. Please select valid scan-list values in interface wireless configuration:
a. 5540,5560,5620+5700
b. 5560,5620-5700
c. 5640~5680
d. default,5560,5600,5660-5700

7. You want to limit bandwidth for your HotSpot users. HotSpot can create dynamic queues on user login to do the speed limitations.
a. Yes/ True
b. No/ False

8. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:
a. dhcp
b. none
c. advanced-tools
d. routing

9. You start a scan for wireless networks on you access point. What will happen ?
a. All connected clients will disconnect
b. You'll see all connected clients
c. You'll see available frequencies

10. What kind of users are listed in the "/user" menu?
a. pptp users
b. wireless users
c. hotspot users
d. router users

11. Which is correct masquerade rule for 192.168.0.0/24 network on the router with outgoing interface=ether1?
a. /ip firewall nat add action=masquerade chain=srcnat out-interface=ether1
b. /ip firewall nat add action=masquerade chain=srcnat src-address=192.168.0.0/24
c. /ip firewall nat add action=masquerade out-interface=ether1 chain=dstnat
d. /ip firewall nat add action=masquerade chain=srcnat

12. Which firewall chain should you use to filter ICMP packets from the router itself?
a. input
b. forward
c. postrouting
d. output

13. Which software version can be installed onto the following RouterBoard types?
a. routeros-mipsbe-x.xx.npk on a RB433
b. routeros-powerpc-x.xx.npk on a RB333
c. routeros-mipsle-x.xx.npk on RB133
d. routeros-x86-x.xx.npk on a RB1100
e. routeros-mipsbe-x.xx.npk on a RB133

14. The highest queue priority is
a. 16
b. 8
c. 256
d. 1

15. Firewall configuration is the following:
1) /ip firewall filter add chain=input protocol=icmp action=jump jump-target=ICMP
2) /ip firewall filter add chain=input protocol=icmp action=log log-prefix=ICMP-DENY
3) /ip firewall filter add chain=input protocol=icmp action=drop
4) /ip firewall filter add chain=ICMP protocol=icmp action=log log-prefix=JUMP-ICMP-DENY
5) /ip firewall filter add chain=ICMP protocol=icmp action=drop

Client sends "ping" to router. What will the router do?
a. Router will drop the packet at the Input drop rule (3rd rule)
b. Router will log it with prefix: JUMP-ICMP-DENY
c. Router will drop the packet at ICMP (jump) chain drop rule (5th rule)
d. Router will log it with prefix: ICMP-DENY

16. MikroTik proxy features are:
a. POP3 caching
b. DNS name filtering
c. SMTP caching
d. HTTP caching
e. FTP caching

17. What does this simple queue do (check the image)?
a. Queue limits host 192.168.1.10 download data rate to one megabit per second.
b. Queue limits host 192.168.1.10 upload data rate to one megabit per second.
c. Queue guarantees download data rate of one megabit per second for host 192.16SID="WAN1"mode="ap-bridge" and a VirtualAP with SSID="VAP1" on the router. Is it possibl8.1.10
d. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10

18. You have a wireless interface with Se to use nstreme protocol?
a. Yes, but Nstreme will be used for all SSID assigned for that physical interface
b. Yes, but Nstreme can be used only for SSID=WLAN1.
c. No, Nstreme can not be used on wireless interface if a VirtualAP is on it.
d. Yes, but Nstreme can be used only for SSID=VAP1.

19. /store allows you to save to external disk
a. User-Manager data
b. dude data
c. web-proxy data
d. system configuration

20. /ip route configuration on router,

/ip route add gateway=192.168.0.1
/ip route add dst-address=192.168.1.0/24 gateway=192.168.0.2
/ip route add dst-address=192.168.2.0/24 gateway=192.168.0.3
/ip route add dst-address=192.168.3.0/26 gateway=192.168.0.4

Router needs to send packets to 192.168.3.240. Which gateway will be used?

a. 192.168.0.2
b. 192.168.0.1
c. 192.168.0.3
d. 192.168.0.4

21. What is the meaning of letter "R" on an active session in the menu PPP Active Connections?
a. Running
b. Radius
c. Remote

22. A station can connect to AP if they both use different country regulation settings, but the frequency chosen is allowed in both countries


23. Hotspot ip-binding is used to allow access to remote host specifying the IP address of the remote host.


24. Router has Wireless and Ethernet client interfaces, all client interfaces are bridged.

To create a DHCP service for all clients you must configure DHCP server on
a. every bridge port
b. only on bridge interface
c. Ethernet and wireless interfaces
d. DHCP service is not possible in this setup

25. EoiP is:
a. MikroTik proprietary tunnel protocol
b. Layer-3 tunnel
c. Layer-2 tunnel, that can be bridged

------------------------------------------------------------------------------------- SET - 8 -------------------------------------------------------------------------------------


1. log messages are stored on disk by default


2. Router OS can set vlan-id value from - to :
a. 1-2048
b. 1-2049
c. 1-4096
d. 1-4095

3. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?
a. Yes
b. No

4. Which of the following is true for connection tracking
a. Enabling connection tracking reduces CPU usage in RouterOS
b. Disable connection tracking for mangle to work
c. Connection tracking must be enable for NAT'ed network
d. Connection tracking must be enabled for firewall to be effective

5. What letters appear next to a route, which is automatically created by RouterOS when user adds a valid address to an active interface?
a. I
b. S
c. C
d. D
e. A

6. Which is the default port of IP-Winbox?
a. TCP 8192
b. UDP 8291
c. TCP 8291
d. TCP 80

7. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.
a. kind=pcqpcq-limit=5000000 pcq-classifier=dst-address
b. kind=pcqpcq-limit=256000 pcq-classifier=src-address
c. kind=pcqpcq-limit=256000 pcq-classifier=dst-address
d. kind=pcqpcq-limit=5000000 pcq-classifier=src-address
e. kind=pcqpcq-limit=1256000 pcq-classifier=dst-address

8. To limit wireless access for your HotSpot users
a. Create MAC Address restriction on PPP user login
b. Create IP Address restriction in the Wireless Access List
c. Create MAC Address restriction on HotSpot user login
d. Create MAC Address restriction in the Wireless Access List

9. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:
a. routing
b. advanced-tools
c. none
d. dhcp

10. To avoid looping on this network, you need to:
a. Enable RSTP on AP1 and AP3
b. Enable RSTP on AP1
c. Enable RSTP on AP1, AP2 and AP3

11. To make the masquerading of the network 192.168.0.0/24, configured on the interface Ether1, you should add rule
a. /ip firewall nat add chain=dstnat in-interface=ether1 src-address=192.168.0.0/24 action=masquerade
b. /ip firewall nat add chain=srcnatsrc-address=192.168.0.0/24 action=masquerade
c. /ip firewall nat add chain=dstnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade
d. /ip firewall nat add chain=srcnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade

12. On the advanced menu of the wireless setup there is a parameter called "Area", it works directly with:
a. None of these
b. Connect List
c. Access List
d. Security Profile

13. The basic unit of a physical network (OSI Layer 1) is the:
a. Header
b. Bit
c. Byte
d. Frame

14. It is impossible to disable user "admin" at the menu "/user"

True
False
 

15.HotSpot is required on the interfaces ether2, ether3, wlan1 (in ap-bridge mode).
These interfaces are bridged in the bridge1 interface.
Which interface should the HotSpot server be configured on?
a. On ether2 interface
b. On ether3 interface
c. On wlan1 interface
d. On bridge1 interface

16. The highest queue priority is
a. 256
b. 1
c. 16
d. 8

17. What is necessary for PPPoE client configuration?
a. Static IP address on PPPoE client interface
b. ip firewall nat masquerade rule
c. Interface (on which PPPoE client is going to work)

18. To be able to do NAT the connection tracking does not need to be enabled.
a. True
b. False

19. Check the allowed input formats for wireless scan-list.
a. 5500,5700
b. 5500-5700
c. 5500/5700
d. 5500 - 5700
e. 5500 5700

20. To connect your MikroTik router to a wireless access point, you have to:
a. Use the same Radio Name
b. Use the same SSID as on accesspoint
c. Use the same Band (5 GHz, 2.4 GHz, ...)

21. Which default route will be active?
/ip route
add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1
add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2
a. Route via gateway 1.1.1.1
b. Route via gateway 2.2.2.2

22. An IP address pool can contain addresses from more than one subnet.
a. True
b. False

23. Is it possible to use the serial port of MikroTik to communicate with an external device connected by null-modem cable?
a. Yes, if port is not being used
b. Yes, when other is a MikroTik router.
c. Yes, it is always possible by /system serial-terminal command.

24. It is required to make a web server on a private LAN visible on the Public Internet. Only the web server port should be visible to the public. Which of the following configuration steps must be met. (select all that apply)

a. A route between the NAT Router and the webserver must exist
b. LAN address of the webserver should be routable on the internet
c. in ip firewall NAT there should be a dst-nat between the public ip of the router and the private ip of the webserver
d. Connection Tracking must be enabled on NAT router
e. Public IP address of the webserver must be installed on the NAT Router

25. Collisions are possible in full-duplex Ethernet networks

True
False

