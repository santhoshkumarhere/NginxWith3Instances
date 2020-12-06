localhost:9000
nginx 9001
apis 3000

docker-compose up --build

docker exec -it scaling-out-docker-nginx-master_backend3_1 bash
node index.js