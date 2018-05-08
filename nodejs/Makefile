build:
	sudo docker build -t iofog/nodejs:latest -t iofog/nodejs:$(TAG) .
push:build
	sudo docker push iofog/nodejs:latest
	sudo docker push iofog/nodejs:$(TAG)
