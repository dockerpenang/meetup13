# Running containers on Cloud using Docker Desktop


- [Docker and ACI](https://docs.docker.com/engine/context/aci-integration/)
- [Docker and ECS](https://docs.docker.com/engine/context/ecs-integration/)


# Azure CLI Command to create an ACI instance
```
az container create --resource-group rg-dockeraci --name dockerpenang --image sujaypillai/simplewhale --dns-name-label acidockerdemo --ports 80
```