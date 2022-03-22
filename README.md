# Nginx-PHP-MySql--phpMyAdmin

To Install Nginx PHP phpMyAdmin in docker Follow the below step:
1. Create a dicretory /docker in your docker host
2. Then Go to the Directory by cd /docker
3. Create a /docker/docker-compose.yml file
4. create a /docker/default.conf file
5. create a /docker/code/ directory
6. Create Directory /docker/secret
7. Create two file:
8.      /docker/secret/mysql_root_password
9.     /docker/secret/mysql_user_password
11. Inside the code directory create a /docker/code/index.php file
12. Finally Run the docker compose by 
13. docker-compose up -d
14. Check nginx URL: http://docker_host_ip:8080 
15. Check mysql Url: http://docker_host_ip:8081   
16. To remove container:  docker-compose down 


Or 
git clone -b with_mariadb https://github.com/manjurulsys0101/Docker-Compose-Nginx-PHP-MySql-phpMyAdmin.git
