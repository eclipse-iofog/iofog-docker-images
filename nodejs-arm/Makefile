build:
	sudo docker build -t iofog/nodejs-arm:$(TAG) -t iofog/nodejs-arm:latest .
push:build
	sudo docker push iofog/nodejs-arm:latest
	sudo docker push iofog/nodejs-arm:$(TAG)