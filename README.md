# Template for running ROS2 projects in docker containers


Build container

```bash
cd ros2-docker
docker compose --file docker-compose.yaml --env-file .env build
```

Run container

```bash
# In one terminal,
cd ros2-docker && docker compose up

# In subsequent terminals,
docker exec -it ros2-docker-dev-1 bash
```
