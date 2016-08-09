# Run mysql on docker at port 3306

docker run --name docker_run_name -p 3306:3306 -e MYSQL_ROOT_PASSWORD=rootpassword -d mysql:latest
