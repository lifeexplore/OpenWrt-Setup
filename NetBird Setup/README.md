NetBird设置


* [官网](https://netbird.io)
* 安装
  * opkg update
  * opkg install netbird
* 自启动设置
  * 创建/var/log/netbird目录
  * /etc/init.d/netbird enable
  * /etc/init.d/netbird start
* 升级
  * netbird down
  * curl -fsSLO https://pkgs.netbird.io/install.sh
  * chmod +x install.sh
  * ./install.sh --update
  * netbird up
