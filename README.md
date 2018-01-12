Start the application in swarm mode
docker stack deploy --compose-file docker-compose-swarm.yml visualizer

Stop the swarm application
docker stack rm visualizer

Open the application
http://www.thalasoft.com:8085

The project
https://github.com/dockersamples/docker-swarm-visualizer
