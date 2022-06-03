# 简历

## 个人资料

- 姓名 **刘东华** 

- 性别 **男** 

- 学历 **工业电气自动化** **统招本科** 

- 要求月薪 **40**k+

- 住址：**[南山区塘朗](https://map.baidu.com/@12690382.13541176，2566696.514393494，17.26z)**

- 电话 **[18681137192](tel:18681137192)** 

- 电邮 **[18681137192@126.com](mailto://18681137192@126.com)**

- 主页：**[github.com/liudonghua](https://github.com/liudonghua)** 
  > 现在已经因为至少三个项目获得github勋章 **[arctic code vault contributor](https://blog.shengxunwei.com/Home/Post/7e7da00c-8df8-4fcb-afc5-3a28f4ae20be)**。

---

## 教育经历
- 22岁 毕业于原华中理工大学汉口分院，后来合并到[江汉大学](http://www.jhun.edu.cn/)
- 17岁 毕业于汉阳一中
- 6岁 开始在协丰中心小学和协丰中学接受八年义务教育

---

## 主要职业经历

### 2021.9-2022.3 在[Silicom.inc](https://www.silicom-usa.com/)

- 行业 **服务器设计/制造** 
- 职位 **嵌入式软件工程师** 
- 月薪 **24k** 
    > 基于**ASPEED**公司(台湾)的芯片开发服务器BMC系统，将**openbmc**和**KCS**相关的程序包移植到**Buildroot**下编译。
    > 
    > 在上述过程中，掌握了Buildroot标准的编译方式（和公司的做法不同），而且通过研究找到了通过'Virtual'方式修改Buildroot本来就有但需要修改的包，达到不改动任何Buildroot代码的目的，用EXTERNAL方式开发自己的产品，不妨碍buildroot升级，改进了原来给Buildroot打补丁的方法，这种做法是Buildroot文档没有的但是完全没问题。
    > 
    > 因为很多巧妙的实现被否定（和公司原来的做法不同），很受委屈，纠结之下离职。
- 技能升级点
    > Yocto Buildroot 'Virtual package'  
---

### 2017.7-2021.3 在[深圳市在那(原派诺德)科技有限公司](http://www.naviecare.com) 

- 行业 **物联网** 
- 职位 **嵌入式(Linux/openWrt)工程师** 
- 月薪 入职**15k** 次年加薪到**18k**

    > 公司是从事物联网开发/生产，我独自负责开发 **LoRa openWrt 网关**，在最初的两个月内实现了完整的网关功能，并打通了从节点到Docker服务器整个流程，因为表现优异，一个月就转正.
    >
    > 为提升产品品质，还开发了 **LoRa** 压力测试工具，用于评估网关的接收能力，以及评估**IPC**服务器的性能，据我所知，很多同行做不到或方案不行。
    >
    > 随着市场的开拓，还把网关从最初的高通的**AR9344**平台扩展到**MTK7688**，**RAK3368**以及**x86**等Linux平台，甚至为方便测试，还把Linux代码移植到**windows**平台。最后，很得意的是，把**LoRa**驱动程序打包到**Docker**容器，以方便部署成边缘计算设备。
    >
    > 很幸运最终解决了**FTDI**方案的LoRa集中器驱动中的BUG，本来这个方案已经被**Semtech** 官方废弃，我应该是世界上第一个解决这一BUG的程序员。
    >
    > 一件事不得不提，后来还赢得了和卫星通讯公司合作的机会，实现LoRa网关和低轨道窄带卫星通讯。

- 记得最初面试的时候，公司老板不看好我，认为我年龄大没创意，幸亏台湾股东力排众议留下我，后来我的表现让老板认为我很特别，看来打脸了。

- 技能升级点
    > I2C USB FTDI SPI miniPCIe PCIe Modbus Docker golang valgrind LTE-4G RS485 低轨卫星窄带通讯 'Luci jsapi' Mingw

---

### 2016.10-2017.7 在[广东扬航电子深圳分公司](http://www.younghead.cn)

- 行业 **通信/消防** 
- 职位 **软件工程师** 
- 月薪 **10k**
    > 最初做农村商业**WiFi**项目，我负责**CPE 路由器**开发，实现了桥接、CPE、路由模式一键切换，并且改写了 **Luci** 底层代码，实现了[设置向导](https://github.com/liudonghua/luci-setup-wizard.git)功能，所有的工作在不到两个月内完工。为这个破解过竞品，但是对方程序员没有能力改写Luci框架，而是在Luci框架之外用cgi方式实现，而且代码质量不行，CSS和HTML混在一起，一个页面就几千行代码，不晓得累不累。
    >
    > 这个项⽬完工后，老板被前项目折磨怕了就捡起以前做过的消防系统，我负责各终端之间接⼝的架构设计（我是被口头任命的项目负责人）以及指挥控制台软件开发，**WPF**上⼿了三个⽉，现学现卖，完成了各项功能，包括低频Wi-Fi、LTE、LoRa三路方式通信，UI线程和后台通讯线程分离，XAML页面数据绑定，在离职前完成了整个项目，消灭了所有BUG，当年公司消防系统销售额达到2千多万。
    >
- 离职结算工资的时候，公司主动退还了最初被扣掉的绩效工资，也算是小气老板对我的肯定。
- 技能升级点
    > GDB gdbserver Luci WPF

---

### 2015.10-2016.9 在深圳市全民尚网科技有限公司(被收购)

- 行业 **商业Wi-Fi** 
- 职位 **嵌入式(Linux/openWrt)工程师** 
- 月薪 **12k**
    > 开发商业 Wi-Fi，刚开始计划了六个任务，我负责三个任务：
    - 改写了**WiFiDog**以兼容 **[爱快](https://www.ikuai8.com/)** 网关的portal认证；
    - 远程控制-最终以**SSH反向代理**方案实现远程控制几百台路由器(实际)；
    - 数据监控（实在不道德，请原谅）- 在openWrt-X86下编译了wireshark命令行部分 [tshark](https://github.com/liudonghua/wireshark-openwrt)作抓包工具；
    > 这三个任务每个只花了一个星期。
    >
    > 后来学会了适配大量不同的平台，如 **AR9341**、**QCA9531**、**QCA9561**、 **MTK7620A**、 **MTK7621** 等等，加深了硬件和软件如何匹配的知识；
    >
    > 还掌握了编译**U-Boot**的本领 ，特别是web升级**U-Boot**。
    > 
    > 另外，还在不到一个月时间里完成了包括**NFC**、**BLE**、**freeRTOS**、**UART**、**Ethernet**等等诸多功能的单片机智能门锁项目，而且通过调试成功解决**内存泄漏**实现稳定运行。

- 在工作快满一年的时候被公司裁员。
- 
- 技能升级点
    > BLE NFC UART freeRTOS Arduino STM32 U-Boot

---

### 2014.10-2015.7 在[深圳会当科技有限公司](http://home.jia.mn/home/)

- 行业 **智能家居** 职位 **软件工程师** 月薪 **8k**
  
    > 我负责路由器和后端 **PHP** ，编程内容包括 **nt_link** 通讯，**PHP** 和**shell** 混合编程，自动升级，**netfilter** 编程，**STUN 穿透**以及 Cordova APP，包括 Android及iOS，本来还有winPhone，我没答应。顺便提一下，这个项目没有使用Luci，而是**Lighttpd + PHP**，因为华为出身的老板觉得Lua太难。

- 技能升级点
    > Cordova nt_link STUN netfilter/iptables

---

### 2013.6-2014.8 为北京一键信达科技有限公司 **远程办公**

- 行业 广告/**[微信公众号平台](https://kf.qq.com/faq/120911VrYVrA151013MfYvYV.html)** 
- 职位 **远程办公** 
- 月薪 **6-9k**(带加班费)

    > 开发了openWrt广告路由器，实现了一个特别的功能就是把 **truecrypt** 加密的文件作为rootfs运行，使用了**PIVOT**方式实现的。
    >
    > 基于开源的**微信公众号平台**开发新功能。
    >
    > 因为出色表现，老板主动给加班费。

- 最后引咎辞职。

- 技能升级点

    > ThinkPHP YUCC

---

## 非程序员职业经历

### 2009/3-2012/5 深圳海盈科技有限公司

> 提一下，在本职工作外尝试**VBA**编程实现办公自动化，提高工作效率，且不到一周实现，发现自己有编程的天赋，上司因为我居然还会这一手称我是天才。

### 2006/5-2008/12 惠州德赛电池有限公司
### 2004/3-2005/6 东莞嘉财电业(船井电机)制造厂
### 2002/2-2003/12 东莞上焱电器制品厂

---

## 特别成就

### [Cordova](https://cordova.apache.org/)基于iOS集成VLC播放器

> 这个智能家居项目是让手机APP透过路由器远程连接家用摄像头实现监控功能。之前我已经在Android平台下实现了这个功能，特别出彩的是在iOS上。
> 
> 为实现这个功能，我认真研究了Cordova 框架下的iOS的代码，经过一个星期的研究，在框架代码里只添加了一行代码引用VLC静态库，实现了VLC播放功能。
> 
> 这是我程序员生涯中最高光时刻，也最能代表我的编程风格-简洁而巧妙。

---

### 优化Luci用户管理
> "18.06"版以前的Luci只支持root登录，但是这样容易让用户轻易得到产品的root权限，导致技术泄密，所以一直有各种多用户方案。
> 
> 这个项目参考了 [github/Hostle的代码](https://github.com/Hostle/openwrt-luci-multi-user) ，但是这个方案有个缺点，就是为了区分页面，把最基本的admin目录改写成admins。但是这样改动，就和Luci官方版本不兼容了，不是我喜欢的方式。
> 
> 经过我的研究，发现可以用对象名比如"admin.system.admin"来替代"admin"字段，实现页面区分和控制，这样，只用很少的补丁就能兼容官方的Luci。

---

### SSH反向代理远程控制平台
> 相信这是世界上最简洁的远程集中控制嵌入式设备的方案。
> 
> 参考了SSH反向代理，网上的方案都是单台设备控制，但是我们的目的是要控制可能的成千上万台设备。经过不断地尝试，不断地失败，灵光一闪，最终找到了实现的捷径，所有这一切在一个星期内实现了。
> 
> 最初的方案包含PHP代码，总觉得碍眼，心里总是个梗。一年春节前夕，闲来无事，尝试去掉这个累赘，不到一天的功夫，终于成功了，而且保证和原来的接口兼容，只改动代理服务器，而路由器不用任何改动。

---

### 优化嵌入式设备上的LoRa服务器
> github上有好几个嵌入式LoRa服务器方案，其中有个方案吸引了我，第一次接触meson还有自动生成代码，应该是相当优秀的程序员写的。
> 
> 我发现代码里有大量的HEX和BYTES相互转换程序，相当绕人，但是HEX其实只有人机接口才需要，于是我将包括SQLITE字段在内的全部HEX数据类型改成BYTES，只在和UI交互中作BYTE2HEX相互转换，终于让代码变得容易理解了。
> 
> 从Qualcomm平台迁移到Mediatek平台时，发现还存在大小端问题，经过研究，用简单的算术实现了大小端自适应，不用判断芯片是大端还是小端。

---

### 低轨卫星窄带通讯
> 在合作之前对方公司和其它公司接触过，但是搞不定找到了我们。这个项目的难点在于每天只有四次窗口通信时间，每次时间不定，最多不超过5分钟；
>
> 刚开始没头绪，就找对方要了单片机版本的代码参考，但是那些代码全放在一个文件里，没有参考价值，就自己着手写；
> 
> 后来发现项目比想象的要简单，和卫星顺利通讯成功；对方也信心大增，也加码从单向通讯升级到双向通讯。

---
### 给LoRa服务器React框架添加百度地图
> 原先的开源代码有个地图是Street，国内不能正常访问，开发经理打算换成百度地图。但是前端程序员不会React只会Vue,为了这个小小的功能居然要用Vue重写前端代码，原本打算很快解决的简单问题最后拖了一年才走人了事。
> 
> 我接手后证实了这个程序员完全不合格，其实连Vue也不会写，根本不懂异步ajax。本来打算修改Vue的，后来想想毫无价值，就着手在React框架下添加百度地图，参照原来的Street地图代码很轻松地实现百度地图功能，在判断浏览器语言为zh_CN时切换到百度地图。
>
> 其实这只是个小案子，根本无足挂齿，之所以提，只是为了强调-**大部分程序员都不合格**。
> 还有，开源代码原先只有英文，但是有必要改成Vue吗？一个简单的**react-intl**就够了。

---
## 职业随想

- 作为程序员，我认为写代码并不是最重要的，最重要的是会读，能读懂代码，理解优秀程序员的设计思想;
    > 如果一个程序员畏难不去读代码，只是利用既有的代码知识去写代码，水平永远停滞不前;
    >    
    > 只有引用优秀代码源，读文档，读代码，才能学到业内先进的代码设计和技术潮流，才能不断提升自己。

- 我从来就爱折腾，从最早为提高效率自学**VBA**，又到**PHP**，后来为刷路由器琢磨编译**openWrt**，其他**黑苹果**，**树莓派**，**安卓**刷机自然不在话下了。
    > 入行以来，一直疑惑如此多的程序员同事不会用Google，其实这个只是个很简单的技能了。更有甚者连电脑系统都只用**Windows 7**，天哪，都是十几年前的东西了，新系统都学不会，还指望能学习新技术吗?
    >    
    > 还有，现在**Centos 7**已经不维护了，但是还有公司抱着这个陈旧的系统不放，借口是稳定。但是，软件业是唯一没有沉没成本的行业，甚至软件出BUG了升级个补丁即可，也没有任何用户因为软件BUG发起起诉(有免责协议)，完全可以尽情折腾，有些开发团队拒绝升级，只能说能力不合格。

- 注重代码规范，注释和git提交都用英语，避免出现乱码，原则是符合基本语法，能彼此看懂就行。这个大家都知道，可以说是合格程序员的基本素养。

---

## 自我评价
    
> 自从事程序员工作以来，我一直是所在公司最优秀的程序员，不管是学习新知识的速度还是克服难题的毅力都超过同事，而且不挑工作，不抱怨公司，因为我的价值观是工作既然是自己选择的，就要自己承担责任(学自弗洛姆《逃避自由》一书),如果不满意，就应该离开。

