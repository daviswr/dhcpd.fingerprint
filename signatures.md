# DHCP Client Signatures

Verified or at least researched (codenames, OUIs, etc) device signatures and their classes/identifications

**PRL** - DHCP Option 55, Parameter Request List

**Vendor ID** - DHCP Option 60, Vendor Class Identifier

**Vendor OUI** - First 24 bits of client MAC address

---
## Apple
### Apple Mac OS
| **Device/OS**                        | **PRL**                                       | **Vendor ID**                                     | **Client Class**                       |
| :-------------                       | :------                                       | :------------                                     | :---------------                       |
| Apple NetBoot PowerPC                | `1:3:2b:3c`                                   | `AAPLBSDPC/ppc/`*model*                           | Apple NetBoot (PPC)                    |
| Apple NetBoot Intel                  | `1:3:43:2b:3c`                                | `AAPLBSDPC/i386/`*model*                          | Apple NetBoot (Intel)                  |
| Apple Mac OS 9.0.4 installer         | `1:3:6:f`                                     | `Mac OS 9.0.4 Open Transport `*version*           | Apple Mac OS 9                         |
| Apple Mac OS 9.1.0                   | `1:3:6:f:21:2a:2c:2d:2e:2f:45:46:47:4a:4e:4f` | `Mac OS 9.1 Open Transport `*version*` `*model*   | Apple Mac OS 9                         |
| Apple Mac OS 9.2.1                   | `1:3:6:f:21:2a:2c:2d:2e:2f:45:46:47:4a:4e:4f` | `Mac OS 9.2.1 Open Transport `*version*` `*model* | Apple Mac OS 9                         |
| Apple Mac OS 9.2.2                   | `1:3:6:f:21:2a:2c:2d:2e:2f:45:46:47:4a:4e:4f` | `Mac OS 9.2.2 Open Transport `*version*` `*model* | Apple Mac OS 9                         |
| Apple Mac OS X "Cheetah" 10.0.0      | `1:3:c:6:f:70:71:4e:4f`                       |                                                   | Apple Mac OS X 10.0                    |
| Apple Mac OS X "Puma" 10.1.4         | `1:3:6:f:70:71:4e:4f`                         |                                                   | Apple Mac OS X 10.1                    |
| Apple Mac OS X "Jaguar" 10.2.0       | `1:3:6:f:70:71:4e:4f:5f`                      |                                                   | Apple Mac OS X 10.2 / 10.3             |
| Apple Mac OS X "Panther" 10.3.0      | `1:3:6:f:70:71:4e:4f:5f`                      |                                                   | Apple Mac OS X 10.2 / 10.3             |
| Apple Mac OS X "Tiger" 10.4.11       | `1:3:6:f:70:71:4e:4f:5f:fc`                   |                                                   | Apple Mac OS X 10.4 / Apple TV G1      |
| AppleTV G1 3.0.2                     | `1:3:6:f:70:71:4e:4f:5f:fc`                   |                                                   | Apple Mac OS X 10.4 / Apple TV G1      |
| Apple Mac OS X "Leopard" 10.5.8      | `1:3:6:f:77:5f:fc:2c:2e:2f`                   |                                                   | Apple Mac OS X 10.5 / 10.6             |
| Apple Mac OS X "Snow Leopard" 10.6.8 | `1:3:6:f:77:5f:fc:2c:2e:2f`                   |                                                   | Apple Mac OS X 10.5 / 10.6             |
| Apple Mac OS X "Lion" 10.7.1         | `1:3:6:f:77:5f:fc:2c:2e`                      |                                                   | Apple OS X 10.7 - 10.10                |
| Apple OS X "Mountain Lion" 10.8.0    | `1:3:6:f:77:5f:fc:2c:2e`                      |                                                   | Apple OS X 10.7 - 10.10                |
| Apple OS X "Mavericks" 10.9.0        | `1:3:6:f:77:5f:fc:2c:2e`                      |                                                   | Apple OS X 10.7 - 10.10                |
| Apple OS X "Yosemite" 10.10.0        | `1:3:6:f:77:5f:fc:2c:2e`                      |                                                   | Apple OS X 10.7 - 10.10                |
| Apple OS X "El Capitan" 10.11.0      | `1:79:3:6:f:77:fc:5f:2c:2e`                   |                                                   | Apple OS X 10.11 / macOS 10.12 - 10.15 |
| Apple macOS "Sierra" 10.12.0         | `1:79:3:6:f:77:fc:5f:2c:2e`                   |                                                   | Apple OS X 10.11 / macOS 10.12 - 10.15 |
| Apple macOS "High Sierra" 10.13.0    | `1:79:3:6:f:77:fc:5f:2c:2e`                   |                                                   | Apple OS X 10.11 / macOS 10.12 - 10.15 |
| Apple macOS "Mojave" 10.14.6         | `1:79:3:6:f:77:fc:5f:2c:2e`                   |                                                   | Apple OS X 10.11 / macOS 10.12 - 10.15 |
| Apple macOS "Catalina" 10.15.7       | `1:79:3:6:f:77:fc:5f:2c:2e`                   |                                                   | Apple OS X 10.11 / macOS 10.12 - 10.15 |
| Apple macOS "Big Sur" 11.5.2         | `1:79:3:6:f:72:77:fc:5f:2c:2e`                |                                                   | Apple macOS 11 - 12                    |
| Apple macOS "Monterey" 12.0.1        | `1:79:3:6:f:6c:72:77:fc:5f:2c:2e`             |                                                   | Apple macOS 12                         |
| Apple macOS "Monterey" 12.2.1        | `1:79:3:6:f:72:77:fc:5f:2c:2e`                |                                                   | Apple macOS 11 - 12                    |
| Apple macOS "Monterey" 12.6.0        | `1:79:3:6:f:6c:72:77:fc:5f:2c:2e`             |                                                   | Apple macOS 12                         |

### Apple iOS
| **Device/OS**                    | **PRL**                  | **Vendor ID** | **Client Class**  |
| :------------                    | :------                  | :------------ | :---------------  |
| Apple iOS 2.2.1 - iPod Touch G1  | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| Apple iOS 3.1.3 - iPhone 2G      | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| Apple iOS 4.3.5 - iPhone 4       | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| AppleTV G2 4.x (iOS 4.x/5.x)     | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| Apple iOS 5.0.1 - iPhone 4       | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| Apple iOS 5.0.1 - iPad G1        | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| AppleTV G3 5.0.1 (iOS 5.1.1)     | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| Apple iOS 6.0 - iPad G3          | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| Apple iOS 7.0 - iPad G3          | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| Apple iOS 8.0.2 - iPhone 4S      | `1:3:6:f:77:fc`          |               | Apple iOS 2 - 8   |
| Apple iOS 9.0 - iPhone 5S        | `1:79:3:6:f:77:fc`       |               | Apple iOS 9 - 13  |
| Apple iOS 10.0.1 - iPhone 5S     | `1:79:3:6:f:77:fc`       |               | Apple iOS 9 - 13  |
| Apple iOS 11.1 Beta - iPhone 6S+ | `1:79:3:6:f:77:fc`       |               | Apple iOS 9 - 13  |
| Apple iOS 12.0 - iPhone SE G1    | `1:79:3:6:f:77:fc`       |               | Apple iOS 9 - 13  |
| Apple iOS 13.0 - iPhone SE G1    | `1:79:3:6:f:77:fc`       |               | Apple iOS 9 - 13  |
| Apple iOS 14.0 - iPhone SE G2    | `1:79:3:6:f:72:77:fc`    |               | Apple iOS 14      |
| Apple iOS 15.6 - iPhone 7        | `1:79:3:6:f:6c:72:77:fc` |               | Apple iOS 15 - 16 |
| Apple iOS 15.6 - iPhone SE G2    | `1:79:3:6:f:6c:72:77:fc` |               | Apple iOS 15 - 16 |
| Apple tvOS 16.0 - AppleTV HD     | `1:79:3:6:f:6c:72:77:fc` |               | Apple iOS 15 - 16 |

### Apple AirPort
| **Device/OS**               | **PRL**                                  | **Vendor ID** | **Client Class**             |
| :------------               | :------                                  | :------------ | :---------------             |
| Apple Time Capsule G4 (7.6) | `1:2:3:f:6:c:2c`                         |               | Apple network appliance      |
| Apple AirPort Express G2    | `1:2:3:f:6:c:2c`                         |               | Apple network appliance      |
| Apple AirPort Express       | `1:3:6:f` (Xbox, DRAC, BB, Netgear, etc) |               | Printer or network appliance |

---
## Linux
### Linux Desktop/Server
| **Device/OS**                                   | **PRL**                                                         | **Vendor ID**                                                     | **Hostname**  | **Client Class**                                |
| :------------                                   | :------                                                         | :------------                                                     | :-----------  | :---------------                                |
| **Debian-based**                                |||||
| Ubuntu 4.10 - 5.10 installer (dhclient)         | `1:1c:2:3:f:6:c` (ISC dhclient default)                         |                                                                   |               | ISC dhclient (Linux/Unix)                       |
| Debian installer (dhclient)                     | `1:1c:2:3:f:6:c:2a` (ReactOS)                                   | `d-i`                                                             |               | Debian Linux (installer)                        |
| Ubuntu 4.10 - 8.0.4 (dhclient)                  | `1:1c:2:3:f:6:c:2c:2f`                                          |                                                                   |               | Ubuntu Linux 4.10 - 8.04                        |
| Debian 4 (dhclient)                             | `1:1c:2:3:f:6:c:2c:2f:1a`                                       |                                                                   |               | Debian Linux 4                                  |
| Ubuntu 8.10 (dhclient)                          | `1:1c:2:3:f:6:77:c:2c:2f:1a`                                    |                                                                   |               | Ubuntu Linux 8.10                               |
| Debian 5 (dhclient)                             | `1:1c:2:3:f:6:77:c:2c:2f:1a:79`                                 |                                                                   |               | Debian Linux 5                                  |
| Debian 6 - 7 (dhclient)                         | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a`                              |                                                                   |               | Debian Linux 6 or derivative (dhclient)         |
| Ubuntu 9.04 - 14.10 (dhclient)                  | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a`                              |                                                                   |               | Debian Linux 6 or derivative (dhclient)         |
| Debian 7 (NetworkManager)                       | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a:79:f9:fc:2a`                  |                                                                   |               | Debian Linux 7 or derivative (NetworkManager)   |
| Ubuntu 11.04 - 13.10 (Indicator/NetworkManager) | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a:79:f9:fc:2a`                  |                                                                   |               | Debian Linux 7 or derivative (NetworkManager)   |
| Linux Mint 11 - 16 (Indicator/NetworkManager)   | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a:79:f9:fc:2a`                  |                                                                   |               | Debian Linux 7 or derivative (NetworkManager)   |
| Linux Mint 11 - 17 (dhclient)                   | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a`                              |                                                                   |               | Debian Linux 6 or derivative (dhclient)         |
| Knoppix 6.7.1 (NetworkManager)                  | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a:79:f9:fc:2a`                  |                                                                   |               | Debian Linux 7 or derivative (NetworkManager)   |
| Knoppix 6.7.1 (dhclient)                        | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a`                              |                                                                   |               | Debian Linux 6 or derivative (dhclient)         |
| Ubuntu 14.04 - 16.04 (NetworkManager)           | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a:79:f9:21:fc:2a`               |                                                                   |               | Debian Linux or derivative                      |
| Linux Mint 17 (NetworkManager)                  | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a:79:f9:21:fc:2a`               |                                                                   |               | Debian Linux or derivative                      |
| **Red Hat-based**                               |||||
| Red Hat Enterprise Linux 5.3 (dhclient)         | `1:1c:2:3:f:6:c:28:29:2a`                                       |                                                                   |               | Red Hat Enterprise Linux 5 or derivative        |
| CentOS 5.5, 5.6 (dhclient)                      | `1:1c:2:3:f:6:c:28:29:2a`                                       |                                                                   |               | Red Hat Enterprise Linux 5 or derivative        |
| CentOS 5.7, 5.8 (dhclient)                      | `1:1c:2:3:f:6:c:28:29:2a:1a`                                    |                                                                   |               | Red Hat Enterprise Linux 5 or derivative        |
| Fedora 14 - 19 (dhclient)                       | `1:1c:2:79:f:6:c:28:29:2a:1a:77:3`                              |                                                                   |               | Red Hat-based Linux (dhclient)                  |
| Fedora 15 - 18 (NetworkManager)                 | `1:1c:2:79:f:6:c:28:29:2a:1a:77:3:79:f9:fc:2a`                  |                                                                   |               | Red Hat-based Linux (NetworkManager)            |
| Red Hat Enterprise Linux 6.0 (dhclient)         | `1:1c:2:3:f:6:c:28:29:2a:1a:77`                                 |                                                                   |               | Red Hat Enterprise Linux 6 or derivative        |
| Red Hat Enterprise Linux 6.3                    | `1:1c:2:79:f:6:c:28:29:2a:1a:77:3:79:f9:2a`                     |                                                                   |               | Red Hat Enterprise Linux 6 or derivative        |
| CentOS 6.0 (dhclient)                           | `1:1c:2:3:f:6:c:28:29:2a:1a:77`                                 |                                                                   |               | Red Hat Enterprise Linux 6 or derivative        |
| CentOS 6.2                                      | `1:1c:2:79:f:6:c:28:29:2a:1a:77:3`                              |                                                                   |               | Red Hat-based Linux (dhclient)                  |
| Oracle Linux 6.2                                | `1:1c:2:79:f:6:c:28:29:2a:1a:77:3`                              |                                                                   |               | Red Hat-based Linux (dhclient)                  |
| Fedora 19                                       | `1:1c:2:79:f:6:c:28:29:2a:1a:77:3:79:f9:21:fc:2a`               |                                                                   |               | Red Hat-based Linux                             |
| Fedora/CentOS/Oracle unknown                    | `1:1c:2:79:f:6:c:28:29:2a:1a:77:3:79:f9:21:2a`                  |                                                                   |               | Red Hat-based Linux                             |
| Fedora 32                                       | `1:2:6:c:f:1a:1c:79:3:21:28:29:2a:77:f9:fc:11`                  |                                                                   |               | Red Hat-based Linux                             |
| Fedora 36                                       | `1:2:6:c:f:1a:1c:79:3:21:28:29:2a:77:f9:fc:11`                  |                                                                   |               | Red Hat-based Linux                             |
| **Other**                                       |||||
| Linux Terminal Server Project thin client       | `1:3:6:c:f:1c:28:29:2a:42`                                      | `udhcp 0.9.9-pre`                                                 |               | Linux Terminal Server Project                   |
| Arch Linux 2022.10.01                           | `1:3:6:c:f:21:2a:78:79`                                         |                                                                   |               | Arch-based Linux                                |
| Mandriva 2011.0 (dhclient)                      | `1:1c:2:3:f:6:c` (ISC dhclient default)                         |                                                                   |               | ISC dhclient (Linux/Unix)                       |
| Mageia 1 (Drakxtools/dhclient)                  | `1:1c:2:3:f:6:c` (ISC dhclient default)                         |                                                                   |               | ISC dhclient (Linux/Unix)                       |
| Mandriva 2011.0 (KNetworkManager)               | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a:79:f9:fc:2a`                  |                                                                   |               | Debian Linux 7 (NetworkManager) *(Problematic)* |
| Gentoo Linux 11.2 (wcid/dhcpcd)                 | `1:79:21:3:6:c:f:1a:1c:2a:33:36:3a:3b:77`                       | `dhcpcd-5.2.12:Linux-`*version*`-gentoo-r1:`*arch*`:GenuineIntel` |               | dhcpcd client (Linux)                           |
| Unknown Arch Linux (dhcpcd)                     | `1:79:21:3:6:c:f:1a:1c:2a:33:36:3a:3b:77`                       | `dhcpcd-5.2.12:Linux-`*version*`-ARCH:`*arch*`:GenuineIntel`      |               | dhcpcd client (Linux)                           |
| Unknown Arch Linux (dhcpcd)                     | `1:79:21:3:6:c:f:1a:1c:2a:33:36:3a:3b:77`                       | `dhcpcd-5.5.6:Linux-`*version*`-ARCH:`*arch*`:GenuineIntel`       |               | dhcpcd client (Linux)                           |
| Parted Magic Live CD                            | `1:79:21:3:6:c:f:1a:1c:2a:33:36:3a:3b:77`                       | `dhcpcd-5.2.12:Linux-`*version*`-pmagic:`*arch*`:GenuineIntel`    | `PartedMagic` | Parted Magic (Linux)                            |
| Unknown Puppy Linux (dhcpcd)                    | `1:79:21:3:6:c:f:1a:1c:2a:33:36:3a:3b:77`                       | `dhcpcd 5.1.5`                                                    | `puppypc`_*_  | Puppy Linux                                     |
| Unknown Puppy Linux (dhcpcd)                    | `1:79:21:3:6:c:f:1a:1c:2a:33:36:3a:3b:77`                       | `dhcpcd-5.6.4:Linux-`*version*`:`*arch*`:GenuineIntel`            | `puppypc`_*_  | Puppy Linux                                     |
| openSUSE 11.4 (dhcpcd)                          | `3a:3b:1:1c:79:21:3:c:77:f:6:28:29:2a:1a:11:78:9:7:2c:2d:2f`    | `dhcpcd 3.2.3`                                                    |               | openSUSE Linux                                  |
| openSUSE 11.4, 12.1 (dhclient)                  | `1:1c:3:79:1a:c:f:77:6:28:29:57:55:56:2c:2d:2e:2f:2a`           |                                                                   |               | openSUSE Linux                                  |
| openSUSE 12.1 (dhcpcd)                          | `3a:3b:1:1c:79:21:3:c:77:f:6:28:29:2a:1a:11:78:9:7:2c:2d:2e:2f` | `dhcpcd 3.2.3`                                                    |               | openSUSE Linux                                  |
| SystemRescue unknown version (reported)         | `1:1c:2:3:f:6:c:2a` (ReactOS, Debian)                           |                                                                   | `sysrescue`   | SystemRescue                                    |
| SystemRescue 9.04 (Arch-based)                  | `1:2:6:c:f:1a:1c:79:3:21:28:29:2a:77:f9:fc:11`                  |                                                                   | `sysrescue`   | SystemRescue                                    |

### Linux Appliances
| **Device/OS**                                | **PRL**                                   | **Vendor ID**                                                | **Hostname**    | **Vendor OUI** | **Client Class**                                     |
| :------------                                | :------                                   | :------------                                                | :-----------    | :------------- | :---------------                                     |
| **Media Appliances**                         ||||||
| Samsung BD-P1500 Blu-ray player              | `1:3:6:c:f:11:17:1c:1d:1f:21:28:29:2a`    | `Linux 2.6.12-3.1-v10r15_340-uclibc-brcm 7440b0`             |                 |                | Linux media appliance                                |
| WD TV Live Streaming Media Player (1.04.12)  | `1:3:6:c:f:11:17:1c:1d:1f:21:28:29:2a`    | `Linux 2.6.22.19-49-4 mips`                                  |                 |                | Linux media appliance                                |
| Unknown appliance                            | `1:3:6:c:f:11:17:1c:1d:1f:21:28:29:2a`    | `Linux 2.6.14.398 armv4l`                                    |                 |                | Linux media appliance                                |
| Unknown appliance, possibly Vizio            | `1:3:6:c:f:11:17:1c:1d:1f:21:28:29:2a`    | `Linux 2.6.18-7.2 3548b0-smp`                                |                 |                | Linux media appliance                                |
| Unknown appliance, possibly Samsung          | `1:3:6:c:f:11:17:1c:1d:1f:21:28:29:2a`    | `Linux 2.6.28.9 7630`                                        |                 |                | Linux media appliance                                |
| Vizio unknown media appliance                | `1:3:6:c:f:11:17:1c:1d:1f:21:28:29:2a`    | `VIZIO VIA`                                                  |                 |                | Vizio media appliance (Linux)                        |
| CTRing DVR                                   | `1:3:6:c:f:1c`                            |                                                              |                 | `0:1E:C6`      | CTRing DVR (Linux)                                   |
| EverFocus video device                       | `1:3:6:c:f:1c`                            |                                                              |                 | `0:11:14`      | EverFocus / Honeywell DVR or camera (Linux)          |
| Pinetron DVR                                 | `1:3:6:c:f:1c`                            |                                                              |                 | `0:2:f1`       | Pinetron DVR (Linux)                                 |
| Rise Display                                 | `1:3:6:c:f:1c`                            |                                                              | `RISE-`_*_      |                | Rise Display media appliance (Linux)                 |
| Samsung unknown media appliance              | `1:3:6:c:f:1c:2a`                         | `udhcp `*version*`-VD Linux VDLinux.`*version*               |                 |                | Samsung media appliance (Linux)                      |
| Samsung unknown media appliance              | `1:3:6:c:f:1c:2a:7d`                      | `udhcp `*version*`-VD Linux VDLinux.`*version*               |                 |                | Samsung media appliance (Linux)                      |
| LG BP220 Blu-ray player                      | `1:3:6:c:f:1c:28:29:2a`                   | `udhcp 0.9.9-pre`                                            |                 |                | Linux media appliance                                |
| Sony SNC-RH124 IP camera                     | `1:3:6:c:f:1c:28:29:2a`                   | `udhcp 0.9.9-pre`                                            |                 |                | Linux media appliance                                |
| Roku 2 XS (3100X)                            | `1:3:6:f:c`                               |                                                              |                 |                | Printer or Linux media appliance (best guess)        |
| Sony Bravia KDL-40EX523 TV                   | `1:3:6:f:1c:c:7:9:2a:30:31`               |                                                              |                 |                | Sony media appliance (Linux)                         |
| Sharp Aquos TV                               | `1:3:6:36`                                |                                                              |                 |                | Sharp media appliance                                |
| LG Infinia 47LE8500 TV                       | `1:3:f:6:c:1c`                            |                                                              |                 |                | LG media appliance (Linux)                           |
| TiVo Roamio                                  | `1:1c:2:3:f:6:c`                          |                                                              | `TIVO-`*serial* |                | TiVo media appliance (Linux)                         |
| Unknown appliance, possibly Vizio            | `1:79:21:3:6:c:f:1a:1c:2a:33:36:3a:3b:77` | `dhcpcd-5.2.10:Linux-2.6.28.9:7631:BCM97xxx Settop Platform` |                 |                | Linux media appliance                                |
| **SOHO Network Appliances**                  ||||||
| Asus unknown network appliance               | `1:3:6:c:f:1c:28:29:2a:79` (Linksys)      | `udhcp 0.9.9-pre`                                            |                 |                | Asus or Linksys network appliance (Linux)            |
| Asus unknown network appliance               | `1:3:6:c:f:1c:2a:79:21:f9`                | `udhcp 1.17.4`                                               |                 |                | Asus network appliance (Linux)                       |
| Belkin unknown network appliance             | `1:3:6:c:f:1c:21:2c`                      |                                                              |                 |                | Belkin network appliance (Linux)                     |
| Belkin unknown network appliance             | `1:3:79:6:c:f:1c:32:21`                   |                                                              |                 |                | Belkin network appliance (Linux)                     |
| Belkin unknown network appliance             | `1:3:6:c:f:1c:32:21`                      | `udhcp 0.9.7`                                                |                 |                | Apple or Belkin network appliance (Linux)            |
| D-Link DIR-605L wireless router              | `1:3:6:c:f:1c:2c:2e:2f`                   |                                                              |                 |                | D-Link network appliance (Linux)                     |
| D-Link DIR-615 wireless router               | `1:3:6:2c:f:2e:2f` (Cradlepoint)          |                                                              | `DIR-`_*_       |                | D-Link network appliance (Linux)                     |
| D-Link DIR-615 wireless router               | `1:3:6:c:f:1c:28:29:2a:2c:2e:2f`          |                                                              |                 |                | D-Link network appliance (Linux)                     |
| D-Link DIR-655 wireless router               | `1:3:6:c:f:1c:21:28:29:2a:2c:2e:2f`       |                                                              |                 |                | D-Link network appliance (Linux)                     |
| D-Link DI-624 wireless router                | `1:3:6:f` (Xbox, DRAC, Netgear, etc)      | `MSFT 98`                                                    |                 |                | D-Link network appliance (Linux)                     |
| D-Link WBR-1310 wireless router              | `1:3:6:f` (Xbox, DRAC, Netgear, etc)      | `MSFT 98`                                                    |                 |                | D-Link network appliance (Linux)                     |
| Linksys WRT54-GL v1.1 (Tomato 1.28)          | `1:3:6:c:f:1c:2a`                         | `udhcp 1.14.4`                                               |                 |                | Linux appliance                                      |
| Linksys BEFSR41v3 router (1.05.00)           | `1:f:3:6:2c:2e:2f`                        |                                                              |                 |                | Linksys network appliance (Linux)                    |
| Linksys unknown network appliance            | `1:3:f:6`                                 |                                                              | `Cisco`_*_      |                | Linksys network appliance                            |
| Linksys unknown network appliance            | `1:3:6:c:f:1c:2a:d4`                      | `udhcp 1.15.2`                                               |                 |                | Linksys network appliance (Linux)                    |
| Linksys unknown network appliance            | `1:3:6:c:f:1c:2a:79`                      | `udhcp 1.15.2`                                               |                 |                | Linksys network appliance (Linux)                    |
| Linksys unknown network appliance            | `1:3:6:c:f:1c:2c`                         | `udhcp 0.9.8`                                                |                 |                | Linksys network appliance (Linux)                    |
| Linksys unknown network appliance            | `1:3:6:c:f:1c:2c:21:f9 `                  | `udhcp 0.9.8`                                                |                 |                | Linksys network appliance (Linux)                    |
| Linksys unknown network appliance            | `1:3:6:c:f:1c:28:29:2a:79` (Asus)         | `udhcp 0.9.9-pre`                                            |                 |                | Asus or Linksys network appliance (Linux)            |
| Netgear RP614v4 router                       | `1:3:6:c:f:1c`                            | `udhcp 0.9.9-pre`                                            | `RP614v4`       |                | Netgear network appliance (Linux)                    |
| Netgear WNR2000 wireless router              | `1:3:6:c:f:1c:21:79`                      | `udhcp 0.9.9-pre`                                            |                 |                | Netgear network appliance (Linux)                    |
| Netgear WNR2000v2 wireless router            | `1:3:6:c:f:1c:21:2c:79`                   | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WGR614v9 wireless router             | `1:3:6:c:f:1c:21:2c:79`                   | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WGR614v10 wireless router            | `1:3:6:c:f:1c:21:2c:79`                   | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WGR614v10 wireless router            | `1:3:6:c:f:1c:21:2c:79:f9`                | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WNR1000v3 wireless router            | `1:3:6:c:f:1c:21:2c:79:f9`                | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WNDR3400 wireless router             | `1:3:6:c:f:1c:21:2c:79:f9`                | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WPN824N wireless router              | `1:79:3:6:c:f:1c:21`                      | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WNR2000v3 wireless router            | `1:79:3:6:c:f:1c:21`                      | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WNR2000v4 wireless router            | `1:79:f9:3:6:c:f:1c:21:2b`                | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WNDR3700v4 wireless router           | `1:79:f9:3:6:c:f:1c:21:2b`                | `udhcp 0.9.8`                                                |                 |                | Netgear network appliance (Linux)                    |
| Netgear WPN824 wireless router               | `3:1:6:f:c`                               |                                                              |                 |                | Netgear network appliance (Linux)                    |
| TP-Link WR720N wireless router               | `1:3:6:f:21:2b:2c:2e:2f:79:f9`            |                                                              |                 |                | TP-Link network appliance (Linux)                    |
| Western Digital MyNet N600 wireless router   | `1:3:6:f:21:2c:2e:2f:79:f9:2b`            |                                                              |                 |                | Western Digital network appliance (Linux)            |
| **Other Appliances**                         ||||||
| Amazon Kindle Paperwhite                     | `1:3:6:c:f:1c:2a`                         | `udhcp 1.17.1`                                               |                 |                | Linux appliance                                      |
| Dell Data Protection                         | `1:3:6:c:f:1c:2a`                         | `udhcp 1.20.2`                                               |                 |                | Linux appliance                                      |
| HID VertX (CBORD Squadron) access controller | `1:3:6:f:1c:2a:e0:e1:e2:e3`               | `CSGold Squadron`                                            |                 |                | HID VertX / CBORD Squadron access controller (Linux) |
| Obvius data acquisition device               | `1:3:6:c:f:1c`                            |                                                              |                 | `00:1E:C6`     | Obvius data acquisition appliance (Linux)            |
| StarDot NetCam XL                            | `1:3:6:c:f:1c:2a:28`                      | `uClinux 2.0.39.1 m68knommu`                                 |                 |                | uClinux (Embedded/Microcontroller Linux)             |
| Unknown Linux appliance                      | `1:3:6:c:f:11:17:1c:1d:1f:21:28:29:2a:77` | `Linux 2.6.18_pro500-hermes-hd_oste ppc`                     |                 |                | Linux appliance                                      |
### Mobile Linux
| **Device/OS**                                        | **PRL**                                 | **Vendor ID**                                                                       | **Hostname**          | **Client Class**                                       |
| :------------                                        | :------                                 | :------------                                                                       | :-----------          | :---------------                                       |
| **HP webOS**                                         |||||
| HP webOS 3.0.5 (dhclient via GUI)                    | `1:1c:2:3:f:6:c` (ISC dhclient default) |                                                                                     |                       | ISC dhclient (Linux/Unix)                              |
| HP webOS 3.0.5 (dhclient via CLI)                    | `1:1c:2:3:f:6:c:2c:2f`                  |                                                                                     |                       | Ubuntu Linux 4.10 - 8.04 *(slightly problematic)*      |
| **Google Chrome OS**                                 |||||
| Google Chrome OS                                     | `1:1c:2:3:f:6:c` (ISC dhclient default) |                                                                                     |                       | ISC dhclient (Linux/Unix)                              |
| Google Chrome OS (201109211 nightly)                 | `1:79:21:3:6:c:f:1a:1c:33:36:3a:3b:77`  | `dhcpcd 5.1.4`                                                                      |                       | Google Chrome OS                                       |
| **Google Android**                                   |||||
| BrightSign HD220                                     | *(Unknown)*                             | `dhcpcd-5.5.4:Linux-2.6.39`*build*`BrightSign HD220`                                |                       | BrightSign media appliance (Android)                   |
| **Google Android 2**                                 |||||
| Android 2.x - Unknown                                | `1:79:21:3:6:f:1c:2c:33:3a:3b:77`       | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.1 / 2.2 / 2.3                         |
| Android 2.1 - B&N Nook Simple Touch                  | `1:79:21:3:6:1c:33:3a:3b`               | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.1 / 2.2 / 2.3                         |
| Android 2.2 - Samsung Fascinate (Galaxy S)           | `1:79:21:3:6:1c:33:3a:3b`               | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.1 / 2.2 / 2.3                         |
| Android 2.2.0 - HTC Incredible                       | `1:79:21:3:6:1c:33:3a:3b`               | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.1 / 2.2 / 2.3                         |
| Android 2.3.3 - HTC Evo 4G                           | `1:79:21:3:6:1c:33:3a:3b`               | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.1 / 2.2 / 2.3                         |
| Android 2.3.3 - HTC Evo Shift 4G                     | `1:79:21:3:6:1c:33:3a:3b`               | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.1 / 2.2 / 2.3                         |
| Android 2.2.1 - Samsung Epic 4G (Galaxy S)           | `1:79:21:3:6:f:1c:33:3a:3b`             | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.2                                     |
| Android 2.2 - Samsung Moment                         | `1:79:21:3:6:f:1c:33:3a:3b`             | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.2                                     |
| Android 2.2 - Motorola Droid family                  | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.32.9-`*build*`:armv7l:mapphone_CDMA`                       |                       | Motorola Droid family (Android 2.2)                    |
| Android 2.2 - Motorola Triumph                       | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.32.59-perf:armv7l:TRIUMPH`                                 |                       | Motorola Triumph (Android 2.2)                         |
| Android 2.2.2 - Cisco Cius                           | `1:96:3:6:f:23:42`                      | `Cisco Cius `*version*                                                              |                       | Cisco Cius (Android 2.2)                               |
| Android 2.3.4 - HTC Evo 3D                           | `1:79:21:3:6:f:1c:33:3a:3b:77`          | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.3                                     |
| Android 2.3.4 - HTC Incredible                       | `1:79:21:3:6:f:1c:33:3a:3b:77`          | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.3                                     |
| Android 2.3.5 - Samsung Nexus S                      | `1:79:21:3:6:f:1c:33:3a:3b:77`          | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.3                                     |
| Android 2.3.7 - LG Optimus S (Cyanogen 7)            | `1:79:21:3:6:f:1c:33:3a:3b:77`          | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.3                                     |
| Android 2.3.7 - Samsung Nexus S                      | `1:79:21:3:6:f:1c:33:3a:3b:77`          | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.3                                     |
| Android 2.3.7 - Samsung Moment (Cyanogen 7)          | `1:79:21:3:6:f:1c:33:3a:3b:77`          | `dhcpcd 4.0.15`                                                                     |                       | Google Android 2.3                                     |
| Android 2.3 - Amazon Kindle Fire                     | `1:79:21:3:6:f:1c:33:3a:3b:77`          | `dhcpcd 4.0.15`                                                                     | `kindle-`_*_          | Amazon Kindle Fire (Android 2.3)                       |
| Android 2.3 - Samsung Nexus S (Herring)              | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.35.7-`*build*`:armv7l:herring`                             |                       | Samsung Nexus S (Android 2.3)                          |
| Android 2.3 - HTC Flyer                              | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.35.10-`*build*`:armv7l:flyer`                              |                       | HTC Flyer / Evo View 4G (Android 2.3)                  |
| Android 2.3 - HP TouchPad (Tenderloin)               | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.35-palm-tenderloin:armv7l:TENDERLOIN`                      |                       | HP TouchPad (Android 2.3)                              |
| Android 2.3 - Motorola Droid family                  | `1:21:3:6:f:1c:2c:33:3a:3b`             | `dhcpcd-5.2.10:Linux-2.6.35.7-`*build*`:armv7l:mapphone_CDMA`                       |                       | Motorola Droid family (Android 2.3)                    |
| Android 2.3 - Vizio vTab 1008 (Brownstone)           | `1:21:3:6:c:f:1c:2a:33:3a:3b:77`        | `dhcpcd-5.2.10:Linux-2.6.35.7+:armv7l:Brownstone`                                   |                       | Vizio vTab 1008 (Android 2.3)                          |
| **Google Android 3**                                 |||||
| Android 3.x - Acer Iconia A100 (VanGogh)             | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.3:armv7l:vangogh`                                       |                       | Acer Iconia Tab A100 (Android 3.0 / 3.1)               |
| Android 3.x - Acer Iconia A500 (Picasso)             | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.3:armv7l:picasso`                                       |                       | Acer Iconia Tab A500 (Android 3.0 / 3.1)               |
| Android 3.x - Acer Iconia A500 (Picasso)             | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.3+:armv7l:picasso`                                      |                       | Acer Iconia Tab A500 (Android 3.0 / 3.1)               |
| Android 3.x - Acer Iconia A500 (Picasso)             | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.3HoneyVillain-`*version*`:armv7l:picasso`               |                       | Acer Iconia Tab A500 (Android 3.0 / 3.1)               |
| Android 3.x - Acer Iconia A500 (Thor kernel)         | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.4-thor-`*version*`:armv7l:ventana`                      |                       | Acer Iconia Tab A500 (Android 3.0 / 3.1)               |
| Android 3.x - Acer Iconia A500 (Thor kernel)         | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.36.4-thor-`*version*`:armv7l:ventana`                      |                       | Acer Iconia Tab A500 (Android 3.0 / 3.1)               |
| Android 3.x - Motorola Xoom (Stingray)               | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.3-`*build*`:armv7l:stingray`                            |                       | Motorola Xoom (Android 3.0 / 3.1)                      |
| Android 3.x - Motorola Xoom (Stingray)               | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.4-Tiamat_Xoom-`*version*`-`*build*`:armv7l:stingray`    |                       | Motorola Xoom (Android 3.0 / 3.1)                      |
| Android 3.x - Samsung Galaxy Tab 7.0 Plus (P6210)    | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36-P6210`*version*`-`*build*`:armv7l:SMDKC210`             |                       | Samsung Galaxy Tab 7.0 Plus (Android 3.0 / 3.1)        |
| Android 3.x - Samsung Galaxy Tab 7.7 (I815)          | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36-I815`*version*`-`*build*`:armv7l:SMDKC210`              |                       | Samsung Galaxy Tab 7.7 (Android 3.0 / 3.1)             |
| Android 3.x - Samsung Galaxy Tab 8.9 (P7310)         | `1:21:3:6:1c:33:3a:3b`                  | `KT_SD_MV_SAMSUNG_GT-P7310`                                                         |                       | Samsung Galaxy Tab 8.9 (Android 3.0 / 3.1)             |
| Android 3.x - Samsung Galaxy Tab 10.1 (P3)           | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.3:armv7l:p3`                                            |                       | Samsung Galaxy Tab 10.1 (Android 3.0 / 3.1)            |
| Android 3.x - Samsung Galaxy Tab 10.1 (P7510)        | `1:21:3:6:1c:33:3a:3b`                  | `KT_SD_MV_SAMSUNG_GT-P7510`                                                         |                       | Samsung Galaxy Tab 10.1 (Android 3.0 / 3.1)            |
| Android 3.x - Toshiba Thrive AT105 (Antares)         | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.3-`*build*`:armv7l:antares`                             |                       | Toshiba Thrive AT105 (Android 3.0 / 3.1)               |
| Android 3.x - Toshiba Thrive AT105 (Antares)         | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-2.6.36.3-`*version*`-`*build*`:armv7l:antares`                 |                       | Toshiba Thrive AT105 (Android 3.0 / 3.1)               |
| Android 3.2 - Acer Iconia A100 (VanGogh)             | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.39.4+:armv7l:vangogh`                                      |                       | Acer Iconia Tab A100 (Android 3.2)                     |
| Android 3.2 - Acer Iconia A200 (Picasso_E)           | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.39.4+:armv7l:picasso_e`                                    |                       | Acer Iconia Tab A200 (Android 3.2)                     |
| Android 3.2 - Acer Iconia A500 (Picasso)             | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.39.4+:armv7l:picasso`                                      |                       | Acer Iconia Tab A500 (Android 3.2)                     |
| Android 3.2 - Motorola Xoom (Stingray)               | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.39.4-`*build*`:armv7l:stingray`                            |                       | Motorola Xoom (Android 3.2)                            |
| Android 3.2 - Motorola Xoom (Stingray)               | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.39.4-`*version*`-`*build*`:armv7l:stingray`                |                       | Motorola Xoom (Android 3.2)                            |
| Android 3.2 - Motorola Xoom (Stingray)               | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.39.4-Tiamat-`*version*`-`*build*`:armv7l:stingray`         |                       | Motorola Xoom (Android 3.2)                            |
| Android 3.2 - Sony Tablet S (NBX03)                  | `1:21:3:6:c:f:1c:33:3a:3b:77`           | `dhcpcd-5.2.10.`*build*`:Linux-2.6.39.4:armv7l:nbx03`                               |                       | Sony Tablet S (Android 3.2)                            |
| Android 3.2 - Sony Tablet S (NBX03)                  | `1:21:3:6:c:f:1c:33:3a:3b:77`           | `dhcpcd-5.2.10.`*build*`:Linux-2.6.39.4:armv7l:nbx03`                               |                       | Sony Tablet S (Android 3.2)                            |
| Android 3.x - Toshiba Thrive AT105 (Antares)         | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.39.4-`*build*`:armv7l:antares`                             |                       | Toshiba Thrive AT105 (Android 3.2)                     |
| **Google Android 4**                                 |||||
| Android 4.0 - Amazon Kindle Fire HD                  | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:OMAP4 blaze board`          | `kindle-`_*_          | Amazon Kindle Fire HD (Android 4.0)                    |
| Android 4.0 - Amazon Kindle Fire HD                  | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:OMAP4 Bowser4 board`        | `kindle-`_*_          | Amazon Kindle Fire HD (Android 4.0)                    |
| Android 4.0 - Amazon Kindle Fire HD                  | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.21-`*version*`-`*build*`:armv7l:OMAP4 Bowser board`        | `kindle-`_*_          | Amazon Kindle Fire HD (Android 4.0)                    |
| Android 4.0 - Amazon Kindle Fire HD                  | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10`                                                                     | `kindle-`_*_          | Amazon Kindle Fire HD (Android 4.0)                    |
| Android 4.0 - Barnes & Noble Nook (HD+?)             | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.31:armv7l:OMAP4 ovation board`                             | `nook-`_*_            | B&N Nook family (Android 4.0)                          |
| Android 4.0 - Barnes & Noble Nook (HD+?)             | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.31:armv7l:OMAP4 Hummingbird board`                         | `nook-`_*_            | B&N Nook family (Android 4.0)                          |
| Android 4.0 - HTC Amaze 4G (Ruby)                    | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:ruby`                                  |                       | HTC Amaze 4G (Android 4.0)                             |
| Android 4.0 - HTC Evo 3D CDMA (Shooter)              | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:shooter`                               |                       | HTC Evo 3D / Evo V 4G (Android 4.0)                    |
| Android 4.0 - HTC Evo 3D GSM (ShooterU)              | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:shooter_u`                             |                       | HTC Evo 3D / Evo V 4G (Android 4.0)                    |
| Android 4.0 - HTC Evo 4G LTE (Jet)                   | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:jet`                        |                       | HTC Evo 4G LTE (Android 4.0)                           |
| Android 4.0 - HTC Evo Design 4G (Kingdom)            | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:kingdom`                               |                       | HTC Evo Design 4G / Hero S (Android 4.0)               |
| Android 4.0 - HTC HD2 (Leo)                          | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.32_tytung_ics_r`*version*`:armv7l:htcleo`                  |                       | HTC HD2 (Android 4.0)                                  |
| Android 4.0 - HTC Incredible 4G (Fighter)            | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:fighter`                    |                       | HTC Incredible 4G (Android 4.0)                        |
| Android 4.0 - HTC One S (Ville)                      | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:ville`                      |                       | HTC One S (Android 4.0)                                |
| Android 4.0 - HTC One SV (K2_CL)                     | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.21-`*build*`:armv7l:k2_cl`                                 |                       | HTC One SV (Android 4.0)                               |
| Android 4.0 - HTC One V (Primo)                      | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:primoc`                                |                       | HTC One V (Android 4.0)                                |
| Android 4.0 - HTC One VX (TC2)                       | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.21-`*build*`:armv7l:tc2`                                   |                       | HTC One VX (Android 4.0)                               |
| Android 4.0 - HTC One X (Elite/Evita)                | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:elite`                      |                       | HTC One X (Android 4.0)                                |
| Android 4.0 - HTC One X (EndeavorU)                  | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-2.6.39.4-`*build*`:armv7l:endeavoru`                           |                       | HTC One X (Android 4.0)                                |
| Android 4.0 - HTC Rezound (Vigor)                    | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:vigor`                                 |                       | HTC Rezound (Android 4.0)                              |
| Android 4.0 - HTC Sensation (Pyramid)                | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:pyramid`                               |                       | HTC Sensation (Android 4.0)                            |
| Android 4.0 - HTC ThunderBolt (Mecha)                | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:mecha`                                 |                       | HTC ThunderBolt (Android 4.0)                          |
| Android 4.0 - HTC Vivid (Holiday)                    | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-`*build*`:armv7l:holiday`                               |                       | HTC Vivid / Raider 4G / Velocity 4G (Android 4.0)      |
| Android 4.0 - LG Optimus L9 (P769)                   | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.21:armv7l:LGE P769 board`                                  |                       | LG Optimus L9 (Android 4.0)                            |
| Android 4.0 - LG Optimus LTE                         | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-perf:armv7l:LGE I BOARD MSM8X60`                         |                       | LG Optimus LTE / Nitro HD / Spectrum (Android 4.0)     |
| Android 4.0 - LG Optimus LTE2 (D1L)                  | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8:armv7l:LGE MSM8960 D1L`                                  |                       | LG Optimus LTE2 (Android 4.0)                          |
| Android 4.0 - LG Optimus Regard                      | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8:armv7l:LGE MSM8960 Lx`                                   |                       | LG Optimus Regard (Android 4.0)                        |
| Android 4.0 - LG Venice (LG730)                      | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-perf:armv7l:LGE MSM7X30 U0`                              |                       | LG Venice (Android 4.0)                                |
| Android 4.0 - Motorola Atrix HD (Qinara)             | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:Qinara`                     |                       | Motorola Atrix HD (Android 4.0)                        |
| Android 4.0 - Motorola Droid Razr HD (Vanquish)      | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:Vanquish`                   |                       | Motorola Droid Razr HD (Android 4.0)                   |
| Android 4.0 - Motorola Droid family                  | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`:armv7l:mapphone_CDMA`                          |                       | Motorola Droid family (Android 4.0)                    |
| Android 4.0 - Pantech Marauder (Star Q)              | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8:armv7l:QCT MSM8960 STARQ`                                |                       | Pantech Marauder (Android 4.0)                         |
| Android 4.0 - Pantech Presto                         | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-perf:armv7l:PANTECH MSM8X60 PRESTO`                      |                       | Pantech Presto (Android 4.0)                           |
| Android 4.0 - Samsung Galaxy family                  | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.15-`*build*`-user:armv7l:SMDK4x12`                         |                       | Samsung Galaxy family (Android 4.0)                    |
| Android 4.0 - Samsung Galaxy family                  | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.41:armv7l:SMDK4210`                                        |                       | Samsung Galaxy family (Android 4.0)                    |
| Android 4.0 - Samsung Galaxy family                  | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.35-Siyah-`*version*`:armv7l:SMDK4210`                      |                       | Samsung Galaxy family (Android 4.0)                    |
| Android 4.0 - Samsung Galaxy Axiom (R830)            | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`:armv7l:SAMSUNG INFINITE`                       |                       | Samsung Galaxy Axiom (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Exhilarate (I577)       | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.8-perf-I577`*carrier*`-`*build*`:armv7l:SGH-I577`          |                       | Samsung Galaxy Exhilarate (Android 4.0)                |
| Android 4.0 - Samsung Galaxy Express                 | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`:armv7l:SAMSUNG EXPRESS`                        |                       | Samsung Galaxy Express (Android 4.0)                   |
| Android 4.0 - Samsung Galaxy Nexus (Tuna)            | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`:armv7l:Tuna`                                   |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Tuna)            | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`:armv7l:Tuna`                                   |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Tuna)            | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`-`*build*`:armv7l:Tuna`                       |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Tuna)            | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8+:armv7l:Tuna`                                            |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Tuna)            | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16:armv7l:Tuna`                                            |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Cyanogen)        | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.14-cyanogenmod-`*version*`-`*build*`:armv7l:Tuna`          |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Custom)          | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-GLaDOS-`*version*`:armv7l:Tuna`                          |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Custom)          | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-PopcornKernel-`*build*`:armv7l:Tuna`                     |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Custom)          | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.16-franco.Kernel-nightly-12:armv7l:Tuna`                   |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Custom)          | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.18-imoseyon-`*version*`-`*build*`-`*build*`:armv7l:Tuna`   |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Custom)          | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.18-tuna-faux123-`*version*`:armv7l:Tuna`                   |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Nexus (Custom)          | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.33-leanKernel-`*version*`-`*build*`-`*build*`:armv7l:Tuna` |                       | Samsung Galaxy Nexus (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Note (E160S)            | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.8-`*version*`:armv7l:SHV-E160S`                            |                       | Samsung Galaxy Note (Android 4.0)                      |
| Android 4.0 - Samsung Galaxy Note (I717)             | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.8-perf-I717`*version*`-`*build*`:armv7l:SGH-I717`          |                       | Samsung Galaxy Note (Android 4.0)                      |
| Android 4.0 - Samsung Galaxy Note (N7000)            | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.15-N7000`*version*`-`*build*`:armv7l:SMDK4210`             |                       | Samsung Galaxy Note (Android 4.0)                      |
| Android 4.0 - Samsung Galaxy Reverb (M950)           | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-perf-`*build*`:armv7l:SPH-M950                           |                       | Samsung Galaxy Reverb (Android 4.0)                    |
| Android 4.0 - Samsung Galaxy Rush (M830)             | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-perf-`*build*`:armv7l:SPH-M830                           |                       | Samsung Galaxy Rush (Android 4.0)                      |
| Android 4.0 - Samsung Galaxy S (Aries)               | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`:armv7l:aries`                                  |                       | Samsung Galaxy S (Android 4.0)                         |
| Android 4.0 - Samsung Galaxy S Blaze 4G (T769)       | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.8-perf-`*version*`-`*build*`:armv7l:SGH-T769`              |                       | Samsung Galaxy S Blaze 4G (Android 4.0)                |
| Android 4.0 - Samsung Galaxy S2 (T989)               | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.8-perf-T989`*version*`-`*build*`:armv7l:SGH-T989`          |                       | Samsung Galaxy S II (Android 4.0)                      |
| Android 4.0 - Samsung Galaxy S2 (I777)               | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.15-I777`*version*`-`*build*`:armv7l:SMDK4210`              |                       | Samsung Galaxy S II (Android 4.0)                      |
| Android 4.0 - Samsung Galaxy S2 Epic 4G Touch (D710) | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.15-SPH-D710`*version*`-`*build*`:armv7l:SMDK4210`          |                       | Samsung Galaxy S II Epic 4G Touch (Android 4.0)        |
| Android 4.0 - Samsung Galaxy S2 Skyrocket (I727)     | `1:21:3:6:1c:33:3a:3b`                  | `dhcpcd-5.2.10:Linux-3.0.8-perf-I727`*version*`-`*build*`:armv7l:SGH-I727`          |                       | Samsung Galaxy S II Skyrocket (Android 4.0)            |
| Android 4.0 - Samsung Galaxy S3                      | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`-user:armv7l:SAMSUNG M2_`*carrier*              |                       | Samsung Galaxy S III (Android 4.0)                     |
| Android 4.0 - Samsung Galaxy Tab 10.1 (M380W)        | `1:21:3:6:1c:33:3a:3b`                  | `KT_SD_MV_SAMSUNG_SHW-M380W`                                                        |                       | Samsung Galaxy Tab 10.1 (Android 4.0)                  |
| Android 4.0 - Samsung Galaxy Tab 2 7.0 (Espresso)    | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`-user:armv7l:Espresso`                          |                       | Samsung Galaxy Tab 2 7.0 (Android 4.0)                 |
| Android 4.0 - Samsung Galaxy Tab 2 7.0 (Espresso)    | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`-user:armv7l:SAMSUNG ESPRESSO`                  |                       | Samsung Galaxy Tab 2 7.0 (Android 4.0)                 |
| Android 4.0 - Samsung Galaxy Tab 2 10.1 (Espesso 10) | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`-user:armv7l:Espresso10`                        |                       | Samsung Galaxy Tab 2 10.1 (Android 4.0)                |
| Android 4.0 - Samsung Nexus S (Herring)              | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`:armv7l:herring`                                |                       | Samsung Nexus S (Android 4.0)                          |
| Android 4.0 - Samsung Nexus S (Herring)              | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8+:armv7l:herring`                                         |                       | Samsung Nexus S (Android 4.0)                          |
| Android 4.0 - Samsung Nexus S (Custom?)              | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.14-ck1-cfs-`*build*`-dirty:armv7l:herring`                 |                       | Samsung Nexus S (Android 4.0)                          |
| Android 4.0 - Samsung Nexus S (Cyanogen)             | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.36-Cyanogenmod-`*build*`:armv7l:herring`                   |                       | Samsung Nexus S (Android 4.0)                          |
| Android 4.0 - Samsung Stratosphere 4G (Aegis 2)      | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8-`*build*`:armv7l:SAMSUNG AEGIS2`                         |                       | Samsung Stratosphere 4G (Android 4.0)                  |
| Android 4.0 - Sony Xperia family                     | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8+:armv7l:riogrande`                                       |                       | Sony Xperia family (Android 4.0)                       |
| Android 4.0 - Sony Xperia Acro S (LT26w)             | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.0.8+`*version*`-`*build*`-`*build*`-`*build*`:armv7l:fuji`   |                       | Sony Xperia family (Android 4.0)                       |
| Android 4.0 - ZTE Force N9100 (Hayes)                | `1:21:3:6:f:1c:33:3a:3b:77`             | `dhcpcd-5.2.10:Linux-3.0.8-perf-`*build*`:armv7l:ZTE MSM8960 HAYES`                 |                       | ZTE Force N9100 (Android 4.0)                          |
| Android 4.0 - CyanogenMod 9                          | *(Unknown)*                             | `dhcpcd-5.2.10:Linux-2.6.39.4_CM9-`*                                                |                       | CyanogenMod 9 (Android 4.0)                            |
| Android 4.1 - Asus Nexus 7                           | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10`                                                                     |                       | Google Android 4.0 / 4.1                               |
| Android 4.1 - Samsung Captivate Glide (I927)         | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.1.10-I927UCLJ3-CL970642:armv7l:n1`                           |                       | Samsung Captivate Glide / Galaxy S Glide (Android 4.1) |
| Android 4.1 - Samsung Galaxy S2 (I777)               | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10:Linux-3.1.0-R59-Siyah-i777-`*version*`-S-:armv7l:SMDK4210`           |                       | Samsung Galaxy S II (Android 4.1)                      |
| Android 4.1 - Samsung Galaxy S3                      | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.2.10`                                                                     |                       | Google Android 4.0 / 4.1                               |
| Android 4.2 - Asus Nexus 7                           | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.5.6`                                                                      |                       | Google Android 4.2                                     |
| Android 4.x - Amazon Fire TV Stick                   | `1:21:3:6:f:1c:33:3a:3b`                | `dhcpcd-5.5.6`                                                                      |                       | Google Android 4.2                                     |
| **Google Android 6**                                 |||||
| Android 6.0.0                                        | `1:3:6:f:1a:1c:33:3a:3b`                | `android-dhcp-6.0`                                                                  |                       | Google Android 6.0                                     |
| Android 6.0.1                                        | `1:3:6:f:1a:1c:33:3a:3b`                | `android-dhcp-6.0.1`                                                                |                       | Google Android 6.0                                     |
| **Google Android 7**                                 |||||
| Android 7.0.0                                        | `1:3:6:f:1a:1c:33:3a:3b`                | `android-dhcp-7.0`                                                                  |                       | Google Android 7.0                                     |
| Android 7.1.0                                        | `1:3:6:f:1a:1c:33:3a:3b`                | `android-dhcp-7.1`                                                                  |                       | Google Android 7.1                                     |
| Android 7.1.1                                        | `1:3:6:f:1a:1c:33:3a:3b`                | `android-dhcp-7.1.1`                                                                |                       | Google Android 7.1                                     |
| Android 7.1.2                                        | `1:3:6:f:1a:1c:33:3a:3b`                | `android-dhcp-7.1.2`                                                                |                       | Google Android 7.1                                     |
| Android 7.x                                          | `1:3:6:f:1a:1c:33:3a:3b`                | `android-dhcp-N`                                                                    |                       | Google Android 7.x                                     |
| Android 7.x                                          | `1:3:6:f:1a:1c:33:3a:3b:2b`             | `android-dhcp-N`                                                                    |                       | Google Android 7.x                                     |
| **Google Android 8**                                 |||||
| Android 8.0.0 - Samsung Galaxy S7                    | `1:3:6:f:1a:1c:33:3a:3b:2b`             | `android-dhcp-8.0.0`                                                                | `Samsung-Galaxy-S7`   | Google Android 8.x                                     |
| Android 8.x                                          | *(Unknown)*                             | `android-dhcp-O`                                                                    |                       | Google Android 8.x                                     |
| **Google Android 9**                                 |||||
| Android 9                                            | *(Unknown)*                             | `android-dhcp-9`                                                                    |                       | Google Android 9                                       |
| **Google Android 10**                                |||||
| Android 10                                           | *(Unknown)*                             | `android-dhcp-10`                                                                   |                       | Google Android 10                                      |
| **Google Android 11**                                |||||
| Android 11 - Google Pixel 4a                         | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-11`                                                                   | `Pixel-4a`            | Google Android 11                                      |
| Android 11 - Samsung Galaxy S10                      | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-11`                                                                   | `Galaxy-S10`          | Google Android 11                                      |
| Android 11 - Samsung Galaxy S20 FE 5G                | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-11`                                                                   | _*_`Galaxy-S20-FE-5G` | Google Android 11                                      |
| Android 11 - Samsung Galaxy S21                      | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-11`                                                                   | _*_`-S21`             | Google Android 11                                      |
| Android 11                                           | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-11`                                                                   |                       | Google Android 11                                      |
| **Google Android 12**                                |||||
| Android 12 - Google Pixel 6 Pro                      | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-12`                                                                   | `Pixel-6-Pro`         | Google Android 12                                      |
| Android 12 - Samsung Galaxy S21                      | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-12`                                                                   | _*_`-S21`             | Google Android 12                                      |
| Android 12                                           | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-12`                                                                   |                       | Google Android 12                                      |
| **Google Android 13**                                |||||
| Android 13 - Google Pixel 6 Pro                      | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-13`                                                                   | `Pixel-6-Pro`         | Google Android 13                                      |
| Android 13                                           | `1:3:6:f:1a:1c:33:3a:3b:2b:72:6c`       | `android-dhcp-13`                                                                   |                       | Google Android 13                                      |

## Unix
| **Device/OS**                     | **PRL**                                   | **Vendor ID**  | **Client Class**              |
| :------------                     | :------                                   | :------------  | :---------------              |
| **Sun**                           ||||
| Sun Solaris 10 (SunOS 5.10) Intel | `1:3:6:c:f:1c:2b`                         | `SUNW.i86pc`   | SunOS-based (Solaris/Illumos) |
| OpenIndiana (SunOS 5.11) Intel    | `1:3:6:c:f:1c:2b`                         |                | SunOS-based (Solaris/Illumos) |
| Joyent SmartOS (SunOS 5.11) Intel | `1:3:6:c:f:1c:2b`                         | `SUNW.i86pc`   | SunOS-based (Solaris/Illumos) |
| **BSD**                           ||||
| FreeBSD 8.2                       | `1:1c:2:79:3:f:6:c`                       |                | FreeBSD                       |
| FreeBSD 9.0                       | `1:1c:2:79:3:f:6:c`                       |                | FreeBSD                       |
| PC-BSD 9.0                        | `1:1c:2:79:3:f:6:c`                       |                | FreeBSD                       |
| DragonFlyBSD 2.10 (dhclient)      | `1:1c:2:3:f:6:c` (ISC dhclient default)   |                | ISC dhclient (Linux/Unix)     |
| NetBSD 5.1 (dhclient 3.0.3)       | `1:1c:2:3:f:6:c` (ISC dhclient default)   |                | ISC dhclient (Linux/Unix)     |
| NetBSD 5.1 (dhcpcd 5.1.3)         | `1:79:21:3:6:c:f:1a:1c:2a:33:36:3a:3b:77` | `dhcpcd 5.1.3` | dhcpcd client (BSD)           |
| OpenBSD 5.0                       | `1:1c:3:f:6:c`                            |                | OpenBSD                       |

---
## Microsoft
See 'Game Consoles' for Xbox family
| **Device/OS**                                      | **PRL**                                         | **Vendor ID**              |  **Hostname** | **Client Class**                                  |
| :------------                                      | :------                                         | :------------              | :------------ | :---------------                                  |
| **Microsoft Windows 3.1/9X**                       |||||
| Microsoft MS-DOS 6.22 (MS TCP/IP 1.0a)             | `1:3:6:f:33:2c`                                 |                            |               | Microsoft MS-DOS                                  |
| Microsoft Windows 3.11 (MS TCP/IP 3.11b)           | `1:3:f:6:2c:2e:2f`                              |                            |               | Microsoft Windows 3.1 / 95                        |
| Microsoft Windows 95 OSR2                          | `1:3:f:6:2c:2e:2f`                              |                            |               | Microsoft Windows 3.1 / 95                        |
| Microsoft Windows 98                               | `1:3:6:f:2c:2e:2f:39`                           |                            |               | Microsoft Windows 98                              |
| Microsoft Windows 98 Second Edition                | `1:f:3:6:2c:2e:2f:2b:4d`                        | `MSFT 98\000`              |               | Microsoft Windows 98SE                            |
| Microsoft Windows Millennium Edition               | `1:f:3:6:2c:2e:2f:1f:21:2b:4d`                  | `MSFT 98\000`              |               | Microsoft Windows ME                              |
| **Microsoft Windows NT**                           |||||
| Microsoft Windows NT 3.5                           | `3:2c:2e:2f:6`                                  |                            |               | Microsoft Windows NT 3.5                          |
| Microsoft Windows NT 3.51                          | `1:f:3:2c:2e:2f:6`                              |                            |               | Microsoft Windows NT 3.51 / 4.0                   |
| Microsoft Windows NT 4                             | `1:f:3:2c:2e:2f:6`                              |                            |               | Microsoft Windows NT 3.51 / 4.0                   |
| Microsoft Windows 2000                             | `1:f:3:6:2c:2e:2f:1f:21:2b`                     | `MSFT 5.0`                 |               | Microsoft Windows 2000                            |
| Microsoft Windows XP SP3                           | `1:f:3:6:2c:2e:2f:1f:21:f9:2b`                  | `MSFT 5.0`                 |               | Microsoft Windows XP / Server 2003                |
| Microsoft Windows Server 2003 SP2                  | `1:f:3:6:2c:2e:2f:1f:21:f9:2b`                  | `MSFT 5.0`                 |               | Microsoft Windows XP / Server 2003                |
| Microsoft Windows Vista                            | `1:f:3:6:2c:2e:2f:1f:21:79:f9:2b`               | `MSFT 5.0`                 |               | Microsoft Windows Vista / Windows 7 / Server 2008 |
| Microsoft Windows 7 SP1                            | `1:f:3:6:2c:2e:2f:1f:21:79:f9:2b`               | `MSFT 5.0`                 |               | Microsoft Windows Vista / Windows 7 / Server 2008 |
| Microsoft Windows 7 (DHCP renew?)                  | `6:3:1:f:42:43:d:2c`                            | `MSFT 5.0`                 |               | Microsoft Windows Vista / Windows 7 / Server 2008 |
| Microsoft Windows 7 (DHCP renew?)                  | `6:3:1:f:42:43:d:2c:c`                          | `MSFT 5.0`                 |               | Microsoft Windows Vista / Windows 7 / Server 2008 |
| Microsoft Windows Server 2008 R2                   | `1:f:3:6:2c:2e:2f:1f:21:79:f9:2b`               | `MSFT 5.0`                 |               | Microsoft Windows Vista / Windows 7 / Server 2008 |
| Microsoft Windows 8                                | `1:f:3:6:2c:2e:2f:1f:21:79:f9:fc:2b`            | `MSFT 5.0`                 |               | Microsoft Windows 8.x / 10 / Server 2012          |
| Microsoft Windows Phone 8 - Nokia Lumia 920        | `1:f:3:6:2c:2e:2f:1f:21:79:f9:fc:2b`            | `MSFT 5.0`                 | _*_`-Phone`   | Microsoft Windows Phone 8                         |
| Microsoft Windows RT 8 - MS Surface RT             | `1:f:3:6:2c:2e:2f:1f:21:79:f9:fc:2b`            | `MSFT 5.0`                 |               | Microsoft Windows 8.x / 10 / Server 2012          |
| Microsoft Windows 8.1                              | `1:f:3:6:2c:2e:2f:1f:21:79:f9:fc:2b`            | `MSFT 5.0`                 |               | Microsoft Windows 8.x / 10 / Server 2012          |
| Microsoft Windows RT 8.1 - MS Surface RT           | `1:f:3:6:2c:2e:2f:1f:21:79:f9:fc:2b`            | `MSFT 5.0`                 |               | Microsoft Windows 8.x / 10 / Server 2012          |
| Microsoft Windows 10 v.1507                        | `1:f:3:6:2c:2e:2f:1f:21:79:f9:fc:2b`            | `MSFT 5.0`                 |               | Microsoft Windows 8.x / 10 / Server 2012          |
| Microsoft Windows 10 "November" v.1511             | `1:3:6:f:1f:21:2b:2c:2e:2f:79:f9:fc`            | `MSFT 5.0`                 |               | Microsoft Windows 10 / Server 2016                |
| Microsoft Windows Phone 10 (1511)                  | `1:3:6:f:1f:21:2b:2c:2e:2f:79:f9:fc`            | `MSFT 5.0`                 | _*_`-Phone`   |  Microsoft Windows Phone 10                       |
| Microsoft Windows 10 "Anniversary" v.1607          | `1:3:6:f:1f:21:2b:2c:2e:2f:79:f9:fc`            | `MSFT 5.0`                 |               | Microsoft Windows 10 / Server 2016                |
| Microsoft Windows 10 "Creators" v.1703             | `1:3:6:f:1f:21:2b:2c:2e:2f:79:f9:fc`            | `MSFT 5.0`                 |               | Microsoft Windows 10 / Server 2016                |
| Microsoft Windows 10 "Fall Creators" 1709          | `1:3:6:f:1f:21:2b:2c:2e:2f:79:f9:fc`            | `MSFT 5.0`                 |               | Microsoft Windows 10 / Server 2016                |
| Microsoft Windows 10 v.1803                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| Microsoft Windows 10 v.1809                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| Microsoft Windows 10 v.1903                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| Microsoft Windows 10 v.1909                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| Microsoft Windows 10 v.2004                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| Microsoft Windows 10 v.20H2                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| Microsoft Windows 10 v.21H1                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| Microsoft Windows 10 v.21H2                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| Microsoft Windows 10 unknown version               | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc:0:44:d0` | `MSFT 5.0`                 |               | Microsoft Windows 10 / Server 2019                |
| Microsoft Windows 11 v.21H2                        | `1:3:6:f:1f:21:2b:2c:2e:2f:77:79:f9:fc`         | `MSFT 5.0`                 |               | Microsoft Windows 10 / 11 / Server 2019           |
| **Microsoft Windows CE**                           |||||
| Microsoft Windows Mobile 6 - HTC Mogul             | `1:3:6:f:2c:2e:2f`                              | `Microsoft Windows CE\000` |               | Microsoft Windows Mobile                          |
| Microsoft Windows Mobile 6 - Palm Treo             | `1:3:6:f:2c:2e:2f`                              | `Microsoft Windows CE\000` |               | Microsoft Windows Mobile                          |
| Microsoft Windows CE 5 - Micros                    | `1:3:6:f:2c:2e:2f`                              |                            |               | Microsoft Windows CE                              |
| Microsoft Windows CE 6 - HumanWare BraileNote Apex | `1:3:6:f:2c:2e:2f`                              |                            | `APEX`_*_     | Microsoft Windows CE                              |
| Unknown Microsoft Windows CE                       | `1:3:6:f:2c:2e:2f:42:43`                        | `Microsoft Windows CE\000` |               | Microsoft Windows CE                              |

---
## Other Desktop OS
| **Device/OS**                       | **PRL**                                 | **Vendor ID**  | **Client Class**                        |
| :------------                       | :------                                 | :------------  | :---------------                        |
| Debian GNU/Hurd 2013                | `1:1c:2:3:f:6:77:c:2c:2f:1a:79:2a`      |                | Debian Linux 6 or derivative (dhclient) |
| IBM OS/2 Warp 4                     | (None)                                  |                | IBM OS/2                                |
| eComStation 2.0 (IBM OS/2 Warp 4.x) | `1:3:6:f:1c:21` (Wii)                   | `IBMWARP_V4.1` | eComStation (IBM OS/2)                  |
| Haiku R1 Alpha 3                    | `1:3:6:1c:f`                            |                | Haiku (BeOS)                            |
| MenuetOS 0.98.46                    | `1:3:6:f` (BB, DRAC, Netgear, etc)      |                | *(Not yet classified)*                  |
| MINIX 3.2                           | `1:3:6:c`                               | `Minix`        | Minix                                   |
| MorphOS 2.7                         | `1:f:3:6:3a:3b`                         |                | MorphOS (AmigaOS-like)                  |
| ReactOS 0.3                         | `1:1c:2:3:f:6:c:2a` (Debian installer)  |                | ReactOS                                 |
| ReactOS 0.4.14                      | `1:1c:2:3:f:6:c:2a` (Debian installer)  |                | ReactOS                                 |
| VMware ESXi 5.0.0                   | `1:1c:2:3:f:6:c` (ISC dhclient default) |                | ISC dhclient (Linux/Unix)               |

---
## Game Consoles
| **Device/OS**                     | **PRL**                                     | **Vendor ID**    | **Hostname**     | **Client Class**      |
| :------------                     | :------                                     | :------------    | :-----------     | :---------------      |
| Nintendo GameCube - Mario Kart DD | `1:3:6:1a:1c:3a:3b`                         |                  |                  | Nintendo GameCube     |
| Nintendo GameCube - Swiss         | `1:3:1c:6`                                  |                  |                  | Nintendo GameCube     |
| Nintendo Wii                      | `1:3:6:f:1c:21` (eComStation, 3DS)          |                  | `Wii`            | Nintendo Wii          |
| Nintendo 3DS                      | `1:3:6:f:1c:21` (eComStation, Wii)          |                  | `Nintendo 3DS`   | Nintendo 3DS          |
| Nintendo Wii U                    | `1:3:6:f` (BB, DRAC, Netgear, etc)          |                  | `Nintendo Wii U` | Nintendo Wii U        |
| Nintendo Switch                   | `1:3:6:1c`                                  |                  |                  | Nintendo Switch       |
| Microsoft Xbox (original)         | `1:3:6`                                     | `XBOX 1.0`       |                  | Microsoft Xbox        |
| Microsoft Xbox 360                | `1:3:6:f` (BB, DRAC, Netgear, etc)          | `Xbox 360`       |                  | Microsoft Xbox 360    |
| Microsoft Xbox One                | `1:f:3:6:2c:2e:2f:1f:21:79:f9:fc:2b` (Win8) | `MSFT 5.0`       | `Xbox-SystemOS`  | Microsoft Xbox One    |
| Microsoft Xbox One                | `1:f:3:6:2c:2e:2f:1f:21:79:f9:fc:2b` (Win8) | `MSFT 5.0`       | `XboxOne`        | Microsoft Xbox One    |
| Microsoft Xbox One (Threshold 2)  | `1:3:6:f:1f:21:2b:2c:2e:2f:79:f9:f` (Win10) | `MSFT 5.0`       | `XboxOne`        | Microsoft Xbox One    |
| Sony PlayStation 3                | `1:3:f:6`                                   | `PS3\000`        |                  | Sony PlayStation 3    |
| Sony PlayStation 4                | `1:3:f:6`                                   | `PS4\000`        |                  | Sony PlayStation 4    |
| Sony PlayStation Vita             | `1:3:f:6`                                   | `PS Vita TV\000` |                  | Sony PlayStation Vita |

---
## Other Appliances
| **Device/OS**                                | **PRL**                                    | **Vendor ID**                              | **Hostname**         | **Vendor OUI** | **Client Class**                          |
| :------------                                | :------                                    | :------------                              | :-----------         | :------------- | :---------------                          |
| APC Smart-UPS RT 5000 XL                     | `6:3:1:f:42:43:d:2b:3a:3b:2a:2:c`          | `APC` (This can be customized)             |                      |                | APC UPS                                   |
| APC Smart-UPS RT 5000 XL                     | `6:3:1:f:42:43:d:2c:2b:3a:3b:2a:2:c`       | `APC` (This can be customized)             |                      |                | APC UPS                                   |
| BlackBerry unknown                           | `1:3:6:f` (Xbox 360, DRAC, Netgear, etc)   | `BlackBerry`                               |                      |                | BlackBerry                                |
| BlackBerry unknown                           | `1:3:6:f` (Xbox 360, DRAC, Netgear, etc)   | `FSVDSL.UMA.RIM.BlackBerry`                |                      |                | BlackBerry                                |
| BlackBerry PlayBook (BB Tablet OS 2)         | `1:1c:2:3:f:6:c` (ISC dhclient default)    | `BlackBerry Tablet OS 2.`*version*         |                      |                | BlackBerry PlayBook                       |
| BlackBerry 10 unknown                        | `1:1c:2:3:f:6:c` (ISC dhclient default)    | `BlackBerry OS 10.`*version*               |                      |                | BlackBerry 10                             |
| Broadcom iSCSI offload engine                | `1:3:33:36`                                | `brcmftsk`                                 |                      |                | Broadcom iSCSI offload engine             |
| ClearOne Converge                            | `1:1c:3:6:f:2:2a:4:42`                     |                                            | `CONVERGE`_*_        |                | ClearOne Converge media appliance         |
| Dell iDRAC 6                                 | `1:3:6:c:f:1c:28:29:2a:2b:77` (Some udhcp) | `iDRAC`                                    |                      |                | Dell DRAC                                 |
| Dell DRAC unknown                            | `1:3:6:f` (BB, Xbox 360, Netgear, etc)     | `DELL RAC TYPE-A`                          |                      |                | Dell DRAC                                 |
| Denon AVR-S920W audio/video receiver         | `1:3:6:f` (Xbox 360, DRAC, Netgear, etc)   |                                            | *mac-addr*           |                | Printer or network appliance (best guess) |
| FitBit Aria smart scale                      | `1:3:6:f:42:43:d:2c`                       |                                            | `GainSpan`*mac-addr* |                | GainSpan IoT appliance                    |
| FitBit Ionic fitness tracker                 | `1:3:6`                                    |                                            | `Ionic`              |                | FitBit Ionic                              |
| FitBit Sense fitness tracker                 | `1:3:6`                                    |                                            | `Sense`              |                | FitBit Sense                              |
| Geist environmental monitor                  | `1:3:6:c:f:1c:2a:28:26:17:25:26:27:13:1a`  |                                            |                      | `0:40:9d`      | Geist environmental monitor               |
| MaceView MVR-SQ80 DVR                        | `1:3:6:1c:f:c`                             |                                            | `DVR`                |                | Mace Security DVR                         |
| Moxa NPort 5232 serial device server         | `1:3:4:6:2b`                               | `MOS 2.0`                                  |                      |                | *(Not yet classified)*                    |
| PowerDsine PoE midspan                       | `1:3:6:2b`                                 | `midspan_ip_list` (This can be customized) |                      |                | PowerDsine midspan                        |
| Rabbit Semiconductor unknown microcontroller | `1:3:2:6:c:f:45:2a:8`                      | `Rabbit-TCPIP:Z-World:DHCP-SNTP:1.0.0`     |                      |                | Rabbit Semiconductor microcontroller      |
| Samsung P260 mobile phone                    | `1:3:6:c:33:3a:3b`                         |                                            |                      |                | Samsung mobile phone                      |
| Unknown serial terminal server               | `1:3:6`                                    |                                            | `CAB`_*_             |                | Vending Terminal Server                   |
| Wyse PCoIP thin terminal                     | `1:3:6:c:f:2a:2b`                          | `PCoIP Endpoint`                           |                      |                | Wyse thin terminal                        |

---
## Network Equipment
### Cisco Systems
| **Device/OS**                              | **PRL**                                  | **Vendor ID**                              | **Client Class**                                    |
| :------------                              | :------                                  | :------------                              | :---------------                                    |
| **Wireless**                               ||||
| Cisco AireOS 8.0.140.0 - vWLC              | `1:3:6:c:f:42:43:96`                     | `Cisco AIR-CTVM-K9`                        | Cisco Wireless LAN Controller                       |
| Cisco AireOS 8.3.141.0 - WLC 2504          | `1:3:6:c:f:42:43:96`                     | `Cisco AIR-CT2504-K9`                      | Cisco Wireless LAN Controller                       |
| Cisco AireOS - WLC 5508                    | `1:3:6:c:f:42:43:96`                     | `Cisco AIR-CT5508-K9`                      | Cisco Wireless LAN Controller                       |
| Cisco AP1200 series (autonomous)           | `1:6:f:2c:3:21:96:2b`                    | `Cisco AP c1200`                           | Cisco wireless network appliance                    |
| Cisco AP1200 series (CAPWAP)               | `1:6:f:2c:3:7:21:96:2b`                  | `Cisco AP c1200`                           | Cisco wireless network appliance                    |
| Cisco AP1142N (CAPWAP)                     | `1:6:f:2c:3:7:21:96:2b`                  | `Cisco AP c1140`                           | Cisco wireless network appliance                    |
| Cisco AP1142N (autonomous)                 | `1:6:f:2c:3:21:96:2b`                    | `Cisco AP c1140`                           | Cisco wireless network appliance                    |
| Cisco BR1310 (CAPWAP)                      | `1:6:f:2c:3:7:21:96:2b`                  | `Cisco AP c1310`                           | Cisco wireless network appliance                    |
| Cisco AP3602 (CAPWAP)                      | `1:6:f:2c:3:21:96:2b`                    | `Cisco AP c3600`                           | Cisco wireless network appliance                    |
| Cisco AP3602 (CAPWAP)                      | `1:6:f:2c:3:7:21:96:2b`                  | `Cisco AP c3600`                           | Cisco wireless network appliance                    |
| Cisco AP3702 (CAPWAP)                      | `1:6:f:2c:3:7:21:96:2b`                  | `Cisco AP c3700`                           | Cisco wireless network appliance                    |
| **Switches**                               ||||
| Cisco IOS 12.2(35)SE5 - WS-C3750G-16-TD-S  | `1:6:f:2c:3:21:96:2b`                    |                                            | Cisco IOS network appliance                         |
| Cisco IOS 12.2(44)SE6 - WS-C2970G-24TS-E   | `1:6:f:2c:3:21:96:2b`                    |                                            | Cisco IOS network appliance                         |
| Cisco IOS 12.2(50)SG1 - WS-C4948           | `1:6:f:2c:3:21:96:2b`                    |                                            | Cisco IOS network appliance                         |
| Cisco IOS 12.2(55)SE10 - WS-C3560-48TS     | `1:42:6:3:43:96:2b:7d`                   |                                            | Cisco IOS network appliance                         |
| Cisco IOS 12.2(55)SE10 - WS-C3560-48TS     | `1:42:6:f:2c:3:43:c:96:2b:7d`            |                                            | Cisco IOS network appliance                         |
| Cisco IOS 12.2(58)SE1 - WS-C2960-8TC-L     | `1:6:f:2c:3:21:96:2b`                    |                                            | Cisco IOS network appliance                         |
| Cisco IOS 15.0(1)SE - WS-C2960-8TC-L       | `1:6:f:2c:3:21:96:2b`                    |                                            | Cisco IOS network appliance                         |
| Cisco IOS 15.2(2)E10 - WS-C2960CG-8TC-L    | `1:6:f:2c:3:21:96:2b`                    | `ciscopnp`                                 | Cisco IOS network appliance                         |
| Cisco IOS 15.2(2)E10 - WS-C3560CG-8PC-S    | `1:6:f:2c:3:21:96:2b`                    | `ciscopnp`                                 | Cisco IOS network appliance                         |
| Cisco IOS 15.2(6)E3 - WS-C2960CX-8TC-L     | `1:6:f:2c:3:21:96:2b`                    | `ciscopnp`                                 | Cisco IOS network appliance                         |
| Cisco Small Business SF302-08P switch      | `1:3:42:43:36:7d:81:96:6:f:64`           | `SF 302-08P`                               | Cisco Small Business network appliance              |
| **Routers**                                ||||
| Cisco IOS 12.4(15)T1 - C851                | `1:6:f:2c:3:21:96:2b`                    |                                            | Cisco IOS network appliance                         |
| Cisco IOS 12.4(15)T10 - C851               | `1:6:f:2c:3:21:2b`                       |                                            | Cisco IOS network appliance                         |
| **Security**                               ||||
| Cisco ASA 5505                             | `1:6:f:2c:3:21`                          |                                            | Cisco ASA network appliance                         |
| Cisco VPN 3002                             | `1:3:6:f` (Xbox 360, DRAC, Netgear, etc) |                                            | Printer or network appliance                        |
| **Voice/Video**                            ||||
| Cisco CP-7960 IP phone                     | `1:42:6:3:f:96:23`                       | `Cisco Systems, Inc. IP Phone CP-7960\000` | Cisco IP phone                                      |
| Cisco CP-7960 IP phone                     | `1:42:6:3:f:96:23:97`                    | `Cisco Systems, Inc. IP Phone CP-7960\000` | Cisco IP phone                                      |
| Cisco CP-7985 IP phone (Tandberg T150)     | `1:3:6:f:42:96:23`                       | `Cisco Systems, Inc. IP Phone CP-7985`     | Cisco IP phone                                      |
| Cisco CP-8945 IP phone                     | `1:3:f:6:c:23:42:96`                     | `Cisco System, Inc. IP Phone CP-8945`      | Cisco IP phone                                      |
| Cisco CP-9951 IP phone                     | `1:42:6:3:f:96:23`                       | `Cisco Systems, Inc. IP Phone CP-9951\000` | Cisco IP phone                                      |
| Tandberg 1000 video endpoint               | `1:3:6`                                  | `TANDBERG:Codec:1.0`                       | Cisco (Tandberg) videoconference unit               |
| Tandberg 990MXP video endpoint             | `1:3:1c:6:c:f:1a:2a:f2:78`               | `TANDBERG:Codec:1.0`                       | Cisco (Tandberg) videoconference unit               |
| Cisco (Tandberg) Edge 95MXP video endpoint | `1:3:1c:6:c:f:1a:2a:f2:78`               | `TANDBERG:Codec:1.0`                       | Cisco (Tandberg) videoconference unit               |
| Cisco (Tandberg) EX60 video endpoint       | `1:1c:3:f:6:c:2a:f2:78:42:2b`            | `TANDBERG:Codec:1.0`                       | Cisco (Tandberg) videoconference unit               |
| Cisco VX Educator video endpoint           | `1:3:6:f:2a`                             | `Educator`_*_                              | Cisco Telepresence VX Educator videoconference unit |
| **Management**                             ||||
| Cisco Prime Infrastructure 3.x             | `1:3:6:c:f:42:43:96`                     |                                            | Cisco ADE-OS network appliance                      |
| **Meraki**                                 ||||
| Meraki Z3 teleworker gateway               | `1:f:3:1c:c:6:1a`                        | `MERAKI`                                   | Cisco Meraki network appliance                      |

### Aruba Networks / HPE
| **Device/OS**                     | **PRL**                            | **Vendor ID**    | **Client Class**                 |
| :------------                     | :------                            | :------------    | :---------------                 |
| Aruba RAP155                      | `1:3:4:6:c:f:1c:2a:2b:3c:42:43:94` | `ArubaInstantAP` | Aruba wireless network appliance |
| Aruba IAP205                      | `1:3:4:6:c:f:1c:2a:2b:42:43:3c`    | `ArubaInstantAP` | Aruba wireless network appliance |
| Aruba IAP224 (8.6.0)              | `1:3:4:6:c:f:1c:2a:2b:3c:42:43:94` | `ArubaInstantAP` | Aruba wireless network appliance |
| Aruba AP225                       | `1:3:4:6:c:f:1c:2a:2b:3c`          | `ArubaAP`        | Aruba wireless network appliance |
| Aruba AP325 (6.4.4.6)             | `1:3:4:6:c:f:1c:2a:2b:3c`          | `ArubaAP`        | Aruba wireless network appliance |
| Aruba AP325 (APBoot ROM)          | `1:3:6:f:2b:3c`                    | `ArubaAP`        | Aruba wireless network appliance |
| Aruba 3600 controller (6.4.4.17)  | `1:3:6:c:f:4:2b:2c:3c:2a:1c`       | `ArubaMC`        | Aruba network appliance          |
| Aruba S1500-12P / ARSW1512 switch | *(Unknown)*                        | `ArubaMC`        | Aruba network appliance          |

### Juniper Networks
| **Device/OS**                             | **PRL**                  | **Vendor ID**                              | **Client Class**                   |
| :------------                             | :------                  | :------------                              | :---------------                   |
| Juniper ScreenOS 5.3 - NS-25              | `33:36:1:3:6:f`          | `NetScreen-25`                             | Juniper ScreenOS network appliance |
| Juniper ScreenOS 6.2.0r19.0 - NS-5GT      | `33:36:1:3:6:f`          | `NetScreen-NS5GT` (This can be customized) | Juniper ScreenOS network appliance |
| Juniper ScreenOS 6.3.0r26.0 - SSG5-Serial | `33:36:1:3:6:f`          | `SSG5-Serial`  (This can be customized)    | Juniper ScreenOS network appliance |
| Juniper ScreenOS 6.3.0r26.0 - SSG5-Serial | `33:36:1:3:6:f:2c`       | `SSG5-Serial`  (This can be customized)    | Juniper ScreenOS network appliance |
| Junper Junos 12.3X48-D65.1 - SRX-210HE2   | (None)                   |                                            | *(Unclassifiable)*                 |
| Juniper SRX-300                           | `3:33:1:f:6:42:43:78:2c` |                                            | Juniper Junos network appliance    |

### Other Network
| **Device/OS**                               | **PRL**                                            | **Vendor ID**               | **Hostname**  | **Vendor OUI** | **Client Class**                     |
| :------------                               | :------                                            | :------------               | :-----------  | :------------- | :---------------                     |
| 3com CDSG10PWR (HP 1905-10G-POE) switch     | `1:3:42:43:36:3d:81:6:f`                           |                             |               |                | HP (3com) network appliance          |
| ActionTec Wireless Broadband Router         | `1:1c:2:3:f:6:4:7:17:1a:2b:32:33:36:37:3c:3d:48`   | `Wireless Broadband Router` |               |                | Actiontec network appliance          |
| Airvana HubBub (Sprint Airave) femtocell    | `1:3:6:c:f:1c` (TrendNet, WatchGuard)              | `udhcp 0.9.7`               |               | `0:5:b9`       | Airvana network appliance            |
| Belkin unknown network appliance            | `1:3:6:f`                                          |                             | `SC`_*_       |                | Belkin network appliance             |
| Belkin unknown network appliance            | `3:1:6:f:79`                                       |                             |               |                | Apple or Belkin network appliance    |
| Cradlepoint wireless router                 | `1:3:6:c:f:1c:2a` (Ubiquiti, D-Link, Samsung)      | `Cradlepoint DHCP Client`   |               |                | Cradlepoint network appliance        |
| Cradlepoint wireless router                 | `1:3:6:2c:f:2e:2f` (D-Link)                        |                             |               |                | Cradlepoint network appliance        |
| D-Link unknown network appliance            | `1:f:3:6:2c:2e:2f:2b:4d` (Win98SE)                 | `MSFT 98`                   | `My Host`     |                | D-Link network appliance             |
| D-Link DI-514 wireless router               | `1:f:3:6:2c:2e:2f:1f:21:2b` (Win2k)                | `MSFT 5.0`                  | `DI-514`      |                | D-Link network appliance             |
| D-Link DCS-900 network camera               | `1:3:6`                                            | `MSFT 98`                   |               |                | D-Link network camera                |
| D-Link unknown network camera               | `1:3:6:c:f:1c:2a` (Samsung, Ubiquiti, Cradlepoint) |                             | `DCS-`*model* |                | D-Link network camera                |
| D-Link unknown network camera               | `1:3:6`                                            |                             | `DCS-`*model* |                | D-Link network camera                |
| Delta Networks unknown appliance            | `1:3:6:f:2c:2e:2f:39` (Win98)                      |                             | `RAS`         |                | Delta Networks network appliance     |
| Linksys unknown network appliance           | `1:3:f:6:d4`                                       |                             |               |                | Linksys network appliance            |
| Linksys unknown network appliance           | `1:1c:3:6:f:2c`                                    |                             |               |                | Linksys network appliance            |
| Linksys SPA-2102 voice gateway/router       | `1:3:2a:6:7:f:3a:3b:2c:42`                         | `LINKSYS SPA-2102`          |               |                | Linksys network appliance            |
| NEC DT700 IP phone                          | `1:3:c:6:f:42:45:46:5f:78:8d:97:a2:2b`             | `NECDT700`                  |               |                | NEC IP phone                         |
| Netgear RP614v3 router                      | `1:3:6:f` (BB, Xbox 360, DRAC, etc)                |                             |               |                | Printer or network appliance         |
| Netgear FR114P firewall                     | `1:3:6:f` (BB, Xbox 360, DRAC, etc)                |                             | `FR114P`      |                | Netgear network appliance            |
| Netgear FVS114 firewall                     | `1:3:6:f` (BB, Xbox 360, DRAC, etc)                |                             | `FVS114`      |                | Netgear network appliance            |
| QLogic SANbox 5202 Fibre-Channel switch     | `1:1c:3`                                           |                             |               |                | QLogic network appliance (Linux)     |
| TP-Link TL-WR541G/542G wireless router      | `1:3:2b:2c:2e:2f:6:21:79:f9`                       | `MSFT 98`                   |               |                | TP-Link network appliance            |
| TP-Link unknown network appliance           | `1:3:2b:2c:2e:2f:6`                                | `MSFT 98`                   |               |                | TP-Link network appliance            |
| TrendNet TW100-S4W1CA router                | `1:3:6:c:f:1c` (Airvana, WatchGuard)               | `TW100-S4W1CA`              |               |                | TrendNet network appliance           |
| TrendNet TEW-654TR wireless router          | *(Unknown)*                                        | `TEW-654TR`                 |               |                | TrendNet network appliance           |
| TrendNet unknown network appliance          | *(Unknown)*                                        | `trendnet`                  |               |                | TrendNet network appliance           |
| TrendNet unknown network appliance          | `1:3:6:c:f:1c:21:28:29:2a:2c`                      |                             |               |                | TrendNet network appliance           |
| TrendNet unknown network appliance          | `1:3:6:c:f:1c:21:28:29:2a:2c:f9`                   |                             |               |                | TrendNet network appliance           |
| Ubiquiti airFiber AF24 v1.5 wireless bridge | `1:3:6:c:f:1c:2a` (Cradlepoint, D-Link, Samsung)   | `udhcp 1.11.2`              |               |                | Linux appliance                      |
| WatchGuard FireBox X55e Edge firewall       | `1:3:6:c:f:1c` (Airvana, TrendNet)                 | `udhcp 0.9.9-pre`           |               | `0:90:7f`      | WatchGuard network appliance (Linux) |
| WIZnet unknown embedded network appliance   | `1:3:6:f:3a:3b`                                    |                             | `WIZnet`      |                | WIZnet embedded network appliance    |
| Yealink SIP-T48S IP phone                   | `1:2:3:4:6:7:c:f:1c:2a:42:43:2b:64:65:78:84:85`    | `yealink`                   | `SIP-T48S`    |                | Yealink IP phone                     |

---
## Printers
### Xerox Printers
| **Device/OS**                      | **PRL**                                        | **Vendor ID**                                                                                           | **Client Class** |
| :------------                      | :------                                        | :------------                                                                                           | :--------------- |
| Xerox WorkCentre Pro 245           | `1:1c:3:f:6:c:2c:4e:4f`                        | `mfg=Xerox,typ=MFP,mod=Xerox WorkCentre Pro 245, v1 Multifunction System,ser=`*serial*`,loc=`*location* | Xerox printer    |
| Xerox WorkCentre 4250              | `1:3:6:7:c:f:12:17:1a:2c:2e:33:36:3a:3b:4e:4f` | `mfg=XEROX;typ=MFP;mod=WorkCentre 4250;ser=`*serial*`;loc=`*location*                                   | Xerox printer    |
| Xerox WorkCentre 5135              | `1:1c:3:f:6:c:2c:4e:4f:2:2a`                   | `mfg=Xerox;typ=MFP;mod=Xerox WorkCentre 5135 v1 Multifunction System;ser=`*serial*`;loc=`*location*     | Xerox printer    |
| Xerox unknown Phaser (DHCP renew?) | `c`                                            | `Xerox Phaser`                                                                                          | Xerox printer    |
| Xerox unknown Phaser               | `1:3:1c:3a:3b:6:f:4e:4f:2c:2e:45:c`            | `Xerox Phaser`                                                                                          | Xerox printer    |
| Xerox unknown Phaser               | `1:3:1c:3a:3b:6:f:4e:4f:2c:2e:45:c:51`         | `Xerox Phaser`                                                                                          | Xerox printer    |

### Dell Printers
| **Device/OS**                  | **PRL**                                                 | **Vendor ID**                                                        | **Hostname** | **Client Class** |
| :------------                  | :------                                                 | :------------                                                        | :----------- | :--------------- |
| Dell unknown printer           | `1:2:3:6:c:f:1a:1c:55:56:57:58:2c:2d:2e:2f:46:45:4e:4f` |                                                                      |              | Dell printer     |
| Dell 5130c color laser printer | `1:2:3:6:c:f:1a:1c:58:2c:2d:2e:2f:46:45:4e:4f`          | `Dell 5130cdn Color Laser`                                           |              | Dell printer     |
| Dell unknown printer           | `1:2:3:6:c:f:1a:1c:58:2c:2d:2e:2f:46:45:4e:4f`          |                                                                      |              | Dell printer     |
| Dell unknown printer           | `1:3:6:7:c:f:12:17:1a:2c:2e:33:36:3a:3b:4e:4f`          | `Dell Network Printer`                                               |              | Dell printer     |
| Dell unknown printer           | `1:3:6:7:c:f:12:17:1a:2c:2e:33:36:3a:3b:4e:4f:51`       | `Dell Network Printer`                                               |              | Dell printer     |
| Dell unknown printer           | `1:3:6:f:1c`                                            |                                                                      |              | Dell printer     |
| Dell 5230n laser printer       | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Lexmark)       | `Mfg=DELL;Typ=Printer;Mod=Dell 5230n Laser Printer;Ser=`*serial*`;`  |              | Dell printer     |
| Dell 5230n laser printer       | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Lexmark)       | `Mfg=DELL;Typ=Printer;Mod=Dell 5230n Laser Printer;Ser=`*serial*`;`  |              | Dell printer     |
| Dell 5310n laser printer       | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Lexmark)       | `Mfg=DELL;Typ=Printer;Mod=Dell Laser Printer 5310n;Ser=`*serial*`;`  |              | Dell printer     |
| Dell 5350dn laser printer      | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Lexmark)       | `Mfg=DELL;Typ=Printer;Mod=Dell 5350dn Laser Printer;Ser=`*serial*`;` |              | Dell printer     |
| Dell 5530dn laser printer      | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Lexmark)       | `Mfg=;Typ=Printer;Mod=Dell 5530dn Laser Printer;Ser=`*serial*`;`     |              | Dell printer     |
| Dell unknown printer           | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Lexmark)       |                                                                      | `DELL`_*_    | Dell printer     |
| Dell unknown printer           | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Lexmark)       |                                                                      | `ET`_*_      | Dell printer     |

### Hewlett-Packard Printers
| **Device/OS**                         | **PRL**                                              | **Vendor ID**               | **Hostname** | **Client Class** |
| :------------                         | :------                                              | :------------               | :----------- | :--------------- |
| Hewlett-Packard unknown printer       | (None)                                               |                             | `NPI`_*_     | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:7:2c:33:36:3a:3b:c:f:90:12`                     | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:2c:6:7:c:f:16:36:3a:3b:45:12:2b`                | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:2c:6:7:c:f:16:36:3a:3b:45:12:2b:77`             | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:2c:6:7:c:f:16:36:3a:3b:45:12:2b:77:9a`          | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:2c:6:7:c:f:16:36:3a:3b:45:12:2b:77:51:99:9a`    | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard Color LaserJet 5500dn | `1:3:2c:6:7:c:f:16:36:3a:3b:45:12:90`                | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:2c:6:7:c:f:16:36:3a:3b:45:12:90`                | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:2c:6:7:c:f:16:36:3a:3b:45:12:90:77`             | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:2c:6:7:c:fc:f:16:36:3a:3b:45:12:2b:77:51:99:9a` | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:3:2c:6:51:7:c:f:16:36:3a:3b:45:12:90`             | `Hewlett-Packard JetDirect` |              | HP printer       |
| Hewlett-Packard unknown printer       | `1:1c:2:3:f:6:c`                                     |                             | `NPI`_*_     | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:42:43:d`                                    |                             | `HP`_*_      | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:42:43:d:c`                                  |                             |              | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:42:43:d:2c:c:51`                            |                             | `HP`_*_      | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:42:43:d:2c:c:51:fc`                         |                             | `HP`_*_      | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:2c:c`                                       |                             | `NPI`_*_     | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:c:2c:51:45:2a:2b:12:42:43:96:7`             |                             | `NPI`_*_     | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:c:2c:51:45:2b:12:42:43:96:7`                |                             | `NPI`_*_     | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:c:42:43:d:2c`                               |                             | `NPI`_*_     | HP printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:42:43:d:2c`                                 |                             | `HP`_*_      | HP Printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:42:43:d:2c`                                 |                             | `NPI`_*_     | HP Printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:42:43:d:2c:c`                               |                             | `HP`_*_      | HP Printer       |
| Hewlett-Packard unknown printer       | `6:3:1:f:42:43:d:2c:c`                               |                             | `NPI`_*_     | HP Printer       |
| Hewlett-Packard unknown printer       | `c:1:1c:3:f:6:2c`                                    |                             | `NPI`_*_     | HP printer       |

### Other Printers
| **Device/OS**                        | **PRL**                                           | **Vendor ID**                                           | **Hostname**  | **Vendor OUI** | **Client Class**                              |
| :------------                        | :------                                           | :------------                                           | :-----------  | :------------- | :---------------                              |
| Boca unknown printer                 | `1:3:2c:33:36:3a:3b:c`                            | `BOCA SYSTEMS PRINTER`                                  |               |                | Boca ticket printer                           |
| Brother MFC-J6510DW multifunction    | `6:3:1:f:42:43:d:c:2c`                            |                                                         | `MFC-J6510DW` |                | Brother printer                               |
| Brother unknown printer              | `6:3:1:f:42:43:d:c:2c`                            |                                                         | `BR`_*_       |                | Brother printer                               |
| Brother unknown printer              | `6:3:1:f:42:43:d:c:2c:2:2a`                       |                                                         | `BR`_*_       |                | Brother printer                               |
| Brother unknown printer              | `6:3:1:f:42:43:d:2c:2:2a:78:7d:c`                 |                                                         | `BR`_*_       |                | Brother printer                               |
| Canon MF4890 multifunction           | `1:3:6:f:c` (Roku)                                |                                                         |               |                | Printer or Linux media appliance (best guess) |
| Canon unknown printer                | `1:3:6:f:2c:2f`                                   |                                                         | `Canon`_*_    |                | Canon printer                                 |
| Canon unknown printer                | `1:3:6:f:45`                                      |                                                         |               |                | Canon printer                                 |
| Canon unknown printer                | `1:3:c:17:6:f:2c:2f`                              |                                                         |               |                | Canon printer                                 |
| Epson Artisan 725 all-in-one printer | `1:3:6:c:f:11:1c:28:29:2a`                        | `udhcp`                                                 |               |                | Epson printer                                 |
| Epson unknown printer                | `1:3:6:c:f:1c:2a:28:26:17:25:27:13:1a`            |                                                         |               |                | Epson printer                                 |
| Epson unknown printer                | `1:3:6:c:f:1c:33:36:3a:3b`                        |                                                         |               |                | Epson printer                                 |
| Epson unknown printer                | `6:3:1:f:42:43:d:2c`                              |                                                         |               |                | Epson Printer                                 |
| Konica Minolta unknown printer       | `1:3:6:f` (Xbox 360, DRAC, Netgear, etc)          |                                                         | `KMBT`_*_     |                | Konica Minolta printer                        |
| Konica Minolta unknown printer       | `1:3:6:f:2c`                                      |                                                         |               |                | Konica Minolta printer                        |
| Konica Minolta unknown printer       | `1:3:6:f:2c:2e`                                   |                                                         |               |                | Konica Minolta printer                        |
| Konica Minolta unknown printer       | `1:3:f:2c:2e`                                     |                                                         | `KM`_*_       |                | Konica Minolta printer                        |
| Kyocera unknown printer              | `1:3:f:6:2c`                                      |                                                         | `KM`_*_       |                | Kyocera printer                               |
| Lexmark X204n multifunction          | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Dell)    | `Mfg=LEXMARK;Typ=MFP;Mod=Lexmark X204n;Ser=`*serial*`;` |               |                | Lexmark printer                               |
| Lexmark unknown printer              | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Dell)    |                                                         | `LXK`_*_      |                | Lexmark printer                               |
| Lexmark unknown printer              | `1:3:2a:4:6:7:c:f:1a:2c:33:36:3a:3b:be` (Dell)    |                                                         |               |                | Dell or Lexmark printer                       |
| Muratec unknown printer              | `1:3:c:17:6:f:2a:2c:2f` (Oki)                     |                                                         |               |                | Muratec printer                               |
| Océ unknown printer                  | `1:3:6:2c:c:f:4:45:46:2a`                         |                                                         | `MFP-`_*_     |                | Océ printer                                   |
| Oki C330 color laser printer         | `1:3:c:17:6:f:2a:2c:2f` (Muratec)                 | `C330`                                                  |               |                | Oki printer                                   |
| Oki MC561 multifunction              | `1:3:c:17:6:f:2a:2c:2f` (Muratec)                 | `MC561`                                                 |               |                | Oki printer                                   |
| Panasonic UF-9000 multifunction      | `1:2:3:6:c:f:12:13:2e:2f:36:39:3a:3b`             |                                                         |               |                | Panasonic printer                             |
| Ricoh Aficio MP 3351 multifunction   | `1:3:6:c:f:1c:2c:2f`                              |                                                         |               |                | Ricoh printer                                 |
| Ricoh unknown printer                | `1:3:6:c:f:1c:2c:2f:cc`                           |                                                         | `RNP`_*_      |                | Ricoh printer                                 |
| Ricoh unknown printer                | `1:3:6:f:1c:2c:2f`                                |                                                         | `RNP`_*_      |                | Ricoh printer                                 |
| Samsung unknown printer              | `1:3:6:7:c:f:12:17:1a:2c:2e:33:36:3a:3b:4e:4f`    | `SAMSUNG Network Printer`                               |               |                | Samsung printer                               |
| Star Micronics unknown printer       | `1:3:6:c:f:1c:28:29:2a`                           |                                                         | `IFBD-H`_*_   |                | Star Micronics printer                        |
| Star Micronics unknown printer       | `1:3:6:c:f:1c:2a:28:26:17:25:26:27:13:1a`         |                                                         |               | `0:11:62`      | Star Micronics printer                        |

---
## Long PRL
| **Device/OS**                               | **PRL**                                                                                             | **Vendor ID**                      | **Client Class** |
| :------------                               | :------                                                                                             | :------------                      | :--------------- |
| **Pre-eXecution Environment**               ||||
| Unknown Preboot eXecution Environment (PXE) | `1:2:3:4:5:6:b:c:d:f:10:11:12:16:17:1c:28:29:2a:2b:32:33:36:3a:3b:3c:42:43:80:81:82:83:84:85:86:87` | `PXEClient:Arch:00000:UNDI:002001` | PXE Boot         |
| Unknown Preboot eXecution Environment (PXE) | `1:2:3:5:6:b:c:d:f:10:11:12:2b:36:3c:43:80:81:82:83:84:85:86:87`                                    | `PXEClient:Arch:00000:UNDI:002001` | PXE Boot         |
| **Other**                                   ||||
| Liebert 6000RT UPS                          | `3:1c:36:1:6:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0:0` |                                    | Liebert UPS      |
