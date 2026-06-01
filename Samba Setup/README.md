* 启动：service samba4 restart
* 设置用户：
  
		opkg update
        opkg install samba4-server luci-app-samba4
        /etc/init.d/uhttpd restart

        opkg install shadow-useradd shadow-groupadd

        useradd -m -s /bin/false name
        smbpasswd -a name

        /etc/init.d/samba4 restart 
* IOS下设置：添加smb://10.0.0.100服务器
* 截图：[1](https://github.com/lifeexplore/OpenWrt-Setup/blob/OpenWrt-Setup/Samba%20Setup/samba1.png)，[2](https://github.com/lifeexplore/OpenWrt-Setup/blob/OpenWrt-Setup/Samba%20Setup/samba2.png)
