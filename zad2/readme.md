# Run commands
```
docker swarm init
```
# 
```
docker stack deploy -c docker-compose.v09.yml image-of-the-day
```
lub
```
docker stack deploy -c docker-compose.v04.yml image-of-the-day
```
# Check if everything is running
```
docker stack ls

docker stack ps image-of-the-day
```

# Remove stack
```
docker stack rm image-of-the-day

docker swarm leave --force
```