
 ### SET - 15 
 

1\. Two hosts, A and B, are connected to a broadcast LAN. Select all the answers showing pairs of IP address/mask which would allow IP connections to be established between the two hosts.

  

a. A: 10.1.2.192/24 and B: 10.1.2.129/26

  

b. A: 10.1.2.66/25 and B: 10.1.2.109/26

  

c. A: 10.2.1.0/23 and B: 10.2.0.1/22

  

d. A: 10.2.2.1/23 and B: 10.2.0.1/22

  

  

2\. Which features are removed when advanced-tools package is uninstalled?

  

a. neighbors

  

b. ip-scan

  

c. netwatch

  

d. LCD support

  

e. ping

  

f. bandwidth-test

  

  

3\. Rate Flapping can be avoided by

  

a. Choose larger channels (40 MHz instead of 20 MHz)

  

b. Reduce supported rates

  

c. Change ap-bridge to bridge

  

d. Set basic rates to only one data rate like 24 Mbps

  

  

4\. Mark possible connection states in the connection tracking table

  

a. Related

  

b. Invalid

  

c. Closed

  

d. Established

  

e. Syn

  

f. New

  

  

5\. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?

  

a. Yes

  

b. No

  

  

6\. You have a queue structure as follows:

  

queue โ€GPโ€ max-limit=10M

  

\- queue โ€Mโ€ parent=โ€GPโ€ limit-at=4M max-limit=6M

  

\- โ€“ queue โ€C1โ€ณ parent=โ€Mโ€ limit-at=1M max-limit=7M priority=4

  

\- โ€“ queue โ€C2โ€ณ parent=โ€Mโ€ limit-at=1M max-limit=4M priority=1

  

\- โ€“ queue โ€C3โ€ณ parent=โ€Mโ€ limit-at=3M max-limit=7M priority=8

  

\- queue โ€Fโ€ parent=โ€GPโ€ limit-at=5M max-limit=8M

  

\- โ€“ queue โ€D1โ€ณ parent=โ€Fโ€ limit-at=3M max-limit=4M priority=5

  

\- โ€“ queue โ€D2โ€ณ parent=โ€Fโ€ limit-at=2M max-limit=5M priority=2

  

If queues โ€C1โ€ณ and โ€D2โ€ณ will not require any traffic, how the total available traffic is going to be distributed in the worst case scenario?

  

a. queue โ€C2โ€ณ will get 3M, โ€C3โ€ณ 2M, โ€D1โ€ณ 4M

  

b. queue โ€C2โ€ณ will get 2M, โ€C3โ€ณ 5M, โ€D1โ€ณ 3M

  

c. queue โ€C2โ€ณ will get 4M, โ€C3โ€ณ 2M, โ€D1โ€ณ 4M

  

d. queue โ€C2โ€ณ will get 2M, โ€C3โ€ณ 3M, โ€D1โ€ณ 5M

  

e. queue โ€C2โ€ณ will get 3M, โ€C3โ€ณ 3M, โ€D1โ€ณ 4M

  

  

7\. A MikroTik Router has the following configuration

  

/ip address

  

add address=1.1.1.2/30 interface=ether1

  

add address=2.2.2.2/30 interface=ether2

  

add address=192.168.10.1/24 interface=ether3

  

/ip firewall mangle

  

add action=mark-connection chain=prerouting

  

dst-port=80 new-connection-mark=web\_c passthrough=yes protocol=tcp

  

add action=mark-routing chain=prerouting

  

connection-mark=web\_c new-routing-mark=web passthrough=no

  

/ip firewall nat

  

add action=masquerade chain=srcnat

  

out-interface=ether3

  

/ip route

  

add gateway=1.1.1.1

  

add gateway=2.2.2.2 routing-mark=web

  

What can be said about the Web Access (port 80) by a customer connected at ether3 interface with IP 192.168.10.2/24, gateway 192.168.10.1 ?

  

a. The customer will access the Web using the gateway 2.2.2.2

  

b. The Customer is unable to access the Web.

  

c. The Customer will access the Web by ECMP, by using both gateways 1.1.1.1 and 2.2.2.2

  

d. The customer will access the Web using the gateway 1.1.1.1

  

  

8\. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

  

a. dhcp

  

b. advanced-tools

  

c. none

  

d. routing

  

  

9\. Which options should be used when you want to prevent access from one specific address to your router web interface?

  

a. Group settings for System users

  

b. Firewall Filter Chain Input

  

c. Firewall Filter Chain Forward

  

d. WWW service from IP Services

  

  

10\. Which MikroTik RouterOS version should you use for IEEE 802.11n standard support?

  

a. Versions 3.x

  

b. Versions 4.x

  

c. Versions 5.x

  

  

11\. A station can connect to AP if they both use different country regulation settings, but the frequency chosen is allowed in both countries

  

  

12\. How long is level 1 (demo) license valid?

  

a. 1 year

  

b. Infinite time

  

c. 24 hours

  

d. 1 month

  

  

13\. Router A and B are both running as PPPoE servers on different broadcast domains of your network. Is it possible to set Router A to use โ€/ppp secretโ€ accounts from Router B to authenticate PPPoE customers ?

  

True

  

False

  

  

14\. You need to save visited web-pages to memory logs from web-proxy. Which is the correct configuration?

  

a. /system logging add topics=web-proxy,debug action=memory

  

b. /system logging add topics=web-proxy,!debug action=disk

  

c. /system logging add topics=web-proxy,!debug action=remote

  

d. /system logging add topics=web-proxy,!debug action=memory

  

  

15\. By default info, error and warning messages are logged into memory of your RouterOS device. You can add logging of visited web-pages and other message topics

  

  

16\. Netinstall can be used to

  

a. Keep configuration, but reset a lost admin password

  

b. Install different software version (upgrade or downgrade)

  

c. Reinstall software without losing licence

  

d. Install package for different hardware architecture

  

  

17\. Which options are necessary to use the HotSpot Universal Client feature?

  

a. arp=enabled on the HotSpot interface

  

b. /ip dhcp-server configuration

  

c. address-pool configuration in /ip hotspot and /ip hotspot user profile

  

d. /ip firewall mangle rules

  

  

18\. What is the correct action to be specified in the NAT rule to hide a private network when communicating to the outside world?

  

a. tarpit

  

b. masquerade

  

c. passthrough

  

d. allow

  

  

19\. Mark all features that are compatible with Nstreme

  

a. WDS between a device in ap-bridge mode with a device in station-wds mode

  

b. Bridging a device in station mode with a device in ap-bridge mode

  

c. Encryption

  

d. WDS between a device in station-wds mode and a device in station-wds mode

  

  

20\. PPP Secrets are used for

  

a. L2TP clients

  

b. IPSec clients

  

c. PPPoE clients

  

d. PPtP clients

  

e. Router users

  

f. PPP clients

  

  

21\. What is term for the hardware coded address found on an interface?

  

a. MAC Address

  

b. Interface Address

  

c. FQDN Address

  

d. IP Address

  

  

22\. Which default route will be active?

  

/ip route

  

add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1

  

add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2

  

a. Route via gateway 2.2.2.2

  

b. Route via gateway 1.1.1.1

  

  

23\. You would like to allow multiple logins with one user name on a HotSpot server. How should this be configured?

  

a. Set โ€Shared Usersโ€ option at /ip hotspot user profile

  

b. Set โ€only-one=noโ€ at /ip hotspot

  

c. Itโ€s not possible

  

d. Set โ€Shared Usersโ€ option at /ip hotspot

  

  

24\. To assign specific traffic to the route โ€“ traffic must be identified by routing mark.Each packet can have only one routing mark.

  

true

  

false

  

  

25\. What can be used as โ€target-addressโ€ in the simple queue?

  

a. clientโ€s MAC address

  

b. address list name

  

c. clientโ€s address

  

d. serverโ€s address
