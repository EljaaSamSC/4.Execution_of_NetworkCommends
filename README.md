# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
netstat
~~~
Microsoft Windows [Version 10.0.26200.9711]
(c) Microsoft Corporation. All rights reserved.

C:\Users\acer>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:5141         TMP215-75-G2:52511     ESTABLISHED
  TCP    127.0.0.1:46935        TMP215-75-G2:61036     ESTABLISHED
  TCP    127.0.0.1:46936        TMP215-75-G2:49691     ESTABLISHED
  TCP    127.0.0.1:46937        TMP215-75-G2:49692     ESTABLISHED
  TCP    127.0.0.1:49669        TMP215-75-G2:49670     ESTABLISHED
  TCP    127.0.0.1:49670        TMP215-75-G2:49669     ESTABLISHED
  TCP    127.0.0.1:49671        TMP215-75-G2:49672     ESTABLISHED
  TCP    127.0.0.1:49672        TMP215-75-G2:49671     ESTABLISHED
  TCP    127.0.0.1:49680        TMP215-75-G2:49681     ESTABLISHED
  TCP    127.0.0.1:49681        TMP215-75-G2:49680     ESTABLISHED
  TCP    127.0.0.1:49683        TMP215-75-G2:49684     ESTABLISHED
  TCP    127.0.0.1:49684        TMP215-75-G2:49683     ESTABLISHED
  TCP    127.0.0.1:49685        TMP215-75-G2:49686     ESTABLISHED
  TCP    127.0.0.1:49686        TMP215-75-G2:49685     ESTABLISHED
  TCP    127.0.0.1:49687        TMP215-75-G2:49688     ESTABLISHED
  TCP    127.0.0.1:49688        TMP215-75-G2:49687     ESTABLISHED
  TCP    127.0.0.1:49689        TMP215-75-G2:49690     ESTABLISHED
  TCP    127.0.0.1:49690        TMP215-75-G2:49689     ESTABLISHED
  TCP    127.0.0.1:49691        TMP215-75-G2:46936     ESTABLISHED
  TCP    127.0.0.1:49692        TMP215-75-G2:46937     ESTABLISHED
  TCP    127.0.0.1:49709        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:49722        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:49736        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:52511        TMP215-75-G2:5141      ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:49709     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:49722     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:49736     ESTABLISHED
  TCP    127.0.0.1:61034        TMP215-75-G2:61035     ESTABLISHED
  TCP    127.0.0.1:61035        TMP215-75-G2:61034     ESTABLISHED
  TCP    127.0.0.1:61036        TMP215-75-G2:46935     ESTABLISHED
  TCP    127.0.0.1:61037        TMP215-75-G2:61038     ESTABLISHED
  TCP    127.0.0.1:61038        TMP215-75-G2:61037     ESTABLISHED
  TCP    127.0.0.1:61039        TMP215-75-G2:61040     ESTABLISHED
  TCP    127.0.0.1:61040        TMP215-75-G2:61039     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:54439     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:57382     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:60169     TIME_WAIT
  TCP    [::1]:15161            TMP215-75-G2:60170     TIME_WAIT
  TCP    [::1]:54439            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:57382            TMP215-75-G2:15161     ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:49327  [2001:4860:4829:200::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:49338  [2620:1ec:33:1::11]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:49547  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:49693  lb-140-82-112-22-iad:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:49708  [2620:1ec:33:1::11]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:50369  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:50963  g2600-140f-5e00-0014-0000-0000-17d3-3c20:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:51281  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:51451  sa-in-xbc:https        ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:51937  lb-140-82-112-22-iad:https  CLOSE_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:52161  whatsapp-cdn6-shv-03-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:52359  [2603:1010:3:b::1e]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:52592  whatsapp-cdn6-shv-03-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:52734  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:53593  whatsapp-cdn6-shv-03-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:53594  [64:ff9b::14be:9220]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:53595  [2603:1046:c04:1018::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:53596  [2603:1046:c04:1018::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:53830  [2001:4860:482a:7700::]:https  CLOSE_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:54223  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:54801  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:55194  sa-in-xbc:https        ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:55205  lcbomp-in-f84:https    ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:56119  lcbomp-in-f84:https    ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:56221  [64:ff9b::14b8:af0f]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:57088  whatsapp-cdn6-shv-03-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:57249  lb-140-82-114-25-iad:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:60968  [2001:4860:482d:700::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:62328  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:63147  [64:ff9b::14b8:af0f]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:64438  [2603:1040:a06:3::13]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:368:dbe7]:64555  [2001:4860:482d:700::]:https  ESTABLISHED
~~~
ipconfig
~~~
C:\Users\acer>ipconfig

Windows IP Configuration


Unknown adapter VPN Unlimited TAP:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . : saveetha.in
   IPv6 Address. . . . . . . . . . . : 2403:8600:c090:42:0:400:368:dbe7
   Link-local IPv6 Address . . . . . : fe80::ee17:f3ff:493:93e5%19
   Autoconfiguration IPv4 Address. . : 169.254.127.126
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . : fe80::eedd:24ff:fe3d:ced5%19

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
~~~
ping www.google.com
~~~

C:\Users\acer>ping www.google.com

Pinging www.google.com [2001:4860:4826:7700::] with 32 bytes of data:
Reply from 2001:4860:4826:7700::: time=82ms
Reply from 2001:4860:4826:7700::: time=16ms
Reply from 2001:4860:4826:7700::: time=31ms
Reply from 2001:4860:4826:7700::: time=106ms

Ping statistics for 2001:4860:4826:7700:::
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 16ms, Maximum = 106ms, Average = 58ms
~~~
tracert www.google.com
~~~
C:\Users\acer>tracert www.google.com

Tracing route to www.google.com [2001:4860:4826:7700::]
over a maximum of 30 hops:

  1    32 ms    15 ms    12 ms  2403:8600:c090:42::1
  2     *        *        *     Request timed out.
  3     *        *        *     Request timed out.
  4     *        *        *     Request timed out.
  5     *        *        *     Request timed out.
  6     9 ms    12 ms    71 ms  2001:4860:4826:7700::

Trace complete.
~~~
nslookup
~~~
C:\Users\acer>nslookup
Default Server:  UnKnown
Address:  2403:8600:c090:42:a000::200

>
~~~
getmac
~~~
Microsoft Windows [Version 10.0.26200.9711]
(c) Microsoft Corporation. All rights reserved.

C:\Users\acer>getmac

Physical Address    Transport Name
=================== ==========================================================
FC-6D-77-6C-2B-63   \Device\Tcpip_{F1E23BE4-41B4-4650-9419-7B9B8553CBE2}
74-D4-DD-CF-7D-29   Media disconnected
00-FF-A5-1B-A0-C6   Media disconnected
~~~
hostname
~~~
C:\Users\acer>hostname
TMP215-75-G2
~~~
nbtstat
~~~
C:\Users\acer>nbtstat

Displays protocol statistics and current TCP/IP connections using NBT
(NetBIOS over TCP/IP).

NBTSTAT [ [-a RemoteName] [-A IP address] [-c] [-n]
        [-r] [-R] [-RR] [-s] [-S] [interval] ]

  -a   (adapter status) Lists the remote machine's name table given its name
  -A   (Adapter status) Lists the remote machine's name table given its
                        IP address.
  -c   (cache)          Lists NBT's cache of remote [machine] names and their IP addresses
  -n   (names)          Lists local NetBIOS names.
  -r   (resolved)       Lists names resolved by broadcast and via WINS
  -R   (Reload)         Purges and reloads the remote cache name table
  -S   (Sessions)       Lists sessions table with the destination IP addresses
  -s   (sessions)       Lists sessions table converting destination IP
                        addresses to computer NETBIOS names.
  -RR  (ReleaseRefresh) Sends Name Release packets to WINS and then, starts Refresh

  RemoteName   Remote host machine name.
  IP address   Dotted decimal representation of the IP address.
  interval     Redisplays selected statistics, pausing interval seconds
               between each display. Press Ctrl+C to stop redisplaying
               statistics.
~~~
arp
~~~
C:\Users\acer>arp

Displays and modifies the IP-to-Physical address translation tables used by
address resolution protocol (ARP).

ARP -s inet_addr eth_addr [if_addr]
ARP -d inet_addr [if_addr]
ARP -a [inet_addr] [-N if_addr] [-v]

  -a            Displays current ARP entries by interrogating the current
                protocol data.  If inet_addr is specified, the IP and Physical
                addresses for only the specified computer are displayed.  If
                more than one network interface uses ARP, entries for each ARP
                table are displayed.
  -g            Same as -a.
  -v            Displays current ARP entries in verbose mode.  All invalid
                entries and entries on the loop-back interface will be shown.
  inet_addr     Specifies an internet address.
  -N if_addr    Displays the ARP entries for the network interface specified
                by if_addr.
  -d            Deletes the host specified by inet_addr. inet_addr may be
                wildcarded with * to delete all hosts.
  -s            Adds the host and associates the Internet address inet_addr
                with the Physical address eth_addr.  The Physical address is
                given as 6 hexadecimal bytes separated by hyphens. The entry
                is permanent.
  eth_addr      Specifies a physical address.
  if_addr       If present, this specifies the Internet address of the
                interface whose address translation table should be modified.
                If not present, the first applicable interface will be used.
Example:
  > arp -s 157.55.85.212   00-aa-00-62-c6-09  .... Adds a static entry.
  > arp -a                                    .... Displays the arp table.
~~~
systeminfo
~~~
C:\Users\acer>systeminfo                                                
Host Name:                     TMP215-75-G2
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              acer
Registered Organization:       N/A
Product ID:                    00342-42784-48687-AAOEM
Original Install Date:         01-09-2025, 15:21:05
System Boot Time:              18-11-2026, 09:49:12
System Manufacturer:           Acer
System Model:                  TravelMate P215-75-G2-TCO
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 170 Stepping 4 GenuineIntel ~1200 Mhz
BIOS Version:                  INSYDE Corp. V1.05tt01a, 01-09-2025
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         15,869 MB
Available Physical Memory:     4,865 MB
Virtual Memory: Max Size:      22,269 MB
Virtual Memory: Available:     7,804 MB
Virtual Memory: In Use:        14,465 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\TMP215-75-G2
Hotfix(s):                     5 Hotfix(s) Installed.
                               [01]: KB5127690
                               [02]: KB5054156
                               [03]: KB5132061
                               [04]: KB5127647
                               [05]: KB5132688
Network Card(s):               3 NIC(s) Installed.
                               [01]: Intel(R) Wi-Fi 6E AX211 160MHz
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     255.255.255.255
                                     IP address(es)
                                     [01]: 169.254.127.126
                                     [02]: fe80::ee17:f3ff:493:93e5
                                     [03]: 2403:8600:c090:42:0:400:368:dbe7
                               [02]: Realtek PCIe GbE Family Controller
                                     Connection Name: Ethernet
                                     Status:          Media disconnected
                               [03]: TAP-Windows Adapter V9
                                     Connection Name: VPN Unlimited TAP
                                     Status:          Media disconnected
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.
~~~
## Result
Thus Execution of Network commands Performed 
