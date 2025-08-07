参考：https://www.cnblogs.com/zhengyiran/p/15850332.html

    docker pull nodered/node-red
	docker run -it -p 1880:1880 -v node_red_data:/data --name mynodered nodered/node-red
