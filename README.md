# Rails-Docker
1- docker-compose run app rails new . --force --database=mysql --skip-bundle

======/config/database.yml========

 database: <%= ENV['DB_NAME'] %>
 
 username: <%= ENV['DB_USER'] %>
 
 password: <%= ENV['DB_PASSWORD'] %>
 
 host: <%= ENV['DB_HOST'] %>
 
===========================

2- docker-compose build

3- docker-compose up
