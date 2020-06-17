# Project Description
---
### Collection of quality safety articles(To be rebuilt)
> #### [collection-document awesome](https://github.com/tom0li/collection-document/)  
```
Some are inconvenient to release.  
Some forget update,can see me star.  
以前的链接中大多不是优质的。
因精力有限，缓慢更新。
Author: [tom0li]  
Blog: https://tom0li.github.io
```
---

Table of Contents
=================

   * [Github-list](#github-list)
   * [预警&amp;研究](#预警研究)
      * [ImageMagick](#imagemagick)
      * [VPN](#VPN)
   * [代码审计-JAVA](#代码审计-JAVA)
      * [反序列化-其他](#反序列化-其他)
      * [RMI](#RMI)
      * [Shiro](#Shiro)
      * [Fastjson](#Fastjson)
      * [模版注入](#模版注入)
   * [安全部](#安全部)
      * [建设](#建设)
      * [加固](#加固)
      * [响应 溯源](#响应-溯源)
      * [威胁情报](#威胁情报)
      * [综合](#综合)
   * [Bug_Bounty](#Bug_Bounty)
      * [总结](#总结)
      * [信息收集](#信息收集)
   * [渗透](#渗透)
      * [靶场](#靶场)
      * [技巧](#技巧)
   * [内网](#内网)
      * [Exchange](#Exchange)
      * [hash ticket Credential](#hash-ticket-Credential)
      * [代理转发](#代理转发)
      * [内网平台](#内网平台)
      * [内网收集](#内网收集)
      * [内网技巧](#内网技巧)
      * [提权](#提权)
   * [APT](#apt)
      * [钓鱼](#钓鱼)
         * [邮件伪造](#邮件伪造)
      * [远控](#远控)
   * [Web](#web)
      * [XXE](#xxe)
      * [XSS](#XSS)
      * [Jsonp](#Jsonp)
      * [CORS](#cors)
      * [tools](#tools)
      * [CSRF](#CSRF)
      * [SSRF](#SSRF)
      * [SQL](#SQL)
      * [文件包含](#文件包含)
      * [上传](#上传)
      * [任意文件读取](#任意文件读取)
      * [Web缓存欺骗](#Web缓存欺骗)
      * [Web缓存投毒](#Web缓存投毒)
      * [SSI](#SSI)
      * [SSTI](#SSTI)
      * [JS](#js)
      * [DNS](#dns)

   * [FUZZ](#fuzz)
   * [WAF](#waf)
   * [IDS](#ids)
   * [其他](#其他)
      * [Git](#git)
      * [特别的wx号](#特别的wx号)
      * [二维码](#二维码)
      * [爬虫](#爬虫)
      * [科普](#科普)
   * [Acknowledgments](#acknowledgments)

## Github-list
----
* [awesome-web-security](https://github.com/qazbnm456/awesome-web-security) - list sec 集合
* [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) - 万星 list 
* [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis)
* [Android Security](https://github.com/ashishb/android-security-awesome) - Collection of Android security related resources.
* [Security](https://github.com/sbilly/awesome-security) - Software, libraries, documents, and other resources.
* [An Information Security Reference That Doesn't Suck](https://github.com/rmusser01/Infosec_Reference)
* [Security Talks](https://github.com/PaulSec/awesome-sec-talks) - Curated list of security conferences.
* [OSINT](https://github.com/jivoi/awesome-osint) - Awesome OSINT list containing great resources.
* [Web-Security-Learning](https://github.com/CHYbeta/Web-Security-Learning) - by CHYbeta
* [Software-Security-Learning](https://github.com/CHYbeta/Software-Security-Learning) - by CHYbeta
* [MiscSecNotes](https://github.com/JnuSimba/MiscSecNotes) - by JnuSimba notes 
* [AndroidSecNotes](https://github.com/JnuSimba/AndroidSecNotes) - notes
* [LinuxSecNotes](https://github.com/JnuSimba/LinuxSecNotes) - notes
* [Security Knowledge Structure](https://github.com/JoyChou93/sks)
* [information security Tools Box](https://github.com/tengzhangchao/Sec-Box) - by Nmask
* [resource collection of python security and code review](https://github.com/bit4woo/python_sec)
* [www.polaris-lab.com_Paper](https://github.com/re4lity/SecPaper)
* [灰袍2017](https://github.com/ChrisLinn/greyhame-2017)
* [The toolbox of open source scanners](https://github.com/We5ter/Scanners-Box) - The toolbox of open source scanners
* [blackhat-arsenal-tools](https://github.com/toolswatch/blackhat-arsenal-tools) - Official Black Hat Arsenal Security Tools Repository
* [物联网安全百科](https://github.com/yaseng/iot-security-wiki) -by  伏宸安全实验室
* [Web-Security-Note](https://github.com/Smi1eSEC/Web-Security-Note)
* [2018-2020青年安全圈-活跃技术博主/博客](https://github.com/404notf0und/Security-Data-Analysis-and-Visualization) - by 404notf0und
* [awesome-iot-hacks](https://github.com/nebgnahz/awesome-iot-hacks)
* [awesome-awesome](https://github.com/emijrp/awesome-awesome)
* [Curated list of awesome lists](https://github.com/sindresorhus/awesome)
* [Awesome Awesomness](https://github.com/bayandin/awesome-awesomeness) - The List of the Lists.
* [PENTESTING-BIBLE](https://github.com/blaCCkHatHacEEkr/PENTESTING-BIBLE) - 安全相关的内容
* [Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing)
* [Donot师傅收集的入侵检测相关的内容](https://github.com/donot-wong/SecAcademic)
* [Pentest_Interview](https://github.com/Leezj9671/Pentest_Interview)
* [Coding Interview University](https://github.com/jwasham/coding-interview-university)
* [tech-interview-handbook](https://github.com/yangshun/tech-interview-handbook) - good
* [面试必备基础知识](https://github.com/CyC2018/CS-Notes)
* [CS基础](https://github.com/selfboot/CS_Offer/)
* [算法/深度学习/NLP面试笔记](https://github.com/imhuay/Algorithm_Interview_Notes-Chinese)
* [reverse-interview](https://github.com/yifeikong/reverse-interview-zh) - 技术面试最后反问面试官的话

----
开发

* [互联网 Java 工程师进阶知识完全扫盲](https://github.com/doocs/advanced-java)
* [Java学习+面试指南 一份涵盖大部分Java程序员所需要掌握的核心知识](https://github.com/Snailclimb/JavaGuide)
* [Python Cheat Sheet ](https://github.com/crazyguitar/pysheeet)
* [A collection of full-stack resources for programmers.](https://github.com/charlax/professional-programming)
* [web, 前端, javascript, nodejs, electron, babel, webpack, rollup, react, vue ...](https://github.com/senntyou/blogs)
* [关于Python的面试题](https://github.com/taizilongxu/interview_python)
* [数据结构和算法必知必会的50个代码实现](https://github.com/wangzheng0822/algo)
* [interview_internal_reference](https://github.com/0voice/interview_internal_reference) 
* [Python-100-Days](https://github.com/jackfrued/Python-100-Days)
* [python3-source-code-analysis](https://github.com/flaggo/python3-source-code-analysis)

----
其它

* [信息安全从业者书单推荐](https://github.com/riusksk/secbook)
* [专为程序员编写的英语学习指南 v1.2](https://github.com/yujiangshui/A-Programmers-Guide-to-English)
* [中国程序员容易发音错误的单词](https://github.com/shimohq/chinese-programmer-wrong-pronunciation)
* [租房要点，适用于北上广深杭](https://github.com/soulteary/tenant-point)
* [SecLists](https://github.com/danielmiessler/SecLists) - Collection of multiple types of lists used during security assessments.
* [A collection of web attack payloads](https://github.com/foospidy/payloads)
* [安全相关思维导图整理收集](https://github.com/phith0n/Mind-Map) - by p牛 
* [安全思维导图集合](https://github.com/SecWiki/sec-chart) -by SecWiki
* [Android-Reports-and-Resources](https://github.com/B3nac/Android-Reports-and-Resources) - HackerOne Reports
* [AppSec](https://github.com/paragonie/awesome-appsec) - Resources for learning about application security.
* [Honeypots](https://github.com/paralax/awesome-honeypots) - Honeypots, tools, components, and more.
* [Infosec](https://github.com/onlurking/awesome-infosec) - Information security resources for pentesting, forensics, and more.
* [YARA](https://github.com/InQuest/awesome-yara) - YARA rules, tools, and people.
* [macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
* [awesome-security-weixin-official-accounts](https://github.com/DropsOfZut/awesome-security-weixin-official-accounts) 
* [Web安全中比较好的文章](https://github.com/spoock1024/web-security)
* [996.Leave](https://github.com/623637646/996.Leave)
* [对开发人员有用的定律、理论、原则和模式](https://github.com/nusr/hacker-laws-zh)
* [awesome-macOS](https://github.com/iCHAIT/awesome-macOS) - mac软件
* [awesome-mac](https://github.com/jaywcjlove/awesome-mac/blob/master/README-zh.md#%E5%BC%80%E5%8F%91%E8%80%85%E5%B7%A5%E5%85%B7) - mac软件
* [jaywcjlove/handbook](https://github.com/jaywcjlove/handbook) - 杂
* [保护隐私](https://github.com/No-Github/Digital-Privacy)
* [ruanyf](https://github.com/ruanyf/weekly) - 科技爱好者周刊

## 预警&研究
* [Top 10 Web Hacking Techniques of 2017](https://portswigger.net/blog/top-10-web-hacking-techniques-of-2017) - 一个nb的网站
* [Top-10-web-hacking-techniques-of-2018](https://portswigger.net/research/top-10-web-hacking-techniques-of-2018)
* [PPT大全](http://www.vipread.com/)
* [从 CVE-2018-8495 看 PC 端 url scheme 的安全问题](https://paper.seebug.org/719/)
* [us-19-Tsai-Infiltrating-Corporate-Intranet-Like-NSA](https://i.blackhat.com/USA-19/Wednesday/us-19-Tsai-Infiltrating-Corporate-Intranet-Like-NSA.pdf) -orange
* [bypass沙箱](https://yuange1975.blogspot.com/2019/08/bypass.html) -yuange
* [Webmin <=1.920 远程命令执行漏洞 -CVE-2019-15107](https://xz.aliyun.com/t/6040) - 精炼
* [Webmin CVE-2019-15642](https://twitter.com/chybeta/status/1167617571287289856)
* [浅谈RASP](https://lucifaer.com/2019/09/25/%E6%B5%85%E8%B0%88RASP/)
* [从 0 开始入门 Chrome Ext 安全（一） -- 了解一个 Chrome Ext](https://paper.seebug.org/1082/)
* [从 0 开始入门 Chrome Ext 安全（二） -- 安全的 Chrome Ext](https://paper.seebug.org/1092/)
* [编译原理在安全领域的应用](https://mp.weixin.qq.com/s/6SqdcbyABfBxSaNfDlFKog)
* [短网址安全浅谈](https://mp.weixin.qq.com/s/4hGUZWXN6qzjMcbtZsYCSA)
* [服务器开放debug安全内容](https://security.tencent.com/index.php/blog/msg/137)

### ImageMagick
---
* [ImageMagick漏洞凑热闹手札](https://d0n9.github.io/2018/08/22/ImageMagick%20%E6%BC%8F%E6%B4%9E%E5%87%91%E7%83%AD%E9%97%B9%E6%89%8B%E6%9C%AD/#)
* [如何使用Fuzzing挖掘ImageMagick的漏洞](https://github.com/lcatro/Fuzzing-ImageMagick/blob/master/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8Fuzzing%E6%8C%96%E6%8E%98ImageMagick%E7%9A%84%E6%BC%8F%E6%B4%9E.md)
* [ImageMagick-CVE-2016-3714 命令执行分析](http://www.zerokeeper.com/vul-analysis/ImageMagick-CVE-2016-3714.html)
* [Imagemagick 邂逅 getimagesize 的那点事儿](https://paper.seebug.org/969/)

### VPN
---
#### Sangfor
* [深信服后台RCE](https://www.cnblogs.com/potatsoSec/p/12326356.html)
* [深信服前台RCE由于没公开不附链接]()

#### Pulse
* [Pulse-secure-rce](https://blog.orange.tw/2019/09/attacking-ssl-vpn-part-3-golden-pulse-secure-rce-chain.html)

#### Palo
* [Attacking SSL VPN - Part 1: PreAuth RCE on Palo Alto GlobalProtect, with Uber as Case Study!](https://blog.orange.tw/2019/07/attacking-ssl-vpn-part-1-preauth-rce-on-palo-alto.html)

#### Fortigate
* [Attacking SSL VPN - Part 2: Breaking the Fortigate SSL VPN](https://blog.orange.tw/2019/08/attacking-ssl-vpn-part-2-breaking-the-fortigate-ssl-vpn.html)
 
#### Citrix Gateway/ADC
* [Citrix Gateway/ADC 远程代码执行漏洞分析](https://blog.riskivy.com/citrix-gateway-adc-%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/)

## 代码审计-JAVA
---
* [javasec.org](https://javasec.org/) -by 园长
* [JAVA代码审计的一些Tips(附脚本)](https://xianzhi.aliyun.com/forum/topic/1633)
* [敏信Java代码审计-层层推进](https://xianzhi.aliyun.com/forum/topic/2074)
* [Java漏洞代码](https://github.com/JoyChou93/java-sec-code)
* [代码审计知识星球精选](https://tricking.io)
* [连续使用过滤函数造成的安全问题总结](https://forum.90sec.org/thread-10917-1-1.html)

### 反序列化-其他
---
* [Java序列化和反序列化](https://xianzhi.aliyun.com/forum/topic/1825)
* [Java反序列化漏洞分析](https://xianzhi.aliyun.com/forum/topic/136)
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

### RMI
---
* [attacking-java-rmi-services-after-jep-290](https://mogwailabs.de/blog/2019/03/attacking-java-rmi-services-after-jep-290/)

### Shiro
---
* [apache-shiro-java反序列化漏洞分析](https://blog.knownsec.com/2016/08/apache-shiro-java/)
* [从一次开发漏洞看shiro的正确使用](https://xz.aliyun.com/t/5287)
* [Shiro RememberMe 1.2.4 反序列化导致的命令执行漏洞](https://paper.seebug.org/shiro-rememberme-1-2-4/)
* [强网杯“彩蛋”——Shiro 1.2.4(SHIRO-550)漏洞之发散性思考](https://blog.zsxsoft.com/post/35)
* [Shiro 721 Padding Oracle攻击漏洞分析](https://www.anquanke.com/post/id/193165#h2-14)
* [Shiro权限绕过漏洞分析](https://www.freebuf.com/vuls/231909.html)

### Fastjson
---
* [fastjson反序列化利用](https://lazydog.me/post/fastjson-JdbcRowSetImpl-rce-exploit.html)
* [FastJson =< 1.2.47 反序列化漏洞浅析](https://bithack.io/forum/393)
* [FASTJSON反序列化之基于JNDI利用方式](https://manning23.github.io/2018/03/01/Fastjson%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96jndi%E5%88%A9%E7%94%A8%E8%BF%87%E7%A8%8B%E5%88%86%E6%9E%90/)
* [Fastjson反序列化漏洞调试分析](https://www.angelwhu.com/blog/?p=552)
* [FastJson 反序列化学习](http://www.lmxspace.com/2019/06/29/FastJson-%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E5%AD%A6%E4%B9%A0/)
* [浅谈Fastjson RCE漏洞的绕过史](https://www.freebuf.com/vuls/208339.html)
* [通过dnslog探测fastjson的几种方法](http://gv7.me/articles/2020/several-ways-to-detect-fastjson-through-dnslog/)

### 模版注入
---
* [Apache Solr Injection Research](https://github.com/veracode-research/solr-injection#introduction)
* [Apache Solr Velocity 模板注入漏洞深度分析](https://paper.seebug.org/1107/)
* [Apache solr Velocity模版远程命令执行漏洞分析](http://gv7.me/articles/2019/apache-solr-velocity-rce-20191031/)

## 安全部

#### 建设

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

## Bug_Bounty

* [bug bounty writeups](https://pentester.land/list-of-bug-bounty-writeups.html) - 类似乌云漏洞库。
* [awesome-bug-bounty](https://github.com/djadmin/awesome-bug-bounty) - A comprehensive curated list of Bug Bounty Programs and write-ups from the Bug Bounty hunters
* [bugbounty-cheatsheet](https://github.com/EdOverflow/bugbounty-cheatsheet) 
* [bug-bounty-reference](https://github.com/ngalongc/bug-bounty-reference)
* [Web Hacking 101 中文版](https://wizardforcel.gitbooks.io/web-hacking-101/content/)
* [hackone-hacktivity](https://hackerone.com/hacktivity?sort_type=popular&filter=type%3Aall&querystring=&page=1)
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

### 总结
* [tom0li: 逻辑漏洞小结](https://tom0li.github.io/%E9%80%BB%E8%BE%91%E6%BC%8F%E6%B4%9E%E5%B0%8F%E7%BB%93/)
* [Web中间件常见漏洞总结](https://www.t00ls.net/viewthread.php?tid=51654&highlight=%E4%B8%AD%E9%97%B4%E4%BB%B6)
* [Tomcat安全测试概要](https://blog.formsec.cn/2018/02/23/%E4%B8%AD%E9%97%B4%E4%BB%B6%E5%AE%89%E5%85%A8-TOMCAT%E5%AE%89%E5%85%A8%E6%B5%8B%E8%AF%95%E6%A6%82%E8%A6%81/)
* [那些年让我们心惊胆战的IIS漏洞](https://www.secpulse.com/archives/82410.html)
* [Mysql数据库渗透及漏洞利用总结simeon](https://xianzhi.aliyun.com/forum/topic/1491)
* [攻击大数据应用：ZooKeeper](http://www.polaris-lab.com/index.php/archives/41/)
* [林林总总的Host Header Attack](https://mp.weixin.qq.com/s?__biz=MzI2NjUwNjU4OA==&mid=2247483858&idx=1&sn=2170052e99a41de3f98a6f1729dba764&chksm=ea8c59e1ddfbd0f7267095ae6da027661993b9d98b06a7d3d1f4c5e11a42cfa741ed7b21826b&scene=0#rd)
* [JBoss高危漏洞分析](https://mp.weixin.qq.com/s/Kjw_abH6a-ifXdQmbc5Pug)
* [Redis未授权访问漏洞的重现与利用](http://www.freebuf.com/vuls/162035.html)
* [Redis安全总结](https://bl4ck.in/categories/2015/11/17/Redis%E5%AE%89%E5%85%A8%E6%80%BB%E7%BB%93.html)
* [Redis在Windows环境下Getshell](https://uknowsec.cn/posts/notes/Redis%E5%9C%A8Windows%E7%8E%AF%E5%A2%83%E4%B8%8BGetshell.html)
* [Redis未授权访问在windows下的利用](https://www.anquanke.com/post/id/170360#h3-4)
* [常见Web源码泄露总结](http://www.mottoin.com/95749.html)
* [未授权访问漏洞总结](https://www.secpulse.com/archives/61101.html)
* [端口渗透总结](http://docs.ioin.in/writeup/blog.heysec.org/_archives_577/index.html)
* [Web攻防之暴力破解 何足道版](https://mp.weixin.qq.com/s/_zzHPAeWvSp4ckDz0_PltQ)
* [登录加密算法破解秘籍](http://liehu.tass.com.cn/archives/1016) 
* [JAVASCRIPT安全性问题总结](https://www.t00ls.net/articles-42182.html)
* [浅谈中间件漏洞与防护](https://thief.one/2017/05/25/1/)
* [NFS的攻击与防御](http://www.4hou.com/system/8069.html)
* [利用Web应用中隐藏的文件夹和文件获取敏感信息](https://xz.aliyun.com/t/3677)
* [ActiveMQ任意文件写入漏洞（CVE-2016-3088）学习](http://www.ko0zh1.cc/2017/07/23/ActiveMQ%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E5%86%99%E5%85%A5%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2016-3088%EF%BC%89%E5%AD%A6%E4%B9%A0/)
* [Whitepaper: Security Cookies](https://www.netsparker.com/security-cookies-whitepaper/)
* [Kubernetes安全入门](https://xz.aliyun.com/t/4276)
* [OOB](https://www.freebuf.com/articles/web/201013.html)
* [solr-injection](https://github.com/artsploit/solr-injection#introduction)

### 信息收集

* [乙方渗透测试之信息收集](http://www.cnnetarmy.com/%E4%B9%99%E6%96%B9%E6%B8%97%E9%80%8F%E6%B5%8B%E8%AF%95%E4%B9%8B%E4%BF%A1%E6%81%AF%E6%94%B6%E9%9B%86/)
* [tom0li:浅谈信息收集](https://tom0li.github.io/%E6%BC%AB%E8%B0%88%E5%89%8D%E6%9C%9F%E4%BF%A1%E6%81%AF%E6%94%B6%E9%9B%86/)
* [透过cdn找目标真实ip](https://klionsec.github.io/2014/12/13/bypasscdn/)
* [浅谈Web渗透测试中的信息收集](http://www.freebuf.com/articles/web/142767.html)
* [Kali Linux渗透基础知识整理（一）：信息搜集](http://www.freebuf.com/sectool/109944.html)
* [我眼中的渗透测试信息搜集](https://bbs.ichunqiu.com/thread-16020-1-1.html)
* [从phpinfo中能获取哪些敏感信息](http://www.am0s.com/penetration/322.html)
* [透过F5获取服务器真实内网IP](https://threathunter.org/topic/5940c85d9c58e020408a79fe)
* [[红日团队]安全攻城师系列文章－敏感信息收集](http://www.mottoin.com/99951.html)
* [论二级域名收集的各种姿势](https://mp.weixin.qq.com/s/ardCYdZzaSjvSIZiFraWGA)
* [WEB应用中的信息泄漏以及攻击方法](http://www.4hou.com/info/news/3926.html)
* [实例演示如何科学的进行子域名收集](http://bobao.360.cn/learning/detail/4119.html)
* [挖掘漏洞的高级方法和思维](http://www.4hou.com/vulnerable/8376.html)
* [渗透测试工程师子域名收集指南](http://www.4hou.com/technology/8535.html)
* [Red Team 视角的信息收集技术](http://blkstone.github.io/2017/04/28/pentest-recon/)
* [渗透神器系列 搜索引擎](https://thief.one/2017/05/19/1/)
* [Google Hacking Database](https://github.com/K0rz3n/GoogleHacking-Page/blob/master/Google%20Hacking%20Database.md)
* [Google Hacking](https://github.com/K0rz3n/GoogleHacking-Page/blob/master/Basic%20knowledge.md)
* [Shodan自动化利用](https://xz.aliyun.com/t/2070)
* [Shodan在渗透测试及漏洞挖掘中的一些用法](https://www.cnblogs.com/miaodaren/p/7904484.html)
* [Shodan的http.favicon.hash语法详解与使用技巧](https://www.cnblogs.com/miaodaren/p/9177379.html)
* [Shodan手册](https://b404.gitbooks.io/shodan-manual/) - 中文
* [Shodan手册](https://community.turgensec.com/shodan-pentesting-guide) dorks


## 渗透

* [渗透标准](https://www.processon.com/view/583e8834e4b08e31357bb727)
* [pentest-bookmarks](https://github.com/riskawarrior/pentest-bookmarks)
* [awesome-pentest](https://github.com/enaqx/awesome-pentest) - A collection of awesome penetration testing resources.
* [Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - Awesome Pentest Cheat Sheets.
* [Pentesting checklists for various engagements](https://github.com/netbiosX/Checklists)
* [pentest-wiki](https://github.com/nixawk/pentest-wiki/)
* [Micropoor](https://github.com/Micropoor/Micro8)
* [渗透测试工具备忘录](https://xz.aliyun.com/t/2482#toc-67)
* [API 接口渗透测试](https://xz.aliyun.com/t/2412)
* [黑盒渗透测试的一些姿势和个人总结](http://www.test404.com/post-1532.html)
* [Web应用程序安全测试备忘录](https://www.secpulse.com/archives/66154.html)
* [从目录信息泄露到渗透内网](http://blog.51cto.com/simeon/1928354)
* [Web Service 渗透测试从入门到精通](http://bobao.360.cn/learning/detail/3741.html)
* [渗透实战中的反取证](https://www.t00ls.net/articles-42351.html)
* [陪妹子玩游戏引起的风波](https://www.t00ls.net/articles-42078.html)
* [攻破黑市最流行的钓鱼网站](https://www.t00ls.net/articles-41342.html)
* [攻破黑市最流行的网站2](https://forum.90sec.org/forum.php?mod=viewthread&tid=10676&extra=page%3D1)
* [实战教你怎么拿到女神的手机号，渗透某偷红包app](https://www.t00ls.net/articles-39902.html)
* [渗透记录1](https://www.secquan.org/Discuss/543)
* [渗透记录2](https://www.secquan.org/Discuss/588)
* [Web黑盒渗透思路之猜想](http://www.freebuf.com/articles/web/161491.html)
* [老文一次艰难的渗透纪实](https://xianzhi.aliyun.com/forum/topic/2122#toc-3)
* [渗透Hacking Team过程](https://xz.aliyun.com/t/2146)
* [代理不当日进内网](https://mp.weixin.qq.com/s/EtUmfMxxJjYNl7nIOKkRmA)
* [浅析反向代理](https://www.anquanke.com/post/id/150436)
* [iptable介绍](https://github.com/tom0li/security_circle/blob/master/15552854825122.md)
* [渗透测试学习笔记之综合渗透案例一](https://www.secpulse.com/archives/72464.html)
* [记一次对某企业的渗透测试实战](https://bbs.ichunqiu.com/thread-41946-1-1.html)
* [Exploit Singapore Hotels: ezxcess.antlabs.com](https://paper.tuisec.win/detail/06b238bc27b9c90)
* [ssrf内网漫游](https://github.com/r35tart/Penetration_Testing_Case/blob/master/%E4%BD%8E%E5%8D%B1SSRF%E6%8F%90%E6%9D%83%E8%BF%9B%E5%86%85%E7%BD%91.pdf)
* [渗透记录1](https://www.freebuf.com/vuls/211842.html)
* [渗透记录2](https://www.freebuf.com/vuls/211847.html)


#### 靶场
* [vulhub](https://github.com/vulhub/vulhub)
* [vulfocus](https://github.com/fofapro/vulfocus)

#### 技巧

* [https的app如何抓包](https://www.t00ls.net/thread-40042-1-1.html)
* [如何使用Xposed+JustTrustMe来突破SSL Pinning](https://bbs.pediy.com/thread-226435.htm)
* [BurpSuite多重代理](https://www.anquanke.com/post/id/85925)
* [Frida.Android.Practice (ssl unpinning)](https://github.com/WooyunDota/DroidDrops/blob/master/2018/Frida.Android.Practice.md)
* [IIS7以上突破无脚本执行权限限制](https://forum.90sec.org/forum.php?mod=viewthread&tid=10562&extra=page%3D2)
* [ACCESS无select SQL注射](https://forum.90sec.org/forum.php?mod=viewthread&tid=10663)
* [SQL注入奇巧淫技——利用DNSLOG获取看不到的信息](http://foreversong.cn/archives/861)
* [修改过狗菜刀](https://forum.90sec.org/forum.php?mod=viewthread&tid=10544&extra=page%3D2)
* [Java版的中国菜刀修改](https://forum.90sec.com/t/topic/513)
* [修改c刀](http://www.freebuf.com/articles/web/100432.html)
* [菜刀HTTP流量中转代理过WAF](https://xz.aliyun.com/t/2739)
* [sql二次注入和截断联合使用](https://forum.90sec.org/forum.php?mod=viewthread&tid=10377&extra=page%3D3)
* [sql二次注入和截断补充说明](https://forum.90sec.org/forum.php?mod=viewthread&tid=10383&extra=page%3D3)
* [盘点那些渗透测试中的奇淫技巧](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=14031&ctid=34)
* [利用Host header attack进行社交工程攻击手法]-文章在90论坛
* [phpMyAdmin新姿势getshell](http://www.91ri.org/17525.html) -感觉默认没开,需用ROOT权限开启
* [phpmyadmin4.8.1后台getshell](https://www.secpulse.com/archives/72817.html)
* [CVE-2018-12613 PhpMyadmin后台文件包含分析](http://www.lsafe.org/?p=300)
* [一个关于二次越权的漏洞分享](https://www.t00ls.net/thread-38883-1-1.html)
* [利用redis写webshell](https://www.leavesongs.com/PENETRATION/write-webshell-via-redis-server.html)
* [异地账号密码登陆qq邮箱(好像没检测是否异地](https://www.t00ls.net/viewthread.php?tid=42162&highlight=%E8%85%BE%E8%AE%AF)
* [pentest-tips](https://jivoi.github.io/2015/07/01/pentest-tips-and-tricks/)
* [维持访问 WebShell](http://www.91ri.org/17340.html)
* [linux远程执行win命令SMB-winexe](https://github.com/tom0li/security_circle/blob/master/51112814181184.md)
* [换个思路，对某培训机构进行一次 YD 的社工检测](https://bobylive.com/static/1936996)
* [渗透技巧--浅析web暴力猜解](https://mp.weixin.qq.com/s/dSIFoBdr44BLc7TrPR8u8Q)
* [奇技淫巧 | 上传web.config文件获取远程代码执行权限](http://www.freebuf.com/articles/web/173831.html)
* [无效HTTP请求绕过Lighttpd重写规则](https://www.anquanke.com/post/id/148328)
* [相对持久的绕过方法和一点想法_已被杀](http://www.freebuf.com/articles/network/175097.html)
* [渗透技巧之SSH篇](http://drops.xmd5.com/static/drops/tips-1951.html)
* [无需sendmail：巧用LD_PRELOAD突破disable_functions](https://www.freebuf.com/articles/web/192052.html)
* [RFI 绕过 URL 包含限制 getshell](https://paper.seebug.org/923/)
* [一次攻击内网rmi服务的深思](https://forum.90sec.com/t/topic/388/1)
* [2个思路](https://xz.aliyun.com/t/6587) - 读取连接mysql客户端系统信息,上传
* [JNI技术绕过rasp防护实现jsp webshell](https://mp.weixin.qq.com/s?__biz=MzA5Mzg3NTUwNQ==&mid=2447804425&idx=1&sn=91515259ee4d8a204d40e0aee8177f58)
* [结合直接系统调用和sRDI来绕过AV / EDR](https://bbs.pediy.com/thread-253564.htm)

### 内网

* [AD-Attack-Defense](https://github.com/infosecn1nja/AD-Attack-Defense)
* [l3m0n:从零开始内网渗透学习](https://github.com/l3m0n/pentest_study)
* [uknowsec / Active-Directory-Pentest-Notes](https://github.com/uknowsec/Active-Directory-Pentest-Notes)
* [内网渗透知识大总结](https://www.anquanke.com/post/id/92646)
* [DarthSidious-Chinese](https://github.com/crazywa1ker/DarthSidious-Chinese)
* [Intranet_Penetration_Tips](https://github.com/Ridter/Intranet_Penetration_Tips)
* [tom0li:内网备忘录](https://tom0li.github.io/%E5%86%85%E7%BD%91%E5%A4%87%E5%BF%98%E5%BD%95/)
* [对国外某内网渗透的一次小结](https://forum.90sec.org/forum.php?mod=viewthread&tid=9264&highlight=%C4%DA%CD%F8) - 老文新手练手入门
* [针对国内一大厂的后渗透 – 持续](https://wsygoogol.github.io/2018/01/11/%E9%92%88%E5%AF%B9%E5%9B%BD%E5%86%85%E4%B8%80%E5%A4%A7%E5%8E%82%E7%9A%84%E5%90%8E%E6%B8%97%E9%80%8F-%E2%80%93-%E6%8C%81%E7%BB%AD/)
* [渗透测试学习笔记之综合渗透案例一](https://mp.weixin.qq.com/s/sKXWjgaViYsCjG33-5Ey8Q)
* [彻底理解Windows认证](https://www.secpulse.com/archives/94848.html)
* [记一次横向渗透](https://www.lz1y.cn/2018/12/26/%E8%AE%B0%E4%B8%80%E6%AC%A1%E6%A8%AA%E5%90%91%E6%B8%97%E9%80%8F/)
* [kerberos](https://shenaniganslabs.io/media/Constructing%20Kerberos%20Attacks%20with%20Delegation%20Primitives.pdf)
* [内网渗透记录](https://paper.seebug.org/1144) 关键词：委派、relay、bypassAV、webdev XXE -by A-TEAM

#### Exchange
* [深入 Exchange Server 在网络渗透下的利用方法](https://paper.seebug.org/775/)
* [Exchange在渗透测试中的利用](https://evi1cg.me/archives/Exchange_Hack.html)
* [Microsoft Exchange漏洞记录(撸向域控) - CVE-2018-8581](https://www.cnblogs.com/iamstudy/articles/Microsoft_Exchange_CVE-2018-8581.html)
* [利用 Exchange SSRF 漏洞和 NTLM 中继沦陷域控](https://xax007.github.io/2019-01-26-pwn-domain-admin-via-exchange-ssrf/)
* [Microsoft Exchange漏洞分析](http://www.cnblogs.com/iamstudy/articles/Microsoft_Exchange_CVE-2018-8581_2.html)
* [Microsoft Exchange 任意用户伪造漏洞（CVE-2018-8581）分析](https://paper.seebug.org/804/)
* [Exchange服务器远程代码执行漏洞复现分析](https://xz.aliyun.com/t/7299)

#### hash ticket Credential

* [Windows下的密码hash——NTLM hash和Net-NTLM hash介绍](https://xianzhi.aliyun.com/forum/topic/1943)
* [域渗透之hash与票据](https://mp.weixin.qq.com/s/ENStRpYspx5W974BKPzZtA)
* [Kerberos的黄金票据详解](https://mp.weixin.qq.com/s/D1idV1cdZeTnpSiXkzD-XA)
* [花式窃取NetNTLM哈希的方法](https://paper.seebug.org/474/)
* [域hash值的导出技巧大全](https://www.t00ls.net/viewthread.php?tid=40118&highlight=hash)
* [敞开的地狱之门：Kerberos协议的滥用](http://www.freebuf.com/articles/system/45631.html)
* [NTLM-Relay](https://mp.weixin.qq.com/s/1LpgGx3-YA5aR0Mx9iryCQ)
* [Practical guide to NTLM Relaying in 2017](https://byt3bl33d3r.github.io/practical-guide-to-ntlm-relaying-in-2017-aka-getting-a-foothold-in-under-5-minutes.html)
* [The worst of both worlds: Combining NTLM Relaying and Kerberos delegation](https://dirkjanm.io/worst-of-both-worlds-ntlm-relaying-and-kerberos-delegation/)
* [红队与理论：Credential Relay 与 EPA](https://paper.seebug.org/844/)
* [高级域渗透技术之传递哈希已死-LocalAccountTokenFilterPolicy万岁](https://www.4hou.com/technology/17668.html)

#### 代理转发
* [代理转发工具汇总分析](https://mp.weixin.qq.com/s/gztsWf8JaugMY0zfuqQxCQ)
* [渗透测试技巧之内网穿透方式与思路总结](https://xz.aliyun.com/t/1623)
* [通过双重跳板漫游隔离内网](https://paper.tuisec.win/detail/60e44a10243185a)
* [一款突破内网防火墙神器ngrok](https://paper.tuisec.win/detail/75e46a067d7b6f8)
* [内网漫游之SOCKS代理大结局](https://paper.tuisec.win/detail/fc04d85ab57c8bf)
* [ew](https://mp.weixin.qq.com/s/VBiwJmpfIcRpdhwwWt2Ciw)
* [代理工具](https://github.com/Dliv3/Venom) 端口复用、游走内网
* [win IIS端口复用](https://www.secrss.com/articles/12696)
* [iptables端口复用](https://threathunter.org/topic/594545184ea5b2f5516e2033)

#### 内网平台
* [Cobalt_Strike_wiki](https://github.com/aleenzz/Cobalt_Strike_wiki)
* [内网剑客三结义](https://paper.tuisec.win/detail/4f04eff9c0f5b82)
* [渗透利器Cobalt Strike - 第1篇 功能及使用](https://xz.aliyun.com/t/3975)
* [Cobalt strike3.0使用手册](https://evi1cg.me/archives/Cobalt_strike.html)
* [Cobalt Strike上手学习](https://rcoil.me/2018/04/Cobalt%20Strike%E5%AD%A6%E4%B9%A0/)
* [渗透利器Cobalt Strike - 第2篇 APT级的全面免杀与企业纵深防御体系的对抗](https://xz.aliyun.com/t/4191)
* [Metasploit域渗透测试全程实录（终结篇）](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=16655&highlight=Metasploit%E5%9F%9F%E6%B8%97)
* [metasploit在后渗透中的作用](https://www.secpulse.com/archives/69766.html)
* [Metasploit驰骋内网直取域管首级](https://www.anquanke.com/post/id/85518)
* [Metasploit 「永恒之蓝」两种模块的利弊](https://www.bodkin.ren/index.php/archives/555/)
* [一篇文章精通PowerShell Empire 2.3（上）](http://bobao.360.cn/learning/detail/4760.html)
* [一篇文章精通PowerShell Empire 2.3（下）](http://bobao.360.cn/learning/detail/4761.html)
* [Powershell攻击指南黑客后渗透之道系列——基础篇](https://www.anquanke.com/post/id/87976)
* [Powershell攻击指南黑客后渗透之道系列——进阶利用](https://www.anquanke.com/post/id/88851)
* [Powershell攻击指南黑客后渗透之道系列——实战篇](https://www.anquanke.com/post/id/89362)
* [nishang-ps](http://www.4hou.com/technology/5962.html)
* [Empire实战域渗透](http://www.4hou.com/technology/4704.html)

#### 内网收集
* [Windows环境下的信息收集](https://mp.weixin.qq.com/s/37xtTdjVetMg5P1WaJvYvA)
* [Windows渗透常用命令](http://www.myh0st.cn/index.php/archives/261/)
* [渗透的本质是信息搜集（第一季）](http://blog.csdn.net/micropoor/article/details/79400904)
* [后渗透攻防的信息收集](https://www.secpulse.com/archives/51527.html)
* [域渗透基础简单信息收集 基础篇](https://xianzhi.aliyun.com/forum/topic/237/)
* [Linux 机器的渗透测试命令备忘表](http://www.91ri.org/17575.html)
* [黑客游走于企业windows内网的几种姿势](https://paper.tuisec.win/detail/4973d8fa7741cb3)
* [内网渗透测试定位技术总结](http://www.mottoin.com/92978.html)
* [内网渗透——网络环境的判断](https://paper.tuisec.win/detail/bc7c4b2c3145d47)
* [PowerView](http://www.freebuf.com/sectool/173366.html)
* [WMI在渗透测试中的重要性](https://www.secpulse.com/archives/72493.html)
* [BloodHound](https://github.com/BloodHoundAD/BloodHound)

#### 内网技巧
* [红队后渗透测试中的文件传输技巧](https://paper.seebug.org/834/)
* [渗透经验 | Windows下载远程Payload并执行代码的各种技巧](http://www.freebuf.com/articles/system/155147.html)
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
* [域渗透——Pass The Hash的实现](https://3gstudent.github.io/3gstudent.github.io/%E5%9F%9F%E6%B8%97%E9%80%8F-Pass-The-Hash%E7%9A%84%E5%AE%9E%E7%8E%B0/)
* [域渗透——获得域控服务器的NTDS.dit文件](https://3gstudent.github.io/3gstudent.github.io/%E5%9F%9F%E6%B8%97%E9%80%8F-%E8%8E%B7%E5%BE%97%E5%9F%9F%E6%8E%A7%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%9A%84NTDS.dit%E6%96%87%E4%BB%B6/)
* [渗透技巧——获得Windows系统的远程桌面连接历史记录](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-%E8%8E%B7%E5%BE%97Windows%E7%B3%BB%E7%BB%9F%E7%9A%84%E8%BF%9C%E7%A8%8B%E6%A1%8C%E9%9D%A2%E8%BF%9E%E6%8E%A5%E5%8E%86%E5%8F%B2%E8%AE%B0%E5%BD%95/)
* [渗透技巧 | Windows上传并执行恶意代码的N种姿势](https://mp.weixin.qq.com/s?__biz=MzUxOTYzMzU0NQ==&mid=2247483675&idx=1&sn=13cc49242df2b8cd7d08d4084af9621b&chksm=f9f7eefdce8067eba45e9fd4090f34703c2e101be06ae83dc7db53f24f343ab907545ab9d423&scene=21#wechat_redirect)
* [域渗透——利用SYSVOL还原组策略中保存的密码](https://xianzhi.aliyun.com/forum/topic/1653/)
* [Windows 日志攻防之攻击篇](https://threathunter.org/topic/593eb1bbb33ad233198afcfa)
* [针对 win 的入侵日志简单处理](https://klionsec.github.io/2017/05/19/wevtutil/)
* [从活动目录中获取域管理员权限的6种方法](http://www.4hou.com/technology/4256.html)
* [当服务器只开web服务并且防火墙不准服务器对外主动发起链接时](https://mp.weixin.qq.com/s/W5npN8YiqG-RBoq2mTv_2g)
* [3gstudent/Pentest-and-Development-Tips](https://github.com/3gstudent/Pentest-and-Development-Tips)
* [渗透测试中常见的小TIPS总结和整理](http://avfisher.win/archives/100)
* [内网渗透思路整理与工具使用](https://www.anquanke.com/post/id/85827)
* [windows内网渗透杂谈](https://bl4ck.in/penetration/2017/03/20/windows%E5%86%85%E7%BD%91%E6%B8%97%E9%80%8F%E6%9D%82%E8%B0%88.html)
* [60字节 - 无文件渗透测试实验](https://www.n0tr00t.com/2017/03/09/penetration-test-without-file.html)
* [关于windows的RDP连接记录](http://rcoil.me/2018/05/%E5%85%B3%E4%BA%8Ewindows%E7%9A%84RDP%E8%BF%9E%E6%8E%A5%E8%AE%B0%E5%BD%95/)
* [Rcoil内网渗透](http://rcoil.me/2017/06/%E5%86%85%E7%BD%91%E6%B8%97%E9%80%8F/)
* [3389user无法添加](http://www.91ri.org/5866.html)
* [丢掉PSEXEC使用wmi来横向渗透](https://threathunter.org/topic/5940a6e59c58e020408a79ea)
* [ms14-068域提权系列总结](https://www.t00ls.net/thread-43786-1-1.html)
* [域渗透之Exchange Server](https://paper.tuisec.win/detail/203cfd7605f41af)
* [域渗透——Skeleton Key](https://paper.tuisec.win/detail/ae1a9ecf9625209)
* [动手打造Bypass UAC自动化测试小工具，可绕过最新版Win10](http://www.freebuf.com/sectool/114592.html)
* [Metasploit – Sessions Command 使用技巧](https://www.secpulse.com/archives/72890.html)
* [渗透技巧——利用图标文件获取连接文件服务器的NTLMv2 Hash](https://xz.aliyun.com/t/1977)
* [在 Windows 环境中使用 Responder 窃取 NTLMv2 哈希并利用](https://xz.aliyun.com/t/3560)
* [DoubleAgent](https://github.com/Cybellum/DoubleAgent) -后渗透对杀软进行注入
* [Extracting NTLM Hashes from keytab files](https://paper.tuisec.win/detail/ceac9f167bf27de)
* [离线导出Chrome浏览器中保存的密码](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-%E7%A6%BB%E7%BA%BF%E5%AF%BC%E5%87%BAChrome%E6%B5%8F%E8%A7%88%E5%99%A8%E4%B8%AD%E4%BF%9D%E5%AD%98%E7%9A%84%E5%AF%86%E7%A0%81/)
* [渗透技巧——利用Masterkey离线导出Chrome浏览器中保存的密码](https://3gstudent.github.io/3gstudent.github.io/%E6%B8%97%E9%80%8F%E6%8A%80%E5%B7%A7-%E5%88%A9%E7%94%A8Masterkey%E7%A6%BB%E7%BA%BF%E5%AF%BC%E5%87%BAChrome%E6%B5%8F%E8%A7%88%E5%99%A8%E4%B8%AD%E4%BF%9D%E5%AD%98%E7%9A%84%E5%AF%86%E7%A0%81/)
* [域渗透——Kerberoasting](https://3gstudent.github.io/3gstudent.github.io/%E5%9F%9F%E6%B8%97%E9%80%8F-Kerberoasting/)
* [BloodHound官方使用指南](https://www.cnblogs.com/backlion/p/10643132.html)
* [老牌工具 PsExec 一个琐碎的细节](https://paper.seebug.org/503/)
* [域渗透之使用CrackMapExec拿到我们想要的东西](https://www.anquanke.com/post/id/84980)
* [Kerberos协议探索系列之委派篇](https://www.anquanke.com/post/id/173477)
* [通过RDP反向攻击mstsc](https://paper.seebug.org/1074/)
* [远程提取凭证](https://beta.hackndo.com/remote-lsass-dump-passwords/)
* [重新思考凭证盗窃](https://labs.f-secure.com/blog/rethinking-credential-theft)
* [Ghost potato实际利用](https://www.lz1y.cn/2019/11/19/Ghost-potato%E5%AE%9E%E9%99%85%E5%88%A9%E7%94%A8/)


#### 提权
* [win提权辅助tool](https://github.com/GDSSecurity/Windows-Exploit-Suggester/)
* [详解Linux权限提升的攻击与防护](https://www.anquanke.com/post/id/98628)
* [windows-kernel-exploits Windows平台提权漏洞集合](https://github.com/SecWiki/windows-kernel-exploits)
* [linux-kernel-exploits Linux平台提权漏洞集合](https://github.com/SecWiki/linux-kernel-exploits)

## APT
* [Red-Team-Infrastructure-Wiki](https://github.com/bluscreenofjeff/Red-Team-Infrastructure-Wiki)
* [论高级威胁的本质和攻击力量化研究](http://www.vxjump.net/files/aptr/aptr.txt)
* [Whats APT：浅谈APT攻击](http://www.freebuf.com/column/160412.html)
* [APT 分析及 TTPs 提取](https://paper.seebug.org/1132/)
* [一次红队之旅](https://xz.aliyun.com/t/2389)
* [Web应用安全测试前期情报收集方法与工具的介绍](http://www.freebuf.com/sectool/174417.html)
* [Top Five Ways the Red Team breached the External Perimeter](https://medium.com/@adam.toscher/top-five-ways-the-red-team-breached-the-external-perimeter-262f99dc9d17)
* [MITRE | ATT&CK 中文站](https://huntingday.github.io)
* [渗透测试实战第三版](https://github.com/tom0li/collection-document/blob/master/%5B%E8%AF%91%5D%20%E6%B8%97%E9%80%8F%E6%B5%8B%E8%AF%95%E5%AE%9E%E6%88%98%E7%AC%AC%E4%B8%89%E7%89%88(%E7%BA%A2%E9%98%9F%E7%89%88).pdf)
* [RemTeam攻击技巧和安全防御](https://xz.aliyun.com/t/4602)
* [隐私保护]()

### 钓鱼
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
win远程连接漏洞CVE-2019-1333
Mysql读文件&反序列化
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

#### 邮件伪造

* [一封伪造邮件引发的“探索”（涉及钓鱼邮件、SPF和DKIM等）](http://www.freebuf.com/articles/web/138764.html)
* [SPF 记录：原理、语法及配置方法简介](https://www.renfei.org/blog/introduction-to-spf.html)
* [邮件伪造技术与检测](https://www.secpulse.com/archives/78738.html)
* [伪造电子邮件以及制造电子邮件炸弹的攻防探讨](https://www.freebuf.com/sectool/184555.html)
* [绕过DKIM验证，伪造钓鱼邮件](http://www.4hou.com/web/7857.html)
* [Best Practices on Email Protection: SPF, DKIM and DMARC](https://wiki.zimbra.com/wiki/Best_Practices_on_Email_Protection:_SPF,_DKIM_and_DMARC)
* [Cobalt Strike Spear Phish](https://evi1cg.me/archives/spear_phish.html)

### 远控
* [Koadic C3 COM Command & Control - JScript RAT](https://github.com/zerosum0x0/koadic)
* [QuasarRAT](https://github.com/quasar/QuasarRAT)
* [Ping Power — ICMP Tunnel](https://medium.com/bugbountywriteup/ping-power-icmp-tunnel-31e2abb2aaea)

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
* [XSS常见利用代码及原理](http://wps2015.org/2016/12/12/usually-used-xss-code/)
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

### tools

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
* [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - Payloads 大全
* [对AWVS一次简单分析](http://blog.wils0n.cn/archives/145/)
* [擦除AWVS一些标志](http://0cx.cc/replace_wvs_by_wyproxy.jspx)
* [nmap](http://www.polaris-lab.com/index.php/archives/390/)
* [nmap谈谈端口探测的经验与原理](http://www.freebuf.com/articles/network/146087.html)

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

## FUZZ
* [我如何使用Cloud Fuzzing挖到了一个Tcpdump漏洞](http://www.freebuf.com/articles/network/147955.html)
* [Fuzzing Android：挖掘Android系统组件组件中的漏洞](http://bobao.360.cn/learning/detail/3213.html)
* [Fuzzing平台建设的研究与设计](http://riusksk.me/2020/01/21/Fuzzing%E5%B9%B3%E5%8F%B0%E5%BB%BA%E8%AE%BE%E7%9A%84%E7%A0%94%E7%A9%B6%E4%B8%8E%E8%AE%BE%E8%AE%A1-paper/)
* [Fuzz自动化Bypass软WAF姿势](https://4hou.win/wordpress/?p=15613)
* [我的Web应用安全模糊测试之路](https://gh0st.cn/archives/2018-07-25/1)
* [Wfuzz初上手](https://www.secpulse.com/archives/78638.html)
* [Wfuzz基本功](https://www.secpulse.com/archives/81560.html)
* [Wfuzz高阶功法1](https://gh0st.cn/archives/2018-10-28/3)
* [Wfuzz高阶功法2](https://www.secpulse.com/archives/83173.html)

## WAF

* [命令注入之Web应用防火墙绕过技巧](https://bbs.ichunqiu.com/thread-32708-1-1.html)
* [个人总结的waf绕过注入思路（附带6种常见waf的绕过方法）](https://www.t00ls.net/viewthread.php?tid=43687&extra=&page=1)
* [SQL注入 | 9种绕过Web应用程序防火墙的方式-基础](http://www.freebuf.com/articles/web/163783.html)
* [WAF攻防之SQL注入篇](http://galaxylab.org/waf%E6%94%BB%E9%98%B2%E4%B9%8Bsql%E6%B3%A8%E5%85%A5%E7%AF%87/)
* [老司机带你过常规WAF](https://www.secpulse.com/archives/69983.html)
* [SQL注入ByPass的一些小技巧](https://mp.weixin.qq.com/s/fSBZPkO0-HNYfLgmYWJKCg)
* [在HTTP协议层面绕过WAF](https://www.freebuf.com/news/193659.html)
* [利用分块传输吊打所有WAF](https://www.anquanke.com/post/id/169738)
* [WAF绕过的捷径与方法](https://www.qiaoyue.net/2019/WAF%E7%BB%95%E8%BF%87%E7%9A%84%E6%8D%B7%E5%BE%84%E4%B8%8E%E6%96%B9%E6%B3%95/)
* [对过WAF的一些认知](http://static.anquanke.com/download/b/security-geek-2019-q2/article-18.html)
* [Bypass 360主机卫士SQL注入防御（多姿势）](https://www.t00ls.net/thread-45943-1-1.html)
* [Bypass D盾_IIS防火墙SQL注入防御（多姿势）](http://www.cnblogs.com/xiaozi/p/7357937.html)
* [不包含数字字母的WebShell](http://www.freebuf.com/articles/web/173579.html)
* [php一句话木马检测绕过研究](https://www.t00ls.net/viewthread.php?tid=45816)
* [利用php特性过D盾，一句话和大马都可使用](https://www.t00ls.net/viewthread.php?tid=44388)
* [构造免杀的asp一句话木马](https://xz.aliyun.com/t/2356)

## IDS

* [我们来谈一谈IDS签名](https://www.anquanke.com/post/id/102948#h2-0)
* [不按顺序来的 TCP 包](https://strcpy.me/index.php/archives/789/)
* [网络层绕过 IDS/IPS 的一些探索](https://paper.seebug.org/1173/)

## 其他

#### Git

* [Git各种错误操作撤销的方法](http://www.bugcode.cn/git_undo.html)
* [Git的tip](https://github.com/521xueweihan/git-tips)

#### 特别的wx号

* [全频带阻塞干扰]  -坚持以非正常体位探寻未知信号。关注无线安全、通信监听、商业反窃密、平行空间、非主流隐私保护、海外情报、犯罪防御、群氓效应、漂亮妹纸和科幻大刘。

#### 二维码

* [微信Netting-QRLJacking分析利用-扫我二维码获取你的账号权限](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=25923&highlight=%E4%BA%8C%E7%BB%B4%E7%A0%81)
* [Android平台下二维码漏洞攻击杂谈](https://wooyun.js.org/drops/Android%E5%B9%B3%E5%8F%B0%E4%B8%8B%E4%BA%8C%E7%BB%B4%E7%A0%81%E6%BC%8F%E6%B4%9E%E6%94%BB%E5%87%BB%E6%9D%82%E8%B0%88.html)
* [二维码登陆的常见缺陷剖析](https://www.t00ls.net/thread-45152-1-1.html)
* [二维码安全-淘宝例子](https://www.t00ls.net/thread-45618-1-1.html)

#### 爬虫

* [浅谈动态爬虫与去重](https://www.anquanke.com/post/id/85298)
* [浅谈动态爬虫与去重(续)](https://www.anquanke.com/post/id/95294#h2-1)
* [爬虫基础篇[Web 漏洞扫描器]](http://blog.fatezero.org/2018/03/05/web-scanner-crawler-01/)

#### 学术

* [安全学术圈2018年度总结](https://mp.weixin.qq.com/s/eQ5os0Fdb498BoQLKUDmrA) - 微信号安全学术圈

#### 科普
* [10大深网搜索引擎](http://www.freebuf.com/news/137844.html)
* [在百度网盘上看到上万条车主个人信息，企业、政府高官信息、各种数据](https://bbs.ichunqiu.com/article-798-1.html)
* [一道 CTF 题 get 到的新姿势](https://mp.weixin.qq.com/s?__biz=MzI5MDQ2NjExOQ==&mid=2247485297&idx=1&sn=b9d5f80bcd37d1ce0596e1a2c251d9fb&chksm=ec1e3759db69be4f84913826e4b4e5d79461061e0f61a4eb8889aa65909e2ab314391d94f87c#rd)
* [iPhone锁屏却锁不住个人信息，iOS安全性真的很高吗？](http://www.freebuf.com/vuls/153848.html)
* [弦哥从新加坡HITB黑客大会进口过来的黑魔法命令](https://github.com/tom0li/security_circle/blob/master/51115142241184.md)
* [编程的重要性之 sqlmap 源码](https://github.com/tom0li/security_circle/blob/master/88511152424522.md)
* [资讯400多个流行站点记录用户键击 或导致个人敏感信息泄露](http://bobao.360.cn/news/detail/4389.html)
* [https劫持理解](https://forum.90sec.org/forum.php?mod=viewthread&tid=10378&extra=page%3D3)
* [银行卡quickpass闪付芯片通过EVM/PBOC读取隐私信息](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=25955&ctid=48)
* [txt文本文件去重及导入数据库处理](https://bbs.ichunqiu.com/forum.php?mod=viewthread&tid=25725&ctid=48)
* [解析U盘病毒传播之文件欺骗](http://www.freebuf.com/articles/terminal/155063.html)
* [深度剖析：手机指纹的马奇诺防线](https://paper.seebug.org/471/)
* [网撸黑话+技巧大全 | 岂安低调分享](https://www.secpulse.com/archives/66549.html)
* [国外14亿数据](http://www.03sec.com/3190.shtml)
* [Word文件加密之后](https://www.secpulse.com/archives/67398.html)
* [腾讯2017年度网络黑产威胁源研究报告](https://book.yunzhan365.com/odqt/yzzl/mobile/index.html)
* [洗钱工具“手机充值卡”卡号卡密灰色行业套现洗白链](http://www.freebuf.com/column/163232.html)
* [kali安装后](http://metaphors.name/coding/2018/03/10/Kali.html)
* [请求方法问题](http://www.freebuf.com/articles/web/172695.html)
* [Python工具分析风险数据](https://www.secpulse.com/archives/66377.html)
* [技术讨论 | 构建一个小巧的来电显示迷惑工具](http://www.freebuf.com/sectool/173730.html)
* [google.com/machine-learning/crash-course/](https://developers.google.com/machine-learning/crash-course/?hl=zh-cn)
* [远程定位追踪联网车辆以及利用思路分析](http://www.freebuf.com/vuls/178604.html)
* [智能锁具攻防系列一初探](https://future-sec.com/intelligent-lock-attack-and-defense-1.html)
* [我的世界观](https://mp.weixin.qq.com/s?__biz=MzA3NTEzMTUwNA==&mid=200044901&idx=1&sn=2a40b65874b54f7d2c80303ee6558d9b#rd)
* [ivideo](https://github.com/phobal/ivideo)
* [baidu云盘](https://github.com/cool2528/baiduCDP)
* [偷U盘文件的神器](https://github.com/kenvix/USBCopyer)
* [内网安全检查/渗透总结](https://xz.aliyun.com/t/2354)
* [Linux内网渗透](https://thief.one/2017/08/09/2/)
* [内网渗透思路探索 之新思路的探索与验证](https://paper.tuisec.win/detail/521f97451904b16)
* [初级域渗透系列 - 01. 基本介绍&信息获取](https://paper.tuisec.win/detail/2a7446285e7d085)
* [初级域渗透系列 - 02. 常见攻击方法 - 1](https://paper.tuisec.win/detail/fc1086dabbc9002)
* [初级域渗透系列 03. 常见攻击方法](https://paper.tuisec.win/detail/cd49c17ca23cece)
* [内网渗透知识基础及流程](https://www.anquanke.com/post/id/170471)
* [linux-suid-privilege-escalation](https://www.leavesongs.com/PENETRATION/linux-suid-privilege-escalation.html)
* [Hard_winGuide.md](https://github.com/CHEF-KOCH/HWAB/blob/master/Guide.md)
* [Enterprise-Registration-Data-of-Chinese-Mainland](https://github.com/imhuster/Enterprise-Registration-Data-of-Chinese-Mainland)
* [red-team-and-the-next](https://devco.re/blog/2019/10/24/evolution-of-DEVCORE-red-team-and-the-next/) -by DEVCORE
* [道哥的黑板报](https://zhuanlan.zhihu.com/taosay) - 思考很深的年轻人 真正的大牛 


## How to contribute?
---
We welcome everyone to contribute,you can open an issue for this if you have some new idea about this project or you have found some quality safety articles,and then I will add your name to Acknowledgments.


## Acknowledgments
---
* @[tom0li](https://github.com/tom0li)
* @[neargle](https://github.com/neargle)
* @[r4v3zn](https://github.com/0nise)
