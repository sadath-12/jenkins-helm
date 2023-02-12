## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server


## We setup pipeline to deploy our java app succesfully on kubernetes using helm by following steps :

### have exisiting docker images of app , db on the docker hub
### spin k8s cluster in ec2
### configure jenkins on ec2
### configure sonarqube ec2
### make sure token and webhooks from sonarqube to jenkins are added (in the jenkins config system) && make sure names are aligned in this case sonar-pro in config and mysonarscanner4 in global tool
### configure k8s as worker node for jenkins by 
#### add node ( make sure u have java version 11 installed on /opt/jenkins ) && and u have given permissions to jenkins to use root user <comand>
### make sure security group of ec2s are configured properly and allow jenkins to ssh to k8s ec2 while adding worker node 
### run the pipeline


<!-- Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql -->


