Tailscale设置


* 官网：https://tailscale.com
* 安装
  
  		opkg update
  		opkg install tailscale
* 运行  
        tailscale up --advertise-routes=10.0.0.100/32 --advertise-exit-node --accept-dns=false
