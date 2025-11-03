```shell
sudo docker compose up -d

http://49.232.232.231:8080
admin
hjh@2023

docker.1ms.run

docker run --pull=always --rm -it -p 8080:8080 --user=root \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v /tmp:/tmp kestra/kestra:latest server local

sudo docker run -d -it -p 8080:8080 --user=root \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v /tmp:/tmp docker.1ms.run/kestra/kestra:latest server local
```