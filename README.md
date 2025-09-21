在线工具箱项目修改左下角友情链接： Github | Blog文件路径:application→index→view→link.html
pixpro图床修改文件路径:public_html→index.php

### 音乐播放器
music-player项目添加域名时选择类型为Node.js，上传项目文件压缩包到public_nodejs文件夹里，ssh里cd到domains/域名/public_nodejs文件夹安装依赖npm install后重启站点
修改歌单api地此文件路径：域名/public_nodejs/public/static/js/player.js和get_music_list.js，修改管理密码文件app.js

```
cd domains/域名/public_nodejs
```
```
npm install
```
```
devil www restart 域名
```
### 应用程序
应用分音量
```
EarTrumpet
```
任务栏透明化
```
TranslucentTB
```
浏览器
```
Borderfree
```
软件卸载
```
geek
```
內存清理
```
Mem Reduct
```
C盘清理工具
```
PrivaZer
```

### Google Cloud谷歌云临时vps
打开链接
```
https://accounts.google.com/v3/signin/identifier?continue=
https%3A%2F%2Fconsole.cloud.google.com%2F&followup=
https%3A%2F%2Fconsole.cloud.google.com%2F&ifkv=
AeZLP9-0IQSq05xeTMuW_HTDcW960bBquuu4bZzNRa3Y1JiTKCW9rsteltb
7DqePmwSSYv987u3_oA&osid=1&passive=
1209600&service=cloudconsole&flowName=
GlifWebSignIn&flowEntry=ServiceLogin&dsh=
S-550021044%3A1734529949831903&ddm=1
```
点击右上角的“激活Cloud Shell”  输入命令：
```
docker run -p 8080:80 dorowu/ubuntu-desktop-lxde-vnc
```
等命令运行完打开终端右上的“网页预览”，会新打开一网页
然后点击左下角，选择Ineernet-Firefox Web Brower

### 谷歌邮箱申诉模版
```
I am a Chinese user, and I cannot access Google Play 
because my device does not have the GMS 
environment and Internet connection. 
I really need Google Play and those apps which depend on GMS. 
I have not done anything that may violate 
Google's policy and could you please resume my account? Thanks a lot！
```
### 谷歌邮箱
```
zxlwq919@outlook.com
```
```                                     
zxlwq919@gmail.com
```
```
zxlwqa@gmail.com
```
```        
zxlwqg@gmail.com
```
```
zxlwqe@gmail.com
```
```
zxIwqc@gmail.com
```
```
zxlwqd@gmail.com
```
```    
zxlwqv@gmail.com
```
```
zxlwqt@gmail.com
```
s16 hsdjkfo
```
zxlwqn@gmail.com
```
```    
zxlwqm@gmail.com
```
```
zxlwq@protonmail.com
```
```
zxlwq919@163.com
```
```       
ntpjk353@hotmail.com
```
```       
ykwbz685@hotmail.com
```
### 微软邮箱    
```        
axmfp870@hotmail.com
```
```
xfeaq311@hotmail.com
```
```
quvzw372@hotmail.com
```
```
ybfgu229@hotmail.com
```
```
yxhpj733@hotmail.com
```
```
jmexe387@hotmail.com
```
IDM不能将下载行为传输到IDM的解决方法
IDM选项设置里取消高级浏览器集成 
关闭IDM 再右键以管理员身份运行IDM

### Chrome浏览器
Chrome 设置暗夜和多线程下载
```
chrome://flags/
```
暗夜模式:
```
dark mode
```
多线程下载:
```
Parallel downloading
```

### AList
下载AList 开源项目地址：
```
https://github.com/alist-org/alist
```
解压到磁盘后在AList.exe路径栏输入CMD进入后输入
```
alist server
```
回车连接网络后password is:复制登录密码，浏览器输入 127.0.0.1:5244 回车登录后，修改密码
开机自启，新建文本文件输入
```
Set ws = CreateObject("Wscript.Shell")
ws.run "AList.exe文件所在路径\alist.exe server",vbhide
```
扩展名为.VBS后，创建一个.VBS快捷方式，Win+r进入开机自启动文件夹 
```
shell:startup
```
把快捷方式放进去
PotPlayer挂载AList，新建专辑—协议“WebDAV”主机IP 
```
127.0.0.1/dav
```
端口:5244，用户名，密码


### 删除Windows10自带浏览器
复制浏览器文件所在路经，打开CMD输入CD空格粘贴路径
在下面粘贴命令：
```
setup.exe --uninstall --system-level --verbose-logging --force-uninstall
```
删除Microsoft里所有文件
显示无法删除，任务管理器结束进程

### 关闭Windows安全中心
Antimalware Service Executable占内存
打开Windows PowerShell管理员粘贴命令
```
reg add "HKEY_LOCAL_MACHINE\SOFTWARE
\Policies\Microsoft\Windows Defender" 
/v "DisableAntiSpyware" /d 1 /t REG_DWORD /f
```
   
### C盘清理
搜索  
```
%temp%
```  
文件夹里全删除
```
C:\Windows\SoftwareDistribution\Download
```
文件夹里全删除
Win+R 输入  
```
prefetch
```
文件夹里全删除
          
### 微软商店重置缓存无法下载
打开CMD输入 
```
WSreset.exe
```
```
ipconfig /flushdns
```
微软商店无网络
开始—设置—网络和lntemet—网络和共享中心—lntemet选项—高级下方勾选“使用TLS1.0,1.1,1.2,1.3”

