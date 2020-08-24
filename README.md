### Hi there 👋
- 🔭 I’m currently working on ... Baseline, NIDS and etc.

#### Quick Navigation

[HTTP 安全头配置](https://github.com/starnightcyber/Security-Learning/wiki/HTTP-%E5%AE%89%E5%85%A8%E5%A4%B4%E9%85%8D%E7%BD%AE)

[WAF](https://github.com/starnightcyber/Security-Learning/wiki#waf)

<!--
**starnightcyber/starnightcyber** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


### FYI ~ 

<details>
  <summary>2020.8.11 ~ 样例数据包 </summary>
  样例数据包下载站点：
  
    PacketLife:https://packetlife.net/captures/
  
    WireShark Sample Captures:https://wiki.wireshark.org/SampleCaptures

</details>

<details>
  <summary>2020.8.3 ~ 漏洞扫描 AWVS + Nessus (Docker版) </summary>
  
  原链：[漏洞扫描 AWVS + Nessus (Docker版)](https://blog.lfoder.cn/2020/06/04/%E6%BC%8F%E6%B4%9E%E6%89%AB%E6%8F%8F-AWVS-Nessus-Docker%E7%89%88/)
 
```  
  # 拉取镜像
  docker pull leishianquan/awvs-nessus:v1
  # 启动
  docker run -it -d -p 13443:3443 -p 8834:8834 leishianquan/awvs-nessus:v1
  # 查看容器
  docker ps –a
  # 启动容器
  docker start container-id
  # 进入容器
  docker exec –it container-id /bin/bash
  
  # 进入容器后，启动nessus
  /etc/init.d/nessusd start
  
  # 访问扫描器地址和账号密码
  Nessus:
  https://127.0.0.1:8834/#/
  account:leishi/leishianquan

  Awvs13:
  https://127.0.0.1:13443/
  account:admin@admin.com/Admin123
```

</details>


<details>
  <summary>2020.7.20 ~ burpsuite_pro_v2020_7 </summary>
 
  burpsuite_pro_v2020_7，破解使用请参考原链：https://segmentfault.com/a/1190000022141253 
  
  下载：[Burp_Suite_Pro_v2020.2_Loader_Keygen.zip](https://github.com/starnightcyber/Miscellaneous/releases/download/burpsuite_pro_v2020_7/Burp_Suite_Pro_v2020.2_Loader_Keygen.zip)
 
</details>

<details>
  <summary>2020.5.26 ~ Web漏扫软件 AppScan 10.0.0 破解版本下载</summary>
 
  Web漏扫软件 AppScan 10.0.0 [破解版本下载](https://mega.nz/file/bZdDVSoS#K0xDXmExFO73Kp2wzexuLDNHSwlWOlJPqJFdmdIge-o)
 
  安装破解步骤：
* 正常安装完成
* 用rcl_rational.dll替换安装目录下的对应文件;
* 在许可证管理中导入AppScanStandard.txt作为许可证;
  
  具体步骤：帮助》许可证》切换到IBM许可证》打开AppScan License Manager 》点击许可证配置》添加选中许可证文件AppScanStandard.txt即可。
 
</details>

<details>
  <summary>2020.4.23 ~ 防火墙账号信息</summary>
  常用防火墙设备的默认账号信息：
  
  [firewall-info](https://github.com/starnightcyber/Miscellaneous/tree/master/firewall-info)

</details>

<details>
  <summary>2020.4.12 ~ AWVS13破解版</summary>
  
  Awvs13破解版 Acunetix Web Vulnerability Scanner 13 cracked
  
  Release:
  https://github.com/starnightcyber/Miscellaneous/releases/tag/awvs13
  
  From:
  https://www.ddosi.com/b238/

破解方式：
```
wvsc.exe覆盖到“C:\Program Files (x86)\Acunetix\13.0.200205121\
license_info.json覆盖到“C:\ProgramData\Acunetix\shared\license”
```
  </details>

<details>
  <summary>2020.3.24 ~ cobaltstrike4.0 原版&破解版</summary>
  Release:
  https://github.com/starnightcyber/Miscellaneous/releases/tag/cobaltstrike4.0

  From:
  https://www.cnblogs.com/ssooking/p/12535998.html?from=timeline

  资料：[破解的cs4.0、cs4.0官方手册翻译和一些笔记](https://github.com/Snowming04/CobaltStrike4.0_related)
</details>

<details>
  <summary>2020.1.9 ~ Cobalt Strike 3.13 破解版</summary>
  Release:
  https://github.com/starnightcyber/Miscellaneous/releases/tag/Cobalt-Strike-3.13

  From:
  https://download.csdn.net/download/ws13129/11100785

</details>

<details>
  <summary>2019.12.23 ~ Seay源代码审计系统2.1</summary>
  Release:
  https://github.com/starnightcyber/Miscellaneous/releases/tag/seay2.1

  From: 
  https://github.com/f1tz/cnseay
</details>

<details>
  <summary>2019.12.19 ~ AWVS 10.5破解版</summary>
  Release:
  https://github.com/starnightcyber/Miscellaneous/releases/tag/awvs10.5

  From：
  https://www.52pojie.cn/thread-377625-1-1.html

  参考：[AWVS 10.5使用指南](https://www.cnblogs.com/Hi-blog/p/AWVS-User-Guide.html)
</details>

<details>
  <summary>2019.12.9 ~  Wireshark-win32-2.9.0-gm.3.exe</summary>
  Release:
  https://github.com/starnightcyber/Miscellaneous/releases/tag/Wireshark-win32-2.9.0
  
</details>

<details>
  <summary>2019.10.21 ~ AWVS 12破解版</summary>
  Release:
  https://github.com/starnightcyber/Miscellaneous/releases/tag/AWVS12
  
  参考：
  [AWVS12破解版的安装使用](https://www.cnblogs.com/Hi-blog/p/AWVS12.html)
</details>
