build:
	sudo docker build -t iofog/python-arm:$(TAG) -t iofog/python-arm:latest .
push:build
	sudo docker push iofog/python-arm:latest
	sudo docker push iofog/python-arm:$(TAG)