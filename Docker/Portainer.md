参考：https://docs.portainer.io/start/install-ce/server/docker/linux

    docker run -d -p 8000:8000 -p 9443:9443 --name portainer \
    --restart=always \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -v /opt/portainer/data:/data \
    portainer/portainer-ce
    
![Portain](https://github.com/lifeexplore/OpenWrt-Setup/blob/OpenWrt-Setup/Docker/Container%20List.png)
