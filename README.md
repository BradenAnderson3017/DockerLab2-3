## Docker Commands for Lab 3

### Deploy your stack:
docker stack deploy -c docker-compose.yaml  myapp-stack
###Checked history:
docker stack ps myapp-stack
### list running services
docker stack services myapp-stack
### stop the container
docker stop ec90ae4fced0
### Redeploy 
docker stack deploy -c docker-compose.yaml  myapp-stack
### Removing stacks 
docker stack rm myapp-stack
