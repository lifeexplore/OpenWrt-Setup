参考：https://blog.csdn.net/lbd_123/article/details/132903740

    docker run -d -it \
  	--name mosquitto \
  	--privileged \
  	-v /opt/mosquitto/config/mosquitto.conf:/mosquitto/config/mosquitto.conf \
  	-v /opt/mosquitto/data:/mosquitto/data \
  	-v /opt/mosquitto/log:/mosquitto/log \
  	-v /opt/mosquitto/config/pwfile.conf:/mosquitto/config/pwfile.conf \
  	-p 1883:1883 -p 9001:9001 \
  	eclipse-mosquitto
设置客户：

    mosquitto_passwd -c /mosquitto/config/pwfile.conf xxxx
