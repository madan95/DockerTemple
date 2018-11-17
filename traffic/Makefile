# Start Docker
docker-start:
	@echo Starting docker
	./createTraffic.sh

# Stop Services
docker-stop:
	@echo Stoping docker services
	docker-compose stop

# Stop and Remove containers, network, images and volumes
docker-remove:
	@echo Removing Docker Container, Network, Images and Volumes
	docker-compose down
	docker network rm traffic
