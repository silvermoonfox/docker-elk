# docker-elk
elasticsearch, logstash, kibana, filebeat, nginx on docker

## How to use
- Step 1. sudo sysctl -w vm.max_map_count=262144
- Step 2. chmod -R 0777 html/
- Step 3. chmod -R 0777 datas/
- Step 4. docker-compose up -d --build

## Use filebeat for local Log
i.g Nginx log

```
sudo cd /var/log/nginx
sudo chown nginx:ec2-user nginx
sudo chmod -R 777 nginx
```