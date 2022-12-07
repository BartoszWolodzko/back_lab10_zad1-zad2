# Run Commands
docker swarm init

docker build -t zad1 .

docker service create --name zad1_s zad1

# Test Commands
docker service ls

docker service ps zad1_s

# Descript
After 35sec of running memory-hog restarts because memory-check return 1 