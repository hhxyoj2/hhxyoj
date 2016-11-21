# 黑河学院在线测评系统——基于开源项目hustoj
![IMG](http://www.hhhxy.cn/images/logo2.png)
##HHXYOJ是什么?

`HUSTOJ` 是采用`GPL`的自由软件。

`HHXYOJ`是来源于`HUSTOJ`的项目.

`注意`：基于本项目源码从事科研、论文、系统开发，"最好"在文中或系统中表明来自于本项目的内容和创意，否则所有贡献者可能会鄙视你和你的项目。
使用本项目源码和freeproblemset题库请尊重程序员职业和劳动

PS: GPL保证你可以合法忽略以上注意事项但不能保证你不受鄙视，呵呵。

---

##目前使用的地址
* [hhxyoj](http://www.lzpweb.cn) 
##快速安装指南

   * 1、安装Ubuntu
   * 2、执行如下命令
```shell
        sudo apt-get update
        sudo apt-get install subversion
        sudo svn co https://github.com/HHXYOJ/hhxyoj/trunk/trunk/install hhxyoj
        cd hhxyoj
	#非腾讯云 使用下面语句
        sudo bash install-interactive.sh
	#腾讯云 使用下面语句
	sudo bash tencent_install-interactive.sh
```

   * 3、修改配置文件中的数据库密码
        文件位置 /var/www/html/JudgeOnline/include/db_info.inc.php 
   * 4、安装后访问服务器80端口上的web服务JudgeOnline目录
        例如 w3m http://127.0.0.1/JudgeOnline

---

##项目维护成员
<br/>
####姓名：李兆鹏
####学院：计算机与信息工程学院
####班级：13科二
####职责:服务器运维&项目维护更新
####Github账号:DeveloperLzp
####E-mail:developer_lzp@163.com
####QQ:524329278
<br/>
####姓名：张欣宇
####学院：计算机与信息工程学院
####班级：14科二
####职责:服务器运维&项目维护更新
####Github账号:zhang916441715
####E-mail:916441715@qq.com
####QQ:916441715
<br/>

---


##更新日志
<br/>
####v1.1版本(2016-05-05 09:59 )
添加了常见问答版块，并修复了底部footer，更改了短消息的显示位置，修复了注册bug

####v1.2版本(2016-05-05 11:58 )
将mail显示移植到nav上，更清晰的展示短消息

####v1.2.1版本(2016-05-05 13:11 )
当有新短信时 字体为红色，短信页面新短信显示红色

####v1.3版本(2016-05-17 19:31 )
修复xss安全漏洞，后台新闻页编辑回显修复，更新新闻页面显示

####v1.4版本(2016-05-18 21:10 )
更换nginx服务器,优化判题模块

---
##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(developer_lzp@163.com)
* QQ: 524329278

---
##感激
感谢以下的项目

* [hustoj](https://github.com/zhblue/hustoj) 
