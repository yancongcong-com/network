| Code        | Data length | Description                                                  | References                                                   |
| ----------- | ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 0           | 0           | [Pad](http://www.networksorcery.com/enp/protocol/bootp/option000.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 1           | 4           | [Subnet Mask](http://www.networksorcery.com/enp/protocol/bootp/option001.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 2           | 4           | [Time Offset](http://www.networksorcery.com/enp/protocol/bootp/option002.htm) (deprecated). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 3           | 4+          | [Router](http://www.networksorcery.com/enp/protocol/bootp/option003.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 4           | 4+          | [Time Server](http://www.networksorcery.com/enp/protocol/bootp/option004.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 5           | 4+          | [Name Server](http://www.networksorcery.com/enp/protocol/bootp/option005.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 6           | 4+          | [Domain Name Server](http://www.networksorcery.com/enp/protocol/bootp/option006.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 7           | 4+          | [Log Server](http://www.networksorcery.com/enp/protocol/bootp/option007.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 8           | 4+          | [Quote Server](http://www.networksorcery.com/enp/protocol/bootp/option008.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 9           | 4+          | [LPR Server](http://www.networksorcery.com/enp/protocol/bootp/option009.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 10          | 4+          | [Impress Server](http://www.networksorcery.com/enp/protocol/bootp/option010.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 11          | 4+          | [Resource Location Server](http://www.networksorcery.com/enp/protocol/bootp/option011.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 12          | 1+          | [Host Name](http://www.networksorcery.com/enp/protocol/bootp/option012.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 13          | 2           | [Boot File Size](http://www.networksorcery.com/enp/protocol/bootp/option013.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 14          | 1+          | [Merit Dump File](http://www.networksorcery.com/enp/protocol/bootp/option014.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 15          | 1+          | [Domain Name](http://www.networksorcery.com/enp/protocol/bootp/option015.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 16          | 4           | [Swap Server](http://www.networksorcery.com/enp/protocol/bootp/option016.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 17          | 1+          | [Root Path](http://www.networksorcery.com/enp/protocol/bootp/option017.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 18          | 1+          | [Extensions Path](http://www.networksorcery.com/enp/protocol/bootp/option018.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 19          | 1           | [IP Forwarding enable/disable](http://www.networksorcery.com/enp/protocol/bootp/option019.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 20          | 1           | [Non-local Source Routing enable/disable](http://www.networksorcery.com/enp/protocol/bootp/option020.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 21          | 8+          | [Policy Filter](http://www.networksorcery.com/enp/protocol/bootp/option021.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 22          | 2           | [Maximum Datagram Reassembly Size](http://www.networksorcery.com/enp/protocol/bootp/option022.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 23          | 1           | [Default IP Time-to-live](http://www.networksorcery.com/enp/protocol/bootp/option023.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 24          | 4           | [Path MTU Aging Timeout](http://www.networksorcery.com/enp/protocol/bootp/option024.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 25          | 2+          | [Path MTU Plateau Table](http://www.networksorcery.com/enp/protocol/bootp/option025.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 26          | 2           | [Interface MTU](http://www.networksorcery.com/enp/protocol/bootp/option026.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 27          | 1           | [All Subnets are Local](http://www.networksorcery.com/enp/protocol/bootp/option027.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 28          | 4           | [Broadcast Address](http://www.networksorcery.com/enp/protocol/bootp/option028.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 29          | 1           | [Perform Mask Discovery](http://www.networksorcery.com/enp/protocol/bootp/option029.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 30          | 1           | [Mask supplier](http://www.networksorcery.com/enp/protocol/bootp/option030.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 31          | 1           | [Perform router discovery](http://www.networksorcery.com/enp/protocol/bootp/option031.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 32          | 4           | [Router solicitation address](http://www.networksorcery.com/enp/protocol/bootp/option032.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 33          | 8+          | [Static routing table](http://www.networksorcery.com/enp/protocol/bootp/option033.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 34          | 1           | [Trailer encapsulation](http://www.networksorcery.com/enp/protocol/bootp/option034.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 35          | 4           | [ARP cache timeout](http://www.networksorcery.com/enp/protocol/bootp/option035.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 36          | 1           | [Ethernet encapsulation](http://www.networksorcery.com/enp/protocol/bootp/option036.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 37          | 1           | [Default TCP TTL](http://www.networksorcery.com/enp/protocol/bootp/option037.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 38          | 4           | [TCP keepalive interval](http://www.networksorcery.com/enp/protocol/bootp/option038.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 39          | 1           | [TCP keepalive garbage](http://www.networksorcery.com/enp/protocol/bootp/option039.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 40          | 1+          | [Network Information Service Domain](http://www.networksorcery.com/enp/protocol/bootp/option040.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 41          | 4+          | [Network Information Servers](http://www.networksorcery.com/enp/protocol/bootp/option041.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 42          | 4+          | [NTP servers](http://www.networksorcery.com/enp/protocol/bootp/option042.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 43          | 1+          | Vendor specific information.                                 | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 44          | 4+          | NetBIOS over TCP/IP name server.                             | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 45          | 4+          | NetBIOS over TCP/IP Datagram Distribution Server.            | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 46          | 1           | NetBIOS over TCP/IP Node Type.                               | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 47          | 1+          | NetBIOS over TCP/IP Scope.                                   | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 48          | 4+          | X Window System Font Server.                                 | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 49          | 4+          | X Window System Display Manager.                             | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 50          | 4           | Requested IP Address.                                        | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 51          | 4           | IP address lease time.                                       | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 52          | 1           | Option overload.                                             | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 53          | 1           | DHCP message type.                                           | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt), [RFC  3203](http://www.networksorcery.com/enp/rfc/rfc3203.txt), [RFC 4388](http://www.networksorcery.com/enp/rfc/rfc4388.txt) |
| 54          | 4           | Server identifier.                                           | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 55          | 1+          | Parameter request list.                                      | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 56          | 1+          | Message.                                                     | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 57          | 2           | Maximum DHCP message size.                                   | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 58          | 4           | Renew time value.                                            | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 59          | 4           | Rebinding time value.                                        | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 60          | 1+          | Class-identifier.                                            | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 61          | 2+          | Client-identifier.                                           | [RFC 1533](http://www.networksorcery.com/enp/rfc/rfc1533.txt), [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt), [RFC  4361](http://www.networksorcery.com/enp/rfc/rfc4361.txt) |
| 62          | 1 to 255    | NetWare/IP Domain Name.                                      | [RFC 2242](http://www.networksorcery.com/enp/rfc/rfc2242.txt) |
| 63          |             | NetWare/IP information.                                      | [RFC 2242](http://www.networksorcery.com/enp/rfc/rfc2242.txt) |
| 64          | 1+          | Network Information Service+ Domain.                         | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 65          | 4+          | Network Information Service+ Servers.                        | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 66          | 1+          | TFTP server name.                                            | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 67          | 1+          | Bootfile name.                                               | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 68          | 0+          | Mobile IP Home Agent.                                        | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 69          | 4+          | Simple Mail Transport Protocol Server.                       | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 70          | 4+          | Post Office Protocol Server.                                 | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 71          | 4+          | Network News Transport Protocol Server.                      | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 72          | 4+          | Default World Wide Web Server.                               | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 73          | 4+          | Default Finger Server.                                       | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 74          | 4+          | Default Internet Relay Chat Server.                          | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 75          | 4+          | StreetTalk Server.                                           | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 76          | 4+          | StreetTalk Directory Assistance Server.                      | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |
| 77          | Variable.   | User Class Information.                                      | [RFC 3004](http://www.networksorcery.com/enp/rfc/rfc3004.txt) |
| 78          | Variable.   | SLP Directory Agent.                                         | [RFC 2610](http://www.networksorcery.com/enp/rfc/rfc2610.txt) |
| 79          | Variable.   | SLP Service Scope.                                           | [RFC 2610](http://www.networksorcery.com/enp/rfc/rfc2610.txt) |
| 80          | 0           | Rapid Commit.                                                | [RFC 4039](http://www.networksorcery.com/enp/rfc/rfc4039.txt) |
| 81          | 4+.         | FQDN, Fully Qualified Domain Name.                           | **[RFC 4702](http://www.networksorcery.com/enp/rfc/rfc4702.txt)** |
| 82          | Variable.   | [Relay Agent Information](http://www.networksorcery.com/enp/protocol/bootp/option082.htm). | [RFC 3046](http://www.networksorcery.com/enp/rfc/rfc3046.txt), **[RFC 5010](http://www.networksorcery.com/enp/rfc/rfc5010.txt)** |
| 83          | 14+         | Internet Storage Name Service.                               | [RFC 4174](http://www.networksorcery.com/enp/rfc/rfc4174.txt) |
| 84          |             |                                                              | RFC 3679                                                     |
| 85          | Variable.   | NDS servers.                                                 | [RFC 2241](http://www.networksorcery.com/enp/rfc/rfc2241.txt) |
| 86          | Variable.   | NDS tree name.                                               | [RFC 2241](http://www.networksorcery.com/enp/rfc/rfc2241.txt) |
| 87          | Variable.   | NDS context.                                                 | [RFC 2241](http://www.networksorcery.com/enp/rfc/rfc2241.txt) |
| 88          | Variable.   | BCMCS Controller Domain Name list.                           | [RFC 4280](http://www.networksorcery.com/enp/rfc/rfc4280.txt) |
| 89          | 4+          | BCMCS Controller IPv4 address list.                          | [RFC 4280](http://www.networksorcery.com/enp/rfc/rfc4280.txt) |
| 90          | Variable.   | Authentication.                                              | [RFC 3118](http://www.networksorcery.com/enp/rfc/rfc3118.txt) |
| 91          | 4           | client-last-transaction-time.                                | [RFC 4388](http://www.networksorcery.com/enp/rfc/rfc4388.txt) |
| 92          | 4n          | associated-ip.                                               | [RFC 4388](http://www.networksorcery.com/enp/rfc/rfc4388.txt) |
| 93          | Variable.   | Client System Architecture Type.                             | [RFC 4578](http://www.networksorcery.com/enp/rfc/rfc4578.txt) |
| 94          | Variable.   | Client Network Interface Identifier.                         | [RFC 4578](http://www.networksorcery.com/enp/rfc/rfc4578.txt) |
| 95          | Variable.   | LDAP, Lightweight Directory Access Protocol.                 | RFC 3679                                                     |
| 96          |             |                                                              | RFC 3679                                                     |
| 97          | Variable.   | Client Machine Identifier.                                   | [RFC 4578](http://www.networksorcery.com/enp/rfc/rfc4578.txt) |
| 98          |             | Open Group's User Authentication.                            | [RFC 2485](http://www.networksorcery.com/enp/rfc/rfc2485.txt) |
| 99          |             | GEOCONF_CIVIC.                                               | RFC 4776                                                     |
| 100         |             | IEEE 1003.1 TZ String.                                       | [RFC 4833](http://www.networksorcery.com/enp/rfc/rfc4833.txt) |
| 101         |             | Reference to the TZ Database.                                | [RFC 4833](http://www.networksorcery.com/enp/rfc/rfc4833.txt) |
| 102  -  111 |             |                                                              | RFC 3679                                                     |
| 112         | Variable.   | NetInfo Parent Server Address.                               | RFC 3679                                                     |
| 113         | Variable.   | NetInfo Parent Server Tag.                                   | RFC 3679                                                     |
| 114         | Variable.   | URL.                                                         | RFC 3679                                                     |
| 115         |             |                                                              | RFC 3679                                                     |
| 116         | 1           | Auto-Configure                                               | [RFC 2563](http://www.networksorcery.com/enp/rfc/rfc2563.txt) |
| 117         | 2+          | Name Service Search.                                         | [RFC 2937](http://www.networksorcery.com/enp/rfc/rfc2937.txt) |
| 118         | 4           | Subnet Selection.                                            | [RFC 3011](http://www.networksorcery.com/enp/rfc/rfc3011.txt) |
| 119         | Variable    | DNS domain search list.                                      | [RFC 3397](http://www.networksorcery.com/enp/rfc/rfc3397.txt) |
| 120         | Variable    | SIP Servers DHCP Option.                                     | [RFC 3361](http://www.networksorcery.com/enp/rfc/rfc3361.txt) |
| 121         | 5+          | Classless Static Route Option.                               | [RFC 3442](http://www.networksorcery.com/enp/rfc/rfc3442.txt) |
| 122         | Variable    | CCC, CableLabs Client Configuration.                         | [RFC 3495](http://www.networksorcery.com/enp/rfc/rfc3495.txt), [RFC 3594](http://www.networksorcery.com/enp/rfc/rfc3594.txt), [RFC  3634](http://www.networksorcery.com/enp/rfc/rfc3634.txt) |
| 123         | 16          | [GeoConf](http://www.networksorcery.com/enp/protocol/bootp/option123.htm). | [RFC 3825](http://www.networksorcery.com/enp/rfc/rfc3825.txt) |
| 124         |             | Vendor-Identifying Vendor Class.                             | [RFC 3925](http://www.networksorcery.com/enp/rfc/rfc3925.txt) |
| 125         |             | Vendor-Identifying Vendor-Specific.                          | [RFC 3925](http://www.networksorcery.com/enp/rfc/rfc3925.txt) |
| 126         |             |                                                              | RFC 3679                                                     |
| 127         |             |                                                              | RFC 3679                                                     |
| 128         |             | TFTP Server IP address.                                      | RFC 4578                                                     |
| 129         |             | Call Server IP address.                                      | RFC 4578                                                     |
| 130         |             | Discrimination string.                                       | RFC 4578                                                     |
| 131         |             | Remote statistics server IP address.                         | RFC 4578                                                     |
| 132         |             | 802.1P VLAN ID.                                              | RFC 4578                                                     |
| 133         |             | 802.1Q L2 Priority.                                          | RFC 4578                                                     |
| 134         |             | Diffserv Code Point.                                         | RFC 4578                                                     |
| 135         |             | HTTP Proxy for phone-specific applications.                  | RFC 4578                                                     |
| 136         | 4+          | [PANA](http://www.networksorcery.com/enp/protocol/pana.htm) Authentication Agent. | [RFC 5192](http://www.networksorcery.com/enp/rfc/rfc5192.txt) |
| 137         | variable    | [LoST](http://www.networksorcery.com/enp/protocol/lost.htm) Server. | [RFC 5223](http://www.networksorcery.com/enp/rfc/rfc5223.txt) |
| 138         |             | CAPWAP Access Controller addresses.                          | [RFC 5417](http://www.networksorcery.com/enp/rfc/rfc5417.txt) |
| 139         |             | OPTION-IPv4_Address-MoS.                                     | RFC 5678                                                     |
| 140         |             | OPTION-IPv4_FQDN-MoS.                                        | RFC 5678                                                     |
| 141         | 2+          | SIP UA Configuration Service Domains.                        | [RFC 6011](http://www.networksorcery.com/enp/rfc/rfc6011.txt) |
| 142         |             | OPTION-IPv4_Address-ANDSF.                                   | RFC 6153                                                     |
| 143         |             | OPTION-IPv6_Address-ANDSF.                                   | RFC 6153                                                     |
| 144  -  149 |             |                                                              | RFC 3942                                                     |
| 150         |             | TFTP server address.                                         | RFC 5859                                                     |
| 150         |             | Etherboot.  GRUB configuration path name.                    |                                                              |
| 151         |             | status-code.                                                 |                                                              |
| 152         |             | base-time.                                                   |                                                              |
| 153         |             | start-time-of-state.                                         |                                                              |
| 154         |             | query-start-time.                                            |                                                              |
| 155         |             | query-end-time.                                              |                                                              |
| 156         |             | dhcp-state.                                                  |                                                              |
| 157         |             | data-source.                                                 |                                                              |
| 158  -  174 |             |                                                              | RFC 3942                                                     |
| 175         |             | Etherboot.                                                   |                                                              |
| 176         |             | IP Telephone.                                                |                                                              |
| 177         |             | Etherboot.  PacketCable and CableHome.                       |                                                              |
| 178  -  207 |             |                                                              | RFC 3942                                                     |
| 208         |             | pxelinux.magic (string) = F1:00:74:7E (241.0.116.126).       | RFC 5071                                                     |
| 209         |             | pxelinux.configfile (text).                                  | RFC 5071                                                     |
| 210         |             | pxelinux.pathprefix (text).                                  | RFC 5071                                                     |
| 211         |             | pxelinux.reboottime (unsigned integer 32 bits).              | RFC 5071                                                     |
| 212         | 18+         | OPTION_6RD.                                                  | RFC 5969                                                     |
| 213         |             | OPTION_V4_ACCESS_DOMAIN.                                     | RFC 5986                                                     |
| 214  -  219 |             |                                                              |                                                              |
| 220         |             | Subnet Allocation.                                           |                                                              |
| 221         | 1+          | Virtual Subnet Selection.                                    | [RFC 6607](http://www.networksorcery.com/enp/rfc/rfc6607.txt) |
| 222  223    |             |                                                              | RFC 3942                                                     |
| 224  -  254 |             | Private use.                                                 |                                                              |
| 255         | 0           | [End](http://www.networksorcery.com/enp/protocol/bootp/option255.htm). | [RFC 2132](http://www.networksorcery.com/enp/rfc/rfc2132.txt) |