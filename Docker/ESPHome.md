参考：https://blog.csdn.net/ysjs888123/article/details/105620084

    docker run -d \
      --name="ESPHome" \
      -e TZ=Asia/Shanghai \
      --hostname="esphome" \
      -v /opt/esphome:/config \
      -v /run/udev:/run/udev \
      --privileged \
      --restart unless-stopped \
      --net=host \
      esphome/esphome pull nodered/node-red
