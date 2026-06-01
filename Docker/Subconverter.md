参考：https://github.com/Toperlock/sing-box-subscribe

	docker run -d \
      --name sing-box \
      -p 5000:5000 \
      -v $(pwd)/template.json:/app/data/template.json \
      --restart always \
      dockerhub16/sing-box-subscribe:latest