### deploy process

```shell
cat /home/ubuntu/ambient/Environments.env ./OtherEnvironment.env > ./Combined.env
docker-compose --env-file /home/ubuntu/ambient/Environments.env -f ambient-docker-compose.yml up -d
```
