# spring_mysql_rest
Spring mysql rest crud example

simple steps : 

1. git clone https://github.com/fl0wo/spring_mysql_rest.git
2. install mysql : 
  2.1 sudo apt-get update
  2.2 sudo apt-get install mysql-server
3. sudo mysql --password
4. create database db_example;
5. create user 'springuser'@'%' identified by 'flo';
6. grant all on db_example.* to 'springuser'@'%';

7. run

8. test with postman
  8.1 POST localhost:8080/demo/add 
  8.2 GET localhost:8080/demo/all
  
or curl 

curl localhost:8080/demo/add -d name=Florian -d email=sabaniflorian@gmail.com
curl 'localhost:8080/demo/all'

