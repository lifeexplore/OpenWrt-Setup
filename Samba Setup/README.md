* 启动：service samba4 restart
* 设置用户：
  
		opkg update
		opkg install shadow-useradd  
		useradd xxxx
		smbpasswd -a xxxx password  
* IOS下设置：添加smb://10.0.0.100服务器
* IOS不能写入问题：vfs填入fruit streams_xattr
* 截图：[1](https://github.com/lifeexplore/OpenWrt-Setup/blob/OpenWrt-Setup/Samba%20Setup/samba1.png)，[2](https://github.com/lifeexplore/OpenWrt-Setup/blob/OpenWrt-Setup/Samba%20Setup/samba2.png)
