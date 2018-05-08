build:
	sudo docker build -t iofog/python:latest -t iofog/python:$(TAG) .
push:build
	sudo docker push iofog/python:latest
	sudo docker push iofog/python:$(TAG)
