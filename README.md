# Project Description
Collection of quality safety articles(To be rebuilt)
```
Some are inconvenient to release.  
Some forget update,can see me star.  
collection-document awesome
以前的链接中大多不是优质的  
渗透测试部分不再更新  
因精力有限，缓慢更新  
Author: [tom0li]  
Blog: https://tom0li.github.io
```
- [Project Description](#project-description)
  - [Github-list](#github-list)
    - [Awesome-list](#awesome-list)
    - [开发](#开发)
    - [其它](#其它)
  - [安全](#安全)
    - [安全list](#安全list)
    - [安全市场洞察](#安全市场洞察)
    - [云安全](#云安全)
      - [云基础知识](#云基础知识)
      - [云原生安全](#云原生安全)
      - [云上攻防](#云上攻防)
    - [AI安全](#ai安全)
    - [新安全方案](#新安全方案)
      - [构建下一代安全](#构建下一代安全)
      - [零信任](#零信任)
      - [DevSecOps](#devsecops)
    - [安全检测](#安全检测)
      - [RASP](#rasp)
      - [HIDS](#hids)
      - [WAF](#waf)
        - [WAF建设指南](#waf建设指南)
        - [BypassWAF](#bypasswaf)
      - [Webshell检测](#webshell检测)
      - [反弹Shell检测](#反弹shell检测)
      - [EDR](#edr)
      - [AV](#av)
      - [横向移动检测-蜜罐思路](#横向移动检测-蜜罐思路)
      - [恶意流量检测](#恶意流量检测)
      - [IDS](#ids)
      - [文本检测](#文本检测)
    - [APT研究](#apt研究)
      - [高级威胁-list](#高级威胁-list)
      - [钓鱼](#钓鱼)
      - [C2-RAT](#c2-rat)
    - [安全运营](#安全运营)
    - [数据安全](#数据安全)
    - [个人安全](#个人安全)
  - [预警&研究](#预警研究)
    - [ImageMagick](#imagemagick)
    - [Privilege-Escalation](#privilege-escalation)
    - [vCenter](#vcenter)
    - [VPN](#vpn)
      - [Sangfor](#sangfor)
      - [Pulse](#pulse)
      - [Palo](#palo)
      - [Fortigate](#fortigate)
      - [Citrix Gateway/ADC](#citrix-gatewayadc)
    - [Tomcat](#tomcat)
    - [FUZZING](#fuzzing)
    - [通信安全](#通信安全)
      - [端对端通信(初版)](#端对端通信初版)
      - [SNI](#sni)
  - [代码审计-JAVA](#代码审计-java)
    - [反序列化-其他](#反序列化-其他)
    - [RMI](#rmi)
    - [Shiro](#shiro)
    - [Fastjson](#fastjson)
    - [Dubbo](#dubbo)
    - [CAS](#cas)
    - [Solr模版注入](#solr模版注入)
    - [Apache Skywalking](#apache-skywalking)
    - [Spring](#spring)
      - [Spring-boot](#spring-boot)
      - [Spring-cloud](#spring-cloud)
      - [Spring-data](#spring-data)
  - [渗透](#渗透)
    - [边界渗透](#边界渗透)
      - [渗透记录和总结](#渗透记录和总结)
      - [信息收集](#信息收集)
      - [靶场](#靶场)
      - [渗透技巧](#渗透技巧)
    - [内网渗透](#内网渗透)
      - [Exchange](#exchange)
      - [hash ticket Credential](#hash-ticket-credential)
      - [代理转发与端口复用](#代理转发与端口复用)
      - [内网平台](#内网平台)
      - [内网技巧](#内网技巧)
      - [提权利用](#提权利用)
  - [Bug_Bounty](#bug_bounty)
  - [Web](#web)
    - [XXE](#xxe)
    - [XSS](#xss)
    - [Jsonp](#jsonp)
    - [CORS](#cors)
    - [CSRF](#csrf)
    - [SSRF](#ssrf)
    - [SQL](#sql)
    - [文件包含](#文件包含)
    - [上传](#上传)
    - [任意文件读取](#任意文件读取)
    - [Web缓存欺骗](#web缓存欺骗)
    - [Web缓存投毒](#web缓存投毒)
    - [SSI](#ssi)
    - [SSTI](#ssti)
    - [JS](#js)
    - [DNS](#dns)
  - [其他](#其他)
      - [Git](#git)
      - [二维码](#二维码)
      - [爬虫](#爬虫)
      - [效率](#效率)
      - [科普](#科普)
  - [Contribute](#contribute)
  - [Acknowledgments](#acknowledgments)
  - [Star](#star)

## Github-list
### Awesome-list

* [awesome-web-security](https://github.com/qazbnm456/awesome-web-security) 
* [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) - 万星list 
* [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis)
* [Android Security](https://github.com/ashishb/android-security-awesome) - Collection of Android security related resources.
* [Security](https://github.com/sbilly/awesome-security) - Software, libraries, documents, and other resources.
* [An Information Security Reference That Doesn't Suck](https://github.com/rmusser01/Infosec_Reference)
* [Security Talks](https://github.com/PaulSec/awesome-sec-talks) - Curated list of security conferences.
* [OSINT](https://github.com/jivoi/awesome-osint) - Awesome OSINT list containing great resources.
* [The toolbox of open source scanners](https://github.com/We5ter/Scanners-Box) - The toolbox of open source scanners
* [blackhat-arsenal-tools](https://github.com/toolswatch/blackhat-arsenal-tools) - Official Black Hat Arsenal Security Tools Repository
* [awesome-iot-hacks](https://github.com/nebgnahz/awesome-iot-hacks)
* [awesome-awesome](https://github.com/emijrp/awesome-awesome)
* [Curated list of awesome lists](https://github.com/sindresorhus/awesome)
* [Awesome Awesomness](https://github.com/bayandin/awesome-awesomeness) - The List of the Lists.
* [PENTESTING-BIBLE](https://github.com/blaCCkHatHacEEkr/PENTESTING-BIBLE) - 安全相关的内容
* [Web-Security-Learning](https://github.com/CHYbeta/Web-Security-Learning) - by CHYbeta
* [Software-Security-Learning](https://github.com/CHYbeta/Software-Security-Learning) - by CHYbeta
* [MiscSecNotes](https://github.com/JnuSimba/MiscSecNotes) - by JnuSimba notes 
* [AndroidSecNotes](https://github.com/JnuSimba/AndroidSecNotes) - notes
* [LinuxSecNotes](https://github.com/JnuSimba/LinuxSecNotes) - notes
* [resource collection of python security and code review](https://github.com/bit4woo/python_sec)
* [Pentest_Interview](https://github.com/Leezj9671/Pentest_Interview)
* [tanjiti 信息源](https://github.com/tanjiti/sec_profile) - by 百度tanjiti 每天爬取的安全信息源
* [CVE-Flow](https://github.com/404notf0und/CVE-Flow) - by 404notfound 监控CVE增量更新、基于深度学习的CVE EXP预测和自动化推送
* [security_w1k1](https://github.com/euphrat1ca/security_w1k1/) euphrat1ca师傅时时刻刻更新和安全相关的仓库

### 开发

* [互联网 Java 工程师进阶知识完全扫盲](https://github.com/doocs/advanced-java)
* [Java学习+面试指南 一份涵盖大部分Java程序员所需要掌握的核心知识](https://github.com/Snailclimb/JavaGuide)
* [Python Cheat Sheet ](https://github.com/crazyguitar/pysheeet)
* [A collection of full-stack resources for programmers.](https://github.com/charlax/professional-programming)
* [web, 前端, javascript, nodejs, electron, babel, webpack, rollup, react, vue ...](https://github.com/senntyou/blogs)
* [关于Python的面试题](https://github.com/taizilongxu/interview_python)
* [Python-100-Days](https://github.com/jackfrued/Python-100-Days)
* [python3-source-code-analysis](https://github.com/flaggo/python3-source-code-analysis)
* [Coding Interview University](https://github.com/jwasham/coding-interview-university)
* [tech-interview-handbook](https://github.com/yangshun/tech-interview-handbook) - good
* [面试必备基础知识](https://github.com/CyC2018/CS-Notes)
* [CS基础](https://github.com/selfboot/CS_Offer/)
* [算法/深度学习/NLP面试笔记](https://github.com/imhuay/Algorithm_Interview_Notes-Chinese)
* [算法手记](https://github.com/labuladong/fucking-algorithm)
* [数据结构和算法必知必会的50个代码实现](https://github.com/wangzheng0822/algo)
* [interview_internal_reference](https://github.com/0voice/interview_internal_reference) 
* [reverse-interview](https://github.com/yifeikong/reverse-interview-zh) - 技术面试最后反问面试官的话

### 其它

* [信息安全从业者书单推荐](https://github.com/riusksk/secbook)
* [专为程序员编写的英语学习指南 v1.2](https://github.com/yujiangshui/A-Programmers-Guide-to-English)
* [中国程序员容易发音错误的单词](https://github.com/shimohq/chinese-programmer-wrong-pronunciation)
* [对开发人员有用的定律、理论、原则和模式](https://github.com/nusr/hacker-laws-zh)
* [SecLists](https://github.com/danielmiessler/SecLists) - Collection of multiple types of lists used during security assessments.
* [A collection of web attack payloads](https://github.com/foospidy/payloads) payloads集
* [安全相关思维导图整理收集](https://github.com/phith0n/Mind-Map) - by p牛 
* [安全思维导图集合](https://github.com/SecWiki/sec-chart) -by SecWiki
* [Android-Reports-and-Resources](https://github.com/B3nac/Android-Reports-and-Resources) - HackerOne Reports
* [AppSec](https://github.com/paragonie/awesome-appsec) - Resources for learning about application security.
* [Infosec](https://github.com/onlurking/awesome-infosec) - Information security resources for pentesting, forensics, and more.
* [YARA](https://github.com/InQuest/awesome-yara) - YARA rules, tools, and people.
* [macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
* [awesome-security-weixin-official-accounts](https://github.com/DropsOfZut/awesome-security-weixin-official-accounts) 
* [2018-2020青年安全圈-活跃技术博主/博客](https://github.com/404notf0und/Security-Data-Analysis-and-Visualization) - by 404notf0und
* [996.Leave](https://github.com/623637646/996.Leave)
* [租房要点，适用于北上广深杭](https://github.com/soulteary/tenant-point)
* [北京买房](https://github.com/facert/beijing_house_knowledge)
* [北京买房图鉴](https://github.com/yangyiRunning/Beijing-House)
* [上海买房](https://github.com/ayuer/shanghai_house_knowledge)
* [杭州买房](https://github.com/houshanren/hangzhou_house_knowledge)
* [awesome-macOS](https://github.com/iCHAIT/awesome-macOS) - mac软件
* [awesome-mac](https://github.com/jaywcjlove/awesome-mac/blob/master/README-zh.md#%E5%BC%80%E5%8F%91%E8%80%85%E5%B7%A5%E5%85%B7) - mac软件
* [ruanyf](https://github.com/ruanyf/weekly) - 科技爱好者周刊

## 安全
### 安全list

* [arxiv.org](https://arxiv.org/) 论文库
* [404notf0und学习记录](https://github.com/404notf0und/Always-Learning#APT%E6%A3%80%E6%B5%8B) 关注安全检测部分
* [Donot师傅收集的入侵检测相关的内容](https://github.com/donot-wong/SecAcademic)
* [郑瀚-Blog](https://www.cnblogs.com/littlehann/) 遍历看
* [cdxy-Blog](https://www.cdxy.me/) 太帅
* [zuozuovera-Blog](https://www.zuozuovera.com/) 心灵手巧
* [安全学术圈2018年度总结](https://mp.weixin.qq.com/s/eQ5os0Fdb498BoQLKUDmrA) - 微信号安全学术圈
* [security-hardening](https://github.com/decalage2/awesome-security-hardening) 安全加固大全

### 安全市场洞察
介绍安全市场概况、趋势、规律。国内外有安全业务厂商

### 云安全
#### 云基础知识

* [虚拟化简介](https://yuvaly0.github.io/2020/06/19/introduction-to-virtualization.html)
* [kvm](https://github.com/yifengyou/learn-kvm) yifengyou师傅 kvm笔记

#### 云原生安全

* [Google:BeyondProd模型](https://cloud.google.com/security/beyondprod?hl=zh-cn)
* [美团云原生之容器安全实践](https://tech.meituan.com/2020/03/12/cloud-native-security.html) 
* [云原生入侵检测趋势观察](https://xz.aliyun.com/t/7841)
* [云原生带来的云安全机遇](https://www.freebuf.com/articles/network/242950.html) 云原生安全市场概况(非技术)
* [阿里云安全白皮书](https://github.com/tom0li/collection-document/blob/master/%E9%98%BF%E9%87%8C%E4%BA%91%E5%AE%89%E5%85%A8%E7%99%BD%E7%9A%AE%E4%B9%A6.pdf)

#### 云上攻防

* [Awesome-serverless](https://github.com/puresec/awesome-serverless-security/)
* [Red Teaming for Cloud](https://mp.weixin.qq.com/s/lUHd6lmFl3m9BMdSC2wwcw) 清晰的阐述什么是red team, 部分典型cloud pentest路径
* [tom0li: docker逃逸小结](https://tom0li.github.io/Docker%E9%80%83%E9%80%B8%E5%B0%8F%E7%BB%93%E7%AC%AC%E4%B8%80%E7%89%88/) 以攻击角度介绍docker逃逸3类方法，介绍一些逃逸实际场景以及针对工程师攻击方法
* [Kubernetes security](https://github.com/kabachook/k8s-security) This repo is a collection of kubernetes security stuff and research.
* [serverless functions攻防初探](https://www.cdxy.me/?p=836) 介绍serverless functions攻击路径和防御检测手法
* [RDS数据库攻防](https://xz.aliyun.com/t/8451) 通过信息泄漏的非子ACCESSKEY，配置后可外网连接RDS
* [容器与云的碰撞——一次对 MinIO 的测试](https://mp.weixin.qq.com/s/X04IhY9Oau-kDOVbok8wEw) 主要是MinIO对象存储的SSRF漏洞，POST SSRF 307跳转构造利用
* [Kubernetes中使用Helm2的安全风险](http://rui0.cn/archives/1573) 阐述针对Helm2获取secrets具体操作
* [K8s 6443批量入侵调查](https://www.cdxy.me/?p=833) 鉴权配置不当,允许匿名用户以特权请求k8s api，请求pod创建docker，在docker执行创建特权docker并执行恶意命令，删除创建pod
* [K8s渗透测试之kube-apiserver利用](https://www.cdxy.me/?p=839) 介绍了经典攻击路径，获取的pod中寻找高权限service acount
* [K8s渗透测试etcd的利用](https://www.cdxy.me/?p=827) 介绍未授权etcd和攻击者有cert时渗透命令，读取service account token命令、接管集群命令
* [K8s数据安全之Secrets防护方案](https://www.cdxy.me/?p=832)
* [Fantastic Conditional Access Policies and how to bypass them](https://dirkjanm.io/assets/raw/fantastic_policies_cloud_roundup.pdf) Dirk-jan师傅的Azure议题
* [I’m in your cloud: A year of hacking Azure AD](https://dirkjanm.io/assets/raw/Im%20in%20your%20cloud%20bluehat-v1.0.pdf) Dirk-jan师傅的Azure议题
* [Istio访问授权再曝高危漏洞CVE-2020-8595](https://mp.weixin.qq.com/s?__biz=MzIyODYzNTU2OA==&mid=2247487481&idx=1&sn=02a38db691331634fe41a413beb58694&chksm=e84fa926df382030ac57be9c1ee9cb8836ec37fc79e3a2cef68acb6945a51f0ed94882e39611) Istio 完全匹配模式exact匹配不当未授权访问



### AI安全
* [AI-for-Security-Learning](https://github.com/404notf0und/AI-for-Security-Learning) AI的力量 - by 404notf0und
* [0xMJ:AI-Security-Learning](https://github.com/0xMJ/AI-Security-Learning#webshell%E6%A3%80%E6%B5%8B)
* [Adversarial ML Threat Matrix](https://github.com/mitre/advmlthreatmatrix) 
* [AI安全的威胁风险矩阵](https://ai.tencent.com/ailab/media/AI%E5%AE%89%E5%85%A8%E7%9A%84%E5%A8%81%E8%83%81%E9%A3%8E%E9%99%A9%E7%9F%A9%E9%98%B5.pdf)

### 新安全方案
#### 构建下一代安全

* [弹性安全网络 - 构建下一代安全的互联网](https://mp.weixin.qq.com/s/epFSC88J7LF3BGwQdoZ-Rg)

#### 零信任

* [张欧：数字银行可信网络实践](https://mp.weixin.qq.com/s/VRG9LEbGTxhpMmCUTUSA8w) 零信任理念
* [零信任下代理工具](https://github.com/mandatoryprogrammer/CursedChrome/blob/master/README.md) 把chrome作为代理，可以通过chrome访问受害者可以访问web服务

#### DevSecOps

* [DevSecOps理念及思考](https://mp.weixin.qq.com/s/_jBmFdtyXY5D_YrrTUP1iQ) 腾讯安全应急响应中心
* [Awesome-DevSecOps](https://github.com/devsecops/awesome-devsecops)

### 安全检测
* [安全智能应用的一些迷思](https://zhuanlan.zhihu.com/p/88042567)

#### RASP

* [浅谈RASP](https://lucifaer.com/2019/09/25/%E6%B5%85%E8%B0%88RASP/)
* [以OpenRASP为基础-展开来港港RASP的类加载](https://xz.aliyun.com/t/8148)

#### HIDS

* [分布式HIDS集群架构设计](https://www.cnxct.com/distributed-hids-cluster-architecture-design/) 美团技术团队

#### WAF
##### WAF建设指南

* [WAF建设运营及AI应用实践](https://mp.weixin.qq.com/s?__biz=MjM5NzE1NjA0MQ==&mid=2651199346&idx=1&sn=99f470d46554149beebb8f89fbcb1578&chksm=bd2cf2d48a5b7bc2b3aecb501855cc2efedc60f6f01026543ac2df5fa138ab2bf424fc5ab2b0&scene=21#wechat_redirect)

##### BypassWAF

* [门神WAF众测总结](https://mp.weixin.qq.com/s/w5TwFl4Ac1jCTX0A1H_VbQ)
* [个人总结的waf绕过注入思路（附带6种常见waf的绕过方法）](https://www.t00ls.net/viewthread.php?tid=43687&extra=&page=1)
* [老司机带你过常规WAF](https://www.secpulse.com/archives/69983.html)
* [SQL注入ByPass的一些小技巧](https://mp.weixin.qq.com/s/fSBZPkO0-HNYfLgmYWJKCg)
* [在HTTP协议层面绕过WAF](https://www.freebuf.com/news/193659.html)
* [利用分块传输吊打所有WAF](https://www.anquanke.com/post/id/169738)
* [WAF绕过的捷径与方法](https://www.qiaoyue.net/2019/WAF%E7%BB%95%E8%BF%87%E7%9A%84%E6%8D%B7%E5%BE%84%E4%B8%8E%E6%96%B9%E6%B3%95/)
* [对过WAF的一些认知](http://static.anquanke.com/download/b/security-geek-2019-q2/article-18.html)
* [WAF Bypass之webshell上传jsp与tomcat](https://www.anquanke.com/post/id/210630#)
* [各种姿势jsp webshell](https://xz.aliyun.com/t/7798)

#### Webshell检测

* [查杀Java web filter型内存马](http://gv7.me/articles/2020/kill-java-web-filter-memshell/)
* [Filter/Servlet型内存马的扫描抓捕与查杀](https://gv7.me/articles/2020/filter-servlet-type-memshell-scan-capture-and-kill/)
* [杂谈Java内存Webshell的攻与防](https://mp.weixin.qq.com/s/DRbGeVOcJ8m9xo7Gin45kQ) 
* [JSP Webshell那些事 -- 攻击篇](https://mp.weixin.qq.com/s/YhiOHWnqXVqvLNH7XSxC9w)
* [Webshell攻与防PHP](https://github.com/qiyeboy/kill_webshell_detect/blob/master/%E7%9F%A5%E8%AF%86%E6%98%9F%E7%90%83-webshell%E6%94%BB%E4%B8%8E%E9%98%B2.pdf) 
* [污点传递理论在Webshell检测中的应用 - PHP篇](https://mp.weixin.qq.com/s/MFmSliCQaaVEQ0E66vN5Xg)
* [新开始:webshell的检测](https://iami.xyz/New-Begin-For-Nothing/)
* [利用 intercetor 注入 spring 内存 webshell](https://github.com/LandGrey/webshell-detect-bypass/blob/master/docs/inject-interceptor-hide-webshell/inject-interceptor-hide-webshell.md) 文章是攻击利用角度

#### 反弹Shell检测

* [反弹Shell原理及检测技术研究](https://www.cnblogs.com/LittleHann/p/12038070.html) -by LittleHann
* [反弹Shell剖析](https://cloud.tencent.com/developer/article/1645464)
* [详解反弹shell多维检测技术](https://www.freebuf.com/articles/network/263684.html)

#### EDR

* [Lets-create-an-edr-and-bypass](https://ethicalchaos.dev/2020/06/14/lets-create-an-edr-and-bypass-it-part-2/)
* [openedr](https://github.com/ComodoSecurity/openedr) 开源产品edr

#### AV

* [exploiting-almost-every-antivirus-software](https://www.rack911labs.com/research/exploiting-almost-every-antivirus-software/) 反制av，使用链接方式借av高权限达到任意文件删除
* [Bypassing Windows Defender Runtime Scanning](https://labs.f-secure.com/blog/bypassing-windows-defender-runtime-scanning/) 枚举测试调用哪些api会触发Defender检测，发现创建CreateProcess和CreateRemoteThread时触发Defender，提出三种解决方案，重写api调用、添加修改指令动态解密加载、使Defender不扫描该区域，作者针对Defender扫描机制(虚拟内存比较大，只扫描MEM_PRIVATE或RWX页权限)，当可疑的API被调用时动态设置PAGE_NOACCESS内存权限Defender不会对其安全扫描
* [Engineering antivirus evasion](https://blog.scrt.ch/2020/06/19/engineering-antivirus-evasion/)
* [Bypass Windows DefenderAttack Surface Reduction](https://data.hackinn.com/ppt/OffensiveCon2019/Bypass%20Windows%20Exploit%20Guard%20ASR.pdf)
* [Defender 扫描文件名问题](http://2016.eicar.org/85-0-Download.html)
* [herpaderping](https://github.com/jxy-s/herpaderping) 一种新型 bypass defender 
* [实现一款 shellcodeLoader](https://paper.seebug.org/1413/) 介绍一些shellcode执行方法,bypass sandbox方法
* [Malware_development_part](https://0xpat.github.io/Malware_development_part_5/) 恶意软件系列教程
* [杀软检测及其Hook点list](https://github.com/D3VI5H4/Antivirus-Artifacts/blob/main/ANTIVURUS_ARTIFACTS.pdf)

#### 横向移动检测-蜜罐思路

* [Honeypots](https://github.com/paralax/awesome-honeypots) - Honeypots, tools, components, and more.
* [Hunting for Skeleton Key Implants](https://riccardoancarani.github.io/2020-08-08-hunting-for-skeleton-keys/) 检测Skeleton Key 持久化
* [创建蜜罐账户检测Kerberoast](https://www.pentestpartners.com/security-blog/honeyroasting-how-to-detect-kerberoast-breaches-with-honeypots/)

#### 恶意流量检测

* [DataCon2020题解:通过蜜罐与DNS流量追踪Botnet](https://www.cdxy.me/?p=829)
* [DNS Tunnel隧道隐蔽通信实验 && 尝试复现特征向量化思维方式检测](https://www.cnblogs.com/LittleHann/p/8656621.html#_label0)
* [maltrail](https://github.com/stamparm/maltrail#introduction) 开源流量检测产品
* [cobalt-strike-default-modules-via-named-pipe检测](https://labs.f-secure.com/blog/detecting-cobalt-strike-default-modules-via-named-pipe-analysis/) 检测CS上线后执行默认模块的内存pipe
* [用DNS数据进行威胁发现](https://mp.weixin.qq.com/s/6CtRd7o4IjreLaU-hFt9vQ) 介绍360DNSMON 使用DNS监控发现skidmap后门，一些分析手法
* [DNSMon: 用DNS数据进行威胁发现](https://blog.netlab.360.com/use-dns-data-produce-threat-intelligence-2/) 通过DNSMON监控到事件，关联分析事件
* [evading-sysmon-dns-monitoring](https://blog.xpnsec.com/evading-sysmon-dns-monitoring/)
* [use-dns-data-produce-threat-intelligence](https://blog.netlab.360.com/use-dns-data-produce-threat-intelligence/)



#### IDS

* [我们来谈一谈IDS签名](https://www.anquanke.com/post/id/102948#h2-0)
* [不按顺序来的 TCP 包](https://strcpy.me/index.php/archives/789/)
* [网络层绕过 IDS/IPS 的一些探索](https://paper.seebug.org/1173/)

#### 文本检测

* [机器学习在二进制代码相似性分析中的应用](https://mp.weixin.qq.com/s?__biz=MjM5NTc2MDYxMw==&mid=2458303210&idx=1&sn=345f8cec156ada8fa9bf6a6d6de83906&chksm=b1818a6086f60376e766baf472171d8e2c780b2913568b46b683e3112fcc5f86c9bf4c19e38b&mpshare=1&scene=1&srcid=&sharer_sharetime=1580984631757&sharer_shareid=5dc01f49f38fd64ff3e64844bc7d2ea7&exportkey=A0qHBeUryuXO6zhGWt5OJNw%3D&pass_ticket=gjTFXl4hPMTBWzlKpWZWqK8HivXQ8q7ChNndmw4I8JrdAK0jWWFvKIq7OMnO3BhL#rd)

### APT研究
前期列出的大部分是攻击的内容，包含apt跟踪报告等。

#### 高级威胁-list

* [Red-Team-Infrastructure-Wiki](https://github.com/bluscreenofjeff/Red-Team-Infrastructure-Wiki)
* [分析APT报告集合](https://github.com/CyberMonitor/APT_CyberCriminal_Campagin_Collections) 强推
* [论高级威胁的本质和攻击力量化研究](http://www.vxjump.net/files/aptr/aptr.txt)
* [OffensiveCon会议](https://www.offensivecon.org/) 不再一一展示
* [ATT&CK](https://attack.mitre.org/matrices/enterprise/)
* [Red Team从0到1的实践与思考](https://mp.weixin.qq.com/s/cyxC4Of4Ic9c_vujQayTLg) 介绍Red Team是什么，适合团队内部red建设
* [MITRE | ATT&CK 中文站](https://huntingday.github.io) 知识导图，已不再更新
* [fireeye 威胁研究](https://www.fireeye.com/blog/threat-research.html) 知名威胁分析公司
* [red-team-and-the-next](https://devco.re/blog/2019/10/24/evolution-of-DEVCORE-red-team-and-the-next/) -by DEVCORE

redrain及其团队的Anti Threat文章
* [Noah blog](http://noahblog.360.cn/)  Anti Threat and Threat Actors through Noah Lab Analysts
* [烽火实验室 blog](https://blogs.360.cn/)
* [APT 分析及 TTPs 提取](https://paper.seebug.org/1132/)
* [关于ATT＆CK/APT/归因的讨论](https://weibo.com/ttarticle/p/show?id=2309404450471736639616)
* [Legends Always Die -- FireEye Summit中英雄联盟供应链攻击简述](https://card.weibo.com/article/m/show/id/2309404426957856047151)
* [XShellGhost事件技术回顾报告](https://cert.360.cn/static/files/XShellGhost%E4%BA%8B%E4%BB%B6%E6%8A%80%E6%9C%AF%E5%9B%9E%E9%A1%BE%E6%8A%A5%E5%91%8A.pdf)
* [Kingslayer A supply chain attack](http://www.hackdog.me/article/Kingslayer-A_supply_chain_attack--Part_1.html)

Solarwinds供应链分析
* [从Solarwinds供应链攻击（金链熊）看APT行动中的隐蔽作战](https://mp.weixin.qq.com/s/UqXC1vovKUu97569LkYm2Q) 代表qianxin分析Solarwinds攻击行为
* [Solarwinds分析](https://go.recordedfuture.com/hubfs/reports/pov-2020-1230.pdf) 
* [Highly Evasive Attacker Leverages SolarWinds Supply Chain to Compromise Multiple Global Victims With SUNBURST Backdoor](https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html)
* [SUNBURST分析其他细节](https://www.fireeye.com/blog/threat-research/2020/12/sunburst-additional-technical-details.html)

#### 钓鱼
* [SMTP用户枚举原理简介及相关工具](http://www.freebuf.com/articles/web/182746.html) - 用于获取用户字典
* [鱼叉攻击](https://payloads.online/archivers/2020-02-05/1)
* [论如何反击用AWVS的黑客](http://www.freebuf.com/news/136476.html)
* [从MySQL出发的反击之路](https://xz.aliyun.com/t/3277)
* [Mysql Client 任意文件读取攻击链拓展](https://paper.seebug.org/1112/)
* [恶意MySQL Server读取MySQL Client端文件](http://scz.617.cn/network/202001101612.txt)
* [https://github.com/BloodHoundAD/BloodHound/issues/267](https://github.com/BloodHoundAD/BloodHound/issues/267) -xss
* [Ghidra从XXE到RCE](https://xlab.tencent.com/cn/2019/03/18/ghidra-from-xxe-to-rce/) 针对工程师
* [来自微信外挂的安全风险](https://xlab.tencent.com/cn/2018/10/23/weixin-cheater-risks/) 针对个人
* [nodejs仓库钓鱼](https://www.cnblogs.com/index-html/p/npm_package_phishing.html) 针对工程师
* [制作Visual Stuio Code的恶意插件](https://d0n9.github.io/2018/01/17/vscode%20extension%20%E9%92%93%E9%B1%BC/#) 针对工程师
* [VS CODE钓鱼](https://blog.doyensec.com/2020/03/16/vscode_codeexec.html) 针对工程师
* [Python package 钓鱼](https://paper.seebug.org/326/)  针对工程师
* [docker客户端钓鱼](https://www.blackhat.com/docs/us-17/thursday/us-17-Cherny-Well-That-Escalated-Quickly-How-Abusing-The-Docker-API-Led-To-Remote-Code-Execution-Same-Origin-Bypass-And-Persistence.pdf) 针对工程师
* [利用恶意页面攻击本地Xdebug](https://xlab.tencent.com/cn/2018/03/)  针对工程师
* [华为HG532路由器钓鱼RCE](https://xlab.tencent.com/cn/2018/01/05/a-new-way-to-exploit-cve-2017-17215/) 针对个人
* [内网钓鱼]()
```
RMI反序列化
WIN远程连接漏洞CVE-2019-1333
Mysql读文件&反序列化
Dubbo反序列化
IDE反序列化
恶意vpn
恶意控件
笔记软件rce
社交软件rce
NodeJS库rce
Python package 钓鱼
VSCODE EXTENSION 钓鱼
VS Studio钓鱼
Twitter钓鱼
红包插件钓鱼防撤回插件
解压rce
破解软件钓鱼
docker客户端钓鱼
docker镜像钓鱼
Xdebug
Ghidra钓鱼
bloodhound钓鱼
AWVS钓鱼
蚁剑
浏览器插件
云盘污染
```
* [..etc]()



邮件伪造
* [一封伪造邮件引发的“探索”（涉及钓鱼邮件、SPF和DKIM等）](http://www.freebuf.com/articles/web/138764.html)
* [SPF 记录：原理、语法及配置方法简介](https://www.renfei.org/blog/introduction-to-spf.html)
* [邮件伪造技术与检测](https://www.secpulse.com/archives/78738.html)
* [伪造电子邮件以及制造电子邮件炸弹的攻防探讨](https://www.freebuf.com/sectool/184555.html)
* [绕过DKIM验证，伪造钓鱼邮件](http://www.4hou.com/web/7857.html)
* [Best Practices on Email Protection: SPF, DKIM and DMARC](https://wiki.zimbra.com/wiki/Best_Practices_on_Email_Protection:_SPF,_DKIM_and_DMARC)
* [Cobalt Strike Spear Phish](https://evi1cg.me/archives/spear_phish.html)
* [Gsuite SMTP inject](https://www.ehpus.com/post/smtp-injection-in-gsuite)

#### C2-RAT

目前只是简单列一下
* [Koadic C3 COM Command & Control - JScript RAT](https://github.com/zerosum0x0/koadic)
* [QuasarRAT](https://github.com/quasar/QuasarRAT)
* [CS]()

### 安全运营

* [如何评价安全工作的好坏](https://zhuanlan.zhihu.com/p/226493047) 腾讯'职业欠钱'的向上管理的一些分享

### 数据安全

* [互联网企业数据安全体系建设](https://tech.meituan.com/2018/05/24/data-security-system-construction.html)
* [浅谈数据安全](https://iami.xyz/Talk-about-data-security/)

### 个人安全

* [Tor-0day-Finding-IP-Addresses](https://www.hackerfactor.com/blog/index.php?/archives/896-Tor-0day-Finding-IP-Addresses.html)
* [lcamtuf灾难计划](https://lcamtuf.coredump.cx/prep/)
* [个人隐私保护](https://tom0li.github.io/%E4%B8%AA%E4%BA%BA%E9%9A%90%E7%A7%81%E4%BF%9D%E6%8A%A4/)
* [保护隐私](https://github.com/No-Github/Digital-Privacy)

## 预警&研究
* [Top 10 Web Hacking Techniques of 2017](https://portswigger.net/blog/top-10-web-hacking-techniques-of-2017) - 一个nb的网站
* [Top-10-web-hacking-techniques-of-2018](https://portswigger.net/research/top-10-web-hacking-techniques-of-2018)
* [安全PPT大全](http://www.vipread.com/)
* [us-19-Tsai-Infiltrating-Corporate-Intranet-Like-NSA](https://i.blackhat.com/USA-19/Wednesday/us-19-Tsai-Infiltrating-Corporate-Intranet-Like-NSA.pdf) -Orange pwn vpn
* [bypass沙箱](https://yuange1975.blogspot.com/2019/08/bypass.html) -yuange
* [编译原理在安全领域的应用](https://mp.weixin.qq.com/s/6SqdcbyABfBxSaNfDlFKog)
* [软件无线电和开源基站在漏洞挖掘中的应用 PART 4：基带安全的一些探索和学习资源整合](https://cn0xroot.com/2020/11/21/part-4/) by 雪碧 0xroot
* [recovering-passwords-from-pixelized-screenshots-sipke-mellema](https://www.linkedin.com/pulse/recovering-passwords-from-pixelized-screenshots-sipke-mellema) 去除文本马赛克,测试限制条件过多,需要同一截图软件、xy坐标、字体、颜色

### ImageMagick

* [ImageMagick漏洞凑热闹手札](https://d0n9.github.io/2018/08/22/ImageMagick%20%E6%BC%8F%E6%B4%9E%E5%87%91%E7%83%AD%E9%97%B9%E6%89%8B%E6%9C%AD/#)
* [如何使用Fuzzing挖掘ImageMagick的漏洞](https://github.com/lcatro/Fuzzing-ImageMagick/blob/master/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8Fuzzing%E6%8C%96%E6%8E%98ImageMagick%E7%9A%84%E6%BC%8F%E6%B4%9E.md)
* [ImageMagick-CVE-2016-3714 命令执行分析](http://www.zerokeeper.com/vul-analysis/ImageMagick-CVE-2016-3714.html)
* [Imagemagick 邂逅 getimagesize 的那点事儿](https://paper.seebug.org/969/)

### Privilege-Escalation
* [Ubuntu-gdm3-accountsservice-LPE](https://securitylab.github.com/research/Ubuntu-gdm3-accountsservice-LPE)

### vCenter
* [CVE-2021-21972 vCenter 6.5-7.0 RCE 漏洞分析](http://noahblog.360.cn/vcenter-6-5-7-0-rce-lou-dong-fen-xi/)

### VPN

#### Sangfor
* [深信服后台RCE](https://www.cnblogs.com/potatsoSec/p/12326356.html)
* [深信服前台RCE由于没公开不附链接]()

#### Pulse
* [Pulse-secure-read-passwd-to-rce](https://blog.orange.tw/2019/09/attacking-ssl-vpn-part-3-golden-pulse-secure-rce-chain.html)  -by orange
* [Pulse Connect Secure RCE CVE-2020-8218](https://www.gosecure.net/blog/2020/08/26/forget-your-perimeter-rce-in-pulse-connect-secure/) 
* [Pulse Connect Secure – RCE via Template Injection (CVE-2020-8243)](https://research.nccgroup.com/2020/10/06/technical-advisory-pulse-connect-secure-rce-via-template-injection-cve-2020-8243/)

#### Palo
* [Attacking SSL VPN - Part 1: PreAuth RCE on Palo Alto GlobalProtect, with Uber as Case Study!](https://blog.orange.tw/2019/07/attacking-ssl-vpn-part-1-preauth-rce-on-palo-alto.html)

#### Fortigate
* [Attacking SSL VPN - Part 2: Breaking the Fortigate SSL VPN](https://blog.orange.tw/2019/08/attacking-ssl-vpn-part-2-breaking-the-fortigate-ssl-vpn.html)
 
#### Citrix Gateway/ADC
* [Citrix Gateway/ADC 远程代码执行漏洞分析](https://blog.riskivy.com/citrix-gateway-adc-%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/)

### Tomcat

* [Apache Tomcat 8.x vulnerabilities](https://tomcat.apache.org/security-8.html)

### FUZZING
* [Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing)
* [Fuzzing平台建设的研究与设计](http://riusksk.me/2020/01/21/Fuzzing%E5%B9%B3%E5%8F%B0%E5%BB%BA%E8%AE%BE%E7%9A%84%E7%A0%94%E7%A9%B6%E4%B8%8E%E8%AE%BE%E8%AE%A1-paper/) by 泉哥
* [探索先进自动化漏洞挖掘技术中的不足](https://mp.weixin.qq.com/s/1q_YCJoyCREtgU3X2_0uqQ) 覆盖度问题
* [Fuzzing战争: 从刀剑弓斧到星球大战](https://mp.weixin.qq.com/s?__biz=MzI3ODI4NDM2MA==&mid=2247483742&idx=1&sn=55414da793fdf882cd6a0e396857678a&scene=21#wechat_redirect) Flanker 讲解Fuzzing历史趋势
* [Fuzzing战争系列之二：不畏浮云遮望眼](https://mp.weixin.qq.com/s/G26MJOH4VPene1Sd_zjEQw) Coverage-Guided Fuzzing 解决闭源思路 Static or Dynamic & Dynamic Tracing
* []()

### 通信安全
#### 端对端通信(初版)
* [史上最全的zoom漏洞和修复方案介绍](https://mp.weixin.qq.com/s/a7mN0lTeXxA3YmZZxIGNRg)
* [对安全即时通讯软件的流量分析攻击](https://www.anquanke.com/post/id/208678#)
* [Shadowsocks基于二次混淆加密传输的数据保密性原理分析](https://www.secrss.com/articles/18469)

#### SNI
* [ESNI](https://www.cloudflare.com/zh-cn/learning/ssl/what-is-encrypted-sni/)  what-is-encrypted-sni
* [encrypted-client-hello-the-future-of-esni-in-firefox](https://blog.mozilla.org/security/2021/01/07/encrypted-client-hello-the-future-of-esni-in-firefox/)
* [encrypted-client-hello](https://blog.cloudflare.com/encrypted-client-hello/)


## 代码审计-JAVA

* [javasec.org](https://javasec.org/) -by 园长
* [JAVA代码审计的一些Tips(附脚本)](https://xz.aliyun.com/t/1633)
* [敏信Java代码审计-层层推进](https://xz.aliyun.com/t/2074)
* [Java漏洞代码](https://github.com/JoyChou93/java-sec-code)
* [代码审计知识星球精选](https://tricking.io)

### 反序列化-其他

* [Java-Deserialization-Cheat-Sheet](https://github.com/GrrrDog/Java-Deserialization-Cheat-Sheet#java-native-serialization-binary)
* [tomcat不出网回显](https://xz.aliyun.com/t/7535)
* [Java 反序列化回显的多种姿势](https://xz.aliyun.com/t/7740)
* [半自动化挖掘request实现多种中间件回显](http://gv7.me/articles/2020/semi-automatic-mining-request-implements-multiple-middleware-echo/)
* [Java 后反序列化漏洞利用思路](http://rui0.cn/archives/1338)
* [URL ECCENTRICITIES IN JAVA](https://blog.pwnl0rd.me/post/lfi-netdoc-file-java/) java url类请求导致的ssrf lfi 泄漏java版本
* [HSQLDB 安全测试指南](https://xz.aliyun.com/t/9162#) HSQLDB(HyperSQL DataBase) 是一个完全由Java编写的小型嵌入式数据库

### RMI

* [Java RMI入门](http://scz.617.cn/network/202003121717.txt)
* [attacking-java-rmi-services-after-jep-290](https://mogwailabs.de/blog/2019/03/attacking-java-rmi-services-after-jep-290/)
* [针对RMI服务的九重攻击 - 上](https://xz.aliyun.com/t/7930)
* [针对RMI服务的九重攻击 - 下](https://xz.aliyun.com/t/7932)
* [一次攻击内网rmi服务的深思](https://forum.90sec.com/t/topic/388/1) 解决REJECTED 报错

### Shiro

* [Shiro RememberMe 漏洞检测的探索之路](https://blog.xray.cool/post/how-to-find-shiro-rememberme-deserialization-vulnerability/) 从使用空SimplePrincipalCollection检测key到Tomcat通用回显到检测过程会碰到的种种困难
* [从一次开发漏洞看shiro的正确使用](https://xz.aliyun.com/t/5287)
* [Shiro RememberMe 1.2.4 反序列化导致的命令执行漏洞](https://paper.seebug.org/shiro-rememberme-1-2-4/)
* [强网杯“彩蛋”——Shiro 1.2.4(SHIRO-550)漏洞之发散性思考](https://blog.zsxsoft.com/post/35)
* [Shiro 721 Padding Oracle攻击漏洞分析](https://www.anquanke.com/post/id/193165#h2-14)
* [Shiro权限绕过漏洞分析](https://www.freebuf.com/vuls/231909.html)
* [Java代码执行漏洞中类动态加载的应用](https://mp.weixin.qq.com/s?__biz=MzAwNzk0NTkxNw==&mid=2247484622&idx=1&sn=8ec625711dcf87f0b6abe67483f0534d) 不出网注册filter reGeorg代理

### Fastjson

* [fastjson反序列化利用](https://lazydog.me/post/fastjson-JdbcRowSetImpl-rce-exploit.html)
* [FastJson =< 1.2.47 反序列化漏洞浅析](https://bithack.io/forum/393)
* [FASTJSON反序列化之基于JNDI利用方式](https://manning23.github.io/2018/03/01/Fastjson%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96jndi%E5%88%A9%E7%94%A8%E8%BF%87%E7%A8%8B%E5%88%86%E6%9E%90/)
* [Fastjson反序列化漏洞调试分析](https://www.angelwhu.com/blog/?p=552)
* [FastJson 反序列化学习](http://www.lmxspace.com/2019/06/29/FastJson-%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E5%AD%A6%E4%B9%A0/)
* [浅谈Fastjson RCE漏洞的绕过史](https://www.freebuf.com/vuls/208339.html)
* [通过dnslog探测fastjson的几种方法](http://gv7.me/articles/2020/several-ways-to-detect-fastjson-through-dnslog/)
* [fastjson 1.2.68 autotype bypass gadget 的一种挖掘思路](https://hackcrowd.com/forum_detail/828)

### Dubbo

* [Dubbo2.7.7反序列化漏洞绕过分析](https://mp.weixin.qq.com/s/jKM-Z2BTFfk_Ro1rJAxg5w) 云鼎实验室
* [Dubbo 2.7.8多个远程代码执行漏洞](https://xz.aliyun.com/t/8917)
* [如何绕过高版本JDK的限制进行JNDI注入利用](https://kingx.me/Restrictions-and-Bypass-of-JNDI-Manipulations-RCE.html) 绕过高版本JDK限制：利用LDAP返回序列化数据，触发本地Gadget。为什么放到Dubbo下面，因为在Dubbo碰到的问题。

### CAS

* [Apereo CAS 4.X execution参数反序列化漏洞分析](https://xz.aliyun.com/t/7032)
* [Apereo CAS 反序列化漏洞分析及回显利用](https://www.anquanke.com/post/id/197086)

### Solr模版注入

* [Apache Solr Injection Research](https://github.com/veracode-research/solr-injection#introduction)
* [Apache Solr Velocity 模板注入漏洞深度分析](https://paper.seebug.org/1107/)
* [Apache solr Velocity模版远程命令执行漏洞分析](http://gv7.me/articles/2019/apache-solr-velocity-rce-20191031/)
* [solr-injection](https://github.com/artsploit/solr-injection#introduction)

### Apache Skywalking
* [Apache Skywalking远程代码执行漏洞分析](https://nosec.org/home/detail/4682.html)

### Spring
#### Spring-boot
* [Spring Boot Vulnerability Exploit CheckList](https://github.com/LandGrey/SpringBootVulExploit)
* [java 安全开发之 spring boot Thymeleaf 模板注入](https://paper.seebug.org/1332/)

#### Spring-cloud
* [Spring Cloud Config Server 路径穿越与任意文件读取漏洞分 CVE-2019-3799](https://xz.aliyun.com/t/4844)

#### Spring-data
* [Spring Data Redis <=2.1.0反序列化漏洞](https://xz.aliyun.com/t/2339)

## 渗透
### 边界渗透
#### 渗透记录和总结

* [hacked-Facebook](https://devco.re/blog/2020/09/12/how-I-hacked-Facebook-again-unauthenticated-RCE-on-MobileIron-MDM/) -by Orange
* [Breaking-Parser-Logic-Take-Your-Path-Normalization-Off-And-Pop-0days-Out](https://i.blackhat.com/us-18/Wed-August-8/us-18-Orange-Tsai-Breaking-Parser-Logic-Take-Your-Path-Normalization-Off-And-Pop-0days-Out-2.pdf) -Orange 打开的潘多拉魔盒
* [渗透标准](https://www.processon.com/view/583e8834e4b08e31357bb727)
* [pentest-bookmarks](https://github.com/riskawarrior/pentest-bookmarks)
* [awesome-pentest](https://github.com/enaqx/awesome-pentest) - A collection of awesome penetration testing resources.
* [Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - Awesome Pentest Cheat Sheets.
* [Pentesting checklists for various engagements](https://github.com/netbiosX/Checklists)
* [pentest-wiki](https://github.com/nixawk/pentest-wiki/)
* [Micropoor](https://github.com/Micropoor/Micro8)
* [渗透测试实战第三版](https://github.com/tom0li/collection-document/blob/master/%5B%E8%AF%91%5D%20%E6%B8%97%E9%80%8F%E6%B5%8B%E8%AF%95%E5%AE%9E%E6%88%98%E7%AC%AC%E4%B8%89%E7%89%88(%E7%BA%A2%E9%98%9F%E7%89%88).pdf)
* [Web Service 渗透测试从入门到精通](https://www.anquanke.com/post/id/85910)
* [老文一次艰难的渗透纪实](https://xz.aliyun.com/t/2122)
* [渗透Hacking Team过程](https://xz.aliyun.com/t/2146)
* [ssrf内网漫游](https://github.com/r35tart/Penetration_Testing_Case/blob/master/%E4%BD%8E%E5%8D%B1SSRF%E6%8F%90%E6%9D%83%E8%BF%9B%E5%86%85%E7%BD%91.pdf)
* [渗透记录1](https://www.freebuf.com/vuls/211842.html)
* [渗透记录2](https://www.freebuf.com/vuls/211847.html)
* [tom0li: 逻辑漏洞小结](https://tom0li.github.io/%E9%80%BB%E8%BE%91%E6%BC%8F%E6%B4%9E%E5%B0%8F%E7%BB%93/)
* [Web中间件常见漏洞总结](https://www.t00ls.net/viewthread.php?tid=51654&highlight=%E4%B8%AD%E9%97%B4%E4%BB%B6)
* [Mysql数据库渗透及漏洞利用总结simeon](https://xianzhi.aliyun.com/forum/topic/1491)
* [林林总总的Host Header Attack](https://mp.weixin.qq.com/s?__biz=MzI2NjUwNjU4OA==&mid=2247483858&idx=1&sn=2170052e99a41de3f98a6f1729dba764&chksm=ea8c59e1ddfbd0f7267095ae6da027661993b9d98b06a7d3d1f4c5e11a42cfa741ed7b21826b&scene=0#rd)
* [Redis主从利用ppt](https://github.com/tom0li/collection-document/blob/master/15-redis-post-exploitation.pdf)
* [Web攻防之暴力破解 何足道版](https://mp.weixin.qq.com/s/_zzHPAeWvSp4ckDz0_PltQ)
* [浅谈中间件漏洞与防护](https://thief.one/2017/05/25/1/)
* [NFS的攻击与防御](http://www.4hou.com/system/8069.html)
* [利用Web应用中隐藏的文件夹和文件获取敏感信息](https://xz.aliyun.com/t/3677)
* [Whitepaper: Security Cookies](https://www.netsparker.com/security-cookies-whitepaper/)
* [服务器开放debug安全内容](https://security.tencent.com/index.php/blog/msg/137)
* [Kubernetes安全入门](https://xz.aliyun.com/t/4276)
* [OOB](https://www.freebuf.com/articles/web/201013.html)
* [H2 database渗透总结](https://www.sec-in.com/article/827)

#### 信息收集

* [Red Team 视角的信息收集技术](http://blkstone.github.io/2017/04/28/pentest-recon/)
* [渗透神器系列 搜索引擎](https://thief.one/2017/05/19/1/)
* [Google Hacking Database](https://github.com/K0rz3n/GoogleHacking-Page/blob/master/Google%20Hacking%20Database.md)
* [Google Hacking](https://github.com/K0rz3n/GoogleHacking-Page/blob/master/Basic%20knowledge.md)
* [Shodan自动化利用](https://xz.aliyun.com/t/2070)
* [Shodan在渗透测试及漏洞挖掘中的一些用法](https://www.cnblogs.com/miaodaren/p/7904484.html)
* [Shodan的http.favicon.hash语法详解与使用技巧](https://www.cnblogs.com/miaodaren/p/9177379.html)
* [Shodan手册](https://b404.gitbooks.io/shodan-manual/) - 中文
* [Shodan手册](https://community.turgensec.com/shodan-pentesting-guide) dorks
* [Web应用安全测试前期情报收集方法与工具的介绍](http://www.freebuf.com/sectool/174417.html)


#### 靶场

* [vulhub](https://github.com/vulhub/vulhub)
* [vulfocus](https://github.com/fofapro/vulfocus)

#### 渗透技巧

* [BurpSuite多重代理](https://www.anquanke.com/post/id/85925)
* [Frida.Android.Practice (ssl unpinning)](https://github.com/WooyunDota/DroidDrops/blob/master/2018/Frida.Android.Practice.md)
* [IIS7以上突破无脚本执行权限限制](https://forum.90sec.org/forum.php?mod=viewthread&tid=10562&extra=page%3D2) 
* [sql二次注入和截断联合使用](https://forum.90sec.org/forum.php?mod=viewthread&tid=10377&extra=page%3D3)
* [sql二次注入和截断补充说明](https://forum.90sec.org/forum.php?mod=viewthread&tid=10383&extra=page%3D3)
* [phpMyAdmin新姿势getshell](http://www.91ri.org/17525.html) -需用ROOT权限设置参数开启
* [phpmyadmin4.8.1后台getshell](https://www.secpulse.com/archives/72817.html)
* [无效HTTP请求绕过Lighttpd重写规则](https://www.anquanke.com/post/id/148328)
* [RFI 绕过 URL 包含限制 getshell](https://paper.seebug.org/923/) win服务器 php文件包含 绕过allow_url_fopen allow_url_include = off
* [2个思路](https://xz.aliyun.com/t/6587) - 读取连接mysql客户端系统信息,上传
* [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - Payloads 大全
* [JNI技术绕过rasp防护实现jsp webshell](https://mp.weixin.qq.com/s?__biz=MzA5Mzg3NTUwNQ==&mid=2447804425&idx=1&sn=91515259ee4d8a204d40e0aee8177f58)
* [代理不当日进内网](https://mp.weixin.qq.com/s/EtUmfMxxJjYNl7nIOKkRmA)
* [浅析反向代理](https://www.anquanke.com/post/id/150436)
* [iptable介绍](https://github.com/tom0li/security_circle/blob/master/15552854825122.md)
* [结合直接系统调用和sRDI来绕过AV / EDR](https://bbs.pediy.com/thread-253564.htm)
* [FB Django Debug Stacktrace RCE](https://blog.scrt.ch/2018/08/24/remote-code-execution-on-a-facebook-server/)
* [Redis on Windows 出网利用探索](https://xz.aliyun.com/t/8153) 太帅了
* [工具| sqlmap payload修改之路](http://www.freebuf.com/column/161535.html)
* [工具| sqlmap payload修改之路（下）](https://mp.weixin.qq.com/s/ZBJ2ZvXv1n4BcvhZFPRqRA)
* [sqlmap源码分析](https://www.t00ls.net/viewthread.php?tid=41863&extra=page%3D1%26amp%3Borderby%3Drecommends%26amp%3Bfilter%3Drecommend)
* [sqlmap源码分析一](https://lorexxar.cn/2016/08/09/sqlmap-source1/)
* [sqlmap源码分析二](https://lorexxar.cn/2016/08/11/sqlmap-source2/)
* [sqlmap源码分析三](https://lorexxar.cn/2016/08/16/sqlmap-source3/)
* [sqlmap源码分析四](https://lorexxar.cn/2016/08/18/sqlmap-source4/)
* [诸神之眼nmap定制化之初识NSE](http://www.freebuf.com/column/164388.html)
* [诸神之眼nmap定制化之NSE进阶](http://www.freebuf.com/column/165252.html)
* [Burpsuite你可能不知道的技巧](http://www.freebuf.com/articles/rookie/156928.html)
* [awesome-burp-extensions](https://github.com/snoopysecurity/awesome-burp-extensions)
* [对AWVS一次简单分析](http://blog.wils0n.cn/archives/145/)
* [擦除AWVS一些标志](http://0cx.cc/replace_wvs_by_wyproxy.jspx)
* [nmap谈谈端口探测的经验与原理](http://www.freebuf.com/articles/network/146087.html)
* [我的Web应用安全模糊测试之路](https://gh0st.cn/archives/2018-07-25/1)
* [Wfuzz初上手](https://www.secpulse.com/archives/78638.html)
* [Wfuzz基本功](https://www.secpulse.com/archives/81560.html)
* [Wfuzz高阶功法1](https://gh0st.cn/archives/2018-10-28/3)
* [Wfuzz高阶功法2](https://www.secpulse.com/archives/83173.html)
* [xray高级版破解](https://lgf.im/posts/security/reverse/xray-cracker/)


### 内网渗透

之前给出的文章有些内容有错误,需要实践检查
* [AD-Attack-Defense](https://github.com/infosecn1nja/AD-Attack-Defense)
* [l3m0n:从零开始内网渗透学习](https://github.com/l3m0n/pentest_study)
* [uknowsec / Active-Directory-Pentest-Notes](https://github.com/uknowsec/Active-Directory-Pentest-Notes)
* [Intranet_Penetration_Tips](https://github.com/Ridter/Intranet_Penetration_Tips)
* [对国外某内网渗透的一次小结](https://forum.90sec.org/forum.php?mod=viewthread&tid=9264&highlight=%C4%DA%CD%F8) - 老文新手练手入门
* [针对国内一大厂的后渗透 – 持续](https://wsygoogol.github.io/2018/01/11/%E9%92%88%E5%AF%B9%E5%9B%BD%E5%86%85%E4%B8%80%E5%A4%A7%E5%8E%82%E7%9A%84%E5%90%8E%E6%B8%97%E9%80%8F-%E2%80%93-%E6%8C%81%E7%BB%AD/) - 入门实战
* [记一次横向渗透](https://www.lz1y.cn/2018/12/26/%E8%AE%B0%E4%B8%80%E6%AC%A1%E6%A8%AA%E5%90%91%E6%B8%97%E9%80%8F/)
* [内网渗透记录](https://paper.seebug.org/1144) 关键词：委派、relay、bypassAV、webdev XXE -by A-TEAM
* [Windows内网渗透入门](https://mp.weixin.qq.com/s/OGiDm3IHBP3_g0AOIHGCKA) -by 腾讯安平部

#### Exchange

* [深入 Exchange Server 在网络渗透下的利用方法](https://paper.seebug.org/775/)
* [Exchange在渗透测试中的利用](https://evi1cg.me/archives/Exchange_Hack.html)
* [Microsoft Exchange漏洞记录(撸向域控) - CVE-2018-8581](https://www.cnblogs.com/iamstudy/articles/Microsoft_Exchange_CVE-2018-8581.html)
* [利用 Exchange SSRF 漏洞和 NTLM 中继沦陷域控](https://xax007.github.io/2019-01-26-pwn-domain-admin-via-exchange-ssrf/)
* [Microsoft Exchange漏洞分析](http://www.cnblogs.com/iamstudy/articles/Microsoft_Exchange_CVE-2018-8581_2.html)
* [Microsoft Exchange 任意用户伪造漏洞（CVE-2018-8581）分析](https://paper.seebug.org/804/)
* [Exchange服务器远程代码执行漏洞复现分析](https://xz.aliyun.com/t/7299)

#### hash ticket Credential

* [花式窃取NetNTLM哈希的方法](https://paper.seebug.org/474/)
* [敞开的地狱之门：Kerberos协议的滥用](http://www.freebuf.com/articles/system/45631.html)
* [NTLM-Relay](https://mp.weixin.qq.com/s/1LpgGx3-YA5aR0Mx9iryCQ)
* [Practical guide to NTLM Relaying in 2017](https://byt3bl33d3r.github.io/practical-guide-to-ntlm-relaying-in-2017-aka-getting-a-foothold-in-under-5-minutes.html)
* [The worst of both worlds: Combining NTLM Relaying and Kerberos delegation](https://dirkjanm.io/worst-of-both-worlds-ntlm-relaying-and-kerberos-delegation/)
* [红队与理论：Credential Relay 与 EPA](https://paper.seebug.org/844/)
* [高级域渗透技术之传递哈希已死-LocalAccountTokenFilterPolicy万岁](https://www.4hou.com/technology/17668.html)
* [Windows内网协议学习NTLM篇之漏洞概述](https://www.anquanke.com/post/id/194514)
* [kerberos介绍](https://shenaniganslabs.io/media/Constructing%20Kerberos%20Attacks%20with%20Delegation%20Primitives.pdf)

#### 代理转发与端口复用

* [渗透测试技巧之内网穿透方式与思路总结](https://xz.aliyun.com/t/1623)
* [内网漫游之SOCKS代理大结局](https://paper.tuisec.win/detail/fc04d85ab57c8bf)
* [iptables端口复用](https://threathunter.org/topic/594545184ea5b2f5516e2033)
* [驱动级端口复用]()
* [Web服务中间件端口复用]()
* [win IIS端口复用](https://www.secrss.com/articles/12696)

#### 内网平台

推荐看官方手册
* [内网剑客三结义](https://paper.tuisec.win/detail/4f04eff9c0f5b82)
* [渗透利器Cobalt Strike - 第2篇 APT级的全面免杀与企业纵深防御体系的对抗](https://xz.aliyun.com/t/4191)
* [CobaltStrike修改指南]()
* [Metasploit驰骋内网直取域管首级](https://www.anquanke.com/post/id/85518)
* [一篇文章精通PowerShell Empire 2.3（上）](http://bobao.360.cn/learning/detail/4760.html)
* [一篇文章精通PowerShell Empire 2.3（下）](http://bobao.360.cn/learning/detail/4761.html)
* [Powershell攻击指南黑客后渗透之道系列——基础篇](https://www.anquanke.com/post/id/87976)
* [Powershell攻击指南黑客后渗透之道系列——进阶利用](https://www.anquanke.com/post/id/88851)
* [Powershell攻击指南黑客后渗透之道系列——实战篇](https://www.anquanke.com/post/id/89362)
* [nishang-ps](http://www.4hou.com/technology/5962.html)
* [Empire实战域渗透](http://www.4hou.com/technology/4704.html)

#### 内网技巧

* [渗透技巧——Windows系统远程桌面的多用户登录](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-Windows%E7%B3%BB%E7%BB%9F%E8%BF%9C%E7%A8%8B%E6%A1%8C%E9%9D%A2%E7%9A%84%E5%A4%9A%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95/)
* [渗透技巧之隐藏自己的工具](https://github.com/tom0li/security_circle/blob/master/51122255581554.md)
* [白名单下载恶意代码的一个技巧](https://github.com/tom0li/security_circle/blob/master/28511224554581.md)
* [白名单下载恶意代码](https://github.com/tom0li/security_circle/blob/master/51288554228124.md)
* [一条命令实现无文件兼容性强的反弹后门,收集自强大的前乌云](https://github.com/tom0li/security_circle/blob/master/15288418585142.md)
* [渗透技巧——从github下载文件的多种方法](https://xianzhi.aliyun.com/forum/topic/1649/)
* [渗透技巧——从Admin权限切换到System权限](http://www.4hou.com/technology/8814.html)
* [渗透技巧——程序的降权启动](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-%E7%A8%8B%E5%BA%8F%E7%9A%84%E9%99%8D%E6%9D%83%E5%90%AF%E5%8A%A8/)
* [强制通过VPN上网,VPN断线就断网](https://www.t00ls.net/articles-38739.html)
* [ip代理工具shadowProxy-代理池](https://mp.weixin.qq.com/s/ENjRuI5FZArtzV5H4LbJng)
* [渗透技巧——Windows系统的帐户隐藏](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-Windows%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%B8%90%E6%88%B7%E9%9A%90%E8%97%8F/)
* [渗透技巧——”隐藏”注册表的更多测试](http://www.4hou.com/penetration/9132.html)
* [渗透技巧——Windows日志的删除与绕过](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-Windows%E6%97%A5%E5%BF%97%E7%9A%84%E5%88%A0%E9%99%A4%E4%B8%8E%E7%BB%95%E8%BF%87/)
* [渗透技巧——Token窃取与利用](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-Token%E7%AA%83%E5%8F%96%E4%B8%8E%E5%88%A9%E7%94%A8/)
* [域渗透——获得域控服务器的NTDS.dit文件](https://3gstudent.github.io/3gstudent.github.io/%E5%9F%9F%E6%B8%97%E9%80%8F-%E8%8E%B7%E5%BE%97%E5%9F%9F%E6%8E%A7%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%9A%84NTDS.dit%E6%96%87%E4%BB%B6/)
* [渗透技巧——获得Windows系统的远程桌面连接历史记录](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-%E8%8E%B7%E5%BE%97Windows%E7%B3%BB%E7%BB%9F%E7%9A%84%E8%BF%9C%E7%A8%8B%E6%A1%8C%E9%9D%A2%E8%BF%9E%E6%8E%A5%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95/)
* [域渗透——利用SYSVOL还原组策略中保存的密码](https://xianzhi.aliyun.com/forum/topic/1653/)
* [Windows 日志攻防之攻击篇](https://threathunter.org/topic/593eb1bbb33ad233198afcfa)
* [针对 win 的入侵日志简单处理](https://klionsec.github.io/2017/05/19/wevtutil/)
* [从活动目录中获取域管理员权限的6种方法](http://www.4hou.com/technology/4256.html)
* [3gstudent/Pentest-and-Development-Tips](https://github.com/3gstudent/Pentest-and-Development-Tips)
* [渗透测试中常见的小TIPS总结和整理](http://avfisher.win/archives/100)
* [60字节 - 无文件渗透测试实验](https://www.n0tr00t.com/2017/03/09/penetration-test-without-file.html)
* [3389user无法添加](http://www.91ri.org/5866.html)
* [丢掉PSEXEC使用wmi来横向渗透](https://threathunter.org/topic/5940a6e59c58e020408a79ea)
* [ms14-068域提权系列总结](https://www.t00ls.net/thread-43786-1-1.html)
* [动手打造Bypass UAC自动化测试小工具，可绕过最新版Win10](http://www.freebuf.com/sectool/114592.html)
* [DoubleAgent](https://github.com/Cybellum/DoubleAgent) -后渗透对杀软进行注入
* [Extracting NTLM Hashes from keytab files](https://paper.tuisec.win/detail/ceac9f167bf27de)
* [离线导出Chrome浏览器中保存的密码](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-%E7%A6%BB%E7%BA%BF%E5%AF%BC%E5%87%BAChrome%E6%B5%8F%E8%A7%88%E5%99%A8%E4%B8%AD%E4%BF%9D%E5%AD%98%E7%9A%84%E5%AF%86%E7%A0%81/)
* [渗透技巧——利用Masterkey离线导出Chrome浏览器中保存的密码](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-%E5%88%A9%E7%94%A8Masterkey%E7%A6%BB%E7%BA%BF%E5%AF%BC%E5%87%BAChrome%E6%B5%8F%E8%A7%88%E5%99%A8%E4%B8%AD%E4%BF%9D%E5%AD%98%E7%9A%84%E5%AF%86%E7%A0%81/)
* [域渗透——Kerberoasting](https://3gstudent.github.io/3gstudent.github.io/%E5%9F%9F%E6%B8%97%E9%80%8F-Kerberoasting/)
* [老牌工具 PsExec 一个琐碎的细节](https://paper.seebug.org/503/)
* [域渗透之使用CrackMapExec拿到我们想要的东西](https://www.anquanke.com/post/id/84980)
* [Kerberos协议探索系列之委派篇](https://www.anquanke.com/post/id/173477)
* [通过RDP反向攻击mstsc](https://paper.seebug.org/1074/) 监控剪切板
* [远程提取凭证](https://beta.hackndo.com/remote-lsass-dump-passwords/)
* [重新思考凭证盗窃](https://labs.f-secure.com/blog/rethinking-credential-theft)
* [Ghost potato实际利用](https://www.lz1y.cn/2019/11/19/Ghost-potato%E5%AE%9E%E9%99%85%E5%88%A9%E7%94%A8/)
* [PowerView](http://www.freebuf.com/sectool/173366.html)
* [WMI在渗透测试中的重要性](https://www.secpulse.com/archives/72493.html)
* [BloodHound](https://github.com/BloodHoundAD/BloodHound)
* [BloodHound官方使用指南](https://www.cnblogs.com/backlion/p/10643132.html)
* [Antimalware Scan Interface Provider for Persistence](https://b4rtik.github.io/posts/antimalware-scan-interface-provider-for-persistence/) 通过AMSI Provider Persistence 
* [Task Scheduler Lateral Movement](https://riccardoancarani.github.io/2021-01-25-random-notes-on-task-scheduler-lateral-movement/) 介绍以更小的动作利用计划任务

#### 提权利用
* [linux-kernel-exploitation](https://github.com/xairy/linux-kernel-exploitation) linux kernel exploitation 必看
* [win提权辅助tool](https://github.com/GDSSecurity/Windows-Exploit-Suggester/)
* [windows-kernel-exploits Windows平台提权漏洞集合](https://github.com/SecWiki/windows-kernel-exploits)
* [linux-kernel-exploits Linux平台提权漏洞集合](https://github.com/SecWiki/linux-kernel-exploits)
* [详解Linux权限提升的攻击与防护](https://www.anquanke.com/post/id/98628) 利用入门


## Bug_Bounty

* [bug bounty writeups](https://pentester.land/list-of-bug-bounty-writeups.html) - 类似乌云漏洞库。
* [hackone-hacktivity](https://hackerone.com/hacktivity?sort_type=popular&filter=type%3Aall&querystring=&page=1) 如果看完就不用看下面的Bug_Bounty
* [awesome-bug-bounty](https://github.com/djadmin/awesome-bug-bounty) - A comprehensive curated list of Bug Bounty Programs and write-ups from the Bug Bounty hunters
* [Recon](https://www.youtube.com/watch?v=p4JgIu1mceI&feature=youtu.be)
* [bugbounty-cheatsheet](https://github.com/EdOverflow/bugbounty-cheatsheet) 
* [bug-bounty-reference](https://github.com/ngalongc/bug-bounty-reference) 
* [Web Hacking 101 中文版](https://wizardforcel.gitbooks.io/web-hacking-101/content/)
* [Webmin <=1.920 远程命令执行漏洞 -CVE-2019-15107](https://xz.aliyun.com/t/6040) - 精炼
* [Webmin CVE-2019-15642](https://twitter.com/chybeta/status/1167617571287289856)
* [从 0 开始入门 Chrome Ext 安全（一） -- 了解一个 Chrome Ext](https://paper.seebug.org/1082/)
* [从 0 开始入门 Chrome Ext 安全（二） -- 安全的 Chrome Ext](https://paper.seebug.org/1092/)
* [从 CVE-2018-8495 看 PC 端 url scheme 的安全问题](https://paper.seebug.org/719/)
* [短网址安全浅谈](https://mp.weixin.qq.com/s/4hGUZWXN6qzjMcbtZsYCSA)

## Web
### XXE
* [XXE (XML External Entity Injection) 漏洞实践](http://www.mottoin.com/101806.html)
* [如何挖掘Uber网站的XXE注入漏洞](http://www.mottoin.com/86853.html)
* [XXE被提起时我们会想到什么](http://www.mottoin.com/88085.html)
* [XXE漏洞的简单理解和测试](http://www.mottoin.com/92794.html)
* [xxe漏洞检测及代码执行过程](http://www.cnblogs.com/wfzWebSecuity/p/6681114.html)
* [浅谈XXE漏洞攻击与防御](http://thief.one/2017/06/20/1/)
* [XXE漏洞分析](http://www.4o4notfound.org/index.php/archives/29/)
* [XML实体注入漏洞攻与防](http://www.hackersb.cn/hacker/211.html)
* [XML实体注入漏洞的利用与学习](http://uknowsec.cn/posts/notes/XML%E5%AE%9E%E4%BD%93%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%E7%9A%84%E5%88%A9%E7%94%A8%E4%B8%8E%E5%AD%A6%E4%B9%A0.html)
* [XXE注入:攻击与防御 - XXE Injection: Attack and Prevent](http://le4f.net/post/xxe-injection-attack_and_prevent)
* [黑夜的猎杀-盲打XXE](https://xianzhi.aliyun.com/forum/topic/122/)
* [Hunting in the Dark - Blind XXE](https://blog.zsec.uk/blind-xxe-learning/)
* [XMLExternal Entity漏洞培训模块](https://www.sans.org/freading-room/whitepapers/application/hands-on-xml-external-entity-vulnerability-training-module-34397)
* [XXE漏洞攻防之我见](http://bobao.360.cn/learning/detail/3841.html)
* [XXE漏洞利用的一些技巧](http://www.91ri.org/17052.html)
* [神奇的Content-Type——在JSON中玩转XXE攻击](http://bobao.360.cn/learning/detail/360.html)
* [XXE-DTD Cheat Sheet](https://web-in-security.blogspot.jp/2016/03/xxe-cheat-sheet.html)
* [通过编码绕过一些cms对于xxe的检测](https://forum.90sec.org/forum.php?mod=viewthread&tid=10334&extra=page%3D3)
* [利用EXCEL进行XXE攻击](https://xz.aliyun.com/t/3741)
* [利用 EXCEL 文件进行 XXE 攻击的漏洞分析](https://www.jishuwen.com/d/2inW)
* [EXCEL依赖库](https://www.cnblogs.com/iyiyang/articles/10055824.html)
* [上传DOC文件XXE](https://www.03sec.com/2916.shtml)
* [一篇文章带你深入理解漏洞之 XXE 漏洞](https://xz.aliyun.com/t/3357)

### XSS
* [AwesomeXSS](https://github.com/s0md3v/AwesomeXSS)
* [浅谈XSS—字符编码和浏览器解析原理](https://security.yirendai.com/news/share/26)
* [深入理解XSS编码--浏览器解析原理](https://xianzhi.aliyun.com/forum/topic/1556)
* [XSS常见利用代码及原理](http://wps2015.org/2016/12/12/usually-used-xss-code/)
* [前端防御从入门到弃坑--CSP变迁](https://paper.seebug.org/423/)
* [XSS测试备忘录](http://momomoxiaoxi.com/2017/10/10/XSS/)
* [浅谈跨站脚本攻击与防御](https://thief.one/2017/05/31/1/)
* [跨站的艺术：XSS Fuzzing 的技巧](https://cloud.tencent.com/developer/article/1004753)
* [从瑞士军刀到变形金刚--XSS攻击面扩展](https://xianzhi.aliyun.com/forum/topic/96)
* [渗透测试技巧之一个XSS引发的漏洞利用与思考](https://xianzhi.aliyun.com/forum/topic/1967)
* [xss_bypass_Uppercase](http://idoge.cc/index.php/archives/27/)
* [XSSpayload交流以及研究](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=31886&highlight=xss)
* [记一次挖掘存储型XSS漏洞过程](http://www.secist.com/archives/5388.html)
* [一次XSS突破的探险](https://mp.weixin.qq.com/s/bqhaRk5Fg1xIGTjbxxZvNw)
* [香香的xss小记录（一）](https://mp.weixin.qq.com/s/S3KDp-XVzF-9pxTD2p9Cmw)
* [Black-Hole专辑](http://www.freebuf.com/author/Black-Hole?page=1) -细读
* [内网xss蠕虫](https://woj.app/2173.html)
* [攻破黑市之拿下吃鸡DNF等游戏钓鱼站群](http://www.freebuf.com/articles/web/172330.html)
* [前端安全系列（一）：如何防止XSS攻击？](https://segmentfault.com/a/1190000016551188)
* [上传Word文件形成存储型XSS路径](http://www.freebuf.com/articles/web/173250.html)
* [XSS without parentheses and semi-colons](https://portswigger.net/blog/xss-without-parentheses-and-semi-colons)

### Jsonp

* [JSONP注入解析](http://www.freebuf.com/articles/web/126347.html)
* [利用JSONP跨域获取信息](https://xianzhi.aliyun.com/forum/topic/176)
* [漫谈同源策略攻防](https://www.anquanke.com/post/id/86078)
* [浅谈跨域11](https://tom0li.github.io/%E6%B5%85%E8%B0%88%E8%B7%A8%E5%9F%9F/)
* [使用request merging bypass referer(jsonp) 检测](http://blog.neargle.com/2017/09/01/use-request-merging-to-bypass-referer-check/)

### CORS
* [JSONP与CORS漏洞挖掘](https://www.anquanke.com/post/id/97671)
* [浅谈CORS可能产生的漏洞](https://pediy.com/thread-225058.htm)
* [cors安全完全指南](https://xz.aliyun.com/t/2745#toc-4)

### CSRF

* [关于JSON CSRF的一些思考](https://mp.weixin.qq.com/s/kLRxHfzikhmV7NjpRJH6SA)
* [谈谈Json格式下的CSRF攻击](https://www.freebuf.com/articles/web/206407.html)
### SSRF

* [关于一些SSRF的技巧](https://mp.weixin.qq.com/s/3r_oBX8dfpDcEwLkAz26Ug)
* [关于SSRF漏洞挖掘思路](https://mp.weixin.qq.com/s/HPNKYL4EvTOchVM1MvIIbw)
* [SSRF in Java](https://xianzhi.aliyun.com/forum/topic/206)
* [Dns Auto Rebinding](http://www.thinkings.org/2017/06/25/dns-auto-rebinding.html)
* [通过DNS rebinding绕过同源策略攻击Transmission分析](https://www.anquanke.com/post/id/97366)
* [SSRF漏洞的挖掘经验](https://sobug.com/article/detail/11)
* [了解SSRF](https://xz.aliyun.com/t/2115)
* [SSRF&redis](https://xz.aliyun.com/t/5665)
* [gopher-attack-surfaces](https://blog.chaitin.cn/gopher-attack-surfaces/)
* [Use DNS Rebinding to Bypass SSRF in Java](https://paper.seebug.org/390)

### SQL
* [MySql注入备忘录](https://chybeta.github.io/2017/07/21/MySql%E6%B3%A8%E5%85%A5%E5%A4%87%E5%BF%98%E5%BD%95/)
* [浅析白盒审计中的字符编码及SQL注入](https://www.leavesongs.com/PENETRATION/mutibyte-sql-inject.html)
* [宽字节注入深度讲解](http://www.freebuf.com/column/165567.html)
* [基于mysql下的几种写shell方法](http://sh1yan.top/?p=190)
* [MSSQL 注入攻击与防御](https://www.anquanke.com/post/id/86011)
* [MSSQL DBA权限获取WEBSHELL的过程](http://liehu.tass.com.cn/archives/608)
* [SQLite手工注入Getshell技巧](http://liehu.tass.com.cn/archives/762)


### 文件包含
* [php文件包含漏洞](https://chybeta.github.io/2017/10/08/php%E6%96%87%E4%BB%B6%E5%8C%85%E5%90%AB%E6%BC%8F%E6%B4%9E/)

### 上传
* [上传漏洞的靶场](https://github.com/c0ny1/upload-labs)

### 任意文件读取

* [新型任意文件读取漏洞的研究](https://www.leavesongs.com/PENETRATION/arbitrary-files-read-via-static-requests.html)
* [一个任意文件读取漏洞记录](http://xdxd.love/2016/05/23/%E4%B8%80%E4%B8%AA%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/)
* [任意文件读取的常用字典](http://blkstone.github.io/2017/12/18/arbitary-file-read-exploit/)

### Web缓存欺骗
* [Web Cache欺骗攻击](https://websec.readthedocs.io/zh/latest/vuln/webcache.html)
* [Web缓存欺骗测试](https://www.freebuf.com/articles/web/161670.html)

### Web缓存投毒
* [Practical Web Cache Poisoning](https://portswigger.net/blog/practical-web-cache-poisoning)

### SSI

* [服务器端包含注入SSI分析总结](https://www.secpulse.com/archives/66934.html)

### SSTI

* [Flask Jinja2开发中遇到的的服务端注入问题研究](http://www.freebuf.com/articles/web/136118.html)
* [FlaskJinja2 开发中遇到的的服务端注入问题研究 II](http://www.freebuf.com/articles/web/136180.html)

### JS

* [关于网站强奸剪切板那点事](https://www.v2ex.com/t/426432)
* [引用外部脚本的隐患及防御](https://paper.seebug.org/527/)
* [两次前端绕过渗透小结](https://www.freebuf.com/articles/web/158508.html)
* [如何对经前端加密后的数据进行爆破](https://www.freebuf.com/articles/web/184455.html)
* [对登录中账号密码进行加密之后再传输的爆破的思路和方式](https://www.freebuf.com/articles/web/127888.html)

### DNS
* [DNS域传送漏洞学习总结](https://larry.ngrep.me/2015/09/02/DNS-zone-transfer-studying/)
* [利用Python实现DGA域名检测](http://www.freebuf.com/articles/web/145981.html)
* [DNS-Persist: 利用 DNS 协议进行远程控制通信](https://github.com/0x09AL/DNS-Persist)
* [本地DNS攻击原理与实例](https://mp.weixin.qq.com/s?__biz=MzI5MDQ2NjExOQ==&mid=2247485308&idx=1&sn=35ef757470ec4057babfb898c5ec5c19&chksm=ec1e3754db69be42b44976d6841842c7a42afc227d7dcd6c50bdbf4edcda028ae7cf90ada9a9#rd)
* [error dns response](https://ripe75.ripe.net/presentations/20-A-curious-case-of-broken-DNS-responses-RIPE-75.pdf)
* [DNS隧道检测平民解决方案](http://www.freebuf.com/articles/network/149328.html)
* [DNS泛解析是怎么被黑客玩坏的](http://www.freebuf.com/news/133873.html)
* [DNS Tunneling及相关实现](http://www.freebuf.com/sectool/112076.html)
* [DNS 域传送tools](http://www.freebuf.com/sectool/79315.html)
* [Dnslog在SQL注入中的实战](https://www.anquanke.com/post/id/98096)

## 其他
#### Git

* [Git各种错误操作撤销的方法](http://www.bugcode.cn/git_undo.html)
* [Git的tip](https://github.com/521xueweihan/git-tips)

#### 二维码

* [微信Netting-QRLJacking分析利用-扫我二维码获取你的账号权限](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=25923&highlight=%E4%BA%8C%E7%BB%B4%E7%A0%81)
* [Android平台下二维码漏洞攻击杂谈](https://wooyun.js.org/drops/Android%E5%B9%B3%E5%8F%B0%E4%B8%8B%E4%BA%8C%E7%BB%B4%E7%A0%81%E6%BC%8F%E6%B4%9E%E6%94%BB%E5%87%BB%E6%9D%82%E8%B0%88.html)
* [二维码登陆的常见缺陷剖析](https://www.t00ls.net/thread-45152-1-1.html)
* [二维码安全-淘宝例子](https://www.t00ls.net/thread-45618-1-1.html)

#### 爬虫

* [浅谈动态爬虫与去重](https://www.anquanke.com/post/id/85298)
* [浅谈动态爬虫与去重(续)](https://www.anquanke.com/post/id/95294#h2-1)
* [爬虫基础篇[Web 漏洞扫描器]](http://blog.fatezero.org/2018/03/05/web-scanner-crawler-01/)

#### 效率
之前的想起来补上

* [chrome-is-bad](https://chromeisbad.com/) chrome带慢mac原因
* [zsh 和 oh my zsh冷启动速度优化](https://blog.skk.moe/post/make-oh-my-zsh-fly/)

#### 科普
* [10大深网搜索引擎](http://www.freebuf.com/news/137844.html)
* [在百度网盘上看到上万条车主个人信息，企业、政府高官信息、各种数据](https://bbs.ichunqiu.com/article-798-1.html)
* [一道 CTF 题 get 到的新姿势](https://mp.weixin.qq.com/s?__biz=MzI5MDQ2NjExOQ==&mid=2247485297&idx=1&sn=b9d5f80bcd37d1ce0596e1a2c251d9fb&chksm=ec1e3759db69be4f84913826e4b4e5d79461061e0f61a4eb8889aa65909e2ab314391d94f87c#rd)
* [iPhone锁屏却锁不住个人信息，iOS安全性真的很高吗？](http://www.freebuf.com/vuls/153848.html)
* [弦哥从新加坡HITB黑客大会进口过来的黑魔法命令](https://github.com/tom0li/security_circle/blob/master/51115142241184.md)
* [编程的重要性之 sqlmap 源码](https://github.com/tom0li/security_circle/blob/master/88511152424522.md)
* [资讯400多个流行站点记录用户键击 或导致个人敏感信息泄露](http://bobao.360.cn/news/detail/4389.html)
* [https劫持理解](https://forum.90sec.org/forum.php?mod=viewthread&tid=10378&extra=page%3D3)
* [TCP 常见故障排查](https://ms2008.github.io/2018/06/01/tcp-troubleshooting/)
* [银行卡quickpass闪付芯片通过EVM/PBOC读取隐私信息](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=25955&ctid=48)
* [txt文本文件去重及导入数据库处理](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=25725&ctid=48)
* [解析U盘病毒传播之文件欺骗](http://www.freebuf.com/articles/terminal/155063.html)
* [深度剖析：手机指纹的马奇诺防线](https://paper.seebug.org/471/)
* [网撸黑话+技巧大全 | 岂安低调分享](https://www.secpulse.com/archives/66549.html)
* [国外14亿数据](http://www.03sec.com/3190.shtml)
* [Word文件加密之后](https://www.secpulse.com/archives/67398.html)
* [腾讯2017年度网络黑产威胁源研究报告](https://book.yunzhan365.com/odqt/yzzl/mobile/index.html)
* [洗钱工具“手机充值卡”卡号卡密灰色行业套现洗白链](http://www.freebuf.com/column/163232.html)
* [请求方法问题](http://www.freebuf.com/articles/web/172695.html)
* [Python工具分析风险数据](https://www.secpulse.com/archives/66377.html)
* [技术讨论 | 构建一个小巧的来电显示迷惑工具](http://www.freebuf.com/sectool/173730.html)
* [google.com/machine-learning/crash-course/](https://developers.google.com/machine-learning/crash-course/?hl=zh-cn)
* [远程定位追踪联网车辆以及利用思路分析](http://www.freebuf.com/vuls/178604.html)
* [智能锁具攻防系列一初探](https://future-sec.com/intelligent-lock-attack-and-defense-1.html)
* [我的世界观](https://mp.weixin.qq.com/s?__biz=MzA3NTEzMTUwNA==&mid=200044901&idx=1&sn=2a40b65874b54f7d2c80303ee6558d9b#rd)
* [偷U盘文件的神器](https://github.com/kenvix/USBCopyer)
* [内网安全检查/渗透总结](https://xz.aliyun.com/t/2354)
* [Linux内网渗透](https://thief.one/2017/08/09/2/)
* [内网渗透思路探索 之新思路的探索与验证](https://paper.tuisec.win/detail/521f97451904b16)
* [初级域渗透系列 - 01. 基本介绍&信息获取](https://paper.tuisec.win/detail/2a7446285e7d085)
* [初级域渗透系列 - 02. 常见攻击方法 - 1](https://paper.tuisec.win/detail/fc1086dabbc9002)
* [初级域渗透系列 03. 常见攻击方法](https://paper.tuisec.win/detail/cd49c17ca23cece)
* [内网渗透知识基础及流程](https://www.anquanke.com/post/id/170471)
* [RemTeam攻击技巧和安全防御](https://xz.aliyun.com/t/4602)
* [Web-Security-Note](https://github.com/Smi1eSEC/Web-Security-Note)
* [Web安全中比较好的文章](https://github.com/spoock1024/web-security) - 主要是新人入门方向
* [Fuzz自动化Bypass软WAF姿势](https://4hou.win/wordpress/?p=15613)
* [灰袍2017](https://github.com/ChrisLinn/greyhame-2017)
* [一次红队之旅](https://xz.aliyun.com/t/2389) 入门
* [非正经硬盘脱密方式](https://mp.weixin.qq.com/s/yaWCeemFXA3DkJNR22Nbig)
* [linux-suid-privilege-escalation](https://www.leavesongs.com/PENETRATION/linux-suid-privilege-escalation.html)
* [Hard_winGuide.md](https://github.com/CHEF-KOCH/HWAB/blob/master/Guide.md)
* [Enterprise-Registration-Data-of-Chinese-Mainland](https://github.com/imhuster/Enterprise-Registration-Data-of-Chinese-Mainland)
* [道哥的黑板报](https://zhuanlan.zhihu.com/taosay) - 思考很深的年轻人 真正的大牛 


旧
```
### 建设

* [Enterprise_Security_Build--Open_Source](https://bloodzer0.github.io)
* [一个人的安全部](http://www.freebuf.com/articles/security-management/126254.html)
* [没有钱的安全部之资产安全](http://www.jianshu.com/p/572431447613?from=timeline)
* [一个人的企业安全建设实践](https://xianzhi.aliyun.com/forum/topic/1568/)
* [单枪匹马搞企业安全建设](https://xianzhi.aliyun.com/forum/topic/1916)
* [“一个人”的互金企业安全建设总结](http://www.freebuf.com/articles/neopoints/158724.html)
* [低成本企业安全建设部分实践](https://xianzhi.aliyun.com/forum/topic/1996)
* [饿了么运维基础设施进化史](https://mp.weixin.qq.com/s?__biz=MzA4Nzg5Nzc5OA==&mid=2651668800&idx=1&sn=615af5f120d1298475aaf4825009cb30&chksm=8bcb82e9bcbc0bff6309d9bbaf69cfc591624206b846e00d5004a68182c934dab921b7c25794&scene=38#wechat_redirect)
* [B站日志系统的前世今生](https://mp.weixin.qq.com/s/onrBwQ0vyLJYWD_FRnNjEg)
* [爱奇艺业务安全风控体系的建设实践](https://mp.weixin.qq.com/s/2gcNY0LmgxpYT1K6uDaWtg)
* [美团外卖自动化业务运维系统建设](https://tech.meituan.com/digger_share.html)
* [携程安全自动化测试之路](http://techshow.ctrip.com/archives/2315.html)
* [企业安全中DevSecOps的一些思考](http://www.freebuf.com/articles/es/145567.html)
* [企业安全经验 应急响应的战争](http://www.freebuf.com/articles/web/155314.html)
* [企业安全项目架构实践分享](https://xianzhi.aliyun.com/forum/topic/1718)
* [以溯源为目的蜜罐系统建设](http://www.4hou.com/technology/9687.html)
* [蜜罐与内网安全从0到1（一）](https://xianzhi.aliyun.com/forum/topic/998)
* [蜜罐与内网安全从0到1（二）](https://xianzhi.aliyun.com/forum/topic/997)
* [蜜罐与内网安全从0到1（三）](https://xianzhi.aliyun.com/forum/topic/996)
* [蜜罐与内网安全从0到1（四）](https://xianzhi.aliyun.com/forum/topic/1730)
* [蜜罐与内网安全从0到1（五）](https://xianzhi.aliyun.com/forum/topic/1955)
* [企业安全建设—模块化蜜罐平台的设计思路与想法](https://xianzhi.aliyun.com/forum/topic/1885)
* [蜜罐调研与内网安全](https://xz.aliyun.com/t/7294)
* [Real-timeDetectionAD](https://github.com/sisoc-tokyo/Real-timeDetectionAD_ver2) - https://bithack.io/forum/505 - 域内蜜罐
* [HFish](https://bithack.io/forum/505) - 蜜罐框架
* [opencanary_web](https://github.com/p1r06u3/opencanary_web)
* [tpotce](https://github.com/dtag-dev-sec/tpotce/)
* [ElastAlert监控日志告警Web攻击行为](http://www.freebuf.com/articles/web/160254.html)
* [OSSIM分布式安装实践](https://www.secpulse.com/archives/67514.html)
* [企业信息安全团队建设](https://xianzhi.aliyun.com/forum/topic/1965)
* [一个人的安全部之ELK接收Paloalto日志并用钉钉告警](http://www.freebuf.com/articles/others-articles/161905.html)
* [账号安全的异常检测](https://mp.weixin.qq.com/s/qMjNURydlhzby9Qhs6RZhQ)
* [一般型网站日志接入大数据日志系统的实现](http://www.freebuf.com/column/166112.html)
* [基础设施的攻击日志 – 第1部分：日志服务器的设置](https://www.secpulse.com/archives/70001.html)
* [基础设施的攻击日志记录 – 第2部分：日志聚合](https://www.secpulse.com/archives/70016.html)
* [基础设施攻击日志记录 – 第3部分：Graylog仪表板](https://www.secpulse.com/archives/70149.html)
* [基础设施的攻击日志记录 – 第4部分：日志事件警报](https://www.secpulse.com/archives/70207.html)
* [宜信防火墙自动化运维之路](http://www.freebuf.com/articles/security-management/166895.html)
* [证书锁定](https://www.secpulse.com/archives/75212.html)
* [中通内部安全通讯实践](https://xz.aliyun.com/t/3759)
* [那些年我们堵住的洞 – OpenRASP纪实](https://anquan.baidu.com/article/855)
* [源头之战，不断升级的攻防对抗技术 —— 软件供应链攻击防御探索](https://security.tencent.com/index.php/blog/msg/140)
* [网络空间安全时代的红蓝对抗建设](https://security.tencent.com/index.php/blog/msg/139)

#### 加固

* [Linux基线加固](https://mp.weixin.qq.com/s/0nxiZw1NUoQTjxcd3zl6Zg)
* [基线检查表&安全加固规范](https://xianzhi.aliyun.com/forum/topic/1127/)
* [浅谈linux安全加固](https://mp.weixin.qq.com/s/y8np-sFzik15x09536QA5w)
* [CentOS 7 主机加固](http://www.cnblogs.com/xiaoxiaoleo/p/6678727.html)
* [APACHE 常见加固](http://cncc.bingj.com/cache.aspx?q=APACHE+%E5%B8%B8%E8%A7%81%E5%8A%A0%E5%9B%BA++0xmh&d=4797622048333774&mkt=zh-CN&setlang=zh-CN&w=WrFf2nH3PRyFtNxa6T7D-zazauskMnwg)
* [Apache服务器安全配置](http://webcache.googleusercontent.com/search?q=cache:GZSS-N0OXY8J:foreversong.cn/archives/789+&cd=1&hl=zh-CN&ct=clnk&gl=sg&lr=lang_en%7Clang_zh-CN)
* [GNU/Linux安全基线与加固](http://cb.drops.wiki/drops/tips-2621.html)
* [windows服务器安全配置策略](https://www.yesck.com/post/528/)
* [15步打造一个安全的Linux服务器](https://www.freebuf.com/articles/system/121540.html)
* [Tomcat7 加固清单](https://threathunter.org/topic/59911277ec721b1f1966e7eb)
* [Tomcat安全设置和版本屏蔽](http://www.freebuf.com/column/163296.html)
* [IIS服务器安全配置](http://foreversong.cn/archives/803)
* [企业常见服务漏洞检测&修复整理](http://www.mottoin.com/92742.html)
* [运维安全概述](http://cb.drops.wiki/drops/%E8%BF%90%E7%BB%B4%E5%AE%89%E5%85%A8-8169.html)
* [浅谈Linux系统MySQL安全配置](https://mp.weixin.qq.com/s/0KrfdrjbcRdvSTKxoNHOcA)
* [Hardening Ubuntu](https://github.com/konstruktoid/hardening)
* [Tomcat Config Security](https://joychou.org/operations/tomcat-config-security.html)
* [安全运维中基线检查的自动化之ansible工具巧用](https://bbs.ichunqiu.com/thread-46896-1-1.html?from=snew)
* [https://github.com/netxfly/sec_check](https://github.com/netxfly/sec_check)

#### 响应 溯源

* [awesome-incident-response](https://github.com/meirwah/awesome-incident-response) - A curated list of tools and resources for security incident response, aimed to help security analysts and DFIR teams.
* [黑客入侵应急分析手工排查](https://xianzhi.aliyun.com/forum/topic/1140/)
* [应急tools](https://github.com/meirwah/awesome-incident-response/blob/master/README_ch.md)
* [Linux服务器应急事件溯源报告](http://wooyun.jozxing.cc/static/drops/tips-12972.html)
* [应急响应小记链接已挂](https://threathunter.org/topic/5943a99c1e3732874e23f996)
* [大型互联网企业入侵检测实战总结](https://xz.aliyun.com/t/1626/)
* [Linux应急响应姿势浅谈](http://bobao.360.cn/learning/detail/4481.html)
* [安全应急姿势](http://rinige.com/index.php/archives/824/)
* [Web日志安全分析浅谈](https://xianzhi.aliyun.com/forum/topic/1121/)
* [域名劫持事件发生后的应急响应策略](http://www.freebuf.com/articles/security-management/118425.html)
* [我的日志分析之道：简单的Web日志分析脚本 ](http://www.freebuf.com/sectool/126698.html)
* [攻击检测和防范方法之日志分析](http://www.freebuf.com/articles/web/109001.html)
* [Tomcat日志如何记录POST数据](https://secvul.com/topics/1087.html)
* [邮件钓鱼攻击与溯源](https://4hou.win/wordpress/?p=28874)
* [应急响应实战笔记](https://github.com/Bypass007/Emergency-Response-Notes) - Bypass007
* [某云用户网站入侵应急响应](http://www.freebuf.com/articles/network/134372.html)
* [IP 定位逆向追踪溯源访客真实身份调查取证](https://lcx.cc/post/4595/)
* [域名背后的真相，一个黑产团伙的沦陷](https://www.freebuf.com/articles/terminal/127228.html)
* [看我如何从54G日志中溯源web应用攻击路径](https://paper.tuisec.win/detail/a56f79f0d7126f5)

#### 威胁情报
* [威胁情报简介及市场浅析](http://www.freebuf.com/column/136763.html)
* [ClickHouse与威胁日志分析](http://www.freebuf.com/column/164671.html)

#### 综合

* [企业安全实践(基础建设)之部分资产收集](http://www.freebuf.com/column/157085.html)
* [企业安全实践(基础建设)之IP资产监控](http://www.freebuf.com/column/157496.html)
* [企业安全实践(基础建设)之主动分布式WEB资产扫描](http://www.freebuf.com/column/157546.html)
* [企业安全实践(基础建设)之被动扫描自动化(上)](http://www.freebuf.com/column/157635.html)
* [企业安全实践(基础建设)之被动扫描自动化(中)](http://www.freebuf.com/column/157947.html)
* [企业安全实践(基础建设)之被动扫描自动化(下)](http://www.freebuf.com/column/157996.html)
* [企业安全实践(基础建设)之WEB安全检查](http://www.freebuf.com/column/158358.html)
* [企业安全实践(基础建设)之HIDS（上）](http://www.freebuf.com/column/158449.html)
* [企业安全实践(基础建设)之HIDS（下）](http://www.freebuf.com/column/158677.html)
* [0xA1: 新官上任三把火](https://zhuanlan.zhihu.com/p/26485293)
* [0xA2 应急响应、防御模型与SDL](https://zhuanlan.zhihu.com/p/26542790)
* [0xA3 安全域划分和系统基本加固](https://zhuanlan.zhihu.com/p/26603906)
* [0xB1 微观安全——一台服务器做安全](https://zhuanlan.zhihu.com/p/27363168)
* [0xB2 事件应急——企业内网安全监控概览](https://zhuanlan.zhihu.com/p/29816766)
* [0xB3 再谈应急响应Pt.1 unix主机应急响应
  elknot](https://zhuanlan.zhihu.com/p/29958172)
* [0xB4 企业安全建设中评估业务潜在风险的思路](https://zhuanlan.zhihu.com/p/31263844?group_id=916355317818970112)
* [企业安全体系建设之路之系统安全篇](https://xianzhi.aliyun.com/forum/topic/1949)
* [企业安全体系建设之路之网络安全篇](https://xianzhi.aliyun.com/forum/topic/1950)
* [企业安全体系建设之路之产品安全篇](https://xianzhi.aliyun.com/forum/topic/1951)
* [SOC异闻录](https://www.anquanke.com/post/id/95231)
* [开源软件创建SOC的一份清单](http://www.freebuf.com/articles/network/169632.html)
* [开源SOC的设计与实践](http://www.freebuf.com/articles/network/173282.html)
* [F5 BIG-IP Security Cheatsheet](https://github.com/dnkolegov/bigipsecurity)

#### 原bug bounty
* [SRC漏洞挖掘小见解](http://www.mottoin.com/95043.html)
* [面向SRC的漏洞挖掘总结](http://blkstone.github.io/2017/05/28/finding-src-vuls/)
* [漏洞挖掘经验分享Saviour](https://xianzhi.aliyun.com/forum/topic/1214/)
* [我的SRC之旅](https://mp.weixin.qq.com/s/2ORHnywrxXPexviUYk7Ccg)
* [浅析通过"监控"来辅助进行漏洞挖掘](https://bbs.ichunqiu.com/thread-28591-1-1.html)
* [威胁情报-生存在SRC平台中的刷钱秘籍](https://bbs.ichunqiu.com/article-921-1.html)
* [威胁情报](https://mp.weixin.qq.com/s/v2MRx7qs70lpnW9n-mJ7_Q)
* [YSRC众测之我的漏洞挖掘姿势](https://bbs.ichunqiu.com/article-655-1.html)
* [SRC的漏洞分析](https://bbs.ichunqiu.com/thread-19745-1-1.html)
* [众测备忘手册](https://mp.weixin.qq.com/s/4XPG37_lTZDzf60o3W_onA)
* [挖洞技巧：如何绕过URL限制](https://www.secpulse.com/archives/67064.html)
* [挖洞技巧：APP手势密码绕过思路总结](https://www.secpulse.com/archives/67070.html)
* [挖洞技巧：支付漏洞之总结](https://www.secpulse.com/archives/67080.html)
* [挖洞技巧：绕过短信&邮箱轰炸限制以及后续](http://mp.weixin.qq.com/s/5OSLC2GOeYere9_lT2RwHw)
* [挖洞技巧：信息泄露之总结](https://www.secpulse.com/archives/67123.html)
* [阿里云oss key利用](https://www.t00ls.net/viewthread.php?tid=52875&highlight=oss)
* [任意文件下载引发的思考](https://www.secpulse.com/archives/68522.html)
* [任意文件Getshell](https://xz.aliyun.com/t/6958)
* [通用性业务逻辑组合拳劫持你的权限](https://www.anquanke.com/post/id/106961)
* [组合漏洞导致的账号劫持](https://xz.aliyun.com/t/3514)
* [我的通行你的证](https://lvwei.me/passport.html#toc_0)
* [那些年我们刷过的SRC之企业邮箱暴破](https://www.secquan.org/Discuss/262)
* [各大SRC中的CSRF技巧](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=28448&highlight=src)
* [一些逻辑](https://secvul.com/topics/924.html)
* [一个登陆框引起的血案](http://www.freebuf.com/articles/web/174408.html)
* [OAuth回调参数漏洞案例解析](https://03i0.com/2018/04/01/OAuth%E5%9B%9E%E8%B0%83%E5%8F%82%E6%95%B0%E6%BC%8F%E6%B4%9E%E6%A1%88%E4%BE%8B%E8%A7%A3%E6%9E%90/)
* [子域名接管指南](https://www.secpulse.com/archives/95304.html)
* [Subdomain Takeover](https://www.secpulse.com/archives/94973.html)
* [Subdomain Takeover/can-i-take-over-xyz](https://github.com/EdOverflow/can-i-take-over-xyz)
* [Subdomain-takeover](https://echocipher.github.io/2019/08/14/Subdomain-takeover/)
* [过期链接劫持的利用方法探讨](http://www.freebuf.com/articles/web/151836.html)
* [国外赏金之路](https://blog.securitybreached.org/2017/11/25/guide-to-basic-recon-for-bugbounty/) - 老司机赏金见解,历史赏金文章 list
* [记一次失败的0元单的挖掘历程与一处成功的XSS案例](https://bbs.ichunqiu.com/article-636-1.html)
* [看我如何发现谷歌漏洞跟踪管理平台漏洞获得$15600赏金](http://www.freebuf.com/articles/web/152893.html)
* [看我如何利用简单的配置错误“渗透”BBC新闻网](http://www.freebuf.com/news/155558.html)
* [分享一个近期遇到的逻辑漏洞案例](http://www.freebuf.com/vuls/151196.html)
* [我是如何挖掘热门“约P软件”漏洞的](http://www.freebuf.com/articles/web/157391.html)
* [新手上路 | 德国电信网站从LFI到命令执行漏洞](http://www.freebuf.com/articles/web/156950.html)
* [Taking over Facebook accounts using Free Basics partner portal](https://www.josipfranjkovic.com/blog/facebook-partners-portal-account-takeover)
* [The bug bounty program that changed my life](http://10degres.net/the-bugbounty-program-that-changed-my-life/)
* [挖洞经验 | 看我如何免费获取价值€120的会员资格](http://www.freebuf.com/articles/web/172438.html)
* [Scrutiny on the bug bounty](https://xz.aliyun.com/t/3935)
* [1hack0/Facebook-Bug-Bounty-Write-ups](https://github.com/1hack0/Facebook-Bug-Bounty-Write-ups)

* [Java反序列化漏洞-金蛇剑之hibernate(上)](https://xianzhi.aliyun.com/forum/topic/2030)
* [Java反序列化漏洞-金蛇剑之hibernate(下)](https://xianzhi.aliyun.com/forum/topic/2031)
* [Java反序列化漏洞-玄铁重剑之CommonsCollection(上)](https://xianzhi.aliyun.com/forum/topic/2028)
* [Java反序列化漏洞-玄铁重剑之CommonsCollection(下)](https://xianzhi.aliyun.com/forum/topic/2029)
* [Java反序列化漏洞从入门到深入](https://xianzhi.aliyun.com/forum/topic/2041)
* [Java反序列化备忘录](https://xianzhi.aliyun.com/forum/topic/2042)
* [Java反序列化漏洞之殇](https://xianzhi.aliyun.com/forum/topic/2043)
* [Java反序列化漏洞学习实践一：从Serializbale接口开始，先弹个计算器](http://www.polaris-lab.com/index.php/archives/447/)
* [Java反序列化漏洞学习实践二：Java的反射机制（Java Reflection）](http://www.polaris-lab.com/index.php/archives/450/)
* [Java反序列化漏洞学习实践三：理解Java的动态代理机制](http://www.polaris-lab.com/index.php/archives/453/)
```

## Contribute
We welcome everyone to contribute,you can open an issue for this if you have some new idea about this project or you have found some quality safety articles,and then I will add your name to Acknowledgments.


## Acknowledgments
* @[tom0li](https://github.com/tom0li)
* @[neargle](https://github.com/neargle)
* @[r4v3zn](https://github.com/0nise)

## Star
感谢Star

[![Stargazers over time](https://starchart.cc/tom0li/collection-document.svg)](https://starchart.cc/tom0li/collection-document)
