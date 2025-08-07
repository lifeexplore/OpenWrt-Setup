    docker run -d \
      --name homeassistant \
      --privileged \
      --restart=unless-stopped \
      -e TZ=Asia/Shanghai \
      -v /opt/Configs/HomeAssistant:/config \
      --network=host \
      homeassistant/home-assistant:lastest
