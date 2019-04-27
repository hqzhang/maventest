
all:
	-docker rm -f docker-web
	-docker rmi nginx
	docker build -t nginx .

run: 
	docker run --name docker-web -dt -p 8090:8090 nginx

