# consul-prometheus

Just `docker-compose up`

If it's not working then start the containers in this order

```
docker-compose up -d consul-server mysql
sleep 60
docker-compose up frontend gateway backend prometheus grafana
```