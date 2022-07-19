<div style="text-align: center;">

# Work Resume

</div>

## Personal Information

|           |                                                                               |
| --------- | ----------------------------------------------------------------------------- |
| Name      | **刘东华** (Bill Leu)                                                                    |
| Gender    | Male                                                                          |
| Education | Electrical Undergraduate degree                                               |
| Born      | Feb 1796                                                                      |
| Address   | [Shenzhen GD China](https://map.baidu.com/@12690382.13541176,2566696.514393494,17.26z) |
| Tel       | [15302685167](tel:15302685167)                                                |
| Email     | <18681137192@126.com>                                                         |
| Site      | <https://github.com/liudonghua>                                               |

---

## Education Experiences

- At 22 years old I graduated from an university named **[江汉大学](http://www.jhun.edu.cn/)**
- At 17 years old I graduated from a high school named **汉阳一中**
- From 6 years old to 14 I have studied at a small school named **协丰中心小学** and a middle school named  **协丰中学**

<div style="text-align: center;">

- ![May 2022 recently](https://avatars.githubusercontent.com/u/5476163?v=4)

</div>

<div style="page-break-after: always;"></div>

## programmer Professional Experiences

### From Sep 2021 to Mar 2022 I programmed as embedded linux engineer at an server designing and manufaturing company named  [Silicom.inc](https://www.silicom-usa.com/) from irasel

- I ported KCS related packages from **openbmc** to **Buildroot** for BMC system based on ast2600/ast2620 chip from **ASPEED** company (at Taiwan).
- I create the virtual packages different from the original packages in buildroot to EXTERNAL directory so that didn't change any property codes in buildroot repository and easily would upgrade builroot to latest version. This is no problem all but didn't exist in buildroot offical documents.

---

### From Jul 2017 to Mar 2021 I programed as embedded Linux/OpenWrt Engineer At an IoT company named  [在那科技](http://www.naviecare.com)

- I was alonely responsible for developing **LoRa openWrt gateway** and finished within the first two months, I realized the complete gateway function and the whole process from the node to the gateway ,next to the server.
- I also developed **LoRa** stress test tool to evaluate the reception capability of the gateway,and our peers cannot done or is unreliable than our.
- I also expanded the gateway from Qualcomm **AR9344** platform to **MTK7688**, **AK3368** and **atom** industrial computers and other linux platforms, and even ported the linux code to **windows** platform for testing purposes. Not only that, the drivers were also packaged into docker containers for easy deployment as edge computing devices.
- I was the first programmer in the world to solve a bug in the LoRa concentrator driver of the **FTDI** solution, which had been officially deprecated by **Semtech**. In addition to this, I also worked with a satellite communication company to implement gateway and satellite communication.

- Keywords

      > I2C, USB, FTDI, SPI, miniPCIe, PCIe, Modbus, docker, golang,valgrind, LTE-4G, RS485, satellite communication, Luci jsapi, mingw

---

### From Oct 2016 to Jul 2017 I programed as communications engineer and C# programmer at a software company named  [广东扬航电子(深圳)](http://www.younghead.cn)

- The company has a commercial **WiFi** business, I am responsible for development of **CPE router** switching bridge, CPE, routing mode one-click only, and rewrite the **Luci** a few lines underlying code for [setup wizard function](https://github.com/liudonghua/luci-setup-wizard) in less than two months.

- After this project was completed, the company transformed into a new project of the fire protection system, I was responsible for the interface design between the terminals and the console software with **WPF** framework on windows system for three months.

- Keywords
      > GDB, gdbserver, Luci, WPF

<div style="page-break-after: always;"></div>

### From Oct 2015 to Sep 2016 I programed as embedded OpenWrt engineer at a commercial Wi-Fi company named  全民尚网(acquired)

- I developed commercial WiFi and rewritten **WiFiDog** to be compatible with **portal** certification of **another iKuai Gateway**. I learned to adapt a lot of different platforms such as **AR9341**,**QCA9531**,**QCA9561**, **MTK7620A**, **MTK7621**, etc. I deepened my knowledge of how to match hardware and software, and also mastered the skills of compiling **U-Boot** with web upgrade.

- I also compiled wireshark (**[tshark](https://github.com/liudonghua/wireshark-openwrt)**) as a packet capture tool for openWrt gateway in a week firstly.

- Keywords

    > BLE, NFC, UART, freeRTOS, Arduino, STM32

--

### From Oct 2014 to Jul 2015 I programed as software develop engineer at a smart home company named  [会当](http://home.jia.mn/home/)

- I am responsible for router and backend **PHP** including **nt_link** communication ,**PHP** and **shell** mixed programming, automatic upgrade, **netfilter** programming, **STUN**.

- Keywords
    > Cordova stun netfilter/iptables

---

### From Jun 2013 to August 2014 I programd remotely for an advertise company named  一键信达 from Peking

- I developed openWrt ad-hoc router that implements a special feature of running **truecrypt** encrypted files as rootfs by pivot root method.

- Keywords

    > ThinkPHP YUCC

## My Achivements

</div>

### VLC player component based on [Cordova](https://cordova.apache.org/) with RTSP protocol for iOS platform

- I had realized this function on Android platform and most prefectly worked on iOS.
- I added a line code in a position of iOS framework codes and referenced a VLC function and realized player function by researching within a week.

- That is my highest light moment within my programmer life and my most presentful coding style - simple and clever.

---

### Optimzation for Luci User Manager [github](https://github.com/liudonghua/admin-multi-users-luci)

- Login of root user only supported before official luci of 18.06 version and easily leaked sercert,there were a lot of solutions for multi user manager.

- I refrenced the repository of [github/Hostle](https://github.com/Hostle/openwrt-luci-multi-user),but there a mistake that change admin directory to admins directory and uncomplcated origin luci repository for diffrenced the page.

- I found a best solution which change section name to object name,sample is from section name of "admin" to lua object name of "admin.system.admin" by used a few patchs only.

---

### SSH Reverse Controller Platform for Mass Embedded Devices [github](https://githubcom/liudonghua/sshtunnel)

- I belive that is most simple solution for remote control mass embedded linux devices.
- I refrenced SSH Reverse Controller Platform for Mass Embedded Devices.But we have a lot of devices needed to remote controlling.
- After trying, after failing, I finally found a shortcut method with a inspiration whthin a week.
- The original solution included PHP code which was always a stumbling block in my heart. On the eve of the China Christmas, I had nothing to do and tried to remove this burden. In less than a day, I finally succeeded, and it was guaranteed to be compatible with the original interface. Only the proxy server was changed, and the endpoints did not need to be changed.

---

### Optimizing LoRa Servers on Embedded Devices

- There are several embedded LoRa server solutions on github. One of them attracted me, including the meson compilation tool, the first contact with meson and the automatic generation of code, which should be written by a very good programmer.
- I found that there are a lot of HEX and BYTES conversion programs in the code, which is quite confusing, but HEX is actually only needed for the human-machine interface, so I changed all the HEX data types only in the UI which finally makes the code easier to understand.
- When migrating from the Qualcomm platform to the Mediatek platform, it was found that there is still a big-endian problem. After research, simple arithmetic is used to achieve big-endian adaptation, without judging whether the chip is big-endian or little-endian.

### Low-orbit satellite narrowband communication

- The partner company has been failed with other companies. The difficulty of this project is that there are only four window communication times per day, and each time is indeterminate, and the maximum duration is no more than 5 minutes;
- Later, it was found that the project was simpler than expected, and the communication with the satellite was successful.

---

### Add Baidu Map to LoRa Server React Framework

- [The original code](https://github.com/as940125/lora-app-server) has a map called Street, which be blocked unormally in China. The development manager plans to replace it with a Baidu map in China. But the front-end programmers don’t know React and only Vue. For this small function, He rewrite full front-end code with Vue. The simple problem that was originally planned to be solved quickly ended up being delayed for a year before leaving.
- After I took over, I confirmed that this programmer is completely unqualified. In fact, he can't even write Vue, and he doesn't understand asynchronous ajax at all. I originally planned to modify Vue, but then I thought it was worthless, so I started to add Baidu map under the React framework, referring to the original Street map code to easily implement the Baidu map function, and switch to Baidu map when judging that the browser language is zh_CN.

---

<div style="text-align: center;">

## My Faith

</div>

- I think that writing code is not the most important rather than reading code as programmers.

    > A programmer will be stalled forever if write code with Previous code knowledge only because is afraid to read the code;
    > A programmer can learn the industry's advanced code design and technical trends to improve themselves continuously by that read the codes and the documents of referencing excellent repositories.

- I have been a tosser that learn **VBA** to improve efficiency earliest and self-learning **PHP** and flash the router to compiling **openWrt** later and easy other that crack **Black Apple** and flash **Android**.

- Since I started working as a programmer, I has been the best programmer at all worked company. I don't escape my job or complain about the company, because I believe that should take responsibility myself for own choicing job (studied from "Escape from Freedom" Written by Fromm). I should leave if not satisfied.

<div style="text-align: center;">

## Non-programmer Career Experiences

</div>

+ From Mar 2009 to May 2012 worked at a battery factory named  **海盈科技**

    > In this company I try **VBA** programming to realize office automation, found the talent of programming, and sprouted the idea of switching to programmer.

+ From May 2006 to Dec 2008 worked at a battery factory named **德赛电池**

+ From Mar 2004 to Jun 2005 worked at a electric(DVD/DVR) factory (FUNAI from Japan) named  东莞嘉财电业制造厂

+ 2002/2-2003/12 From Feb 2002 to Dec 2003 worked  at a power supply adapter factory from Taiwan named  东莞上焱电器制品厂

<div style="page-break-after: always;"></div>

<div style="text-align: center;">
