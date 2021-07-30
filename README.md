
# Personal CTF Toolkit

此工具包最初是基于精灵表哥和一个佚名表哥的工具包整理的，后来加上本人打CTF和渗透时所添加的一些工具，应当还算全面。

希望这份工具包可以为刚刚接触CTF的朋友构造自己的工具链带来一些微小的帮助。

考虑Github国内访问问题，下载还是放在网盘：

- 链接：https://pan.baidu.com/s/1qW11wUoDR3z9q5SnLVMaEw 提取码：2333 
- 7z Password: hacktheworld



愿世间心诚剑士人人会两袖青蛇，

愿天下惊艳后辈人人可剑开天门。



## Note

1. 部分工具运行时的目录中不可有空格或中文字符。
2. 目录只放了三层，再多则影响阅读。详细列表也上传了一份，以供参考。
3. 部分工具可能带有一定攻击性，仅供安全学习，禁止非法使用。



## Update log

- 2019.1.29
渗透测试实习中，根据实际渗透测试Update部分工具。
- 2019.3.20
随着经验以及和同事的互通有无，再度Update部分工具。
- 2020.12.29
  随着实际渗透的发展、CTF的新变化以及对IoT、工控等方向的接触，Update.



## index:
```
.
├── Web
│   ├── BruteTools
│   │   ├── August 一句话木马爆破工具 1.0 .rar
│   │   ├── K8_FuckOneShell
│   │   ├── OraclePasswords
│   │   ├── PKAV HTTP Fuzzer 1.5.6.zip
│   │   ├── hydra-7.3
│   │   ├── md5crack3.rar
│   │   ├── phpMyAdmin批量破解工具.rar
│   │   ├── phpMyadmin
│   │   ├── tomcat_manager_bruter
│   │   ├── 一句话快速爆破工具.zip
│   │   └── 一句话猜解工具.rar
│   ├── Burp Suite
│   │   ├── Burp_Suite_Pro_v2.1.04_Loader_Keygen.zip
│   │   └── plugin
│   ├── Cobalt Strike
│   │   ├── Ladon7.0.rar
│   │   └── cobaltstrike4.0.zip
│   ├── Exploits
│   │   ├── 0sec_exp
│   │   ├── CSRF-Request-Builder-master.zip
│   │   ├── CSRFTester-1.0.zip
│   │   ├── ECshop批量.py
│   │   ├── GetWebShell增强版.exe
│   │   ├── Mobile-Security-Framework-MobSF-1.0.3Beta
│   │   ├── OWASP_Xenotix_XSS_Exploit_Framework_V6.1.zip
│   │   ├── _漏洞利用载荷
│   │   ├── commix
│   │   ├── phpcmsv9  Getshell.py
│   │   ├── pker
│   │   ├── sqlmap-master
│   │   ├── tplmap-master
│   │   ├── ysoserial
│   │   ├── 双文件上传
│   │   ├── 手工注入辅助工具
│   │   ├── 超级SQL注入工具【SSQLInjection】V1.0 正式版 20190905
│   │   └── 超级SQL注入工具【SSQLInjection】V1.0 正式版 20190905.zip
│   ├── Payload
│   │   └── PayloadsAllTheThings-master
│   ├── Shell Ctrl
│   │   ├── AntSword-Loader-v4.0.3-win32-x64.zip
│   │   ├── Behinder
│   │   ├── Chopper
│   │   ├── behinder-过杀软.zip
│   │   ├── python反弹shell.txt
│   │   └── redis远程连接漏洞脚本.rar
│   ├── Trace Clear
│   │   └── anti-honeypot
│   ├── Trojan
│   │   └── 马还是自己收集比较好.txt
│   ├── 信息收集
│   │   ├── AWVS
│   │   ├── GitHack-master
│   │   ├── Goby
│   │   ├── GourdScan-master
│   │   ├── IIS短文件名漏洞利用工具
│   │   ├── K8_Fck_Exploit.exe
│   │   ├── Layer子域名挖掘机4.1 重构版
│   │   ├── M7lrvCMS 网站扫描程序V2.0(2015-08-13)
│   │   ├── OneForAll
│   │   ├── Seay批量域名解析IP.exe
│   │   ├── SourceLeakHacker
│   │   ├── WebAliveScan-master
│   │   ├── Xray
│   │   ├── crawlergo
│   │   ├── ds_store_exp
│   │   ├── lijiejie_subDomainsBrute-master
│   │   ├── sk15_redis_V_11.py
│   │   ├── 御剑后台扫描珍藏版
│   │   ├── 摄像头工具
│   │   └── 邮箱采集
│   ├── 免杀工具
│   │   ├── DefenderCheck
│   │   └── VMProtect_Ultimate_v3.5.0_x32_Build_1213_Retail_Licensed
│   ├── 内网工具
│   │   ├── CVE-2018-2893.zip
│   │   ├── LaZagne
│   │   ├── Venom v1.1.0
│   │   ├── lcx.zip
│   │   ├── linux lcx端口转发.zip
│   │   ├── nishang
│   │   ├── nps
│   │   └── 免杀mimikatz.zip
│   ├── 字典
│   │   ├── 100.txt
│   │   ├── 1000.txt
│   │   ├── 10000.txt
│   │   ├── 10000a.txt
│   │   ├── 12.txt
│   │   ├── 500姓名.txt
│   │   ├── 6000常用.txt
│   │   ├── Top100弱口令.txt
│   │   ├── darkweb2017-top1000.txt
│   │   ├── fuzz
│   │   ├── kaliwordlist
│   │   ├── pass.txt
│   │   ├── shell.txt
│   │   ├── shell1.txt
│   │   ├── superdic.exe
│   │   ├── top100.txt
│   │   ├── top3000.txt
│   │   ├── 轻型字典
│   │   └── 重型字典
│   ├── 审计工具
│   │   ├── D盾.zip
│   │   ├── Fortify
│   │   ├── Seay2.2修改版.rar
│   │   ├── Seay代码审计工具（二次修改）
│   │   ├── Seay源代码审计系统2.1.zip
│   │   ├── TextForever_1.79
│   │   ├── Web日志安全分析工具 v2.0.zip
│   │   ├── chip
│   │   ├── cobra-master
│   │   ├── lynis-2.7.2.tar.gz
│   │   └── rips-0.55.zip
│   ├── 提权工具
│   │   ├── linux
│   │   ├── nc提权
│   │   ├── pcanywhere
│   │   ├── php+mysql
│   │   ├── serv-u提权综合工具.rar
│   │   ├── windows
│   │   ├── 启动项提权.bat
│   │   ├── 常见提权工具
│   │   ├── 开启3389
│   │   ├── 扫目录.rar
│   │   ├── 权限维持
│   │   ├── 补丁对应提权方式.txt
│   │   └── 解决tcp限制.rar
│   └── 流量分析
│       ├── USB Monitor Pro.txt
│       ├── Wireshark.txt
│       ├── ctf_ics_traffic
│       ├── modbus
│       ├── 安装包
│       └── 推荐书籍
├── list.txt
├── 取证
│   ├── Elcomsoft Forensic Disk Decryptor
│   │   ├── Gold WareZ.nfo
│   │   ├── doa.nfo
│   │   ├── efdd_setup_en.msi
│   │   ├── file_id.diz
│   │   └── key.txt
│   ├── ScreenToGif_v2.16.0.0.zip
│   ├── kali forensics集合.txt
│   ├── routerpassview
│   │   ├── RouterPassView.cfg
│   │   ├── RouterPassView.chm
│   │   ├── RouterPassView.exe
│   │   ├── conf.bin
│   │   └── readme.txt
│   ├── routerpassview(1).zip
│   ├── snap7-full-1.4.2
│   │   ├── LabVIEW
│   │   ├── README.txt
│   │   ├── build
│   │   ├── doc
│   │   ├── examples
│   │   ├── gpl.txt
│   │   ├── lgpl-3.0.txt
│   │   ├── release
│   │   ├── rich-demos
│   │   ├── src
│   │   ├── utility
│   │   └── win-clean.bat
│   ├── snap7-full-1.4.2.7z
│   ├── 取证大师
│   │   ├── Bin
│   │   ├── Config
│   │   ├── Face
│   │   ├── Help
│   │   ├── Report
│   │   ├── Skin
│   │   ├── Update.txt
│   │   ├── UpdateCenter
│   │   ├── Viewer
│   │   ├── 取证大师.exe
│   │   └── 案例
│   ├── 取证大师.rar
│   ├── 日志分析
│   │   └── apache-scalp-master
│   ├── 秋式网站日志分析器.rar
│   └── 计算机安全检查取证系统.zip
├── 工控
│   ├── MMS.pdf
│   └── icsmaster
│       ├── README.md
│       ├── SCADA_Metasploit_Modules.csv
│       ├── SCADA_Metasploit_Modules.xls
│       ├── Scada_Dorks.csv
│       ├── Scada_Dorks.xls
│       ├── Scada_Password.csv
│       ├── Scada_Password.xls
│       ├── doc
│       ├── exploit
│       ├── nse
│       ├── pcap
│       ├── protocol
│       └── tool
├── 文件分析
│   ├── BeyondCompare_4.3.5.24893_64bit_Portable.7z
│   ├── FileAnalysis V2.2.1 D20140401
│   │   └── FileAnalysis
│   ├── FiletypeID
│   │   ├── Definitions
│   │   ├── FiletypeID.exe
│   │   ├── FiletypeID.ini
│   │   ├── License.txt
│   │   ├── PyQt4.QtCore.pyd
│   │   ├── PyQt4.QtGui.pyd
│   │   ├── QtCore4.dll
│   │   ├── QtGui4.dll
│   │   ├── ReadMe.txt
│   │   ├── TrIDLib
│   │   ├── _ctypes.pyd
│   │   ├── _hashlib.pyd
│   │   ├── _socket.pyd
│   │   ├── _ssl.pyd
│   │   ├── bz2.pyd
│   │   ├── library.zip
│   │   ├── python27.dll
│   │   ├── sip.pyd
│   │   └── unicodedata.pyd
│   ├── dmg2iso.exe
│   └── foremost文件分离.rar
├── 编码与密码
│   ├── ASCII码随心换v3.0.0.1.exe
│   ├── CTFcrack
│   │   ├── CTFcrack.jar
│   │   ├── Plugin
│   │   ├── Setting.json
│   │   └── girl
│   ├── CyberChef_v9.21.0
│   │   ├── CyberChef_v9.21.0.html
│   │   ├── assets
│   │   ├── images
│   │   └── modules
│   ├── Hash & Crypto Detector v1.4
│   │   ├── AT4RE.nfo
│   │   ├── HCD.exe
│   │   └── Readme.txt
│   ├── JDicTac.jar
│   ├── Keygener_Assistant
│   │   ├── History.txt
│   │   ├── Readme.txt
│   │   └── keyAssistant Remixed.exe
│   ├── PYG密码学综合工具 v5.0.0.5
│   │   ├── PYG.dll
│   │   ├── PYG_TOOLS5.ini
│   │   └── PYG_TOOLS_VER5.exe
│   ├── UNICODE2ANSI.exe
│   ├── Wintools编码转换.exe
│   ├── key_Assistant.exe
│   ├── online-decode
│   │   ├── README.md
│   │   ├── app
│   │   ├── base32_decode.html
│   │   ├── base32_encode.html
│   │   ├── base64_decode.html
│   │   ├── base64_encode.html
│   │   ├── crc16.html
│   │   ├── crc32.html
│   │   ├── crc32_checksum.html
│   │   ├── css
│   │   ├── html_decode.html
│   │   ├── html_encode.html
│   │   ├── index.html
│   │   ├── js
│   │   ├── keccak_224.html
│   │   ├── keccak_256.html
│   │   ├── keccak_384.html
│   │   ├── keccak_512.html
│   │   ├── md2.html
│   │   ├── md4.html
│   │   ├── md5.html
│   │   ├── md5_checksum.html
│   │   ├── sha1.html
│   │   ├── sha1_checksum.html
│   │   ├── sha224.html
│   │   ├── sha256.html
│   │   ├── sha384.html
│   │   ├── sha3_224.html
│   │   ├── sha3_256.html
│   │   ├── sha3_384.html
│   │   ├── sha3_512.html
│   │   ├── sha512.html
│   │   ├── sha512_224.html
│   │   ├── sha512_256.html
│   │   ├── shake_128.html
│   │   ├── shake_256.html
│   │   ├── url_decode.html
│   │   └── url_encode.html
│   ├── 万能字符转换Character1.2.exe
│   ├── 加密与编码合集v1.2
│   │   ├── Qt5Core.dll
│   │   ├── Qt5Gui.dll
│   │   ├── Qt5Widgets.dll
│   │   ├── dict
│   │   ├── icudt52.dll
│   │   ├── icuin52.dll
│   │   ├── icuuc52.dll
│   │   ├── libgcc_s_dw2-1.dll
│   │   ├── libstdc++-6.dll
│   │   ├── libwinpthread-1.dll
│   │   ├── platforms
│   │   ├── 加密与编码小工具v1.2.exe
│   │   └── 更新.txt
│   ├── 加密解密图和方法
│   │   ├── ADFGX加密法.png
│   │   ├── Blue-punch-card-front-horiz.png
│   │   ├── 二进制加密解密法.txt
│   │   ├── 倒叙加密解密.txt
│   │   ├── 凯撒密码加密.jpg
│   │   ├── 培根密码.jpg
│   │   ├── 字母表顺序加密法和反字母表加密法和小键盘加密法.jpg
│   │   ├── 当铺密码.jpg
│   │   ├── 手机键盘加密解密.jpg
│   │   ├── 摩尔密码加密与解密.jpg
│   │   ├── 数字坐标加密字母.png
│   │   ├── 波利比奥斯棋盘.png
│   │   ├── 猪圈密码.png
│   │   ├── 猪圈密码加密解密.jpg
│   │   ├── 电脑键盘QWE加密法.jpg
│   │   ├── 电脑键盘坐标加密.jpg
│   │   ├── 电脑键盘棋盘加密.jpg
│   │   ├── 维吉尼亚.txt
│   │   ├── 维吉尼亚密码.png
│   │   └── 非斯的象形文字翻译图.png
│   ├── 加密解密小玩具.exe
│   ├── 加密解密编码解码工具SENCODE.exe
│   ├── 字典生成
│   │   ├── N.C.P.H社会工程学字典生成器
│   │   ├── 万能钥匙字典生成工具(强).exe
│   │   ├── 亦思社会工程学字典生成器.exe
│   │   ├── 全国各地手机号码段查询.url
│   │   ├── 品轩字典生成器V0.5.exe
│   │   ├── 易优软件-超级字典生成器.exe
│   │   ├── 真空密码字典生成器
│   │   └── 黑刀超级字典生成器.exe
│   ├── 密码
│   │   ├── Code
│   │   ├── DES
│   │   ├── Hash
│   │   ├── MD5
│   │   ├── Office
│   │   ├── PYG密码学综合工具
│   │   ├── RAR
│   │   ├── RSA
│   │   ├── Wireless
│   │   ├── Zip
│   │   ├── asp_encode_decode
│   │   ├── 单表置换碰撞在线解密
│   │   ├── 古典密码
│   │   ├── 古典密码工具
│   │   ├── 序列密码
│   │   └── 词频分析
│   ├── 小葵多功能转换工具.exe
│   ├── 常见密码.txt
│   ├── 编码
│   │   ├── BrainTools.zip
│   │   ├── Brainfuck
│   │   ├── Braintools
│   │   ├── CTF中那些脑洞大开的编码和加密.txt
│   │   ├── GB2312 UNICODE 转换工具.html
│   │   ├── JPK_406.jar
│   │   ├── LoveString
│   │   ├── Shellcode
│   │   ├── jjdecode.html
│   │   ├── 字符ASCII码互转.exe
│   │   ├── 字符信息与二进制(字符串转16进制).exe
│   │   ├── 摩斯电码编码解码.exe
│   │   └── 编码转换工具
│   └── 编码转换.exe
├── 脚本
│   ├── CRC32碰撞
│   │   ├── crc-collision.py
│   │   ├── crc32
│   │   ├── crc32.py
│   │   ├── crc32Collision.py
│   │   └── crc32_4.py
│   ├── PIL.py
│   ├── _常用的小脚本
│   │   ├── bash盲注
│   │   ├── ip_extraction.py
│   │   ├── md5veify.py
│   │   ├── sha1ex6.py
│   │   ├── 二次注入
│   │   └── 盲注
│   ├── file_hex_show.py
│   ├── name_birthday_weak_password.py
│   ├── phpjiami解密
│   │   └── jiemi.php
│   ├── png IDAT顺序修复
│   │   ├── odrrere-final.png
│   │   ├── odrrere-progress.png
│   │   ├── odrrere-start.png
│   │   └── pngIDAT_order_fix.py
│   ├── pngsignature_0x0a_replace_0x0d0a.py
│   ├── qr_gen.py
│   ├── read_LSB.py
│   ├── read_png_datablock.py
│   ├── zlib
│   │   ├── zlib.py
│   │   └── zlib_decompress.py
│   ├── 反相
│   │   ├── Inverting.py
│   │   ├── input.png
│   │   └── output_inverted.png
│   ├── 正则表达式
│   │   └── RegexTester.exe
│   └── 简单替换破解
│       └── break.py
├── 逆向
│   ├── 010_Editor_11
│   │   ├── 010EditorWin64Installer11.0.exe
│   │   └── 010editor-patch.zip
│   ├── C32Asm
│   │   ├── Bmp
│   │   ├── C32ASM.INI
│   │   ├── C32Asm.exe
│   │   ├── KeyWord
│   │   ├── LANGUAGE
│   │   ├── PeSave
│   │   ├── Symbol
│   │   ├── plugs
│   │   └── 修改记录.txt
│   ├── ExeinfoPe
│   │   ├── ExeinfoPe.zip
│   │   ├── Ext_Detector.dll
│   │   ├── exeinfope.exe
│   │   ├── exeinfopeRUN.cfg
│   │   ├── file_id.diz
│   │   ├── languages
│   │   ├── plugins
│   │   ├── scripts
│   │   ├── skins
│   │   └── userdb.txt
│   ├── IDA
│   │   ├── IDA Pro 7.5 SP3.zip
│   │   └── IDA_插件
│   ├── JPEXSFreeFlashDecompiler
│   │   ├── ffdec_9.0.0_setup.exe
│   │   └── 使用说明.txt
│   ├── PEID
│   │   ├── 173绿色软件.url
│   │   ├── 173软件下载.txt
│   │   ├── HA.PEiD.0.95
│   │   └── ha.peid.0.95.rar
│   ├── WinHex
│   │   ├── linholer.txt
│   │   ├── winhex19.3 SR-4 x86 x64
│   │   ├── winhex19.3 SR-4 x86 x64.zip
│   │   └── 中文补丁
│   ├── dex2jar
│   │   ├── d2j-dex2jar.bat
│   │   └── d2j-dex2jar.sh
│   ├── dex2jar-2.0
│   │   ├── classes-error.zip
│   │   ├── d2j-baksmali.bat
│   │   ├── d2j-baksmali.sh
│   │   ├── d2j-dex-recompute-checksum.bat
│   │   ├── d2j-dex-recompute-checksum.sh
│   │   ├── d2j-dex2jar.bat
│   │   ├── d2j-dex2jar.sh
│   │   ├── d2j-dex2smali.bat
│   │   ├── d2j-dex2smali.sh
│   │   ├── d2j-jar2dex.bat
│   │   ├── d2j-jar2dex.sh
│   │   ├── d2j-jar2jasmin.bat
│   │   ├── d2j-jar2jasmin.sh
│   │   ├── d2j-jasmin2jar.bat
│   │   ├── d2j-jasmin2jar.sh
│   │   ├── d2j-smali.bat
│   │   ├── d2j-smali.sh
│   │   ├── d2j-std-apk.bat
│   │   ├── d2j-std-apk.sh
│   │   ├── d2j_invoke.bat
│   │   └── d2j_invoke.sh
│   ├── dnSpy-netcore-win64
│   │   ├── Accessibility.dll
│   │   ├── CSharpInteractive.rsp
│   │   ├── D3DCompiler_47_cor3.dll
│   │   ├── DirectWriteForwarder.dll
│   │   ├── FileLists
│   │   ├── Humanizer.dll
│   │   ├── ICSharpCode.Decompiler.dll
│   │   ├── ICSharpCode.Decompiler.pdb
│   │   ├── ICSharpCode.NRefactory.CSharp.dll
│   │   ├── ICSharpCode.NRefactory.CSharp.pdb
│   │   ├── ICSharpCode.NRefactory.VB.dll
│   │   ├── ICSharpCode.NRefactory.VB.pdb
│   │   ├── ICSharpCode.NRefactory.dll
│   │   ├── ICSharpCode.NRefactory.pdb
│   │   ├── ICSharpCode.TreeView.dll
│   │   ├── ICSharpCode.TreeView.pdb
│   │   ├── Iced.dll
│   │   ├── LicenseInfo
│   │   ├── Microsoft.CSharp.dll
│   │   ├── Microsoft.CodeAnalysis.CSharp.ExpressionEvaluator.dll
│   │   ├── Microsoft.CodeAnalysis.CSharp.ExpressionEvaluator.pdb
│   │   ├── Microsoft.CodeAnalysis.CSharp.Features.dll
│   │   ├── Microsoft.CodeAnalysis.CSharp.Scripting.dll
│   │   ├── Microsoft.CodeAnalysis.CSharp.Workspaces.dll
│   │   ├── Microsoft.CodeAnalysis.CSharp.dll
│   │   ├── Microsoft.CodeAnalysis.ExpressionEvaluator.dll
│   │   ├── Microsoft.CodeAnalysis.ExpressionEvaluator.pdb
│   │   ├── Microsoft.CodeAnalysis.Features.dll
│   │   ├── Microsoft.CodeAnalysis.Scripting.dll
│   │   ├── Microsoft.CodeAnalysis.VisualBasic.ExpressionEvaluator.dll
│   │   ├── Microsoft.CodeAnalysis.VisualBasic.ExpressionEvaluator.pdb
│   │   ├── Microsoft.CodeAnalysis.VisualBasic.Features.dll
│   │   ├── Microsoft.CodeAnalysis.VisualBasic.Workspaces.dll
│   │   ├── Microsoft.CodeAnalysis.VisualBasic.dll
│   │   ├── Microsoft.CodeAnalysis.Workspaces.dll
│   │   ├── Microsoft.CodeAnalysis.dll
│   │   ├── Microsoft.DiaSymReader.Native.amd64.dll
│   │   ├── Microsoft.Diagnostics.Runtime.dll
│   │   ├── Microsoft.VisualBasic.Core.dll
│   │   ├── Microsoft.VisualBasic.dll
│   │   ├── Microsoft.VisualStudio.Composition.NetFxAttributes.dll
│   │   ├── Microsoft.VisualStudio.Composition.dll
│   │   ├── Microsoft.VisualStudio.CoreUtility.dll
│   │   ├── Microsoft.VisualStudio.Language.Intellisense.dll
│   │   ├── Microsoft.VisualStudio.Text.Data.dll
│   │   ├── Microsoft.VisualStudio.Text.Logic.dll
│   │   ├── Microsoft.VisualStudio.Text.UI.Wpf.dll
│   │   ├── Microsoft.VisualStudio.Text.UI.dll
│   │   ├── Microsoft.VisualStudio.Validation.dll
│   │   ├── Microsoft.Win32.Primitives.dll
│   │   ├── Microsoft.Win32.Registry.dll
│   │   ├── Microsoft.Win32.SystemEvents.dll
│   │   ├── Mono.Debugger.Soft.dll
│   │   ├── Mono.Debugger.Soft.pdb
│   │   ├── Ookii.Dialogs.Wpf.dll
│   │   ├── PenImc_cor3.dll
│   │   ├── PresentationCore-CommonResources.dll
│   │   ├── PresentationCore.dll
│   │   ├── PresentationFramework-SystemCore.dll
│   │   ├── PresentationFramework-SystemData.dll
│   │   ├── PresentationFramework-SystemDrawing.dll
│   │   ├── PresentationFramework-SystemXml.dll
│   │   ├── PresentationFramework-SystemXmlLinq.dll
│   │   ├── PresentationFramework.Aero.dll
│   │   ├── PresentationFramework.Aero2.dll
│   │   ├── PresentationFramework.AeroLite.dll
│   │   ├── PresentationFramework.Classic.dll
│   │   ├── PresentationFramework.Luna.dll
│   │   ├── PresentationFramework.Royale.dll
│   │   ├── PresentationFramework.dll
│   │   ├── PresentationNative_cor3.dll
│   │   ├── PresentationUI.dll
│   │   ├── ReachFramework.dll
│   │   ├── SOS.NETCore.dll
│   │   ├── System.AppContext.dll
│   │   ├── System.Buffers.dll
│   │   ├── System.CodeDom.dll
│   │   ├── System.Collections.Concurrent.dll
│   │   ├── System.Collections.Immutable.dll
│   │   ├── System.Collections.NonGeneric.dll
│   │   ├── System.Collections.Specialized.dll
│   │   ├── System.Collections.dll
│   │   ├── System.ComponentModel.Annotations.dll
│   │   ├── System.ComponentModel.Composition.dll
│   │   ├── System.ComponentModel.DataAnnotations.dll
│   │   ├── System.ComponentModel.EventBasedAsync.dll
│   │   ├── System.ComponentModel.Primitives.dll
│   │   ├── System.ComponentModel.TypeConverter.dll
│   │   ├── System.ComponentModel.dll
│   │   ├── System.Composition.AttributedModel.dll
│   │   ├── System.Composition.Convention.dll
│   │   ├── System.Composition.Hosting.dll
│   │   ├── System.Composition.Runtime.dll
│   │   ├── System.Composition.TypedParts.dll
│   │   ├── System.Configuration.ConfigurationManager.dll
│   │   ├── System.Configuration.dll
│   │   ├── System.Console.dll
│   │   ├── System.Core.dll
│   │   ├── System.Data.Common.dll
│   │   ├── System.Data.DataSetExtensions.dll
│   │   ├── System.Data.dll
│   │   ├── System.Design.dll
│   │   ├── System.Diagnostics.Contracts.dll
│   │   ├── System.Diagnostics.Debug.dll
│   │   ├── System.Diagnostics.DiagnosticSource.dll
│   │   ├── System.Diagnostics.EventLog.dll
│   │   ├── System.Diagnostics.FileVersionInfo.dll
│   │   ├── System.Diagnostics.Process.dll
│   │   ├── System.Diagnostics.StackTrace.dll
│   │   ├── System.Diagnostics.TextWriterTraceListener.dll
│   │   ├── System.Diagnostics.Tools.dll
│   │   ├── System.Diagnostics.TraceSource.dll
│   │   ├── System.Diagnostics.Tracing.dll
│   │   ├── System.DirectoryServices.dll
│   │   ├── System.Drawing.Common.dll
│   │   ├── System.Drawing.Design.dll
│   │   ├── System.Drawing.Primitives.dll
│   │   ├── System.Drawing.dll
│   │   ├── System.Dynamic.Runtime.dll
│   │   ├── System.Globalization.Calendars.dll
│   │   ├── System.Globalization.Extensions.dll
│   │   ├── System.Globalization.dll
│   │   ├── System.IO.Compression.Brotli.dll
│   │   ├── System.IO.Compression.FileSystem.dll
│   │   ├── System.IO.Compression.ZipFile.dll
│   │   ├── System.IO.Compression.dll
│   │   ├── System.IO.FileSystem.AccessControl.dll
│   │   ├── System.IO.FileSystem.DriveInfo.dll
│   │   ├── System.IO.FileSystem.Primitives.dll
│   │   ├── System.IO.FileSystem.Watcher.dll
│   │   ├── System.IO.FileSystem.dll
│   │   ├── System.IO.IsolatedStorage.dll
│   │   ├── System.IO.MemoryMappedFiles.dll
│   │   ├── System.IO.Packaging.dll
│   │   ├── System.IO.Pipes.AccessControl.dll
│   │   ├── System.IO.Pipes.dll
│   │   ├── System.IO.UnmanagedMemoryStream.dll
│   │   ├── System.IO.dll
│   │   ├── System.Linq.Expressions.dll
│   │   ├── System.Linq.Parallel.dll
│   │   ├── System.Linq.Queryable.dll
│   │   ├── System.Linq.dll
│   │   ├── System.Memory.dll
│   │   ├── System.Net.Http.dll
│   │   ├── System.Net.HttpListener.dll
│   │   ├── System.Net.Mail.dll
│   │   ├── System.Net.NameResolution.dll
│   │   ├── System.Net.NetworkInformation.dll
│   │   ├── System.Net.Ping.dll
│   │   ├── System.Net.Primitives.dll
│   │   ├── System.Net.Requests.dll
│   │   ├── System.Net.Security.dll
│   │   ├── System.Net.ServicePoint.dll
│   │   ├── System.Net.Sockets.dll
│   │   ├── System.Net.WebClient.dll
│   │   ├── System.Net.WebHeaderCollection.dll
│   │   ├── System.Net.WebProxy.dll
│   │   ├── System.Net.WebSockets.Client.dll
│   │   ├── System.Net.WebSockets.dll
│   │   ├── System.Net.dll
│   │   ├── System.Numerics.Vectors.dll
│   │   ├── System.Numerics.dll
│   │   ├── System.ObjectModel.dll
│   │   ├── System.Printing.dll
│   │   ├── System.Private.CoreLib.dll
│   │   ├── System.Private.DataContractSerialization.dll
│   │   ├── System.Private.Uri.dll
│   │   ├── System.Private.Xml.Linq.dll
│   │   ├── System.Private.Xml.dll
│   │   ├── System.Reflection.DispatchProxy.dll
│   │   ├── System.Reflection.Emit.ILGeneration.dll
│   │   ├── System.Reflection.Emit.Lightweight.dll
│   │   ├── System.Reflection.Emit.dll
│   │   ├── System.Reflection.Extensions.dll
│   │   ├── System.Reflection.Metadata.dll
│   │   ├── System.Reflection.Primitives.dll
│   │   ├── System.Reflection.TypeExtensions.dll
│   │   ├── System.Reflection.dll
│   │   ├── System.Resources.Reader.dll
│   │   ├── System.Resources.ResourceManager.dll
│   │   ├── System.Resources.Writer.dll
│   │   ├── System.Runtime.CompilerServices.Unsafe.dll
│   │   ├── System.Runtime.CompilerServices.VisualC.dll
│   │   ├── System.Runtime.Extensions.dll
│   │   ├── System.Runtime.Handles.dll
│   │   ├── System.Runtime.InteropServices.RuntimeInformation.dll
│   │   ├── System.Runtime.InteropServices.WindowsRuntime.dll
│   │   ├── System.Runtime.InteropServices.dll
│   │   ├── System.Runtime.Intrinsics.dll
│   │   ├── System.Runtime.Loader.dll
│   │   ├── System.Runtime.Numerics.dll
│   │   ├── System.Runtime.Serialization.Formatters.dll
│   │   ├── System.Runtime.Serialization.Json.dll
│   │   ├── System.Runtime.Serialization.Primitives.dll
│   │   ├── System.Runtime.Serialization.Xml.dll
│   │   ├── System.Runtime.Serialization.dll
│   │   ├── System.Runtime.WindowsRuntime.UI.Xaml.dll
│   │   ├── System.Runtime.WindowsRuntime.dll
│   │   ├── System.Runtime.dll
│   │   ├── System.Security.AccessControl.dll
│   │   ├── System.Security.Claims.dll
│   │   ├── System.Security.Cryptography.Algorithms.dll
│   │   ├── System.Security.Cryptography.Cng.dll
│   │   ├── System.Security.Cryptography.Csp.dll
│   │   ├── System.Security.Cryptography.Encoding.dll
│   │   ├── System.Security.Cryptography.OpenSsl.dll
│   │   ├── System.Security.Cryptography.Pkcs.dll
│   │   ├── System.Security.Cryptography.Primitives.dll
│   │   ├── System.Security.Cryptography.ProtectedData.dll
│   │   ├── System.Security.Cryptography.X509Certificates.dll
│   │   ├── System.Security.Cryptography.Xml.dll
│   │   ├── System.Security.Permissions.dll
│   │   ├── System.Security.Principal.Windows.dll
│   │   ├── System.Security.Principal.dll
│   │   ├── System.Security.SecureString.dll
│   │   ├── System.Security.dll
│   │   ├── System.ServiceModel.Web.dll
│   │   ├── System.ServiceProcess.dll
│   │   ├── System.Text.Encoding.CodePages.dll
│   │   ├── System.Text.Encoding.Extensions.dll
│   │   ├── System.Text.Encoding.dll
│   │   ├── System.Text.Json.dll
│   │   ├── System.Text.RegularExpressions.dll
│   │   ├── System.Threading.AccessControl.dll
│   │   ├── System.Threading.Overlapped.dll
│   │   ├── System.Threading.Tasks.Dataflow.dll
│   │   ├── System.Threading.Tasks.Extensions.dll
│   │   ├── System.Threading.Tasks.Parallel.dll
│   │   ├── System.Threading.Tasks.dll
│   │   ├── System.Threading.Thread.dll
│   │   ├── System.Threading.ThreadPool.dll
│   │   ├── System.Threading.Timer.dll
│   │   ├── System.Threading.dll
│   │   ├── System.Transactions.Local.dll
│   │   ├── System.Transactions.dll
│   │   ├── System.ValueTuple.dll
│   │   ├── System.Web.HttpUtility.dll
│   │   ├── System.Web.dll
│   │   ├── System.Windows.Controls.Ribbon.dll
│   │   ├── System.Windows.Extensions.dll
│   │   ├── System.Windows.Forms.Design.Editors.dll
│   │   ├── System.Windows.Forms.Design.dll
│   │   ├── System.Windows.Forms.dll
│   │   ├── System.Windows.Input.Manipulations.dll
│   │   ├── System.Windows.Presentation.dll
│   │   ├── System.Windows.dll
│   │   ├── System.Xaml.dll
│   │   ├── System.Xml.Linq.dll
│   │   ├── System.Xml.ReaderWriter.dll
│   │   ├── System.Xml.Serialization.dll
│   │   ├── System.Xml.XDocument.dll
│   │   ├── System.Xml.XPath.XDocument.dll
│   │   ├── System.Xml.XPath.dll
│   │   ├── System.Xml.XmlDocument.dll
│   │   ├── System.Xml.XmlSerializer.dll
│   │   ├── System.Xml.dll
│   │   ├── System.dll
│   │   ├── Themes
│   │   ├── UIAutomationClient.dll
│   │   ├── UIAutomationClientSideProviders.dll
│   │   ├── UIAutomationProvider.dll
│   │   ├── UIAutomationTypes.dll
│   │   ├── WindowsBase.dll
│   │   ├── WindowsFormsIntegration.dll
│   │   ├── api-ms-win-core-console-l1-1-0.dll
│   │   ├── api-ms-win-core-datetime-l1-1-0.dll
│   │   ├── api-ms-win-core-debug-l1-1-0.dll
│   │   ├── api-ms-win-core-errorhandling-l1-1-0.dll
│   │   ├── api-ms-win-core-file-l1-1-0.dll
│   │   ├── api-ms-win-core-file-l1-2-0.dll
│   │   ├── api-ms-win-core-file-l2-1-0.dll
│   │   ├── api-ms-win-core-handle-l1-1-0.dll
│   │   ├── api-ms-win-core-heap-l1-1-0.dll
│   │   ├── api-ms-win-core-interlocked-l1-1-0.dll
│   │   ├── api-ms-win-core-libraryloader-l1-1-0.dll
│   │   ├── api-ms-win-core-localization-l1-2-0.dll
│   │   ├── api-ms-win-core-memory-l1-1-0.dll
│   │   ├── api-ms-win-core-namedpipe-l1-1-0.dll
│   │   ├── api-ms-win-core-processenvironment-l1-1-0.dll
│   │   ├── api-ms-win-core-processthreads-l1-1-0.dll
│   │   ├── api-ms-win-core-processthreads-l1-1-1.dll
│   │   ├── api-ms-win-core-profile-l1-1-0.dll
│   │   ├── api-ms-win-core-rtlsupport-l1-1-0.dll
│   │   ├── api-ms-win-core-string-l1-1-0.dll
│   │   ├── api-ms-win-core-synch-l1-1-0.dll
│   │   ├── api-ms-win-core-synch-l1-2-0.dll
│   │   ├── api-ms-win-core-sysinfo-l1-1-0.dll
│   │   ├── api-ms-win-core-timezone-l1-1-0.dll
│   │   ├── api-ms-win-core-util-l1-1-0.dll
│   │   ├── api-ms-win-crt-conio-l1-1-0.dll
│   │   ├── api-ms-win-crt-convert-l1-1-0.dll
│   │   ├── api-ms-win-crt-environment-l1-1-0.dll
│   │   ├── api-ms-win-crt-filesystem-l1-1-0.dll
│   │   ├── api-ms-win-crt-heap-l1-1-0.dll
│   │   ├── api-ms-win-crt-locale-l1-1-0.dll
│   │   ├── api-ms-win-crt-math-l1-1-0.dll
│   │   ├── api-ms-win-crt-multibyte-l1-1-0.dll
│   │   ├── api-ms-win-crt-private-l1-1-0.dll
│   │   ├── api-ms-win-crt-process-l1-1-0.dll
│   │   ├── api-ms-win-crt-runtime-l1-1-0.dll
│   │   ├── api-ms-win-crt-stdio-l1-1-0.dll
│   │   ├── api-ms-win-crt-string-l1-1-0.dll
│   │   ├── api-ms-win-crt-time-l1-1-0.dll
│   │   ├── api-ms-win-crt-utility-l1-1-0.dll
│   │   ├── clrcompression.dll
│   │   ├── clretwrc.dll
│   │   ├── clrjit.dll
│   │   ├── coreclr.dll
│   │   ├── dbgshim.dll
│   │   ├── de
│   │   ├── debug
│   │   ├── dnSpy.Analyzer.x.deps.json
│   │   ├── dnSpy.Analyzer.x.dll
│   │   ├── dnSpy.Analyzer.x.pdb
│   │   ├── dnSpy.AsmEditor.x.deps.json
│   │   ├── dnSpy.AsmEditor.x.dll
│   │   ├── dnSpy.AsmEditor.x.pdb
│   │   ├── dnSpy.BamlDecompiler.x.deps.json
│   │   ├── dnSpy.BamlDecompiler.x.dll
│   │   ├── dnSpy.BamlDecompiler.x.pdb
│   │   ├── dnSpy.Console.deps.json
│   │   ├── dnSpy.Console.dll
│   │   ├── dnSpy.Console.dll.config
│   │   ├── dnSpy.Console.exe
│   │   ├── dnSpy.Console.pdb
│   │   ├── dnSpy.Console.runtimeconfig.json
│   │   ├── dnSpy.Contracts.Debugger.DotNet.CorDebug.dll
│   │   ├── dnSpy.Contracts.Debugger.DotNet.CorDebug.pdb
│   │   ├── dnSpy.Contracts.Debugger.DotNet.CorDebug.xml
│   │   ├── dnSpy.Contracts.Debugger.DotNet.Mono.dll
│   │   ├── dnSpy.Contracts.Debugger.DotNet.Mono.pdb
│   │   ├── dnSpy.Contracts.Debugger.DotNet.Mono.xml
│   │   ├── dnSpy.Contracts.Debugger.DotNet.dll
│   │   ├── dnSpy.Contracts.Debugger.DotNet.pdb
│   │   ├── dnSpy.Contracts.Debugger.DotNet.xml
│   │   ├── dnSpy.Contracts.Debugger.dll
│   │   ├── dnSpy.Contracts.Debugger.pdb
│   │   ├── dnSpy.Contracts.Debugger.xml
│   │   ├── dnSpy.Contracts.DnSpy.dll
│   │   ├── dnSpy.Contracts.DnSpy.pdb
│   │   ├── dnSpy.Contracts.DnSpy.xml
│   │   ├── dnSpy.Contracts.Logic.dll
│   │   ├── dnSpy.Contracts.Logic.pdb
│   │   ├── dnSpy.Contracts.Logic.xml
│   │   ├── dnSpy.Debugger.DotNet.CorDebug.x.deps.json
│   │   ├── dnSpy.Debugger.DotNet.CorDebug.x.dll
│   │   ├── dnSpy.Debugger.DotNet.CorDebug.x.pdb
│   │   ├── dnSpy.Debugger.DotNet.Interpreter.dll
│   │   ├── dnSpy.Debugger.DotNet.Interpreter.pdb
│   │   ├── dnSpy.Debugger.DotNet.Interpreter.xml
│   │   ├── dnSpy.Debugger.DotNet.Metadata.dll
│   │   ├── dnSpy.Debugger.DotNet.Metadata.pdb
│   │   ├── dnSpy.Debugger.DotNet.Metadata.xml
│   │   ├── dnSpy.Debugger.DotNet.Mono.x.deps.json
│   │   ├── dnSpy.Debugger.DotNet.Mono.x.dll
│   │   ├── dnSpy.Debugger.DotNet.Mono.x.pdb
│   │   ├── dnSpy.Debugger.DotNet.x.deps.json
│   │   ├── dnSpy.Debugger.DotNet.x.dll
│   │   ├── dnSpy.Debugger.DotNet.x.pdb
│   │   ├── dnSpy.Debugger.x.deps.json
│   │   ├── dnSpy.Debugger.x.dll
│   │   ├── dnSpy.Debugger.x.pdb
│   │   ├── dnSpy.Decompiler.ILSpy.Core.dll
│   │   ├── dnSpy.Decompiler.ILSpy.Core.pdb
│   │   ├── dnSpy.Decompiler.ILSpy.x.deps.json
│   │   ├── dnSpy.Decompiler.ILSpy.x.dll
│   │   ├── dnSpy.Decompiler.ILSpy.x.pdb
│   │   ├── dnSpy.Decompiler.dll
│   │   ├── dnSpy.Decompiler.pdb
│   │   ├── dnSpy.Images.dll
│   │   ├── dnSpy.Images.pdb
│   │   ├── dnSpy.Roslyn.CSharp.EditorFeatures.dll
│   │   ├── dnSpy.Roslyn.CSharp.EditorFeatures.pdb
│   │   ├── dnSpy.Roslyn.CSharp.Internal.dll
│   │   ├── dnSpy.Roslyn.CSharp.Internal.pdb
│   │   ├── dnSpy.Roslyn.EditorFeatures.dll
│   │   ├── dnSpy.Roslyn.EditorFeatures.pdb
│   │   ├── dnSpy.Roslyn.Internal.dll
│   │   ├── dnSpy.Roslyn.Internal.pdb
│   │   ├── dnSpy.Roslyn.VisualBasic.EditorFeatures.dll
│   │   ├── dnSpy.Roslyn.VisualBasic.EditorFeatures.pdb
│   │   ├── dnSpy.Roslyn.VisualBasic.Internal.dll
│   │   ├── dnSpy.Roslyn.VisualBasic.Internal.pdb
│   │   ├── dnSpy.Roslyn.dll
│   │   ├── dnSpy.Roslyn.pdb
│   │   ├── dnSpy.Roslyn.xml
│   │   ├── dnSpy.Scripting.Roslyn.x.deps.json
│   │   ├── dnSpy.Scripting.Roslyn.x.dll
│   │   ├── dnSpy.Scripting.Roslyn.x.pdb
│   │   ├── dnSpy.deps.json
│   │   ├── dnSpy.dll
│   │   ├── dnSpy.dll.config
│   │   ├── dnSpy.exe
│   │   ├── dnSpy.pdb
│   │   ├── dnSpy.runtimeconfig.json
│   │   ├── dnlib.dll
│   │   ├── es
│   │   ├── es-ES
│   │   ├── fa
│   │   ├── fr
│   │   ├── hostfxr.dll
│   │   ├── hostpolicy.dll
│   │   ├── hu
│   │   ├── it
│   │   ├── mscordaccore.dll
│   │   ├── mscordaccore_amd64_amd64_4.6.27622.75.dll
│   │   ├── mscordbi.dll
│   │   ├── mscorlib.dll
│   │   ├── mscorrc.debug.dll
│   │   ├── mscorrc.dll
│   │   ├── netstandard.dll
│   │   ├── pt-PT
│   │   ├── ru
│   │   ├── sos.dll
│   │   ├── sos_amd64_amd64_4.6.27622.75.dll
│   │   ├── tr
│   │   ├── ucrtbase.dll
│   │   ├── uk
│   │   ├── vcruntime140_cor3.dll
│   │   ├── wpfgfx_cor3.dll
│   │   └── zh-CN
│   ├── jd-gui1.6
│   │   ├── classes-dex2jar.jar
│   │   └── jd-gui-1.6.3.jar
│   ├── upx
│   │   └── upx-3.96-win64.zip
│   └── 吾爱破解专用版Ollydbg
│       ├── DBGHELP.DLL
│       ├── ICO
│       ├── LIB
│       ├── LoadDll.dll
│       ├── Loaddll.exe
│       ├── OLLYDBG.HLP
│       ├── OllyDBG.EXE
│       ├── UDD
│       ├── Udd Cleaner.exe
│       ├── ollydbg.ini
│       ├── ollydbg_白底黑字配置.ini
│       ├── plugin
│       ├── 使用说明.txt
│       ├── 原版
│       ├── 吾爱破解[LCG].exe
│       └── 路径修复工具.exe
└── 隐写
    ├── Andriod
    │   ├── ImgHid and Reveal
    │   ├── My Secret
    │   └── StegDroid0.75.apk
    ├── FileSystem
    │   └── ntfs流隐写
    ├── Html隐写.txt
    ├── IOS
    │   ├── InvisiLetter
    │   ├── Spy Pix
    │   └── Stego Sec
    ├── OpenPuff
    │   ├── OpenPuff.exe
    │   ├── OpenPuff_license.txt
    │   ├── html
    │   ├── libObfuscate.dll
    │   └── libObfuscate_license.txt
    ├── PDF隐写
    │   ├── OWASP TOP10.pdf
    │   ├── PDFStreamDumper_Setup.exe
    │   ├── PDFTemplate.zip
    │   ├── kali_pdfto.txt
    │   ├── make-pdf_V0_1_6.zip
    │   ├── pdf-parser_V0_6_5.py
    │   ├── pdf-parser_V0_6_5.zip
    │   ├── pdfid_v0_2_1
    │   ├── pdfid_v0_2_1.zip
    │   ├── pdfxray_lite-master.zip
    │   ├── peepdf_0.3.zip
    │   ├── wbs43open-win32
    │   └── wbs43open-win32.zip
    ├── Rizzy
    │   ├── COPYING
    │   ├── README
    │   ├── rizzy.glade
    │   ├── rizzy.py
    │   ├── rizzy.xml
    │   ├── rstep.py
    │   └── stepic.py
    ├── StegSpy2.1
    │   ├── Comdlg32.ocx
    │   └── StegSpy2.1.exe
    ├── StegoStick
    │   ├── EndUser Version
    │   └── Source Code
    ├── openstego
    │   ├── LICENSE
    │   ├── README
    │   ├── build
    │   ├── build.xml
    │   ├── doc
    │   ├── installer.nsi
    │   ├── lib
    │   ├── msb_examples
    │   ├── openstego.bat
    │   ├── openstego.sh
    │   └── src
    ├── s-tools4
    │   ├── 1000046611283.bmp
    │   ├── GIFutil.dll
    │   ├── S-Tools.exe
    │   ├── S-Tools.hlp
    │   ├── cryptlib.dll
    │   ├── new.bmp
    │   └── zlib.dll
    ├── 可执行文件隐写
    │   ├── hydan
    │   └── hydan-0.13.tar.gz
    ├── 各种格式的文件头.doc
    ├── 图像隐写
    │   ├── 1.py
    │   ├── BlindWaterMark
    │   ├── CameraShy.0.2.23.1.exe
    │   ├── CoagulaLight1666
    │   ├── Exif Tag Remover.rar
    │   ├── F5
    │   ├── Filters
    │   ├── GifSplitter 2.0
    │   ├── IHDR.py
    │   ├── Image Steganography
    │   ├── Image Steganography Setup.exe
    │   ├── ImageHide.EXE
    │   ├── JCS.jar
    │   ├── LSB
    │   ├── Namo Gif Animator.exe
    │   ├── Outguess Rebirth_1-3
    │   ├── PNG-Steganography
    │   ├── StegoTool
    │   ├── Stegsolve.jar
    │   ├── busysteg-master
    │   ├── exiftool-18.25
    │   ├── gifshuffle-win-bin.zip
    │   ├── hinaLayer
    │   ├── jpeg-v4.tar.gz
    │   ├── jpgx211
    │   ├── jphs_05
    │   ├── mandsteg-10.tar.gz
    │   ├── openstego-0.6.1
    │   ├── outguess-0.2.tar.gz
    │   ├── png-debugger
    │   ├── pngcheck-2.3.0-win32
    │   ├── steganabara-1.1.1.tar.gz
    │   ├── stegdetect-0.4-windows
    │   ├── steghide
    │   ├── tweakpng-1.4.6
    │   ├── vsl-1.1
    │   ├── wbs43open-win32
    │   ├── wbs43open-win32.zip
    │   ├── 二维码
    │   ├── 拼图
    │   ├── 深入理解JPEG图像格式Jphide隐写.html
    │   └── 盲水印
    ├── 在线工具.txt
    ├── 必看书籍
    │   └── 数据隐藏技术揭秘：破解多媒体、操作系统、移动设备和网络协议中的隐秘数据.pdf
    ├── 视频隐写
    │   ├── AVI
    │   ├── DeEggerSetup131.msi
    │   ├── MP4 QuickTime
    │   └── ffmpeg-latest-win32-static
    ├── 隐写和数字水印工具表.txt
    └── 音频隐写
        ├── audacity-win-2-1-2.exe
        ├── mp3stego-gui
        ├── mp3stego-gui.zip
        └── silenteye-0.4.1-win32.exe
```

