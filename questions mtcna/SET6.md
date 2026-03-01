SET - 6 

  

  

1\. What can you do with Netinstall?

a. Reset password in RouterOS

b. Install Linux

c. Add configuration to RouterOS

d. Reinstall RouterOS

  

  

2\. Consider the attached diagram:

In order for Router 1 to see all of the networks the following commands could be used (choose all answers that could work)

  

  

a. /routing add dst-address=0.0.0.0/0 gateway=10.10.0.2

b. /ip route add dst-address=0.0.0.0/0 gateway=10.10.0.2

c. /ip route add dst-address=172.16.0.0/24 gateway=10.10.0.2, /ip route add dst-address=172.32.0.0/24 gateway=10.10.0.2

d. /ip route add dst-address=172.16.0.0/24 gateway=10.10.0.2, /ip route add dst-address=172.32.0.0/24 gateway=10.50.0.2

  

  

3\. Configuring HotSpot is possible on MikroTikRouterOS only with a wireless interface.

  

Yes

  

No

  

  

 4. What menus should be used to allow certain websites to be accessed from behind a hotspot interface, without client authentication

a. ip hotspot ip-binding

b. ip hotspot profile

c. ip hotspot walled-garden ip

d. ip hotspot walled-garden

  

5\. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

a. none

b. routing

c. advanced-tools

d. dhcp

  

6\. Netinstall can be used to

a. Install different software version (upgrade or downgrade)

b. Keep configuration, but reset a lost admin password

c. Reinstall software without losing licence

d. Install package for different hardware architecture

  

7\. In which order are the entries in Access List and Connect List processed?

a. By interface name

b. In sequence order

c. By Signal Strength Range

d. In a random order

  

8\. In Winbox, Hide Passwords unchecked shows passwords for the following

a. RouterOS user

b. Hotspot User

c. RADIUS shared secret

d. PPP secrets

  

9\. Which options should be used when you want to prevent access from one specific address to your router web interface?

a. Firewall Filter Chain Forward

b. Firewall Filter Chain Input

c. Group settings for System users

d. WWW service from IP Services

  

10\. Which of the following would prevent unknown clients from connecting to your AP? Choose the BEST answer.

a. Check the "Do not permit unknown client" box in the wireless configuration

b. Uncheck "Default Authenticate" in the wireless card configuration, and add each known client's MAC address to your access-list configuration ensuring that you enable "authenticate" in the entry

c. Add each known client's MAC address to your access-list configuration is the only step needed

d. Uncheck "Default Authenticate" in the wireless card configuration, and add each known client's MAC address to your connect-list configuration

e. Configure the radius server under "/radius"

  

11\. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?

a. Yes

b. No

  

12\. Mark the queue types that are available in RouterOS

a. SFQ – Stochastic Fairness Queuing

b. RED – Random Early Detect (or Drop)

c. FIFO - First In First Out (for Bytes or for Packets)

d. DRR - Deficit Round Robin

e. LIFO - Last In First Out

f. PCQ – Per Connection Queuing

  

13\. Check the allowed input formats for wireless scan-list.

a. 5500 5700

b. 5500-5700

c. 5500,5700

d. 5500 - 5700

e. 5500/5700

  

14\. Choose all valid hosts address range for subnet 15.242.55.62/27

a. 15.242.55.31-15.242.55.62

b. 15.242.55.33-15.242.55.63

c. 15.242.55.33-15.242.55.62

d. 15.242.55.32-15.242.55.63

  

15\. After putting this rule: /ipfirewall add chain=input action=drop, you will still be able to access the Router using the mac-address.

Yes

  

16\. You need to reboot a RouterBoard after importing a previously exported rsc file to activate the new configuration.

  

True

False

  

17\. What is necessary for PPPoE client configuration?

a. ip firewall nat masquerade rule

b. Interface (on which PPPoE client is going to work)

c. Static IP address on PPPoE client interface

  

18\. In order to use dynamic keys in your security profile for an AP, you MUST set up the dhcp server to provide the dynamic keys.

  

19\. You have a router with configuration

\- Public IP :202.168.125.45/24

\- Default gateway:202.168.125.1

\- DNS server: 248.115.148.136, 248.115.148.137

\- Local IP: 192.168.2.1/24

  

Mark the correct configuration on client PC to access to the Internet

a. IP:192.168.0.1/24 gateway:192.168.2.1

b. IP:192.168.2.2/24 gateway:202.168.125.45

c. IP:192.168.1.223/24 gateway:248.115.148.136

d. IP:192.168.2.115/24 gateway: 192.168.2.1

e. IP:192.168.2.253/24 gateway:202.168.0.1

  

20\. Router OS can set vlan-id value from - to :

a. 1-2049

b. 1-4096

c. 1-4095

d. 1-2048

  

21\. Collisions are possible in full-duplex Ethernet networks

  

True

False

  

22\. Where can you monitor (see addresses and ports) real-time connections which are processed by the router?

a. Queue Tree

b. Tool Torch

c. Firewall Counters

d. Firewall Connection Tracking

  

23\. Action=redirect applies to

a. SRC-NAT rules

b. DST-NAT rules

c. Firewall Filter rules

d. Route rules

  

24\. What does this simple queue do (check the image)?

a. Queue limits host 192.168.1.10 download data rate to one megabit per second.

b. Queue guarantees download data rate of one megabit per second for host 192.168.1.10

c. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10

d. Queue limits host 192.168.1.10 upload data rate to one megabit per second.

  

25\. Is it possible that the same IP address is included in multiple address lists and still be used by these multiple address lists?

  

a. Destination NAT rule is required to utilize transparent proxy facility

b. To deny access to a specific website, caching should be enabled

c. Controls domains or servers which are allowed to cache by Proxy

d. Can deny access to a specific domains or servers, but not specific web pages
